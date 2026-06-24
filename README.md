# MAISON — Editorial Luxury Shopify Theme

Black & white minimalist Shopify theme inspired by chanel.com and prada.com.

## Import to Shopify

1. Zip the contents of this folder (the `assets/`, `config/`, `layout/`, `locales/`, `sections/`, `snippets/`, `templates/` folders must be at the **root** of the zip).
2. In Shopify admin: **Online Store → Themes → Add theme → Upload zip file**.
3. Click **Customize** to edit sections, images, and copy in the theme editor.

A pre-built zip is provided as `maison-theme.zip`.

## Structure

- `layout/theme.liquid` — global shell
- `templates/index.json` — homepage section composition
- `sections/` — hero, marquee, services, gallery, stats, process, reviews, contact, header, footer
- `templates/` — product, collection, cart, page, search, 404, customers (login/register/account)
- `assets/theme.css` — design system (Cormorant Garamond + Inter, B&W)
- `config/settings_schema.json` — theme settings exposed in editor

## Customizing

Open the theme editor in Shopify to:
- Swap hero image and copy
- Reorder homepage sections
- Edit categories, gallery images, stats, process steps, press reviews
- Update brand name, social links, colors
