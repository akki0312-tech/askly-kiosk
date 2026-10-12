# Askly Kiosk Presentation

An eye-catching, animated, full-screen infographic presentation built for kiosk displays.

## Deploying to Vercel

### Option 1: Via Vercel CLI (Fastest)
From this directory:
```bash
npx vercel
```
Follow the interactive prompts:
- Set up and deploy? **Y**
- Which scope? (Select your account)
- Link to existing project? **N**
- Project name: `askly-kiosk`
- Directory: `./`
- Want to modify settings? **N**

For production deployment:
```bash
npx vercel --prod
```

### Option 2: Via GitHub & Vercel Dashboard
1. Push this folder to a new GitHub repository (e.g. `askly-kiosk`):
   ```bash
   git init
   git add .
   git commit -m "feat: initial askly kiosk showcase"
   git branch -M main
   # git remote add origin <your-github-repo-url>
   # git push -u origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import the `askly-kiosk` repository.
4. Click **Deploy** (No build settings or framework presets needed; it's a zero-dependency static site with instant loading!).
