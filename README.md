# Experiment 1

A modern Next.js web application with 3D capabilities built using React Three Fiber and Three.js.

## Features

- **Next.js 15.4.6** - Latest React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **React Three Fiber** - React renderer for Three.js
- **Three.js** - 3D graphics library
- **ESLint** - Code linting and formatting

## Tech Stack

- **Framework:** Next.js 15.4.6
- **Language:** TypeScript
- **Styling:** Tailwind CSS v4
- **3D Graphics:** Three.js v0.160.0 + React Three Fiber v9.0.0
- **Package Manager:** npm
- **Linting:** ESLint with Next.js config

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/manansh11/experiment_1.git
cd experiment_1
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Project Structure

```
src/
├── app/
│   ├── layout.tsx      # Root layout
│   ├── page.tsx        # Homepage
│   ├── globals.css     # Global styles
│   └── favicon.ico     # Site favicon
├── components/         # Reusable components (add as needed)
└── lib/               # Utility functions (add as needed)
```

## 3D Development

This project includes React Three Fiber and Three.js for creating 3D experiences. You can start building 3D scenes by importing the necessary components:

```tsx
import { Canvas } from '@react-three/fiber'
import * as THREE from 'three'
```

## Contributing

1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [React Three Fiber Documentation](https://docs.pmnd.rs/react-three-fiber)
- [Three.js Documentation](https://threejs.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
