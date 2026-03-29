# Vishal Kumawat Portfolio

A modern, responsive personal portfolio built with React, TypeScript, Vite, and Tailwind CSS.  
This project showcases profile information, skills, projects, education, certifications, and contact details in an interactive single-page experience, plus a dedicated resume download page.

## Live Focus

- Personal branding and professional presentation
- Smooth, animated UI with a clean section-based layout
- Recruiter-friendly resume download options (DOCX and TXT)

## Features

- Animated landing experience with preloader and hero interactions
- Sectioned portfolio flow:
	- About
	- Skills
	- Projects
	- Education
	- Certifications
	- Contact
- Theme context with dark-mode-first behavior
- Dedicated Resume page at `/resume`
- Resume export utilities:
	- Dynamic DOCX generation
	- Plain text resume generation
- Responsive UI components powered by Tailwind and Radix/shadcn-ui patterns

## Tech Stack

- Frontend: React 18, TypeScript, Vite
- Styling: Tailwind CSS, tailwindcss-animate
- UI Primitives: Radix UI, shadcn-style component architecture
- Animations: Framer Motion, GSAP
- Routing: React Router
- Data/State Utilities: TanStack React Query
- Resume Export: file-saver
- Optional Static Server: Express

## Project Structure

```
.
├─ public/
├─ src/
│  ├─ components/
│  ├─ contexts/
│  ├─ hooks/
│  ├─ lib/
│  ├─ pages/
│  ├─ App.tsx
│  └─ main.tsx
├─ index.html
├─ tailwind.config.ts
├─ vite.config.ts
└─ package.json
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm (or bun)

### Installation

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

Default dev server: `http://localhost:8080`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Serve Built Files with Express (Optional)

```bash
npm run start
```

This uses `src/app.js` to serve files from the `dist` folder.

## Available Scripts

- `npm run dev` - Start Vite dev server
- `npm run build` - Build production bundle
- `npm run preview` - Preview production bundle locally
- `npm run start` - Start Express server for built assets

## Customization Guide

- Update personal content in section components under `src/components`
- Update SEO metadata in `index.html`
- Update resume text/template in:
	- `src/lib/resumeGenerator.ts`
	- `src/lib/resumeGeneratorTxt.ts`
- Adjust design tokens and animations in `tailwind.config.ts` and `src/index.css`

## Deployment

You can deploy this project to any static hosting provider:

- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

Typical deployment flow:

1. Run `npm run build`
2. Deploy the generated `dist` directory

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

- Name: Vishal Kumawat
- Website: https://vishalkumawat.dev
- GitHub: https://github.com/vishalkumawatx
- LinkedIn: https://linkedin.com/in/vishalkumawatx
