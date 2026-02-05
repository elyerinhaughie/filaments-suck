# filaments-suck
## A Practical Survival Guide for Filaments That Don’t Print Like You Expected

Welcome.

If you're here, you have probably experienced at least one of the following:

- A filament marketed as *“high speed”* that prints worse the faster you go  
- Manufacturer settings that produce blobs, tearing, or weak parts  
- Hours lost chasing moisture ghosts  
- Perfect first layers followed by catastrophic infill  
- A spool you regret buying — but refuse to throw away  

You are not alone.

This repository exists to turn **printer frustration into reproducible engineering profiles.**

---

# Mission

The goal of this project is simple:

> **Document real-world filament behavior and provide stable, production-grade profiles that actually work.**

Not marketing settings.  
Not theoretical maxima.  
Not lab conditions.

**Reality.**

We focus on identifying where manufacturer recommendations diverge from the physical limits of consumer printers — especially thermal throughput constraints that most spec sheets ignore.

---

# Transparency Statement (AI-Assisted Authoring)

This repository is built on **extensive real-world testing**, failed prints, iterative tuning, and engineering analysis.

To improve clarity, readability, and accessibility for a wider range of makers, portions of the written material are **AI-assisted** during the authoring process.

What this means:

- ✅ **All profiles originate from real printer testing**
- ✅ **Observations are human-validated**
- ✅ **Conclusions are based on physical behavior**
- ✅ **AI is used to help structure, refine, and communicate technical ideas**

What this does *not* mean:

- ❌ Blindly generated settings  
- ❌ Unverified technical claims  
- ❌ Synthetic testing  

Think of AI here as an editorial amplifier — not a substitute for experimentation.

The goal is to make complex thermal and extrusion concepts easier to understand so fewer people waste time fighting preventable print failures.

If something in this repo is wrong, incomplete, or machine-specific:

**Open an issue. Challenge assumptions. Improve the data.**

Engineering thrives on iteration.

---

# Why This Repo Exists

Modern printers are extremely fast.

Hotends are not.

The result is a widening gap between:

### What filaments claim to support  
vs  
### What polymers can physically tolerate  

Most print failures are not user error — they are **heat transfer problems disguised as slicer problems.**

Common root causes include:

- Melt-zone saturation  
- Heater power limitations  
- Pressure instability  
- Polymer relaxation behavior  
- Thermal gradients  
- Chamber overheating  

Once you understand these constraints, many “bad filaments” suddenly become predictable.

This repository is about closing that knowledge gap.

---

# Philosophy

We follow one guiding principle:

> **Extrusion is constrained by thermal physics, not motion capability.**

Fast printers make it easy to accidentally exceed melt capacity.

When that happens, you see:

- random blobs  
- surface tearing  
- apparent over-extrusion  
- nozzle plowing  
- matte finishes  
- weak layer bonding  

Most people respond by endlessly tweaking settings.

We respond by identifying the **true thermal ceiling** — and operating just below it.

That is where stability lives.

---

# What Makes This Repo Different

This is NOT a slicer preset dump.

Each filament entry aims to explain:

✅ Why the default profile fails  
✅ What the polymer is actually doing  
✅ Where the thermal boundary exists  
✅ How to reach melt equilibrium  
✅ Which signals indicate stability  

The goal is to teach users how to think about extrusion — not just copy settings blindly.

---

# Structure

Each filament will include:

## Overview
- Manufacturer claims  
- Observed behavior  
- Known failure patterns  

## Root Cause Analysis
- Thermal constraints  
- Pressure dynamics  
- Polymer behavior  

## Stability Profile
A quality-first configuration derived from real printer limits.

## Diagnostic Signals
What the printer will tell you when you're inside — or outside — the stable process window.

## Comparison Tables
Manufacturer vs reality.

---

# Example Problem Patterns We Track

- “Rapid” filaments that outrun heater blocks  
- PETG that only prints clean when slowed dramatically  
- Materials sensitive to chamber heat  
- High-flow blends requiring higher melt temps than advertised  
- Filaments that appear wet but are actually under-melted  
- Materials that improve once volumetric flow is reduced  

---

# Who This Is For

This repo is especially valuable for users running:

- CoreXY printers  
- High acceleration systems  
- Enclosed machines  
- Large nozzles  
- High-flow hotends  

But the underlying physics applies to **all FDM printers.**

---

# Contributing

If you have a filament that fought you — contribute it.

Great submissions include:

- Printer model  
- Nozzle size  
- Layer height  
- Volumetric flow  
- Temperature  
- Cooling  
- Chamber conditions  
- Failure symptoms  
- What finally fixed it  

Even better:

Explain **why** the fix worked.

We are building an engineering resource, not just a settings archive.

---

# Ground Rules

### ❌ No brand bashing  
This is not about attacking manufacturers.

Most recommended ranges are technically achievable — just often not optimal on consumer hardware.

### ❌ No ego tuning  
If a profile only works on one machine in one room during a full moon, it isn’t stable.

### ✅ Prefer conservative stability over theoretical speed  
Production reliability beats benchmark numbers.

---

# A Note on “Bad Filament”

Many filaments labeled as problematic are simply:

> **Operating outside the thermal envelope of the printer.**

Once tuned correctly, they often become excellent materials.

The spool is rarely the enemy.

Physics is just undefeated.

---

# The Engineering Takeaway

If you remember one thing from this repository, let it be this:

> **The fastest successful print is rarely the highest-flow print — it is the one operating just below the hotend’s thermal limit.**

Find that boundary.

Stay slightly under it.

Printers become dramatically easier to control.

---

# Future Goals

- Expand filament database  
- Provide printer-class tuning guidance  
- Establish realistic volumetric benchmarks by material  
- Document thermal ceilings across hotend architectures  
- Reduce wasted filament across the community  

---

If this repo saves even one maker from burning through a brand-new spool in frustration — it has done its job.
