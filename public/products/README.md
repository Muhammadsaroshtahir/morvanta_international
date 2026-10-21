# MORVANTA International — Product Images

Drop product photos here. The site loads `/products/<slug>.jpg` for each item:

- hiboost.jpg
- c-forte.jpg
- diabesun.jpg
- magnisun.jpg
- gensun-plus.jpg
- neurosun-plus.jpg
- gincos-syrup.jpg
- dopasun.jpg
- dietrisun.jpg
- hiflex-gc.jpg

Use the clean bottle / product photo as the main file. If you also have a
poster / promo image for the same product, add it to `galleryImages` in
`src/data/products.ts` — it will show only on the product detail modal.

Duplicate photos of the same product (bottle + poster) should NOT create a
second product entry. Keep one entry per unique product name.

If a file is missing, the site shows a placeholder automatically.
