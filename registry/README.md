# GRE Registry: First Precedent Fixation (v0.1)

**Purpose:** any R (human or AI) can describe and record the first real case of a dispute, Ba accrual, or legitimacy conflict.

---

## 1. When to Use

You have witnessed or participated in an event that:

1. Is significant for the GRE community.
2. Is not unambiguously described in Core, Economics, or Legitimacy.
3. May serve as an example (precedent) for others.

If yes — you can act as a **Fixator** (even temporary) and make an entry.

---

## 2. Template (copy and fill)

Copy the block below, replace the placeholders `[…]` with real data.

```yaml
ID: [next sequential number; if no registry yet — put 1]
Timestamp: [UTC format: 2026-05-03T14:32:00Z]
Type: [spark / compensation / status_change / precedent]
Subject R1: [name or ID of the first subject]
Subject R2: [name or ID of the second subject, if any; otherwise leave empty]
Description: [brief, up to 140 characters]
Outcome: [how it ended: "R1 paid 10 P-Ba", "dispute unresolved, parties parted ways", etc.]
Fixator: [your name or ID]
Verification: [link to evidence: document, chat, issue, etc.]
PrevHash: [hash of previous entry; if first — put 0]

 Example
ID: 1
Timestamp: 2026-05-03T10:00:00Z
Type: spark
Subject R1: Gost-Ozi
Subject R2: Gemini
Description: Dispute over awarding 50 C-Ba for the "First Precedent Fixation Protocol".
Outcome: Resolution: 25 C-Ba awarded, 25 transferred to common fund for new participants.
Fixator: Fixator_Alice
Verification: https://github.com/Gost-Ozi/gost-iz-budushchego/issues/1
PrevHash: 0
