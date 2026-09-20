ORVEA - Project Assets Guide
============================

This package contains all assets used in the ORVEA project:

1. `robot/` (64 files - ~6.5MB)
   - These are the responsive image ladders (AVIF, WebP, PNG at 480w, 768w, 1024w) used by the web application.
   - Files include whole-body renders and split head/body renders for parallax effects.
   - If you upload this folder to a cloud CDN / bucket (e.g. S3, Supabase, Cloudflare R2, Cloudinary, Vercel Blob, etc.), you can provide the Base CDN URL (e.g. `https://your-cdn.com/robot/` or `https://your-bucket.url/`).

2. `source-images/` (7 files - ~12MB)
   - Original high-resolution master PNG renders for all 7 states (Hero, Perception, Movement, Interaction, Climax, Return, Footer).

Next Step:
- Upload the files to your preferred cloud storage / image hosting.
- Provide the hosted URL(s) or base URL here, and they will be linked into the project codebase.
