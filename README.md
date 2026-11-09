# Vancouver Grocery Price Comparison
Static single-file site. Deployed via Coolify (nginx:alpine container).

## Weekly update flow
1. On the build machine: run build_compare_data.py + build_compare_site.py
2. Copy price-compare/index.html into this repo (overwrite)
3. git commit && git push  (Coolify webhook redeploys automatically)
