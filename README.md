# Optimising EV Charging Station Deployment in India

### Lean Six Sigma — DMAIC Analyse Phase

> **Discovering the Drivers of Deployment Delays — LT vs. HT Focus**

---

## 📌 Project Overview

The rapid adoption of electric vehicles (EVs) in India requires a reliable and scalable charging infrastructure. However, deploying an EV charging station can take several months, with the majority of the timeline often being consumed not by physical construction, but by **administrative approvals, DISCOM coordination, grid-capacity constraints, and multi-agency handoffs**.

This project applies the **Lean Six Sigma DMAIC (Define–Measure–Analyse–Improve–Control)** methodology to investigate the causes of excessive and highly variable EV charging station deployment times.

The project focuses on answering a central question:

> **Why does EV charging station deployment take significantly longer than the actual physical construction and installation process?**

The Analyse phase identifies and statistically validates the **vital few factors** responsible for deployment delays, with particular emphasis on:

* **x₂ — DISCOM/Grid Connection Delays**
* **x₄ — Municipal Approval Delays**

The analysis indicates that the physical engineering process is relatively stable, while the major source of cycle-time variation lies in **administrative and grid-related waiting time**.

---

# 🎯 Project Objective

The primary objective is to establish a data-driven understanding of the current EV charging station deployment process and identify the root causes responsible for excessive cycle time.

The project aims to:

1. Establish a baseline for EV charging station deployment time.
2. Identify the major sources of non-value-added waiting.
3. Determine which process variables have the greatest impact on total cycle time.
4. Statistically validate the suspected root causes.
5. Separate physical/engineering constraints from administrative bottlenecks.
6. Develop improvement opportunities capable of reducing deployment time.
7. Move the process toward a **stable and predictable deployment cycle of approximately 30–45 days**.

---

# 🏗️ Problem Statement

The current EV charging station deployment process exhibits:

* Long overall deployment times.
* Significant geographical variation.
* Large amounts of administrative waiting.
* Unpredictable municipal approval timelines.
* DISCOM-related delays.
* Additional delays when sites require **High Tension (HT) transformer augmentation**.
* Multiple handoffs between government departments and survey teams.
* Lack of standardisation across cities and states.

The baseline analysis identified an average setup cycle time of approximately **85 days**, with some deployments exceeding **105 days**.

A key observation is that the physical work itself is comparatively short.

Civil/site work was identified as taking approximately **12 days**, while the larger portion of the timeline is associated with administrative and grid-related waiting.

This creates a significant Lean waste problem:

> **The station is technically capable of being built faster, but the project spends substantial time waiting for approvals and infrastructure-related decisions.**

---

# 🔄 DMAIC Framework

The project follows the Lean Six Sigma DMAIC framework:

```text
DEFINE
   ↓
MEASURE
   ↓
ANALYSE
   ↓
IMPROVE
   ↓
CONTROL
```

The current repository primarily documents the **Analyse Phase**, building on the baseline established during Measure and translating it into validated root causes and improvement opportunities.

---

# 📊 Measure Phase Recap

The Measure phase established the baseline performance of the EV charging station setup process.

### Key baseline observations

| Metric                       |                Observation |
| ---------------------------- | -------------------------: |
| Average setup cycle time     |                   ~85 days |
| Severe deployment cases      |                  105+ days |
| Physical civil work          |                   ~12 days |
| Major waste category         |     Administrative waiting |
| Primary bottleneck variables |                  x₂ and x₄ |
| Scope                        | National EV infrastructure |

The baseline showed that the process is not simply "slow"; it is **highly variable**.

Deployment times differ considerably across geographic regions, with examples of relatively streamlined processes in Gujarat compared with more severe delays in states such as Karnataka and Uttar Pradesh.

This geographical variation suggested that the problem could be systemic and process-driven rather than purely technical.

---

# 🔍 Analyse Phase

The Analyse phase is the third stage of DMAIC.

Its purpose is to transform the baseline measurements into a statistically supported understanding of **why the process behaves the way it does**.

The analysis focuses on:

```text
Observed Problem
      ↓
Process Stratification
      ↓
Pareto Analysis
      ↓
Stakeholder / Gemba Validation
      ↓
Hypothesis Testing
      ↓
Regression & Correlation
      ↓
Fishbone Root Cause Analysis
      ↓
Validated Root Causes
```

