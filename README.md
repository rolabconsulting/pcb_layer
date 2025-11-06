# PCB Measurement App

A web-based application for PCB layer measurements.

## Deployment to Vercel

### Steps:

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Deploy to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Sign in with GitHub
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy" (no configuration needed)

Your app will be live at: `https://your-project-name.vercel.app`

## Local Development

To run locally:
```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
