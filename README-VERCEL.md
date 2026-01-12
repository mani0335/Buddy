Deploying this static site to Vercel

This project is a simple static site. Two main options to deploy:

1) Quick (CLI)

- Install Vercel CLI:

```bash
npm install -g vercel
```

- Login (interactive) or use token:

```bash
vercel login
# or non-interactive
vercel --token $VERCEL_TOKEN
```

- From the project root run:

```bash
vercel --prod
```

2) Recommended: GitHub integration (automatic deploys)

- Go to https://vercel.com and create an account.
- Import the GitHub repository `https://github.com/mani0335/Buddy`.
- Vercel will detect the project as a static site and deploy automatically on pushes to `main`.

Notes
- No build step is required (static files). `vercel.json` is included to ensure Vercel treats the repo as static.
- If you want me to run the CLI deploy from here, I will need your Vercel token (or to use an interactive login in your terminal). Do you want me to proceed?"