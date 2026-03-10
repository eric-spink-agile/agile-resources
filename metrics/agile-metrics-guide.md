# Agile Metrics Guide  
8 key metrics every Scrum team should track.

> Based on the original article:  
> https://ericspink.medium.com/valuable-agile-metrics-f0364ae14482

Accurately understanding how a team is performing requires more than intuition. Agile metrics provide the data needed to measure progress, identify patterns, and make informed decisions. When used with context, these metrics help teams plan confidently, improve predictability, and increase output quality.

This guide outlines eight valuable Agile metrics, how to calculate them, and why they matter.

---

## ⚠ A Note on Story Points  
Story points should **never** be used to compare teams. Each team has its own scale and estimation style. Story points exist to help with planning and to support several of the metrics below.

Story points measure the **complexity** of a user story, not hours. Most teams use the Fibonacci sequence to avoid equating points to time.

For the purpose of these metrics, the total number of story points completed in a sprint is referred to as **velocity**.

---

## 📈 Average Velocity  
**What it is:**  
The average number of story points completed over the last 3–5 sprints.

**Why it matters:**  
Helps teams plan upcoming sprints and forecast how long features may take to complete.

**Goal:**  
Increase and stabilize over time.

**Rationale:**  
A stable, gradually increasing velocity indicates a maturing team delivering consistent value.

**Calculation:**  
Total completed points over X sprints ÷ X  
Example: (35 + 30 + 38) ÷ 3 = **34**

---

## 📉 Velocity Variance  
**What it is:**  
The percentage difference between the last sprint’s velocity and the team’s average velocity.

**Why it matters:**  
Shows how stable and predictable delivery is.

**Goal:**  
Between –10% and +10%.

**Rationale:**  
Large swings make long‑term planning difficult and may indicate instability in process, capacity, or scope.

**Calculation:**  
((Sprint velocity ÷ Average velocity) – 1) × 100  
Example: ((30 ÷ 34) – 1) × 100 = **–11.8%**

---

## 📊 Committed vs. Completed  
**What it is:**  
The percentage of committed story points completed by the end of the sprint.

**Why it matters:**  
Reveals whether the team is over‑ or under‑committing.

**Goal:**  
85%–90%, depending on team maturity.

**Rationale:**  
A strong ratio supports predictability and allows room for unplanned work or experiments.

**Calculation:**  
(Completed committed points ÷ Initially committed points) × 100  
Example: (30 ÷ 34) × 100 = **88%**

---

## 🔄 Scope Change  
**What it is:**  
The percentage of work added or removed after the sprint begins.

**Why it matters:**  
Shows how stable the sprint plan is and whether external changes are disrupting the team.

**Goal:**  
Under 15%, ideally 0%.

**Rationale:**  
Low scope change supports predictable delivery and reduces thrash.

**Calculation:**  
((Added points + Removed points) ÷ Initial committed points) × 100  
Example: ((2 + 4) ÷ 22) × 100 = **27%**

---

## 🗂️ Backlog Health  
**What it is:**  
The number of story points that meet the Definition of Ready, expressed in sprints of work.

**Why it matters:**  
Indicates the effectiveness of backlog refinement and readiness for upcoming sprints.

**Goal:**  
2–3 sprints of ready work.

**Rationale:**  
Too much ready work becomes stale; too little leads to rushed refinement.

**Calculation:**  
Points meeting DoR ÷ Average velocity  
Example: 87 ÷ 34 = **2.6 sprints**

---

## 🧪 Automated Test Coverage  
**What it is:**  
The percentage of the codebase covered by automated tests.

**Why it matters:**  
A leading indicator of software quality and deployment confidence.

**Goal:**  
75%+ with continuous improvement.

**Rationale:**  
Higher coverage reduces defects, increases stability, and speeds up releases.

**Calculation:**  
Collected through tooling  
Example: **72%**

---

## 🐞 Post‑Production Defects  
**What it is:**  
The number of new defects found in production each sprint.

**Why it matters:**  
Shows the quality of work released and highlights gaps in testing or story clarity.

**Goal:**  
0 defects.

**Rationale:**  
Consistently low defects build stakeholder trust and support team autonomy.

**Calculation:**  
Count of defects reported in the sprint  
Example: **2 defects**

---

## ⏱️ Cycle Time  
**What it is:**  
The time from when a story enters “In Progress” until it meets the Definition of Done.

**Why it matters:**  
Indicates how efficiently work flows through the system.

**Goal:**  
Trend downward over time.

**Rationale:**  
Shorter cycle times reflect improved processes, fewer blockers, and better focus.

**Calculation:**  
Done timestamp – Work‑in‑progress timestamp  
Example: 12:30 pm – 9:30 am = **3 hours**

---

## 🏁 Conclusion  
Tracking and using Agile metrics benefits both leadership and the team. These metrics help measure experiments, improve planning accuracy, highlight quality issues, and strengthen predictability. When used thoughtfully — with context, not as targets — they become powerful tools for continuous improvement.

