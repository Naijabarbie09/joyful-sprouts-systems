# Cart shipping message: DRAFT for owner approval (not live)

Verified 2026-11-27 (Shopify delivery profile): Free Standard Shipping at order total >= $75; UPS and USPS rates below that.
NOT VERIFIED: whether Shopify tests the $75 on the total before or after discounts.

**Rule for the amount remaining:** compute it from the cart total AFTER discounts. If Shopify actually tests before discounts, a shopper sees a shortfall they do not really have, which under-promises. The reverse would over-promise, so this is the safe choice.

Below $75:
> You are $X away from free shipping. Free standard shipping on orders of $75 or more. Otherwise, shipping is calculated at checkout.

At or above $75:
> You have unlocked free standard shipping.

Placement: below the subtotal in the cart page and the cart drawer, mobile first.
Test before publishing: Starter Set alone ($60.80 with the sale), Starter Set plus bodysuit, Everyday Pair plus bodysuit. Confirm the message matches what checkout shows.
