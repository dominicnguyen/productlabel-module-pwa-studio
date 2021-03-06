# Auto Related Rroducts  module for Magento PWA Studio

This module acts as an add-on for [Mageplaza's Auto Related Rroducts extension](https://www.mageplaza.com/magento-2-automatic-related-products/) to make it work with Magento PWA Studio.

End result: https://automatic-related-products.pwa-commerce.com/

## Requirements

- Magento version 2.4.* or >= 2.3.5
- Got [Mageplaza Product Label extension](https://www.mageplaza.com/magento-2-product-labels/) and [Product Label GraphQL](https://github.com/mageplaza/magento-2-product-labels-graphql) installed

## Installation

### 1. Init project
```
npm init @magento/pwa@1.1.2
```

Fill in your project information and `cd` into it.

### 2. Start the project

From the root directory of the project you created above, clone the repository:

```
  git clone https://github.com/Simicart/productlabel-module-pwa-studio ./@simicart/label
```

### 3. Modify .env

Change the .env MAGENTO_BACKEND_URL with your Magento site URL, or use our demo URL:

```
  MAGENTO_BACKEND_URL=https://mpmed.pwa-commerce.com/
```
### 4. Modify package.json

Modify the dependencies of your project to add Shop By Brand extension.

```
  "dependencies": {
    "@magento/pwa-buildpack": "~7.0.0",
    "@simicart/label": "link:./@simicart/label"
  },
```

### 5. Install and Start Project

```
  yarn install && yarn watch
```
