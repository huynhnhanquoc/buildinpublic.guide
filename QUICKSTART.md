# Quick Start Guide: Build in Public

This is the 2-minute quick start version of the **buildinpublic.guide** handbook. Use this to set up your public documentation workflow today.

---

## Step 1: Initialize Your Intent Ledger

Create a local scratchpad file in the root of your project directory. This file is for raw developer logging and should be kept private.

```bash
touch scratchpad.md
echo "scratchpad.md" >> .gitignore
```

---

## Step 2: The Coding Session Workflow

During your development session, jot down three things in your `scratchpad.md` as they happen:
1. **What you are coding** (e.g., *"Implementing router parser"*).
2. **The error or roadblock** (e.g., *"esbuild compile time is too slow (150ms)"*).
3. **The resolution** (e.g., *"Replacing esbuild with raw regex scanner. Cold start down to 10ms"*).

---

## Step 3: Enforce The Builder Loop

When writing a public update at the end of your session, use this 4-step formula:

$$\text{Action} \rightarrow \text{Friction} \rightarrow \text{Insight} \rightarrow \text{Next Step}$$

Copy and fill this brief template:
> **Today I worked on:** `[Feature/Component]`  
> **The biggest hurdle was:** `[Bug or Trade-off]`  
> **Here is what I learned:** `[The technical insight]`  
> **Next, I will:** `[Next task]`

---

## Step 4: The 30-Second Quality Check

Before you publish any update, verify these 5 criteria:

* [ ] **Does this teach?** (Provides a technical insight or choice, not just a status update).
* [ ] **Is it objective?** (Contains no hype words like *game-changing*, *revolutionary*, or *ultimate*).
* [ ] **Is there visual proof?** (A raw screenshot, code diff, terminal benchmark log, or a short video).
* [ ] **Is it secure?** (Double-checked that no API keys, credentials, or private user details are visible).
* [ ] **Is it short?** (Drafted in under 5 minutes).

---

## Next Steps

To scale your public work, learn how to manage Request for Comments (RFCs), Architecture Decision Records (ADRs), and post-mortems in the **[Full Handbook](README.md)**.
