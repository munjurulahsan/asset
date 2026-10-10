==================================================
CELESTE / ALTITUDE WEBSITE - CORE PRODUCTION ASSETS
==================================================

1. celeste_bg.jpg (CRITICAL & ACTIVE)
   - The primary background image currently powering the WebGL Liquid Lens shader.
   - Code reference: src/components/LiquidLens.tsx (img.src = '/celeste_bg.jpg')

2. altitude_bg.jpg
   - Alternate Arctic mountain background option.

3. video.mp4
   - The original/source reference hero video.

4. clean_background.png
   - Extracted high-resolution clean background without overlaid text.

--------------------------------------------------
HOW TO USE WITH CLOUD STORAGE / CDN:
--------------------------------------------------
1. Upload celeste_bg.jpg (and optionally video.mp4 or others) to your cloud storage
   (e.g., Cloudinary, Supabase Storage, AWS S3, Imgur, GitHub Releases, etc.).
2. Send the public URL link here.
3. We will immediately replace '/celeste_bg.jpg' with your cloud CDN URL in LiquidLens.tsx!
