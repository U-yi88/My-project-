# 🎯 MNISHARE

**Global Social + Real Estate + Marketplace Platform**

A fully interactive, modern web application featuring social networking, real estate listings, marketplace functionality, chat, live streaming, and integrated banking/escrow services.

## ✨ Features

- 🌍 **Global Social Network** - Connect, share, and build communities
- 🏠 **Real Estate Platform** - Browse, list, and manage properties
- 🛍️ **Marketplace** - Buy/sell with secure escrow protection
- 💬 **Chat System** - Real-time messaging and communications
- 🎬 **Live Streaming** - Host and watch live events
- 💰 **Escrow & Banking** - Integrated payment solutions
- 📱 **Fully Responsive** - Works on all devices
- ✨ **Modern UI** - Luxurious gold-themed design

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/U-yi88/My-project-.git
cd My-project-

# Install dependencies
npm install

# Create environment file
cp .env.example .env.local

# Start development server
npm start
```

The app will open at `http://localhost:3000`

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` folder.

## 📦 Deployment - Choose Your Platform

### ⚡ Option 1: Vercel (Recommended - 2 minutes)

Fastest & easiest deployment for React apps.

```bash
# 1. Push to GitHub
git push origin main

# 2. Go to vercel.com, import this repo
# 3. Set environment variables
# 4. Done! Auto-deploys on every push
```

### 🐳 Option 2: Docker

```bash
# Build image
docker build -t mnishare .

# Run locally
docker run -p 3000:3000 mnishare

# Deploy to AWS/Google Cloud/Azure
```

### 🌐 Option 3: Netlify

```bash
# Build app
npm run build

# Deploy
# Option A: Drag build/ folder to netlify.com
# Option B: Connect GitHub for auto-deployment
```

### 📄 Option 4: GitHub Pages

```bash
npm run deploy
# Live at: https://U-yi88.github.io/My-project-
```

**[👉 Full Deployment Guide](DEPLOYMENT_GUIDE.md)**

## 📋 Environment Variables

Create a `.env.local` file:

```env
REACT_APP_API_URL=https://api.mnishare.com
REACT_APP_ENV=production
REACT_APP_VERSION=1.0.0
REACT_APP_STRIPE_KEY=your_stripe_key
REACT_APP_FIREBASE_API_KEY=your_firebase_key
```

## 🔄 CI/CD Pipeline

Automated GitHub Actions workflow included:
- ✅ Tests on every push
- ✅ Builds application
- ✅ Auto-deploys to Vercel

**Setup secrets in GitHub:**
- `VERCEL_TOKEN`
- `VERCEL_ORG_ID`
- `VERCEL_PROJECT_ID`

## 📱 Tech Stack

- **Frontend:** React 18
- **Styling:** CSS3 with CSS Variables
- **Fonts:** Playfair Display & Inter
- **Build:** Create React App
- **Deployment:** Vercel / Docker / Netlify
- **CI/CD:** GitHub Actions

## 🎨 Design

Luxury-themed color scheme:
- Primary: Gold (#c9a84c)
- Background: Deep dark (#07070f)
- Accents: Emerald, Red, Blue, Purple, Pink, Orange

## ⚡ Performance

- ⚡ Optimized bundle
- 🎯 Fast Core Web Vitals
- 📱 Mobile-first responsive
- 🔍 SEO friendly

## 🔐 Security

- ✅ Env variables for secrets
- ✅ HTTPS enforced
- ✅ CSP headers configured
- ✅ XSS protection

## 🤝 Contributing

```bash
# Create feature branch
git checkout -b feature/amazing-feature

# Commit & push
git commit -m 'Add amazing feature'
git push origin feature/amazing-feature

# Open Pull Request
```

## 📝 License

Boost Software License 1.0 - see LICENSE file.

## 📞 Support

- 📧 Email: support@mnishare.com
- 🐛 Issues: [GitHub Issues](https://github.com/U-yi88/My-project-/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/U-yi88/My-project-/discussions)

## 🎯 Roadmap

- [ ] Mobile app (React Native)
- [ ] AI-powered recommendations
- [ ] Advanced analytics
- [ ] Video optimization
- [ ] Multi-language support
- [ ] Blockchain integration

---

**Made with 💛 by MNISHARE Team**

**[👉 Live Demo](https://mnishare.com)** | **[👉 Deployment Guide](DEPLOYMENT_GUIDE.md)**
