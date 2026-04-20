# Contoso Outdoors

Contoso Outdoors is a fictional enterprise retail organization that sells hiking and camping gear to outdoor adventuring enthusiasts. The [Contoso Outdoors dataset](https://github.com/nitya/contoso-outdoors) has been used in past demos and workshops including [Contoso Chat](https://aka.ms/aitour/contoso-chat).

## About Contoso Outdoors

Contoso Outdoors equips adventurers with premium gear for hiking, camping, and exploring the great outdoors. Their catalog spans tents, backpacks, sleeping bags, footwear, clothing, stoves, and camp furniture — all sourced from trusted outdoor brands.

## Data Available

This folder contains a curated product catalog with **20 products** across **7 categories** and **11 brands**.

<br/>

### 1. Data Files

| File | Description |
|------|-------------|
| `products.json` | Full product catalog with descriptions, pricing, brand, category, image paths, and manual links |
| `categories.json` | Products organized by category, each with a category description |
| `brands.json` | Products organized by brand |

<br/>

### 2. Product Categories

| Category | Description |
|----------|-------------|
| Tents | Camping shelters from 2-person to family-sized |
| Backpacks | Hiking and trekking packs |
| Sleeping Bags | Sleeping gear for various conditions |
| Hiking Footwear | Boots and shoes for trail use |
| Hiking Clothing | Apparel for outdoor activities |
| Camping Stoves | Portable cooking equipment |
| Camping Tables | Portable camp furniture |

**Brands:** AlpineGear, CampBuddy, CompactCook, CozyNights, EcoFire, HikeMate, MountainDream, MountainStyle, OutdoorLiving, PowerBurner, TrekReady

<br/>

### 3. Product Manuals & Images

The `manuals/` folder contains **20 detailed markdown product manuals** (`product_info_1.md` – `product_info_20.md`), one per product, with specifications, features, and care instructions.

The `images/` folder contains product images organized by product ID (`images/1/`, `images/2/`, etc.), with multiple images per product.

<br/>

## Product Item Example

Here's an example of a typical product in the Contoso Outdoors catalog (Tents):

### TrailMaster X4 Tent

![TrailMaster X4 Tent](./images/1/242e7165-7c79-4f97-8e63-280f9f8982e2.png)

**Additional Product Images:**

![Product Image 2](./images/1/42614d79-4013-4303-9750-7c48f3fb61a9.png) ![Product Image 3](./images/1/6a3111b5-3803-473b-a3dd-12056becea0a.png)

![Product Image 4](./images/1/cb803f98-9bfa-4156-b0ee-df0581ae2862.png) ![Product Image 5](./images/1/ff681635-0ce2-4c9a-b227-58de609e3a4e.png)

**Product Structure Elements:**

| Element | Value |
|---------|-------|
| **Product Name** | TrailMaster X4 Tent |
| **Product ID** | 1 |
| **Price** | $250.00 |
| **Category** | Tents |
| **Brand** | OutdoorLiving |
| **Description** | Durable polyester tent perfect for four occupants with water-resistant construction, mesh panels for airflow, multiple doors, and included carry bag. |
| **Key Features** | 4-person capacity, water-resistant rainfly, freestanding design, reflective guy lines, mesh panels, interior pockets |
| **Ideal For** | Overnight getaways and week-long camping adventures |
| **Images** | 5 product images available |
| **Manual** | /manuals/product_info_1.md |

Each product in the catalog has structured data including product metadata (ID, price, category, brand), detailed description, multiple product images, and a corresponding markdown manual with specifications and care instructions.

---