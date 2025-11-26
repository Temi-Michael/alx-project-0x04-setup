# ALX — Project 0x03 (Next.js)

A small Next.js + TypeScript project created for the ALX curriculum. It demonstrates a basic Next.js app structure (pages, API routes), TypeScript support, ESLint, and Tailwind/PostCSS integration.

**Tech stack:** Next.js, TypeScript, React, ESLint, Tailwind CSS (PostCSS)

## Quick Start

Prerequisites: Node.js v16+ and a package manager (`npm`, `yarn`, or `pnpm`).

1. Install dependencies

```powershell
npm install
```

2. Run development server

```powershell
npm run dev
```

Open `http://localhost:3000` in your browser.

## Available Scripts

- `npm run dev`: Runs the app in development mode (`next dev`).
- `npm run build`: Builds the app for production (`next build`).
- `npm run start`: Starts the production server (`next start`).
- `npm run lint`: Runs ESLint.

## Project Structure (key files)

- `pages/` — React pages and API routes (`pages/api/hello.ts`).
- `components/` — React components (e.g. `common/Button.tsx`).
- `layouts/` — Layout components (`Header.tsx`, `Footer.tsx`, `Layout.tsx`).
- `public/` — Static assets served from `/`.
- `styles/` — Global CSS (`globals.css`).
- `next.config.ts` — Next.js configuration.
- `package.json` — Project metadata and scripts.

## Notes

- This project is written in TypeScript. Type definitions live in `tsconfig.json` and `interface/`.
- API routes are available under `/api/*`. Example: `GET /api/hello`.

## Contributing

If you want to contribute, update or open a pull request. For small changes, editing `pages/index.tsx` or components in `components/` is a good place to start.

## Author & License

Replace the author and license information below as needed.

- **Author:** Your Name
- **License:** MIT (change as required)

---

If you want, I can add a short `DEV_SETUP.md` with detailed setup steps or update the `package.json` `homepage`/`repository` fields. What would you like next?
