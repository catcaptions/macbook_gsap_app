<div align="center">
	<h1>MacBook GSAP Landing Page</h1>
	<p>Apple-style product landing page built with React, GSAP, Three.js (R3F), and Tailwind CSS.</p>

	<p>
		<a href="#getting-started">Getting started</a> ·
		<a href="#deploy-to-vercel">Deploy to Vercel</a>
	</p>

	<p>
		<a href="https://vercel.com/new/clone?repository-url=https://github.com/catcaptions/macbook_gsap_app">
			<img src="https://vercel.com/button" alt="Deploy with Vercel" />
		</a>
	</p>

	<img
		src="https://github.com/adrianhajdin/gsap_macbook_landing/raw/main/public/readme/hero.webp"
		alt="MacBook landing page hero"
		width="900"
	/>
</div>

## Features

- Scroll-driven GSAP animations and section highlights
- Interactive 3D product viewer powered by `three` + React Three Fiber
- Responsive layout (desktop → mobile)
- Lightweight global state via Zustand

## Tech stack

- React + Vite
- Tailwind CSS
- GSAP (`gsap`, `@gsap/react`)
- Three.js (`three`, `@react-three/fiber`, `@react-three/drei`)
- Zustand

## Getting started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Install

```bash
npm install
```

### Run locally

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Deploy to Vercel

### Option A — Vercel dashboard (recommended)

1. Push this repo to GitHub.
2. In Vercel, click **New Project** → import the repo.
3. Use these settings (Vercel usually detects them automatically for Vite):
	 - **Framework**: Vite
	 - **Build Command**: `npm run build`
	 - **Output Directory**: `dist`
4. Deploy.

### Option B — Vercel CLI

```bash
npm i -g vercel
vercel
vercel --prod
```

## Attribution

- The README hero image is embedded from
	https://github.com/adrianhajdin/gsap_macbook_landing (it is not stored in this repository).
