# 🏪 Amazon Seller API: Competitor & Storefront Intelligence

The **Amazon Seller API** is specifically designed for deep-level analysis of merchant operations. By crawling Amazon seller pages, this module retrieves comprehensive store information and categorized product lists, providing the raw data necessary for advanced competitor research and seller operation analysis.

## 🚀 Key Features

* **Seller Storefront Crawling:** Automated extraction of all products listed under a specific merchant's storefront.
* **Merchant Metadata:** Retrieve essential seller details including Merchant Name, Merchant Address, and official ratings.
* **Categorized Product Lists:** Data is organized by category, making it easier to analyze a competitor’s product mix and inventory focus.
* **Operational Benchmarking:** Use seller-level data to identify top-performing merchants and their market strategies.

## 📦 Structured Data Sample

Tailored for market analysts and brands who need to monitor the footprint of specific sellers across regional marketplaces.

```json
{
  "status": "success",
  "seller_info": {
    "merchant_name": "Premium Tech Europe",
    "merchant_id": "A3P5ROKL5A1OLE",
    "rating": 4.9,
    "merchant_address": "75008 Paris, France",
    "storefront_url": "[https://www.amazon.fr/sp?seller=A3P5ROKL5A1OLE](https://www.amazon.fr/sp?seller=A3P5ROKL5A1OLE)"
  },
  "product_inventory": [
    {
      "asin": "B07ZPKN6L1",
      "title": "Pro Wireless Mouse",
      "category": "Electronics",
      "price": 45.99,
      "currency": "EUR",
      "availability": "In Stock"
    }
  ]
}
```

