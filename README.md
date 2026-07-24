# IVO Marketplace — e-commerce plugin downloads

Public distribution point for the **IVO Marketplace** plugins/extensions.
This repository holds only the built, installable packages — the plugin
source lives in a separate private repository.

Each platform folder always contains the **latest** package under a stable
filename, so the download links below never change between releases.

## Downloads

| Platform | File | Download (latest) |
|----------|------|-------------------|
| OpenCart 4 | `opencart/ivo_marketplace.ocmod.zip` | https://raw.githubusercontent.com/ivo-md/ecommerce-plugins/main/opencart/ivo_marketplace.ocmod.zip |
| OpenCart 3 | `opencart/ivo_marketplace-oc3.ocmod.zip` | https://raw.githubusercontent.com/ivo-md/ecommerce-plugins/main/opencart/ivo_marketplace-oc3.ocmod.zip |
| WooCommerce | `woocommerce/ivo-marketplace-woocommerce.zip` | https://raw.githubusercontent.com/ivo-md/ecommerce-plugins/main/woocommerce/ivo-marketplace-woocommerce.zip |
| Magento 2 | `magento/ivo-marketplace-magento-latest.zip` | https://raw.githubusercontent.com/ivo-md/ecommerce-plugins/main/magento/ivo-marketplace-magento-latest.zip |
| PrestaShop | `prestashop/ivo-marketplace-prestashop-latest.zip` | https://raw.githubusercontent.com/ivo-md/ecommerce-plugins/main/prestashop/ivo-marketplace-prestashop-latest.zip |

## Updating a package

Replace the file under the relevant platform folder (keeping the same
filename) and push to `main`. The raw URL updates automatically; append a
`?v=<version>` query string on the linking side to bust any CDN cache.

Installation and configuration steps for each platform are documented in the
IVO merchant help center.
