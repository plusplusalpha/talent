# client.plusalpha.agency — Vercel-ready structure

Upload / push THIS folder as the Vercel project root.

client-plusalpha-vercel/
├── vercel.json
└── dino-svt/
    └── 2026/
        ├── index.html
        └── assets/
            ├── pa-logo.svg
            ├── dino-profile.png
            └── picheolin.jpg

Expected URL:
https://client.plusalpha.agency/dino-svt/2026

Important:
1. In Vercel, Root Directory must be the folder containing `vercel.json`.
2. Do not set the Root Directory to `dino-svt/2026`.
3. Framework Preset can be `Other`.
4. No build command is required for this static HTML package.
5. `vercel.json` explicitly rewrites `/dino-svt/2026` to the nested `index.html`.
