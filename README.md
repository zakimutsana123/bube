# BuBe.co (HTML)

Versi HTML statis (multi-page) untuk UI premium BuBe.co. Cocok untuk review desain, flow belanja, dan demo tanpa backend.

## Cara Review
1. Buka file ini dengan browser (paling mudah):
   - `c:\BUBE\bubeco-html\index.html`
2. Halaman penting:
   - Home: `index.html`
   - Shop: `shop.html`
   - Detail produk: `product.html?slug=aurelia-tunik-linen`
   - Keranjang: `cart.html`
   - Checkout: `checkout.html`
   - Pembayaran/Tracking: `payment.html?order=<id>` (otomatis setelah checkout)
   - Akun: `account.html`
   - Admin: `admin.html` (butuh login admin)

## Data & Login (Simulasi)
- Cart/Wishlist/Order disimpan di localStorage browser.
- Admin demo:
  - Email: `admin@bubeco.co`
  - Password: `Admin1234`

## Analytics / Pixel (Opsional)
Edit:
- `assets/js/env.js`
Isi `GA_MEASUREMENT_ID` dan `META_PIXEL_ID`.

