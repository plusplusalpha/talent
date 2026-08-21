# client.plusalpha.agency — FINAL Vercel package

Deploy this folder as the Vercel project root.

Expected URL:
https://client.plusalpha.agency/dino-svt/2026

Key fixes:
- Local image/logo URLs use root-absolute paths:
  /dino-svt/2026/assets/...
- This prevents broken assets when the public URL has no trailing slash.
- Desktop page scale is set to `zoom: .8`, matching the PA report system.
- Mobile resets to `zoom: 1`.

Structure:

client-plusalpha-vercel-final/
├── vercel.json
└── dino-svt/
    └── 2026/
        ├── index.html
        └── assets/
            ├── pa-logo.svg
            ├── dino-profile.png
            └── picheolin.jpg