The objective was not simply to identify possible causes, but to determine which causes could be **validated using data and operational evidence**.

---

# 👷 Gemba / Industry Validation

An important component of the analysis was a primary stakeholder interaction with an active EV charging operator/provider.

The project followed the Lean principle of **Gemba** — going to the source of the process to understand what actually happens in practice rather than relying exclusively on theoretical assumptions.

The stakeholder interaction produced an important insight:

## The Civil Work Fallacy

Physical site preparation and hardware installation can occur **while administrative approvals are still pending**.

Therefore:

> Physical construction is not the primary bottleneck.

Instead, projects spend substantial time waiting for external approvals and coordination.

---

# 🔗 The Handoff Waste

The stakeholder highlighted **multi-agency coordination** as a major source of project volatility.

Files can move through as many as **five different municipal survey teams**, creating:

* Repeated handoffs
* Idle waiting
* Overprocessing
* Lack of ownership
* Communication delays
* Unpredictable approval timelines

This represents classic Lean waste, particularly:

### Muda — Non-Value-Added Activity

The project therefore shifted its analytical focus away from physical construction and toward the administrative process surrounding deployment.

---

# 🥇 Pareto Analysis — Identifying the Vital Few

A Pareto analysis was used to identify the factors contributing most significantly to deployment delays.

The analysis indicated that approximately **80% of cumulative delay** was concentrated in two major factors:

### x₂ — DISCOM/Grid Connection Delays

and

### x₄ — Municipal Approval Delays

This supports the Lean principle of focusing improvement efforts on the **vital few** rather than attempting to optimise every process step simultaneously.

The physical activities were classified as the "trivial many" compared with the administrative and grid-related bottlenecks.

---

# ⚡ Root Cause 1 — DISCOM Grid Constraints (x₂)

One of the most significant findings was the difference between:

### Low Tension (LT) connection

and

### High Tension (HT) connection

When sufficient existing LT capacity is available, the connection process can be substantially faster.

However, when the selected site does not have sufficient grid capacity, the project may require an **HT transformer augmentation**.

The baseline analysis identified approximately:

```text
LT connection  → ~30 days
HT augmentation → ~90 days
```

This creates an approximate **60-day structural difference** in the deployment process.

The presentation describes the HT requirement as a roughly **30-day penalty relative to the relevant process baseline**, while the broader baseline highlights the much longer transformer-augmentation timeline.
The key problem is therefore not simply "DISCOMs are slow."

The deeper root cause is:

> **Sites are sometimes selected without sufficient upfront visibility into available grid capacity.**

This creates a **Sequential Trap**:

```text
Select site
    ↓
Sign / proceed with site
    ↓
Apply for connection
    ↓
Discover insufficient LT capacity
    ↓
HT upgrade required
    ↓
Transformer augmentation
    ↓
Major deployment delay
```

A better process would reverse the sequence:

```text
Identify candidate site
        ↓
Check existing LT capacity
        ↓
Assess grid feasibility
        ↓
Select site
        ↓
Proceed with deployment
```

---

# 🏛️ Root Cause 2 — Municipal Approval Delays (x₄)

The second major bottleneck is municipal approval.

EV charging infrastructure can require approvals/NOCs involving multiple authorities and functions, including:

* Fire
* Parking
* Right-of-Way
* Municipal surveys
* Other local clearances

The problem is not necessarily the technical complexity of each approval.

Instead, the problem is:

### Fragmentation + Lack of Standardisation + Lack of SLA

Approval processes can involve multiple departments operating sequentially, resulting in significant waiting time.

The project identified an **SLA blindspot**, where certain municipal approvals do not have clearly enforced legal deadlines.

Consequently, the process can experience uncontrolled variation in approval time.

---

# 📈 Statistical Validation — 2-Sample t-Test

To determine whether grid connection type genuinely affects deployment time, a **2-sample t-test** was conducted.

### Significance level

```text
α = 0.05
```

### Null Hypothesis

```text
H₀ : μLT = μHT
```

There is no statistically significant difference between the average deployment times of LT and HT sites.

### Alternative Hypothesis

```text
Hₐ : μLT < μHT
```

