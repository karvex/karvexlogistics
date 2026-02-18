KARVEX LOGISTICS — simple RU/EN business card website

Deploy (GitHub Pages):
1) Create a GitHub repo (public), e.g. "karvexlogistics"
2) Upload index.html to the root of the repo
3) GitHub: Settings → Pages → Deploy from branch → main / (root)
4) Add Custom domain: karvexlogistics.com
5) Namecheap → Domain List → Manage → Advanced DNS:
   A     @     185.199.108.153
   A     @     185.199.109.153
   A     @     185.199.110.153
   A     @     185.199.111.153
   CNAME  www  karvexlogistics.com

Wait for DNS (30–120 min). Then in GitHub Pages enable "Enforce HTTPS" if available.
