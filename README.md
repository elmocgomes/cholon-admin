# Cholon Admin Portal (static UI)

This is the static HTML front-end for the Cholon + Maven analytics admin portal. The JSON API lives in a separate Supabase Edge Function.

Usage: open `index.html?token=<WEBHOOK_TOKEN>` in a browser.

The token is a shared secret; never share the URL publicly. The HTML itself contains no secrets — only the public Supabase project URL.