Sites requiring HT grid upgrades take significantly longer to deploy.

### Result

```text
p-value < 0.05
```

Therefore:

```text
Reject H₀
```

The analysis statistically validates that the difference between LT and HT deployment times is significant.

### Business Interpretation

Grid capacity is not merely a suspected operational factor.

It is a **statistically significant driver of deployment cycle time**.

Therefore, selecting a site without checking grid capacity creates a measurable risk of deployment delay.

This provides a quantitative basis for making **upfront grid visibility a critical part of site selection**.

---

# 📊 Regression & Correlation Analysis

The project also examined the relationship between administrative waiting time and total deployment cycle time.

The analysis found a:

### Strong Positive Correlation

with:

```text
R² = 0.85
```

and the regression relationship:

```text
Y = 1.05x + 30
```

where:

* `Y` = total deployment cycle time
* `x` = administrative waiting time

---

# 💡 What Does R² = 0.85 Mean?

An R² of **0.85** indicates that approximately **85% of the observed variation in deployment timeline is explained by the administrative waiting variable used in the regression**.

This is a strong relationship.

The remaining approximately 15% is associated with other factors.

The result reinforces the central project finding:

> **The dominant source of deployment-time variation is administrative rather than physical.**

The presentation therefore concludes that the physical engineering process has a relatively stable baseline of approximately 30 days, while administrative friction drives the extreme variation observed in the overall process.

---

# 🐟 Fishbone Root Cause Analysis

A Fishbone analysis was used to organise the causes behind the major administrative delays.

Three major root-cause mechanisms emerged.

---

## 1. Handoff Waste

Files move between multiple municipal survey teams.

### Consequences

* Overprocessing
* Idle time
* Repeated coordination
* Poor ownership
* Increased cycle time

### Root issue

**No single-window clearance mechanism.**

---

## 2. SLA Blindspot

Some municipal approvals lack clearly enforced deadlines.

### Consequences

* Unpredictable waiting time
* High process variation
* Lack of accountability
* Difficulty forecasting deployment dates

### Root issue

**Absence of standardised approval SLAs.**

---

## 3. Sequential Site Selection

Sites may be selected primarily on commercial considerations such as foot traffic without first verifying grid capacity.

### Consequences

```text
Site selected
     ↓
Grid capacity checked later
     ↓
LT unavailable
     ↓
HT upgrade required
     ↓
Deployment delay
```

### Root issue

**Grid feasibility is not sufficiently integrated into the initial site-selection decision.**

These findings led to the conclusion that the major delays are **systemic rather than physical**.

---

# 🧠 Consolidated Root Cause Analysis

The complete causal chain can be represented as:

```text
                    EV Deployment Delay
                            │
              ┌─────────────┴─────────────┐
              │                           │
       DISCOM / Grid                Municipal Approvals
          (x₂)                           (x₄)
              │                           │
      ┌───────┴───────┐           ┌───────┴────────┐
      │               │           │                │
 Limited LT       HT upgrade   Multiple        No clear
 visibility       required     handoffs          SLAs
      │               │           │                │
      └───────┬───────┘           └───────┬────────┘
              │                           │
       Longer deployment           Unpredictable
           cycle                    waiting time
              │                           │
              └─────────────┬─────────────┘
                            │
                  High Cycle-Time
                     Variation
```

---

# 🎯 Key Findings

The Analyse phase produced five major conclusions.

### 1. Physical construction is not the primary bottleneck

Civil work can be completed in a relatively short period, while administrative approvals continue in parallel.

### 2. Grid capacity is a structural deployment driver

Sites requiring HT upgrades take significantly longer than sites that can utilise existing LT infrastructure.

### 3. Site selection and grid feasibility must be integrated

Failure to check grid availability early can structurally create additional deployment time.

### 4. Municipal approval processes create significant variation

Multiple agencies, handoffs and unclear SLAs create unpredictable waiting periods.

### 5. Administrative factors explain most of the observed variation

The regression analysis produced an R² of 0.85, reinforcing the importance of administrative waiting time in explaining deployment-cycle variation.

---

# 🚀 Improve Phase Strategy

Based on the validated root causes, the next phase focuses on eliminating the sources of non-value-added waiting rather than attempting to optimise physical construction.

Two major interventions are proposed.

---

