# Asterisk Call Routing Stability & SIP Contact Management

##  Overview

This project documents the analysis and resolution of call routing inconsistencies in an Asterisk PBX environment using standard SIP principles.

The objective was to ensure stable and deterministic call delivery by addressing SIP contact handling behavior.

---

##  Problem

Calls were not consistently reaching the intended endpoint.

Observed behavior included:
- Inconsistent call delivery
- Calls not reaching the softphone
- Unpredictable routing outcomes

---

##  Root Cause

Multiple SIP contacts were being associated with the same user.

This caused:
- Ambiguous endpoint selection
- Non-deterministic routing behavior
- Incorrect call termination paths

---

##  Solution

Implemented single-contact enforcement using standard Asterisk PJSIP configuration:

```ini
type = aor
max_contacts = 1
remove_existing = yes
``
