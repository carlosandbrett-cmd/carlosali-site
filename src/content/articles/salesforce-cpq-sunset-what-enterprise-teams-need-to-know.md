---
title: "The Salesforce CPQ Sunset: What Enterprise Teams Actually Need to Know"
description: "Salesforce is ending sales of legacy CPQ. Here's what that means for your implementation, your roadmap, and the decisions you need to make now."
date: 2026-02-23
ogImage: /og/og-cpq-sunset.png
tags: ["Salesforce CPQ", "Revenue Cloud"]
---

If you've been in the Salesforce Quote-to-Cash space for any length of time, you've probably heard the news: Salesforce is sunsetting its legacy CPQ product in favor of Revenue Cloud. And if you're running a production CPQ instance right now, you're probably wondering what this actually means for your team.

I've spent the last two years helping enterprise clients navigate this transition, and I want to share what I've learned — because the vendor messaging doesn't always match the ground truth.

## What's Actually Happening

Let's be precise about what "sunset" means here. Salesforce has ended new sales of the legacy CPQ product (the one that originated from the SteelBrick acquisition). Existing customers will continue to receive support for a defined period, but the platform roadmap — new features, performance improvements, integrations — is now focused entirely on Revenue Cloud.

This isn't a sudden shutdown. It's a strategic redirect. But the implications are significant, especially if you're mid-implementation or planning a major enhancement to your current CPQ setup.

## The Three Questions Every Team Should Ask

### 1. How dependent are we on legacy CPQ-specific features?

Revenue Cloud isn't a 1:1 replacement for legacy CPQ. Some features work differently, some are still catching up, and some are genuinely improved. Before you plan anything, audit your current configuration and identify which features you rely on that may not have direct equivalents yet.

The areas I see causing the most friction in migrations: complex approval chains, highly customized guided selling flows, and complex discount schedules. If your implementation leans heavily on any of these, your migration timeline is longer than you think.

### 2. What's our contract renewal timeline?

Your Salesforce contract renewal is your natural decision point. If renewal is 12+ months away, you have time to evaluate properly. If it's sooner, you need to start the conversation with your Salesforce account team now — not because you need to rush, but because you need to understand what your licensing options look like going forward.

I've seen organizations get significantly better terms by starting this conversation early rather than waiting until renewal pressure hits.

### 3. Is this actually a migration — or a reimplementation?

This is the question most teams don't ask until it's too late. If your legacy CPQ instance has years of accumulated technical debt — custom Apex triggers, workaround flows, pricing logic that nobody fully understands — a "migration" might actually be a reimplementation in disguise. And that's not necessarily a bad thing. Sometimes the best move is to use the platform transition as an opportunity to redesign your Q2C process from scratch.

The organizations getting the best outcomes from this transition are the ones treating it as a strategic initiative, not a technical lift-and-shift.

## What I'd Recommend Right Now

If you're running Salesforce CPQ today, here's what I'd tell my clients:

**Don't panic, but don't wait.** The legacy product isn't disappearing overnight, but the window for proactive planning is open now. The teams that move deliberately will have better outcomes than those who wait for forced urgency.

**Audit before you plan.** Get a clear picture of your current state — what's configured, what's customized, what's working, and what's held together with duct tape. This audit is the foundation of every good migration plan.

**Talk to practitioners, not just vendors.** Salesforce will tell you Revenue Cloud is ready. Partners will tell you they can migrate you in 12 weeks. Neither of those statements is wrong, exactly, but neither tells the full story. Find people who've actually done this at your scale and your complexity level.

**Consider the full Q2C lifecycle.** The shift to Revenue Cloud isn't just about quoting. It's an opportunity to rethink how quoting connects to contracting, billing, and revenue recognition. If you're going to go through the disruption of a platform change, extract maximum value from it.

## The Bigger Picture

The Salesforce CPQ sunset is one signal of a broader shift in the market. CPQ is no longer a standalone tool decision — it's an architecture decision. The platforms winning in 2026 are the ones that treat configuration, pricing, and quoting as one piece of an end-to-end revenue lifecycle.

For enterprise teams, this means the CPQ conversation needs to include finance, legal, and operations — not just sales and IT. The cross-functional ownership model isn't a nice-to-have anymore. It's the difference between a successful implementation and an expensive shelf decoration.

I'll be writing more about each of these dimensions in the coming weeks. If you're navigating this transition, I'd genuinely like to hear what challenges you're facing — reach out on [LinkedIn](https://linkedin.com/in/carlosali).
