# Spraymax Sea Salt Spray: listing guide

You'll end up with **3 separate products**:

| Product | Price | Compare-at (= MRP) | Description file |
|---|---|---|---|
| Spraymax Himalayan Sea Salt Spray – 100 mL *(existing)* | ₹449 | ₹600 | `description.html` |
| Spraymax Himalayan Sea Salt Spray – Pack of 2 *(new)* | ₹799 | ₹1,200 | `description-pack-of-2.html` |
| Spraymax Himalayan Sea Salt Spray – Pack of 3 *(new)* | ₹999 | ₹1,800 | `description-pack-of-3.html` |

The compare-at price is the label MRP (₹600 per bottle). Never sell above MRP.

The descriptions already link to each other by URL handle. **Use the handles below exactly**, or those links will break.

---

## Step 1: Update the existing single bottle

**Products → Spraymax Sea Salt Spray - 100 mL**

| Field | Value |
|---|---|
| **Title** | `Spraymax Himalayan Sea Salt Spray – 100 mL` |
| **Description** | Click `<>` (Show HTML), select all, then paste `description.html` |
| **Price / Compare-at** | 449 / 600 (no change) |
| **Product type** | `Hair Styling Spray` |
| **Tags** | `sea salt spray, hair volume, hair texture, single` |

**Search engine listing → Edit:**

| Field | Value |
|---|---|
| Page title | `Himalayan Sea Salt Spray for Hair Volume \| Spraymax` |
| Meta description | `Spraymax Himalayan sea salt spray adds instant volume and matte texture without stiffness or grease. Paraben & sulfate free. Free shipping across India.` |
| URL handle | `himalayan-sea-salt-spray` |

When you change the handle, **keep "Create a URL redirect" ticked** so the old `demo-sea-salt-spray` link keeps working.

---

## Step 2: Create the Pack of 2

**Products → Add product**

| Field | Value |
|---|---|
| **Title** | `Spraymax Himalayan Sea Salt Spray – Pack of 2` |
| **Description** | `<>` (Show HTML), then paste `description-pack-of-2.html` |
| **Price** | 799 |
| **Compare-at price** | 1200 |
| **SKU** | `SM-SSS-100-2` |
| **Weight** | 400 g (check against a packed parcel) |
| **Physical product** | ticked |
| **Inventory** | see "Stock" below |
| **Product type / Vendor** | `Hair Styling Spray` / `Spraymax` |
| **Tags** | `sea salt spray, hair volume, bundle` |
| **Sales channels** | Online Store, plus any others you use |
| **Status** | **Draft** until you've checked it, then **Active** |

**Search engine listing:**

| Field | Value |
|---|---|
| Page title | `Sea Salt Spray Pack of 2 (2 × 100 mL) \| Spraymax` |
| Meta description | `Get 2 Spraymax Himalayan sea salt sprays for ₹799, ₹400 per bottle. Instant hair volume and matte texture. Free shipping across India.` |
| URL handle | `himalayan-sea-salt-spray-pack-of-2` |

---

## Step 3: Create the Pack of 3

The fastest way is to open the Pack of 2, click **⋯ → Duplicate**, then change these:

| Field | Value |
|---|---|
| **Title** | `Spraymax Himalayan Sea Salt Spray – Pack of 3` |
| **Description** | paste `description-pack-of-3.html` |
| **Price** | 999 |
| **Compare-at price** | 1800 |
| **SKU** | `SM-SSS-100-3` |
| **Weight** | 600 g |
| **Tags** | `sea salt spray, hair volume, bundle, best value` |
| Page title | `Sea Salt Spray Pack of 3 (3 × 100 mL) \| Spraymax` |
| Meta description | `Our best value pack: 3 Spraymax Himalayan sea salt sprays for ₹999, just ₹333 per bottle. Save ₹348. Free shipping across India.` |
| URL handle | `himalayan-sea-salt-spray-pack-of-3` |

