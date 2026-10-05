# CYBERNEXUS AI — SIH Prototype

**AI-Powered Continuous Cyber Risk Quantification and Investment Optimization Platform**

This is the cleaned VS Code-ready copy of the CYBERNEXUS AI prototype exported from Google AI Studio.

## Cost

**₹0 external service cost.**

- No Gemini/OpenAI API key required
- No paid API required
- No cloud account required
- No database subscription required
- Uses synthetic/local prototype data
- AI assistant uses the local deterministic decision engine

## Project structure

```text
CYBERNEXUS-AI-SIH/
├── src/                  # React frontend
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── types/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── server/               # Backend API + risk/decision engines
│   ├── data/
│   ├── routes/
│   └── services/
├── server.ts             # Express + Vite full-stack server
├── index.html
├── vite.config.ts
├── tsconfig.json
└── package.json
```

## Requirements

Install Node.js 20+ (Node.js 22 LTS recommended).

## Run in VS Code

Open this folder in VS Code:

```powershell
cd "C:\path\to\CYBERNEXUS-AI-SIH"
npm install
npm run dev
```

Then open:

```text
http://localhost:3000
```

The same server provides the React application and `/api/*` backend endpoints.

## Useful commands

```powershell
npm run dev
npm run build
npm run start
npm run lint
```

## Health check

```text
http://localhost:3000/api/health
```

## Important

This is an SIH demonstration prototype. Enterprise integrations are represented using synthetic/demo telemetry. The financial-risk figures are explainable prototype estimates and should not be treated as real-world financial forecasts.
