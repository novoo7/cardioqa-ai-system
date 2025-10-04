# CardioQA Frontend - AI Medical Assistant Interface 🫀

A professional React/Next.js frontend for the CardioQA AI-powered cardiac diagnostic assistant system.

## 🌟 Project Overview

CardioQA Frontend provides an intuitive, healthcare-grade user interface for interacting with the CardioQA medical AI system. Built with modern web technologies and optimized for medical information display with proper safety features.

## 🚀 Features

- **Interactive Medical Chat Interface** - Professional healthcare UI/UX design
- **Real-time AI Responses** - Connects to CardioQA RAG backend API
- **Medical Safety Validation** - Displays safety scores and confidence levels
- **Emergency Detection Alerts** - Prominent warnings for critical health situations
- **Professional Medical Disclaimers** - Automatic safety disclaimers and consultation recommendations
- **Responsive Design** - Optimized for desktop and mobile healthcare environments
- **Accessibility Features** - Healthcare-compliant interface design

## 🛠️ Technology Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript for type safety
- **Styling**: Tailwind CSS with custom healthcare theme
- **UI Components**: Shadcn/UI component library
- **HTTP Client**: Axios for API communication
- **Deployment**: Vercel (Production), localhost (Development)

## 🏗️ Architecture

```
┌─────────────────┐    HTTP/API    ┌─────────────────┐
│   Next.js       │   ────────>    │   CardioQA      │
│   Frontend      │                │   Backend API   │
│   (This Repo)   │   <────────    │   (FastAPI)     │
└─────────────────┘    JSON        └─────────────────┘
```

## ⚙️ Getting Started

### Prerequisites

- Node.js 18+ installed
- Access to CardioQA backend API

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/novoo5/cardioqa-ai-system.git
   cd cardioqa-ai-system/cardioqa-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Configure environment variables**
   ```bash
   # Create .env.local file
   NEXT_PUBLIC_API_URL=https://novoo5-cardioqa-ai-system.hf.space
   ```

4. **Run development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. **Open application**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🌐 Live Demo

- **Production**: [https://cardioqa-frontend.vercel.app](https://cardioqa-frontend.vercel.app)
- **Backend API**: [https://novoo5-cardioqa-ai-system.hf.space](https://novoo5-cardioqa-ai-system.hf.space)

## 📱 Usage

1. **Ask Medical Questions**: Enter cardiac health queries in the main interface
2. **Review AI Response**: Get evidence-based information with confidence scoring
3. **Check Safety Alerts**: Review medical warnings and professional recommendations
4. **View System Metrics**: Monitor API status, response times, and knowledge sources

## 🛡️ Medical Safety Features

- **Professional Disclaimers**: Automatic medical consultation recommendations
- **Emergency Detection**: Critical situation alerts and immediate care guidance
- **Safety Scoring**: 70-100/100 safety validation scores
- **Confidence Levels**: High/Medium/Low confidence ratings based on knowledge similarity
- **Source Transparency**: Number of medical sources used for each response

## 📊 System Integration

### API Endpoints Used

- `GET /health` - Backend system health check
- `POST /query` - Submit medical queries and receive AI responses
- `GET /stats` - System statistics and model information

### Data Flow

1. User submits cardiac health query
2. Frontend validates input and sends to backend API
3. Backend processes query through RAG pipeline
4. AI generates response with safety validation
5. Frontend displays formatted response with medical disclaimers

## 🔧 Development

### Key Components

- `app/page.tsx` - Main CardioQA interface
- `components/ui/` - Reusable UI components
- `lib/` - Utility functions and configurations

### Code Quality

- **TypeScript**: Full type safety throughout the application
- **ESLint**: Code quality and consistency enforcement
- **Tailwind CSS**: Utility-first styling approach
- **Component Architecture**: Modular, reusable component design

## 🚀 Deployment

### Vercel (Recommended)

1. Connect GitHub repository to Vercel
2. Set environment variable: `NEXT_PUBLIC_API_URL`
3. Deploy automatically on git push

### Manual Build

```bash
npm run build
npm run start
```

## 👨‍💻 Developer

**Novonil Basak** - B.Sc. Biotechnology Student  
Specialized in Healthcare AI and Medical Technology

## 📄 License

MIT License - see [LICENSE](../LICENSE) file for details.

## ⚠️ Medical Disclaimer

This application provides educational information only. Always consult qualified healthcare professionals for medical advice, diagnosis, or treatment. For medical emergencies, contact emergency services immediately.

***

**Part of the CardioQA AI Medical Assistant System**  
Backend Repository: [CardioQA API](../src/api/)


