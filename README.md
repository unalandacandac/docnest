# docnest# 1) tüm değişiklikleri commit et
git add .
git commit -m "Add DocNest demo"
git push origin main

# 2) gh-pages branch'e deploy (yerel build gerekmez; sadece index.html varsa aşağıdaki adım çalışır)
git checkout -b gh-pages
git push -u origin gh-pages

# 3) GitHub repo > Settings > Pages kısmında "gh-pages branch" seç ve deploy'u etkinleştir
# Sonra bu linki al: https://<github-username>.github.io/<repo-ismi>/

