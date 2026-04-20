# Zava Retail
Zava is a fictional enterprise retail organization that is exploring AI enablement across its products and services. 

## About Zava DIY

Zava DIY is the chain of home improvement stores from Zava. They serve homeowners, contractors, and hobbyists with a wide range of products spanning hand tools, power tools, hardware, lumber and building materials, plumbing, electrical, paint and finishes, garden and outdoor supplies, and storage and organization.

## About Cora AI

Cora is the planned AI Shopping Assistant for Zava DIY stores. It supports conversational interactions with online and in-store customers, helping them find the right products and take next steps to work on their DIY projects. Zava wants to design Cora as a _multi-agent_ experience with _custom behaviors_ and _performance goals_.

For instance: 
1. An inventory agent - checks if a product is in stock.
1. A loyalty agent - can compute discounts for a customer.
1. A vision agent - can analyze images & provide context.
1. A weather agent - uses local weather to recommend products.

Custom behaviors:

1. Agent should be polite - always start by greeting customer.
1. Agent should be helpful - always end with offer to do more.
1. Agent should be reliable - always provide valid responses
1. Agent should be concise - keep answers short & actionable.

Target Objectives:
1. Agent should pass quality assessments.
1. Agent should pass safety assessments.
1. Agent should pass performance assessments.
1. Agent should be cost-effective to deploy.

<br/>

## Data Available

This folder contains a curated subset of the Zava DIY product catalog with **422 products** across **9 categories**.

<br/>

### 1. Data Files

| File | Description |
|------|-------------|
| `products.csv` | Full product catalog (422 products) with SKU, price, description, stock level, image path, and category |
| `products.json` | JSON version of the product catalog |
| `products-paints.csv` | Curated set of ~50 products from the Paint & Finishes category |
| `products-md.csv` | Curated set of products that have corresponding markdown manuals in `manuals/` |
| `generate_product_files.py` | Script used to generate the per-product markdown manual files |

<br/>

### 2. Product Categories

| Category | Description |
|----------|-------------|
| Hand Tools | Hammers, wrenches, screwdrivers, and more |
| Power Tools | Drills, saws, sanders, grinders, and more |
| Hardware | Fasteners, hinges, brackets, and cabinet hardware |
| Lumber & Building Materials | Plywood, boards, molding, insulation, and subfloring |
| Plumbing | Faucets, valves, pipes, and fittings |
| Electrical | Breakers, outlets, cables, and wiring accessories |
| Paint & Finishes | Paints, primers, brushes, rollers, and drop cloths |
| Garden & Outdoor | Fertilizers, potting mixes, pruners, and lawn care |
| Storage & Organization | Cabinets, shelving, and storage solutions |

<br/>

### 3. Product Manuals

The `manuals/` folder contains **211 detailed markdown product manuals**, each covering specifications, features, safety information, and usage instructions. These manuals correspond to products listed in the `products-md.csv` file, which contains **230 curated products** across all 9 categories.

**Categories covered in manuals:**

| Category | Count | Examples |
|----------|-------|----------|
| Hand Tools | 15 | Hammers, wrenches, hex sets, pruners |
| Power Tools | 28 | Drills, saws, sanders, grinders, impact drivers |
| Hardware | 33 | Hinges, brackets, fasteners, cabinet hardware |
| Lumber & Building Materials | 24 | Plywood, boards, molding, insulation, subflooring |
| Plumbing | 19 | Faucets, valves, pipes, connectors, stops |
| Electrical | 20 | Breakers, outlets, cables, wiring, connectors |
| Paint & Finishes | 25 | Paints, primers, brushes, rollers, drop cloths |
| Garden & Outdoor | 22 | Fertilizers, potting mixes, pruners, soil, mulch |
| Storage & Organization | 24 | Cabinets, shelving, storage boxes, organizers |

<br/>

## Product Item Example

Here's an example of a typical product in the Zava DIY catalog (Paint & Finishes):

### Aerosol Primer Spray

![Aerosol Primer Spray](https://raw.githubusercontent.com/microsoft/ai-tour-26-zava-diy-dataset-plus-mcp/refs/heads/main/images/paint_%26_finishes_spray_paint_aerosol_primer_spray_20250620_193704.png)

**Product Structure Elements:**

| Element | Value |
|---------|-------|
| **Product Name** | Aerosol Primer Spray |
| **SKU** | PFSP000026 |
| **Price** | $7.00 |
| **Category** | PAINT & FINISHES → SPRAY PAINT |
| **Stock Level** | 76 units available |
| **Description** | Fast-drying spray primer for metal, wood, and plastic with excellent adhesion and coverage. |
| **Key Features** | Professional quality, reliable performance, versatile application |
| **Ideal For** | Professional contractors, DIY projects, workshop applications |

Each product in the `products-md.csv` and corresponding manual in `manuals/` contains similar elements: product metadata (SKU, price, category, stock), product image, detailed description, features, and use cases.

---

> **Note:** These files were created specifically to support key workshops and curricula in this repo. If you are building your own Zava scenarios, please reference and use the official [Zava DIY Dataset Plus MCP](https://github.com/microsoft/ai-tour-26-zava-diy-dataset-plus-mcp) instead.