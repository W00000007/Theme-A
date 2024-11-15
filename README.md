Komplettes Theme: finales_theme.zip

Bisheriges Theme überarbeiten:
Code bearbeiten ->

Sections: <br>
main-product.liquid<br>
image-with-text.liquid<br>
video-slider.liquid<br>
image-banner-slider.liquid<br>
O-Garantie.liquid<br>


Snippets:<br>
cart-drawer.liquid<br>
product-variant-picker.liquid<br>
product-media.liquid<br>
product-media-gallery.liquid<br>
buy-buttons.liquid<br>

Assets:<br>
base.css<br>
component-cart-drawer.css<br>
component-cart-items.css<br>
image-banner-slider.css<br>
section-main-product.css<br>
global.js<br>
Datei hinzufügen: c-style.css.liquid<br>

Layout:<br>
theme.liquid -> Suche nach „{{ 'base.css' | asset_url | stylesheet_tag }}“ und füge folgendes darunter ein: „{{ 'c-style.css' | asset_url | stylesheet_tag }}“

Config:<br>
settings_schema.json
