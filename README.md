# 🔥 Nation of Nanih Oba - Portal Activation Instructions

Use these steps to launch your TikTok Broadcast Portal at https://portal.nanihoba.org

---

## STEP 1: Create GitHub Repository
1. Go to: https://github.com/new
2. Name your repo: `portal.nanihoba.org`
3. Set to Public, click Create

---

## STEP 2: Upload Files
Upload the contents of this ZIP:
- index.html
- manifest.json
- README.md
- folders: /css, /js, /images

GitHub: Click Code > Add file > Upload files

---

## STEP 3: Enable GitHub Pages
1. Go to Settings > Pages
2. Source: main branch, /root
3. Click Save
➡️ Your GitHub page will publish a live preview like:
   https://yourusername.github.io/portal.nanihoba.org

---

## STEP 4: Connect Domain via Cloudflare
1. Visit: https://dash.cloudflare.com
2. Add domain: nanihoba.org
3. Under DNS, add a CNAME record:
   - Type: CNAME
   - Name: portal
   - Target: yourusername.github.io
   - Proxy: DNS Only

---

## STEP 5: Final GitHub Settings
1. Go to Settings > Pages
2. Add custom domain: portal.nanihoba.org
3. Check: Enforce HTTPS

---

Done! Your portal is now live at:
🔗 https://portal.nanihoba.org