---

## Stock

Each product has its **own** stock count. Selling a Pack of 3 does **not** reduce the single bottle's stock, and Shopify can't link them without an app.
Split your real bottles across the three products. For example, with 150 bottles:
- Single: 60 bottles → stock **60**
- Pack of 2: 40 bottles → stock **20**
- Pack of 3: 50 bottles → stock **16**

Top them up from Shopify as each one sells. If you'd rather not juggle this, untick **Track quantity** and keep an eye on your real stock yourself.

---

## Reviews on the pack pages

Your 14 Judge.me reviews are attached to the single-bottle product, so the new pack pages will start with **0 reviews**. Options:
- In Judge.me, look for **Product Groups**. It lets several products share one set of reviews, but it may need a paid Judge.me plan. Check in the app.
- If not, each pack description already links to the single bottle. You can also add a review-carousel or testimonial block on the pack pages in the theme editor.

---

## Showing the packs on the single-bottle page

Your product page already has a **"Pairs well with"** block. Use it to show the packs:
1. Install Shopify's free **Search & Discovery** app.
2. **Recommendations → Spraymax Himalayan Sea Salt Spray – 100 mL → Complementary products:** add Pack of 3, then Pack of 2.
3. "Pairs well with" now shows both packs under Add to cart.

Also add both packs to your **Home page** collection (Products → each pack → Collections), so they show in Catalog and on the homepage.

---

## Photos

Your current photos are WhatsApp-compressed (`IMG-…-WA00xx.jpg`). Re-upload the originals. Use square images, 2048 × 2048 px if you can.

**Single bottle:**

| # | Shot | Alt text |
|---|---|---|
| 1 | Bottle on a plain background | `Spraymax Himalayan Sea Salt Spray 100 mL bottle` |
| 2 | Before / after hair | `Hair before and after using Spraymax sea salt spray` |
| 3 | How to use: Shake, Spray, Style | `How to use Spraymax sea salt spray` |
| 4 | "What's not in it" icons | `Spraymax is paraben, sulfate and silicone free` |
| 5 | Back label (ingredients) | `Spraymax sea salt spray ingredients label` |
| 6 | Real customer review screenshots | `Spraymax customer reviews` |

**Pack of 2 / Pack of 3:** the **first image must show 2 or 3 bottles together**, with "Pack of 3 · ₹999 · Save ₹348" on it.
After that, reuse images 2–6 from the single bottle. Alt text: `Spraymax sea salt spray pack of 3 bottles` (or 2).

---

## Theme fixes (Online Store → Themes → Customize → product page)

- **Ingredients section:** change *"selected for max benefits to the **skin**"* to *"…for your **hair**"*.
- **"TEXTURE: clean / VOLUME: Safe-styling" boxes:** change them to something meaningful, for example `HOLD: Light–Medium` and `FINISH: Matte`.
- **Near Add to cart:** add a text block, for example `🚚 Free shipping across India · Secure prepaid checkout (UPI, cards, net banking)`.

## Homepage and store settings (Online Store → Preferences)

- **Homepage title:** `Spraymax – Himalayan Sea Salt Spray for Hair Volume | India`
- **Homepage meta description:** `India's Himalayan sea salt spray for instant hair volume and natural texture. Clean formula, no parabens or sulfates. Free shipping India-wide.`
- **Social sharing image:** upload the hero bottle photo.

Leave the shipping policy as it is.

---

## Final check

- [ ] All 3 products show in the Catalog with the right price and strike-through MRP.
- [ ] The links inside each description open the right pack page.
- [ ] The old link `spraymax.in/products/demo-sea-salt-spray` redirects to the single bottle.
- [ ] "Pairs well with" on the single bottle shows both packs.
- [ ] Add each product to the cart. The checkout shows ₹449 / ₹799 / ₹999 with free shipping and no COD.
- [ ] Check all three on your phone.
