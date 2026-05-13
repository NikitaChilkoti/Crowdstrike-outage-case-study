## Why I Started This Project

To learn... duhh!
Actually, when this outage happened I did read about it in a news headline, as I wasn't in this domain, so I barely knew, and I barely cared.
But now, when I am, I need to know every bit of it.

## All about the Crowdstrike-outage

This project is a breakdown of how a routine security update turned into one of the biggest IT outages the modern internet has ever recorded, I guess.

When the CrowdStrike outage happened in July 2024, almost everyone was talking about the visible impact:

* blue screens,
* grounded flights,
* broken checkout systems,
* and enterprise machines suddenly going offline.

But while reading about the incident, I kept getting stuck on one thought.

What exactly made this one explode at such a massive scale?

How did a single update manage to affect:

* airlines,
* hospitals,
* banks,
* broadcasters,
* retailers,
* and enterprise infrastructure…. everything within just a few hours?

That question pulled me into this project.

And the more I explored the outage, the more I got to learn.

# What Actually Happened

On July 19, 2024, CrowdStrike pushed a faulty update to its Falcon Sensor platform running on Windows systems.

That update ended up causing systems to crash during boot, leading to widespread blue screen failures across the world.

Microsoft later estimated that around 8.5 million Windows devices were affected globally.

Now honestly, 8.5 million is already a huge number.

But the more important thing was where those systems existed.

Airports.
Hospitals.
Banks.
Retail chains.
Corporate offices.
Support centers... and where not!

And because many of these environments were deeply dependent on Windows-based infrastructure, the disruption spread extremely fast.

What made the incident especially interesting to me was this:

The outage was not caused by hackers, it was not ransomware, it was not even a cyberattack.
The systems failed because they trusted a security update that was supposed to protect them.

This was big!

---

# What This Project Is

This project is my attempt to understand the outage from both an engineering and operational perspective.

I wanted to understand:

* what technically failed,
* why the impact spread so aggressively,
* why recovery became so painful,
* and what this incident revealed about how modern infrastructure is actually designed.

I also wanted the writing to feel natural. So, did not took help from ChatGPT for this.

Because honestly, this outage exposed some very uncomfortable realities about modern systems.

---

# What I Found Most Interesting

One thing became very obvious while researching this outage.

Modern infrastructure is heavily automated. But it is also heavily interconnected.

Now, this combination can become is awesome, but for failures. Ouch!

CrowdStrike’s Falcon Sensor operates very deep inside the Windows operating system at the kernel level.

That deep integration is useful because security tools need visibility into low-level system behavior.

But during this outage, that same level of access became part of the problem.

A faulty update was enough to destabilize operating system behaviour.

And once machines started crashing globally, recovery became its own operational challenge.

This part fascinated me the most.

Because even though the faulty update was reverted quickly, many organizations still had a difficult recovery process.

In a lot of cases, systems needed manual intervention.

Which meant:

* rebooting machines,
* entering safe mode,
* removing files manually,
* and physically accessing systems.

---

### Repository structure will include the what, the how, the analysis, and the improvements with learnings.

### Who This Project Is For

I’m mainly writing this for:

* myself, yes obviously
* cloud learners,
* DevOps engineers,
* SRE enthusiasts,
* platform engineers,
* and people curious about how real systems behave under failure.

Even when the topics become technical, I’ll try to keep the explanations connected and readable.

The goal is not just to explain what happened…

…but to understand why modern infrastructure reacted the way it did.
