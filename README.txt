KATHYA CASTILLO PORTFOLIO — Vercel deploy

Option A (CLI, fastest)
  1. Unzip this folder.
  2. In a terminal inside it:  npx vercel --prod
  3. When asked, link it to your existing project (or create one).
  4. Vercel dashboard > Project > Settings > Domains > add your domain.

Option B (GitHub)
  1. Push this folder to a new GitHub repo.
  2. Vercel > Add New > Project > import the repo.
     Framework preset: Other. No build command. Output directory: leave blank (root).
  3. Add your domain under Settings > Domains.

Files
  index.html     the whole site
  media/         videos, thumbnails, portrait (also used for link previews)
  vercel.json    clean URLs + long caching for media

Résumé direct link:  https://YOURDOMAIN/#resume
