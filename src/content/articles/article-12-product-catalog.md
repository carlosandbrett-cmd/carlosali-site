---
title: "Your Product Catalog Is the Foundation of Your CPQ Implementation. Most Teams Get It Wrong."
description: "Teams design their Revenue Cloud catalog for the future and ignore what's already in the field. Start from your actual customer orders and install base, or you'll build a system that can't support the business on day one."
date: 2026-05-26
tags: ["Revenue Cloud", "CPQ", "Q2C", "Product Catalog", "Implementation"]
draft: false
---

Before you configure a single pricing rule or approval workflow in Revenue Cloud, the state of your product catalog will determine whether your implementation succeeds or struggles. Teams that underinvest in catalog design spend months fighting configuration problems that are actually data problems in disguise.

Most of those problems trace back to the same mistake: designing the catalog for the business you want to be, without accounting for the business you already are.

## Start with Customer Orders, Not Your Product Hierarchy

The instinct for most teams is to open up the product catalog, identify the mess, and rationalize it from the inside out — consolidating SKUs based on how product management thinks about the portfolio. That approach produces a clean taxonomy that often has little relationship to how customers actually buy.

**Start from your order data instead.** Pull your last two years of closed orders and look at what's on them — what products appear, in what combinations, at what price points, with what terms. This is your real product catalog. It's the one your customers are paying for, the one your reps know how to sell, and the one your Revenue Cloud configuration needs to support from go-live.

What you'll find almost always surprises teams. The product combinations that actually sell are rarely the ones product management intended. The pricing that closes deals includes discounts, adjustments, and custom terms that don't exist in the official price list. The SKUs on active contracts include retired products that no one is selling anymore but hundreds of customers are still paying for. None of that shows up when you rationalize from the inside out.

## The Install Base Problem

Your order history tells you what sold. Your install base tells you what's currently under contract — and both inputs are required to design a catalog that works on day one.

Revenue Cloud go-live isn't a cutover from old to new. Most organizations run new business through the new system while continuing to service existing customers under their current terms. The old model doesn't disappear; it has to run alongside the new one. That means the system needs to support every product variant, pricing structure, and contract term that a current customer is on — not just the clean new models you're building for future business.

Teams that ignore the install base discover this the hard way. They build a catalog optimized for new selling motions, go live, and immediately find that renewal quoting, upsell transactions, and add-on orders for existing customers can't be processed through the new system. The install base ends up handled manually or through workarounds, defeating much of the point of the implementation.

**Map your install base before you design the catalog.** What products are customers currently on? What price points are they paying? What contract terms are active? The catalog has to support all of it. Some of that means migrating legacy SKUs into Revenue Cloud even if they're no longer sold. Some of it means preserving pricing tiers that exist only because a specific customer cohort was grandfathered in. None of it is optional if you want the system to carry the full business.

## SKU Rationalization Grounded in Reality

SKU proliferation is a real problem. Most enterprise catalogs have grown organically over years, with duplicates, retired products, regional variants, and one-off configurations that were never cleaned up. Migrating that mess into Revenue Cloud embeds it into the new system.

The right answer isn't to preserve everything or to rationalize aggressively based on internal taxonomy. It's to let your order data and install base tell you which complexity is real and which is accidental.

Real complexity is a SKU that appears on hundreds of active contracts and needs to be renewable and quotable. That stays. Accidental complexity is a SKU that was created for a one-time deal in 2019, has never appeared on another order, and has no active contracts. That goes. The audit question for every SKU isn't "does this belong in our product hierarchy" — it's "does any customer have this, or will any rep ever quote it?"

**Let order frequency and install base presence drive rationalization decisions.** Product managers will push back on consolidation. Sales will argue that every variant is necessary. The order data settles the argument. If it's not on a contract and hasn't appeared on a quote in two years, it doesn't need to live in the new system.

## Bundle Design from Real Order Patterns

Bundles are where Revenue Cloud delivers significant value — and where implementations get complicated. The same principle applies: design from actual customer behavior, not from how you think bundles should work in theory.

Look at your order history and identify the combinations that actually get sold together. Those are your real bundles. Then look at the combinations customers have added over time through amendments and upsells — that tells you how bundles grow in the field. Build your bundle logic to support both the initial sale and the typical expansion path, because renewals and add-ons on existing bundles will be some of your highest-volume transactions from day one.

The test before you go live: can a rep take a real existing customer account, look up what they currently have, and generate a renewal quote or an upsell order entirely within the system? If the answer is no for a meaningful percentage of your install base, you have a catalog gap that will show up immediately after go-live.

## New Selling Models Go on Top, Not Instead Of

Revenue Cloud enables selling models that are difficult or impossible to manage manually — usage-based pricing, flexible bundles, automated renewals, multi-year ramp deals. Those capabilities are part of why organizations invest in the platform.

The mistake is treating those new models as the primary design objective and treating the existing business as a migration project you'll get to later. The existing business is the primary design requirement. It's the revenue your organization is protecting.

Build the catalog to support your current customers and current selling motions first. Then layer new pricing models and selling structures on top of that foundation. The new models are additions to a system that already works, not replacements for a system that doesn't exist yet.

Organizations that sequence it the other way — building for new business first and treating existing business as a legacy problem — spend the first year of post-go-live managing exceptions for customers the system can't handle. That's the outcome the catalog design is supposed to prevent.

---
*I work on Revenue Cloud and Q2C implementations at Slalom. Connect with me on [LinkedIn](https://linkedin.com/in/carlosali) if you want to talk through catalog design before your project kicks off.*
