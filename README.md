# Sentinel 🛡️

### AI Evidence-Intelligence & Decision-Support System for Disaster Response

Sentinel is an AI-powered evidence-intelligence system designed to help authorities make better decisions during disaster and crisis situations.

During a disaster, authorities may receive a large number of reports from citizens, officials, and other sources. These reports can be duplicated, incomplete, or contradictory.

Sentinel does not attempt to determine absolute truth.

Instead, it organizes available evidence, identifies related reports, detects conflicting claims, calculates separate Severity and Confidence scores, explains why those scores were given, and recommends an appropriate action.

A human authority always remains responsible for the final decision.

---

## 🎯 Core Problem

During a disaster, the problem is not always a lack of information.

The problem can be too much information.

For example:

- One report says a bridge has collapsed.
- Another says the bridge is damaged but still usable.
- Several citizens report the same incident.
- An image provides additional evidence.
- An official source later confirms part of the information.
- A newer report may contradict an earlier report.

Without a system that organizes and compares this information, decision-makers may struggle to understand the situation quickly.

---

## 💡 Our Solution

Sentinel creates an evidence-backed view of an incident from multiple reports.

The MVP focuses on five core capabilities:

1. **Text → Structured Claims**
2. **Report → Incident Clustering**
3. **Contradiction Detection**
4. **Separate Severity + Confidence Scoring**
5. **Incident Investigation & Human Verification**

---

## 🧠 How Sentinel Works

```text
Reports
   ↓
Structured Information Extraction
   ↓
Incident Clustering
   ↓
Claim Comparison
   ↓
Contradiction Detection
   ↓
Evidence Evaluation
   ↓
Severity + Confidence
   ↓
Why? Explanation
   ↓
Recommended Action
   ↓
Human Verification