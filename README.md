Code bearbeiten ->

Sections: 
main-product.liquid
image-with-text.liquid
video-slider.liquid
image-banner-slider.liquid
O-Garantie.liquid


Snippets:
cart-drawer.liquid
product-variant-picker.liquid
product-media.liquid
product-media-gallery.liquid
buy-buttons.liquid

Assets:
base.css
component-cart-drawer.css
component-cart-items.css
image-banner-slider.css
section-main-product.css
global.js
Datei hinzufügen: c-style.css.liquid

Layout:
theme.liquid -> Suche nach „{{ 'base.css' | asset_url | stylesheet_tag }}“ und füge folgendes darunter ein: „{{ 'c-style.css' | asset_url | stylesheet_tag }}“

Config:
settings_schema.json
