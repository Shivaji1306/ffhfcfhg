# SereniTea — Simple Tea Shop

This is a small static multi-page website demo for a tea shop called SereniTea. It's built with plain HTML, Tailwind CSS (via CDN), and vanilla JavaScript. No build step is required — just open the files in a browser.

Files

- index.html — Home page: hero, featured tea products, newsletter form, and a simple cart modal. Uses localStorage to persist cart items.
- about.html — About page: company story and team profiles.
- contact.html — Contact page: contact information and a contact form (demo-only submission behavior).

Notes

- Tailwind is used via the official CDN (https://cdn.tailwindcss.com). You can replace this with your own setup if you prefer.
- Image placeholders use special Unsplash placeholders in the format required by the project: e.g. <img src="{{unsplash: description}}" />. Replace these placeholders with real image URLs or a server-side image resolver that understands the {{unsplash: ...}} format.
- The cart on index.html is a simple demo. It stores items in localStorage under the key serenitea_cart, allows adding/removing items, clearing the cart, and a mock checkout alert.

How to run

1. Download the files and keep them in the same folder.
2. Open index.html in your browser. Navigate to About and Contact using the links in the header.

Customization ideas

- Replace the Unsplash placeholders with actual image URLs or connect to the Unsplash API.
- Add persistent backend checkout endpoints and form handling.
- Convert to a single-page app or integrate with a framework for more complex features.

License

This demo is provided as-is for educational and prototyping use.
