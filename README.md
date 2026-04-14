# 🚀 NexeN.AI - AI Automation Agency Portfolio

[![Website Live](https://img.shields.io/badge/Live_Website-nexen--ai.vercel.app-success?style=for-the-badge&logo=vercel)](https://nexen-ai.vercel.app)

NexeN.AI is a high-throughput AI automation agency portfolio. We design, build, and deploy intelligent autonomous systems that operate at machine speed. 

## 🌐 Live Website
Check out the fully functional live portfolio here: **[https://nexen-ai.vercel.app](https://nexen-ai.vercel.app)**

## ⚡ Core Technologies & Stack
- **Workflows:** n8n (Node-based automation)
- **Database Backend:** Supabase (PostgreSQL)
- **Hosting & Deployment:** Vercel (Edge-ready)
- **Integrations:** Telegram API, Custom Webhooks, Express Server
- **Frontend Stack:** HTML/CSS/JS with smooth 3D animations and responsive UI

## ✨ Built For
- **SaaS founders** automating growth operations
- **Agencies** scaling client workflows
- **Crypto & AI startups** shipping intelligent products
- **Teams** needing high-volume content or support systems

## 🛠 What We Automate
- Lead generation and CRM workflows
- Content pipelines and publishing systems
- Telegram / WhatsApp bots and messaging ops
- AI customer support and task orchestration

## 📈 Proven Impact
- **GeoNews AI Stream:** Real-time AI news curation and summarization. An n8n-to-Telegram pipeline processing 12,000+ messages daily with sub-second latency.
- **Ops Optimization:** Reduced manual ops by 82% for a finance platform by connecting data ingestion, orchestration, and reporting.
- **Enterprise Support:** Delivered 18x throughput improvement for support flows with an AI-driven ticket triage layer.

---

## 💻 Local Development Guide

If you'd like to run this web application locally, follow these steps:

### Prerequisites
- Node.js installed (v14 or higher)
- npm or yarn

### Installation & Setup

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Environment Variables**
   Create a `.env.local` file based on `.env.example`:
   ```bash
   cp .env.example .env.local
   # Note for Windows: copy .env.example .env.local
   ```
   Add your `SUPABASE_KEY` and `TELEGRAM_BOT_TOKEN` for full functionality.

3. **Start the Server**
   ```bash
   npm start
   ```
   Or for development with auto-reload:
   ```bash
   npm run dev
   ```

4. **Open in Browser**
   Navigate to `http://localhost:8080`

### Available API Endpoints
- `GET /api/news` - Returns array of live news feed items.
- `POST /api/news` - Update live news feed.
- `GET /api/projects` - Dynamically load portfolio projects.
- `POST /api/contact` - Submits a new lead form. Saves to Supabase and sends an instant Telegram alert.
- `GET /api/contacts` - Admin view of connected leads.

## 📞 Contact Information
- **Email:** nagasaireddy0123@gmail.com
- **Phone:** +91 72039 59848
- **LinkedIn:** [Nagasai Reddy (CEO)](https://www.linkedin.com/in/nagasai-reddy-lankireddy/)
- **GitHub:** [SaiReddy-Sr](https://github.com/SaiReddy-Sr)