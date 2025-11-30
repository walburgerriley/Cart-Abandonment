# MyCoke360 Cart Abandonment Analysis
Senior Project for Master's Program MSBA

## Project Overview
Swire Coca-Cola’s MyCoke360 platform enables digital ordering for business customers, but many sessions end with items left in the cart and no order submitted. These incomplete sessions represent lost revenue and indicate friction in the ordering experience. Our goal was to understand where customers get stuck and identify actions that can improve order completion.

---

## How We Measured Cart Abandonment
We used a session-based definition:

- A session is a sequence of add-to-cart events occurring within 30 minutes of each other.
- A session was labeled abandoned if no purchase occurred within 72 hours after the session ended.

We also used the purchase-to-cart ratio to measure how often cart activity led to purchase behavior.

[Code found here](cart_abandonment_redefined.qmd)

---

## Findings
- Modeling showed that purchase history, especially the purchase to cart ratio, was the strongest driver of abandonment, with timing patterns and cart activity also playing important roles.
- The highest abandonment comes from high-intent users who browse deeply, add many items, and edit their carts but still fail to complete the order.
- Many short “quick-look” sessions were low intent and not the main opportunity for improvement.
- Behavioral indicators such as cart editing, number of adds, session duration, and purchase-to-cart ratio strongly predict abandonment.

---

## Business Value
Focusing improvements on high-intent users can increase completed orders, reduce frustration, and strengthen adoption of MyCoke360.

---

## Recommendations
- Streamline the checkout flow  
- Surface prices earlier  
- Send targeted reminders to at-risk customers. 
- AB Testing  
- Customer Survey  

