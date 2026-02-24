---
title: "ACV vs. ARR vs. TCV — Why Getting These Wrong Breaks Your CPQ Design"
description: "Picking the wrong revenue metric when designing your CPQ system creates broken approvals, bad reporting, and misaligned compensation. Here's how to choose correctly."
date: 2026-03-10
ogImage: /og/og-article-2.png
tags: ["Revenue Metrics", "CPQ", "Q2C", "ACV", "ARR"]
draft: false
---

Revenue metrics look simple until you're six months into a CPQ implementation and your sales team is approving deals based on the wrong number, your commission plan is paying out on revenue that hasn't been earned, and your CFO is asking why ARR in the CRM doesn't match ARR in the finance system.

This is what happens when you don't align on metric definitions before you configure CPQ. It's one of the most common and most avoidable mistakes in Q2C implementation.

## What These Metrics Actually Mean

Let's be precise, because the definitions matter more than most teams realize.

**ACV (Annual Contract Value)** is the value of a contract normalized to one year. A three-year $300K deal has an ACV of $100K. A six-month $50K deal has an ACV of $100K. ACV ignores duration — it tells you the annualized run rate of a specific contract.

**ARR (Annual Recurring Revenue)** is the normalized annual value of all recurring revenue across your customer base. ARR excludes one-time fees, professional services, and non-recurring items. It only counts revenue that's expected to repeat. ARR is a portfolio metric — it tells you the health and trajectory of your revenue base.

**TCV (Total Contract Value)** is the total revenue you expect from a contract over its full term, including everything: recurring fees, one-time setup fees, professional services, and any other contractual commitments. A three-year $300K recurring deal with a $50K implementation fee has a TCV of $350K.

These are not interchangeable. They answer different questions, and they're designed for different audiences.

## How Getting This Wrong Breaks Your CPQ

CPQ systems use metrics to trigger business logic. Approval thresholds, discount authorization levels, commission calculations, contract terms — all of this gets configured against a number. If that number is the wrong metric, every downstream decision is wrong.

**Broken approval thresholds.** Your CPQ requires VP approval for deals over $500K. But $500K of what? If the threshold is TCV and your sales reps are quoting three-year deals, almost every enterprise deal hits the VP approval threshold. If the threshold is ACV, most deals flow through without delay. These produce very different selling experiences and very different approval workloads. Get this wrong in configuration and you've either over-controlled your sales process or created compliance exposure.

**Misaligned quota and compensation.** Your sales reps are measured on ACV. But your CPQ is calculating TCV as the deal value. A rep who closes a one-year $200K deal and a three-year $200K/year deal will see very different numbers in the system — even though they've delivered the same ACV. If compensation and quota tracking are built on TCV, you're paying your reps incorrectly and measuring performance inaccurately.

**Revenue reporting that doesn't reconcile.** Your CRM shows ACV bookings. Your finance system tracks ARR. Your board deck reports TCV. None of these numbers agree, and nobody can easily explain why. This isn't a data problem — it's a definitions problem that started in CPQ design and propagated everywhere downstream.

**Discount authorization based on wrong value.** Your discount policy allows sales managers to authorize up to 15% off on deals under $100K. But 15% of what? TCV, ACV, and ARR will produce very different answers for the same deal. A discount policy that makes sense under one metric creates either too much risk or too much friction under another.

## Which Metric to Design Around

There's no universal answer, but there are clear guidelines based on business model.

**Subscription SaaS businesses** should anchor on ARR. ARR is the north star metric for subscription businesses — it reflects the health of your recurring revenue base and is what investors, boards, and finance teams care about. Your CPQ approval thresholds, quota tracking, and revenue reporting should all operate in ARR terms. ACV is useful for individual deal analysis; ARR is the system-of-record metric.

**One-time or project-based businesses** should anchor on TCV. If your revenue is primarily project-based — implementation, consulting, or one-time software licenses — TCV reflects the true economic value of each contract. ARR doesn't apply when revenue doesn't recur. ACV can be misleading for multi-year deals that don't have equal annual values.

**Hybrid businesses** — SaaS with professional services, or subscription plus one-time components — need to explicitly separate recurring from non-recurring in CPQ. Your approval thresholds, reporting, and compensation should distinguish between ARR impact (recurring) and TCV impact (total deal). This sounds complicated, but it's necessary. Blending them produces numbers that mean nothing.

## The Practical Fix

Before you configure a single approval threshold or compensation rule in CPQ, write down — formally, with finance and sales leadership sign-off — the answers to these questions:

- What is our primary deal metric for quota and compensation purposes?
- How do we handle multi-year vs. annual contracts for quota credit?
- What metric drives approval thresholds?
- How do we report bookings — ACV, ARR, or TCV?
- How do we handle one-time fees in recurring revenue metrics?

Once you have these answers documented, your CPQ configuration becomes straightforward. Without them, every configuration decision is an educated guess that someone will argue with later.

The companies that get this right close faster, compensate accurately, and report cleanly. The companies that get it wrong spend the better part of a year reconciling numbers that shouldn't need reconciling.

---
*I work on Revenue Cloud and Q2C implementations at Slalom. Connect with me on [LinkedIn](https://linkedin.com/in/carlosali) if you're designing a Q2C system and want to talk through your metric framework.*
