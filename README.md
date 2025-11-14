# E-INTEL Frontend (Vite + React + Tailwind) - Deploy Ready

This frontend is ready to deploy on Vercel. Steps:

1. Install dependencies:
   ```bash
   npm install
   ```

2. Local dev:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

4. Deploy on Vercel:
   - Import the GitHub repo and point the root to the project (this repo contains only frontend).
   - Vercel will run `npm run build` and publish the `dist` folder.
   - Set environment variable `VITE_API_URL` to your backend URL.
