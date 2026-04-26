## Dressify Hub | Flutter E‑Commerce App
Dressify Hub is a responsive e‑commerce frontend-only app built with Flutter (Dart) a proper multi‑screen mobile app experience. It focuses on UI/UX, navigation, and core shopping flow without authentication or backend.

## Main Features
Home: announcement bar, hero carousel, categories, best deals (demo)
Categories: responsive category grid → opens filtered products
Products: responsive grid with category filter, sorting, max price filter
Product Details: full info + add to cart + wishlist toggle
Search: real-time search results
Wishlist: view/remove saved items
Cart: quantity update, remove/clear items, subtotal + delivery fee (demo) + total
Checkout (UI Demo): address form validation + payment method selection (COD / Card Demo)
Order Success + Orders (UI Demo): place order, view orders list (session-based)
Data & Storage
Products come from a static list (lib/data/products.dart)
Cart + Wishlist persist offline using SharedPreferences
Orders are UI demo (in-memory, reset after restart)
Responsiveness
Works across mobile, tablet, and desktop/web using adaptive grids and max-width layout.

## Tech Stack
Flutter, Dart, Provider, SharedPreferences, intl.
