Open index.html to view the store.

Admin page is hidden from navigation. To access admin, open admin/index.html directly.
- The admin page is protected by a simple passcode prompt.
- Default passcode: change-this-pass (edit in admin/index.html, PASSCODE variable)

- Products are stored in browser localStorage by Admin.
- You can export/import JSON from Admin.
- Storefront reads products from products.json on first load, then you can update via Admin.
- Cart persists in localStorage.
- Checkout sends an EmailJS notification from cart.html. Replace placeholders:
  - In cart.html: YOUR_EMAILJS_PUBLIC_KEY, YOUR_SERVICE_ID, YOUR_TEMPLATE_ID

Deploy by uploading this folder to any static host.
