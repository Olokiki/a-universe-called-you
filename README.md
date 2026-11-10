# A Universe Called You

A cinematic personal birthday experience built with React, TypeScript, Vite, Tailwind CSS and Framer Motion.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Personalise
Most copy and story content lives in `src/content.ts`: `timeline` (relationship chapters), `loveReasons` (reasons collection, add up to 100), `letters` (open-when letters), and `adventures` (future plans). Photos live in `public/images/`; update the `photos` array in `src/main.tsx` and image references in `src/content.ts`. The repository includes optimised WebP versions of supported photos from the supplied archive. Some HEIC originals could not be converted by the available image tooling, so the gallery uses a selected subset and can be expanded with JPG/WebP files. The birthday date is November 11, 2026; update date labels in `src/main.tsx` if needed.

## Deploy with Vercel
1. Import `Olokiki/a-universe-called-you` from GitHub.
2. Choose Vite (or framework auto-detection).
3. Build command: `npm run build`.
4. Output directory: `dist`.
5. No environment variables or backend are required.
6. Deploy and share the generated URL. The GitHub repository is private; the hosted URL is public by default unless Vercel access protection is enabled.

## Deploy with Netlify
Build command: `npm run build`; publish directory: `dist`. Connect the repository and deploy.