## 🗺️ Solution 1 — Real-Time DISCOM Heatmap

### Target Root Cause

**x₂ — DISCOM Grid Constraints**

A real-time grid-capacity visibility system could allow charging-station operators to determine whether adequate LT capacity exists before committing to a location.

### Concept

```text
Candidate Location
       ↓
Grid Capacity Check
       ↓
 ┌─────┴─────┐
 │           │
LT Available  LT Insufficient
 │           │
Proceed      Consider
 │           │
 │          Alternative
 ↓          Location
Deployment
```

This acts as a **Poka-Yoke** by preventing an avoidable error at the beginning of the process.

Instead of discovering the grid limitation after site commitment, the constraint becomes visible during site selection.

### Expected Benefit

* Avoid unnecessary HT upgrades.
* Reduce structural deployment delays.
* Improve site-selection quality.
* Increase deployment predictability.

The proposed system specifically targets the "Sequential Trap" identified during root-cause analysis.

---

# 🏛️ Solution 2 — Single Window Clearance

### Target Root Cause

**x₄ — Municipal Approval Delays**

The proposed process re-engineers the fragmented approval workflow into a **single-window clearance system**.

### Current State

```text
Operator
   ↓
Survey Team 1
   ↓
Survey Team 2
   ↓
Survey Team 3
   ↓
Survey Team 4
   ↓
Survey Team 5
   ↓
Final Approval
```

### Proposed State

```text
              ┌───────────────┐
              │ Single Window │
              │   Clearance   │
              └───────┬───────┘
                      │
             ┌────────┼────────┐
             ↓        ↓        ↓
           Fire    Parking   ROW
             │        │        │
             └────────┼────────┘
                      ↓
                Final Approval
```

Where possible, approvals should occur **in parallel rather than sequentially**.

### Expected Benefit

* Eliminate unnecessary handoffs.
* Reduce overprocessing.
* Improve accountability.
* Establish predictable approval timelines.
* Introduce enforceable SLAs.
* Reduce administrative waiting.

The proposed approach is designed to eliminate the major sources of Muda identified during the Analyse phase.

---

# 📉 Expected Process Transformation

### Current State

```text
~105+ Days
│
├── Administrative waiting
├── DISCOM coordination
├── HT upgrade risk
├── Municipal NOCs
├── Multiple handoffs
└── Process variation
```

### Target State

```text
~30–45 Days
│
├── Grid feasibility verified upfront
├── LT-focused site selection
├── Parallel municipal approvals
├── Single-window clearance
├── SLA-driven process
└── Stable physical execution
```

The project targets a transition from a highly variable **105+ day process** toward a more stable **30–45 day deployment cycle**.

---

# 🧮 Lean Perspective

The project demonstrates how Lean thinking changes the question from:

> "How can we make construction faster?"

to:

> **"Why is the project waiting in the first place?"**

The analysis distinguishes between:

### Value-Added Activity

Activities that physically contribute to establishing the charging station.

### Non-Value-Added Activity

Waiting for:

* Grid approvals
* Transformer augmentation
* Municipal NOCs
* Surveys
* Departmental handoffs
* Administrative decisions

The central improvement philosophy is therefore:

```text
Identify NVA Waiting
        ↓
Remove Root Cause
        ↓
Reduce Variation
        ↓
Stabilise Process
        ↓
Reduce Cycle Time
```

---

# 🌐 Industry Validation

The analysis was further validated through an interaction with:

**Mr. Devansh Shah, Founder — Mobilane**

The discussion focused on real-world barriers to EV charging deployment.

The industry interaction independently reinforced several conclusions from the analysis:

* Administrative barriers are more significant than technical barriers.
* Multi-agency approvals create major timeline uncertainty.
* DISCOM coordination is a critical bottleneck.
* Transformer upgrades significantly affect deployment timelines.
* Lack of standardisation across cities increases process variation.
* Site selection without grid visibility can cause structural delays.

The stakeholder findings aligned strongly with both major analytical root causes:

```text
x₂ → DISCOM / Grid Constraints
x₄ → Municipal Approval Delays
```

The industry validation therefore strengthened the direction of the proposed Improve phase.

---

# 📚 Data Sources

The project draws upon:

