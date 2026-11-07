# Trilla Labs listing assets

Listing pictures and encrypted buyer files that Trilla Labs uses to publish its tools on Payhip.

- `assets/<product id>/picture-N.jpg`: listing pictures, the same ones shown in the shop.
- `assets/<product id>/<name>.zip.enc`: the buyer file, encrypted with AES-256-GCM. It can't be opened without its key, which is not stored here.

Shop: https://payhip.com/TrillaLabs
