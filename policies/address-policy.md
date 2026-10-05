# Fixing incomplete-address problems

Three parts:
1. **Stop bad addresses at checkout** (fewer problems to begin with)
2. **A clear written policy** (so there's nothing to argue about)
3. **Ready-made replies for staff** (copy, paste, done)

Your delivery timelines (1–3 days processing, 7–14 days delivery) are **not changed** anywhere below.

---

## Part 1: Stop bad addresses at checkout (10 minutes)

### A. Shopify checkout settings
**Settings → Checkout → Customer information:**

| Setting | Change to |
|---|---|
| Shipping address phone number | **Required** |
| Address line 2 (apartment, suite, etc.) | **Optional** (leave it; making it required annoys people in houses) |
| Company name | **Don't include** (less clutter) |
| Use address autocompletion | **On** (if the option is shown) |

### B. Razorpay Magic Checkout
Your store has Razorpay Magic Checkout installed. If customers check out through Razorpay's popup instead of the normal Shopify checkout, **the address is collected there**, and the Shopify settings above won't apply.
Check this by placing a test order. If the address form is Razorpay's, open your **Razorpay dashboard → Magic Checkout settings** and:
- make phone number mandatory
- turn on PIN code auto-fill for city and state
- turn on any address validation or "landmark" field it offers

### C. A warning in the cart, before they pay
**Online Store → Themes → Customize → Cart page** (and the cart drawer, if your theme has one) → **add a Text block above the Checkout button:**

> 📦 **Please enter your FULL address:** house/flat no., building, street, area, landmark, city and PIN code, plus a phone number you'll answer.
> Orders with incomplete addresses or unreachable phone numbers **can't be delivered on time** and may be returned to us. See our [Shipping Policy](/policies/shipping-policy).

### D. Confirm before dispatch (optional, but it ends most disputes)
Before shipping, have staff send one WhatsApp or SMS: *"Please confirm your address: [address]. Reply YES within 24 hours."*
- Customer confirms → ship it. If it's wrong later, it's on record that they confirmed it.
- Customer replies with a fix → update the address in Shopify, then ship.
- No reply in 24 hours → ship to the address as entered. The policy covers you.

---

## Part 2: Policy text (paste into Settings → Policies)

### Add this to your Shipping Policy
Replace your existing **"Address Accuracy"** section with the section below. Leave the rest of the policy (timelines etc.) exactly as it is.
Fill in the `[ ]` values first. Suggested values are in brackets.

> **Shipping Address & Delivery Responsibility**
>
> **1. Complete address required.** You are responsible for entering a complete and accurate shipping address at checkout, including house/flat number, building name, street, area, landmark, city, state and PIN code, along with a working phone number. We ship orders exactly as entered at checkout.
>
> **2. Address changes.** Address changes are accepted only **before your order is dispatched**, by contacting us at [email / WhatsApp number]. Once an order is dispatched, the address cannot be changed.
>
> **3. Delivery timelines.** Delivery timelines apply only to complete and correct addresses. We are not responsible for delays caused by an incomplete or incorrect address, or by the phone number being unreachable.
>
> **4. Failed delivery.** If an order cannot be delivered because the address is incomplete or incorrect, the phone is unreachable, or the delivery is refused, the courier will return it to us. In that case you can choose to:
> - **(a) Re-ship:** we send the order again after you pay a re-shipping fee of **₹[99]**, or
> - **(b) Refund:** we refund the order amount minus **₹[150]**, which covers the forward and return shipping costs.
>
> Please tell us your choice within **[7] days** of being notified. Refunds are processed within [7] business days to the original payment method.
>
> **5. Delivered orders.** Orders shown as delivered by the courier to the address entered at checkout are considered delivered. If you did not receive an order marked as delivered, contact us within **[48 hours]** and we will raise it with the courier.

### Add this to your Refund Policy
> **Undelivered orders:** If an order is returned to us because of an incomplete or incorrect address, an unreachable phone number or a refused delivery, the order amount will be refunded minus ₹[150] for shipping costs, or re-shipped for ₹[99], as described in our Shipping Policy.

### Why "refund minus shipping" and not "no refund"
India's e-commerce consumer rules don't let you keep the full payment for an order the customer never received. Deducting the **actual shipping cost** is fair, it's clearly disclosed, and it holds up if a customer complains to a payment provider or consumer forum. "No refund" doesn't, and it costs you more time in chargebacks than it saves.
Set ₹[150] to your real forward + return courier cost for one parcel.

---

## Part 3: Ready-made staff replies

Staff should **send the matching reply and stop**. No back-and-forth. The policy does the arguing.

**1. Address looks incomplete (before dispatch)**
> Hi [Name], thanks for ordering from Spraymax! Your address seems incomplete: [what's missing, e.g. "house/flat number"]. Please reply with your full address so we can dispatch your order. As per our Shipping Policy, orders ship to the address as entered if we don't hear back within 24 hours.

**2. Customer wants an address change after dispatch**
> Hi [Name], your order has already been dispatched, so the address can't be changed now (Shipping Policy, point 2). You can contact the courier directly using your tracking link: [link]. If the parcel comes back to us, we'll offer you a re-ship or a refund as per our policy.

**3. Order delayed because of incomplete address or unreachable phone**
> Hi [Name], the courier couldn't complete delivery because [the address was incomplete / your phone was unreachable]. Delivery timelines apply only to complete addresses (Shipping Policy, point 3). We've shared the correct details with the courier and it should reach you soon. Tracking: [link].

**4. Parcel returned to us (RTO)**
> Hi [Name], your parcel was returned to us because [reason]. As per our Shipping Policy (point 4), you can choose:
> (a) re-ship for ₹[99], or
> (b) a refund of ₹[amount minus 150].
> Please reply with your choice within 7 days.

**5. Customer keeps arguing**
> We understand the frustration. Our Shipping Policy is shown at checkout and on our website: [spraymax.in/policies/shipping-policy]. We've offered [the options above], and that's the best we can do. Let us know how you'd like to proceed.

Then don't reply further unless they choose an option.

---

## Checklist
- [ ] Checkout: phone number **Required**
- [ ] Test order: check whether Razorpay Magic Checkout collects the address, and tighten its settings if so
- [ ] Cart: full-address warning added above the Checkout button
- [ ] Shipping Policy: "Address Accuracy" section replaced
- [ ] Refund Policy: "Undelivered orders" line added
- [ ] Staff: replies saved as quick replies in WhatsApp Business