* **NITI Aayog EV Handbook**
* **Observer Research Foundation (ORF)**
* **Primary Gemba Interview — EV Fleet Operator**
* **Industry interaction with Mobilane Founder**
* **DISCOM-related information discussed during stakeholder interaction**

The project scope is focused on **EV infrastructure deployment in India**.

---

# 🛠️ Methodologies Used

The project combines Lean Six Sigma process analysis with statistical methods.

### Lean Six Sigma

* DMAIC
* Muda identification
* Pareto analysis
* Process stratification
* Poka-Yoke
* Process re-engineering
* Root-cause analysis

### Statistical Analysis

* 2-Sample t-Test
* Hypothesis testing
* p-value analysis
* Regression analysis
* Correlation analysis
* R² interpretation

### Qualitative Analysis

* Gemba investigation
* Stakeholder interviews
* Industry validation
* Fishbone analysis
* Process mapping

---

# 📁 Project Structure

A suggested repository structure is:

```text
EV-Charging-Deployment-LSS/
│
├── README.md
│
├── presentation/
│   └── LSS_Analyse_Phase.pdf
│
├── data/
│   ├── raw/
│   └── processed/
│
├── analysis/
│   ├── pareto/
│   ├── hypothesis_testing/
│   ├── regression/
│   └── process_stratification/
│
├── visuals/
│   ├── pareto_chart/
│   ├── regression_plot/
│   ├── fishbone/
│   └── process_map/
│
└── documentation/
    └── methodology.md
```

*The exact folder structure can be adapted depending on which datasets, scripts and visualisations are included in the final repository.*

---

# 📌 Project Takeaway

The central insight from this project is that **EV charging deployment delays are not primarily an engineering problem**.

The physical infrastructure can be established relatively quickly. The major challenge is the administrative system surrounding deployment.

Two factors dominate:

```text
        EV Deployment Delay
                │
       ┌────────┴────────┐
       │                 │
      x₂                x₄
       │                 │
 DISCOM / Grid       Municipal
 Constraints         Approvals
       │                 │
   HT upgrades       Multi-agency
   & LT visibility   handoffs / SLAs
       │                 │
       └────────┬────────┘
                ↓
      Administrative Muda
                ↓
       High Cycle-Time
          Variation
```

The analysis therefore recommends shifting the improvement strategy from **optimising physical construction** to **redesigning the administrative and grid-connection process**.

The two key interventions are:

### 1. Real-Time DISCOM Grid-Capacity Visibility

Use grid-capacity information during site selection to prioritise locations capable of using existing LT infrastructure and avoid unnecessary HT upgrades.

### 2. Single-Window Municipal Clearance

Replace fragmented sequential approval processes with a coordinated, parallel, SLA-driven approval mechanism.

Together, these interventions aim to transform EV charging deployment from:

> **A volatile, administration-heavy 105+ day process**

into:

> **A stable and predictable 30–45 day process.**

---

# 🏁 Conclusion

This Lean Six Sigma Analyse phase demonstrates that reducing EV charging infrastructure deployment time requires addressing the **system around the engineering**, not simply the engineering itself.

The statistical and operational evidence points toward two validated root causes:

* **x₂ — DISCOM grid constraints and inadequate upfront grid visibility**
* **x₄ — fragmented municipal approvals and SLA gaps**

The 2-sample t-test provides statistical evidence that HT requirements significantly increase deployment time, while the regression analysis demonstrates a strong relationship between administrative waiting and total cycle-time variation.

The Gemba and industry validation further support the conclusion that the dominant problem is **administrative coordination and process design**.

The next step is therefore not to build faster.

It is to **remove the reasons the project has to wait.**

---

## 👥 Team

**Team 1**
MS491-XVI — Lean Six Sigma
IIT Gandhinagar

### Methodology

**DMAIC → Define → Measure → Analyse → Improve → Control**

---

## 🔖 Keywords

`Lean Six Sigma` `DMAIC` `EV Charging Infrastructure` `Electric Vehicles` `Process Improvement` `Root Cause Analysis` `Pareto Analysis` `Hypothesis Testing` `2-Sample T-Test` `Regression Analysis` `Process Capability` `Muda` `Poka-Yoke` `DISCOM` `LT` `HT` `Municipal Approvals` `EV Infrastructure` `India`
