---
title: "Revenue Cloud Migrations Are Not One-Size-Fits-All: Your Starting Point Changes Everything"
description: "Whether you're migrating from Salesforce CPQ, Oracle, Conga, or a homegrown system, your Revenue Cloud implementation path looks completely different. Here's what actually changes."
date: 2026-03-03
tags: ["Revenue Cloud", "CPQ", "Q2C", "Implementation", "Migration"]
ogImage: /og/og-article-1.png
draft: false
---

Every Revenue Cloud implementation I've walked into has one thing in common: the client thinks their situation is unique, and they're right — but not always in the ways they expect.

The starting point matters enormously. Where you're coming from shapes your data migration complexity, your integration risk, your user adoption curve, and how long it actually takes to go live. Treating a migration from Salesforce CPQ the same way you'd treat a migration off a 15-year-old homegrown system is a mistake that adds months and budget to a project before it even begins.

Here's what actually changes depending on where you're starting.

## Coming from Salesforce CPQ (Steelbrick)

This is the transition getting the most attention right now, given Salesforce's end-of-sale announcement. The instinct is to assume this is the easiest path because you're staying in the Salesforce ecosystem. That instinct is partially right and partially dangerous.

What's easier: your data is already in Salesforce. Products, price books, accounts, opportunities, none of that needs to move. Your users are already on the platform. Your existing Salesforce integrations don't need to be rebuilt from scratch. Unless, you try to optimize your product catalog along the way. Which, why wouldn't you since you're going to a much more feature rich catalog?

What's harder than people expect: CPQ and Revenue Cloud have fundamentally different data models. The way you've configured product rules, pricing waterfalls, and approval chains in CPQ doesn't map 1:1 into Revenue Cloud. Any team that built heavy customizations in CPQ, and most enterprise teams did, is essentially doing a redesign, not a migration. The temptation to lift-and-shift your CPQ configuration is one of the most expensive mistakes I see on these projects.

The key question to ask before you start: How much of your current CPQ configuration is business logic vs. workarounds for CPQ's limitations? If the honest answer is "a lot of workarounds," Revenue Cloud is your chance to fix that but you need to budget for it.

## Coming from Oracle CPQ

Oracle CPQ is a capable enterprise tool, and the organizations using it tend to have sophisticated pricing models: often multi-dimensional pricing, complex bundles, and deep ERP integrations. Moving to Revenue Cloud from Oracle means you're not just changing a configure-price-quote tool. You're changing your integration architecture.

Oracle CPQ clients almost always have a tightly coupled Oracle ERP connection. Revenue Cloud will need to replicate that integration with your ERP whether that's Oracle EBS, Oracle Fusion, or SAP. This is typically the longest part of the project and the highest-risk dependency. Unless, of course, you work with my team who has already developed best practice templates for these types of integrations.

The good news: teams coming from Oracle CPQ usually have well-documented pricing logic. The business requirements are known. The hard part is the technical translation, not the requirements discovery.

The key question to ask before you start: Who owns the ERP integration today, and are they in the room? If your ERP team is a dependency and not a partner on the implementation, you will miss your go-live date.

## Coming from Conga (Apttus)

Conga implementations tend to be sprawling. What started as a CPQ tool often evolved to own contract generation, CLM, billing, and sometimes revenue recognition. The footprint is frequently larger than anyone on the current team remembers.

Before scoping a Revenue Cloud migration from Conga, you need an honest audit of what Conga actually owns in your process. I've seen discovery calls where a client says "we just use Conga for quoting" and three weeks into discovery we find out Conga is also generating every customer contract, managing renewals, and feeding the billing system.

Conga to Revenue Cloud also tends to surface CLM gaps. Revenue Cloud's native CLM capability is growing, but if you've built sophisticated contract workflows in Conga, you need to evaluate whether Revenue Cloud closes that gap or whether you're introducing a new point solution for contracts.

The key question to ask before you start: Do a full process audit before scoping. Map every step from quote to cash and confirm which system owns each step today. Don't scope based on what people think Conga does, scope based on what it actually does.

## Coming from a Homegrown System

This is the most underestimated migration path. Homegrown CPQ systems, usually a combination of spreadsheets, custom Salesforce development, and tribal knowledge, feel simple because "we built it ourselves." In practice, they're the hardest migrations.

The complexity isn't in the technology. It's in the undocumented logic. Every custom system has pricing rules, approval thresholds, and edge case handling that live in someone's head or in a spreadsheet maintained by one person. Migrating to Revenue Cloud means surfacing all of that logic, documenting it, and deciding what to keep, what to fix, and what to leave behind.

The silver lining: teams coming from homegrown systems have the most to gain. They've been operating with significant manual effort and workarounds. Revenue Cloud, implemented well, is a step-change improvement. The ROI is usually the clearest of any migration path.

The key question to ask before you start: Identify your system owner, the person who knows how everything works. If that person isn't actively involved in the implementation, you will spend months in discovery that could have been weeks.

## The One Thing That's True Regardless of Starting Point

No matter where you're coming from, the biggest risk is the same: scoping the technical migration without first aligning on the future-state process.

Revenue Cloud is not just a better version of whatever you have today. It's an opportunity to redesign how your organization quotes, contracts, and bills. Teams that use the migration as a forcing function to clean up their Q2C process consistently outperform teams that try to replicate their current state in a new system.

The starting point changes the technical path. The destination, a clean, scalable quote-to-cash process, should be the same.

---

I work on Revenue Cloud and Q2C implementations at Slalom. If you're evaluating a migration and want a candid conversation about your specific starting point, connect with me on [LinkedIn](https://linkedin.com/in/carlosali).
