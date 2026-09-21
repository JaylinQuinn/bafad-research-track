# Task C — Research Reflection

> **BAFAD Accelerated Research Track · Fall 2026**
> Complete **after** finishing Tasks A and B.

---

## Instructions

Write your responses directly in this file (replace the placeholder text).
Aim for **150–200 words total** across both questions.
Be specific — reference your actual experience with the data and code.

---

## Question 1 — Connecting the Work to Research

*After completing Tasks A and B, how does hands-on data exploration relate to the research problem described in **Anomaly Detection in Tactical Sensor Streams** (the document you read before the Canvas quiz)?*

Consider: What patterns did you observe in the SMAP data? How might those patterns complicate or inform the design of an autoencoder-based anomaly detector?

**Your response (75–100 words):**

> After working with the SMAP data one thing I noticed was that there was a lot more normal data than anomaly data. I also noticed that some of the anomaly values overlapped with the normal values which surprised me because I thought the anomalies would stand out more. This could make detecting anomalies harder because the model cannot just look for values that seem unusual. An autoencoder could help by learning the patterns of normal sensor data first and then finding data that does not follow those patterns.

---

## Question 2 — Self-Assessment of Readiness

*What specific gaps in your current knowledge — Python skills, statistics concepts, or ML background — do you expect to encounter if you join the research group? What is your plan for addressing them?*

Be honest. There are no wrong answers — this helps us plan the onboarding schedule.

**Your response (75–100 words):**

> I think my biggest gap right now is that I am still pretty new to Python and statistics so there are a lot of things I still have to learn. I understand some of the basics, but I still need more practice with working with data and knowing when to use certain functions. Machine learning is also very new to me especially things like autoencoders and anomaly detection. My plan is to keep practicing Python, ask questions when I do not understand something, and use the research experience to learn more as I go.

---

*Submission: commit this file to your fork and include it in the GitHub repo URL you submit on Canvas.*
