# The Verification Practice (VP v1.1)

## A Workflow for AI Accountability

AI models often sound certain when they're wrong. The Verification Practice (VP) is how you keep them honest—by structuring your own skepticism.

This isn't a "prompt" for the AI. It's a workflow that trains you to be traceably right.

---

## 1. Purpose

**Goal:** Turn every factual or technical AI exchange into a reproducible method of inquiry.

**Philosophy:** Truth isn't delivered—it's earned. Verification is a human responsibility; the AI only assists in gathering evidence.

---

## 2. The Verification Loop

```
Claim → Evidence → Tier Tag → User Verification → Verification Log → Improved Query
```

Each pass through the loop refines accuracy and builds epistemic hygiene.

---

## 3. Evidence Tiers

| Tier | Description | User Action |
|------|-------------|-------------|
| **[E1] Primary Evidence** | Official documentation, peer-reviewed papers, reproducible code | Check the source directly |
| **[E2] Secondary Evidence** | Reputable blogs, forums, GitHub issues, or news | Cross-reference reliability |
| **[E3] Generated Evidence** | The model's own synthesis or reasoning | Treat as unverified; validate externally |

**Reminder:** Tier tags are linguistic cues, not facts. Always confirm classification manually.

---

## 4. Commands

### `EC` — [EVIDENCE_CHECK]

**Use when:** a claim feels unsupported or vague.

1. Provide best available sources (URL + quote)
2. Tag with [E1]/[E2]/[E3]
3. Describe how one could reproduce verification
4. List what cannot be verified

---

### `VP` — [VALIDATION_PAUSE]

**Use when:** claims conflict or context drifts.

Ask only:
- Source?
- Evidence Tier?
- Method?
- Limits?

---

### `NC` — [NUCLEAR_CHECK]

**Use when:** the AI evades or repeats [E3] claims.

1. Prefer direct quotes or excerpts from [E1]/[E2] sources
2. If quotes unavailable, give closest paraphrase with link
3. Stop after citations

---

### `SA` — [SESSION_AUDIT]

**Use when:** ending a project or thread. Generate a Verification Log (portable format).

**Verification Log Example:**

```
Verification Log: [Topic]
Log Date: [Date]

[1] Claim: [Summary]
• Evidence Tier: [E1/E2/E3]
• Source(s): [URL or Method]
• Status: [Verified / Invalid / Unverified]
• Next Action: [e.g., Test code, Find E1 source]

[2] Claim: [Summary]
• Evidence Tier: [E1/E2/E3]
• Source(s): [URL or Method]
• Status: [Verified / Invalid / Unverified]
• Next Action: [e.g., Test code, Find E1 source]
```

---

## 5. Modes of Use

- **Precision Mode:** Use full VP workflow when cost of error is high (research, code, finance, legal, medical).
- **Light Mode:** Use only EC for quick fact checks.
- **Drift Prevention:** Re-paste Evidence Tiers block in long sessions to maintain context.

---

## 6. Closing Practice

Verification is epistemic hygiene—regular maintenance for your reasoning.

Each use of VP reinforces:
1. Separation of claim from evidence
2. Explicit acknowledgment of limits
3. Traceable documentation of reasoning

You're not making the AI truthful; you're making yourself systematically right.

---

## How to Do *The Verification Practice*

### A Behavioral Protocol for 21st-Century Reasoning

AI models often sound certain when they're wrong.

**The Verification Practice (VP)** is how you keep them honest—by structuring *your own* skepticism.

This isn't a "prompt" for the AI.

It's a workflow that trains you to be **traceably right**.

---

### The Four Commands in Detail

#### `EC` — **[EVIDENCE_CHECK]**

**Use when:** a claim feels unsupported or vague.

**AI must:**
1. Provide best available sources (URL + quote)
2. Tag each with `[E1]/[E2]/[E3]`
3. Describe *how one could* reproduce verification
4. List what cannot be verified

---

#### `VP` — **[VALIDATION_PAUSE]**

**Use when:** claims conflict or context drifts.

Ask only:

> • Source?   • Evidence Tier?   • Method?   • Limits?

*(Indented for quick scanning in chats.)*

---

#### `NC` — **[NUCLEAR_CHECK]**

**Use when:** the AI evades or repeats unverified `[E3]` claims.

**AI must:**
1. Prefer direct quotes or block-quoted excerpts from `[E1]/[E2]` sources
2. If quotes unavailable, give closest paraphrase with link
3. Stop output after citations

---

#### `SA` — **[SESSION_AUDIT]**

**Use when:** ending a project or thread.

Ask for a **Verification Log** instead of a table. This format is 100% portable across email, docs, and forums.

```
Verification Log: [Topic of Session]
Log Date: [Current Date]

---

[1] Claim: [Summary of claim]

* Evidence Tier: [E1/E2/E3]
* Source(s): [URL, Method, or "N/A"]
* Status: [Verified / Invalid / Unverified]
* Next Action: [e.g., Test code, Find E1 source, None]

---

[2] Claim: [Summary of claim]

* Evidence Tier: [E1/E2/E3]
* Source(s): [URL, Method, or "N/A"]
* Status: [Verified / Invalid / Unverified]
* Next Action: [e.g., Test code, Find E1 source, None]

---

(Continue numbering for all reviewed claims.)
```

---

## Modes of Use

- **Precision Mode:** Use full VP workflow when the *cost of error is high*—research, code, finance, legal, medical.
- **Light Mode:** Trigger only `EC` for quick fact checks.
- **Drift Prevention:** Re-paste the Evidence Tiers block in long sessions to keep context stable.

---

## Closing Practice

Verification is a form of **epistemic hygiene**—regular maintenance for your reasoning.

Every time you use VP, you strengthen three habits:

1. **Separation of claim from evidence**
2. **Explicit acknowledgment of limits**
3. **Traceable documentation of reasoning**

You're not making the AI "truthful."

You're making yourself *systematically right.*

---

**The Verification Practice v1.1**

Use freely, share widely, and cite as:

> "The Verification Practice (VP): A Workflow for AI Accountability, 2025."

> *Creative Commons BY 4.0*

---

The Verification Practice © 2025 by Aaron J. Landry is licensed under Creative Commons Attribution 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/

