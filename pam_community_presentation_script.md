# PAM Community Session | November 2026

## CHARM PAM+ Compliance Metrics \& Power BI Walkthrough Script

**Target Duration:** 25–30 Minutes (Presentation) + Live Power BI Demo  
**Audience:** PAM Community, Market Security Leads, Governance \& Risk Stakeholders

\---

## Part 1: Slide-by-Slide Presentation Script (25–30 Mins)

### Slide 1: Title \& Agenda Overview

* **Title:** PAM Community Session | November 2026 – CHARM PAM+ Compliance Metrics
* **Suggested Time:** 2 Minutes
* **Script:**

> "Good morning, everyone, and welcome to the November 2026 PAM Community session. Today, we are walking through our upgraded, standardized reporting framework for Privileged Access Management—aligning our global markets under the \*\*CHARM PAM+\*\* initiative. 
  > 
  > Over the next 25 minutes, we will cover three core security pillars: \*\*Password Hygiene\*\*, \*\*Password Exposure\*\*, and \*\*Session Isolation\*\*. More importantly, we’re going to look at \*how\* we measure these globally while strictly adhering to privacy-by-design principles—ensuring that only aggregate compliance metrics leave individual markets while sensitive operational data stays local."

\---

### Slide 2: Data Flow \& Governance Boundary

* **Title:** What we ask from Markets: metrics only | Privacy by design
* **Suggested Time:** 3 Minutes
* **Script:**

> "Let's establish our governance and privacy boundary right off the bat. When we talk about global reporting in a multinational footprint like ours, data privacy and residency are paramount. 
  > 
  > As shown on this slide, what gets \*\*shared with PAM+\*\* are strictly aggregated components: the Market name, the metric identifier, the final compliance percentage, and agreed supporting totals. 
  > 
  > What \*\*stays strictly in the Market\*\*—meaning it never crosses regional boundaries—includes safe names, platform names, specific account names, underlying objects, and owner details. Risk and CHARM define the governance rules, exceptions, and reporting structures, but local evidence stays local for your internal validation and remediation."

\---

### Slide 3: The Three Core Metrics Framework

* **Title:** Three metrics, one simple question each
* **Suggested Time:** 4 Minutes
* **Script:**

> "To keep things transparent and comparable across all markets on a like-for-like basis, we track three foundational metrics. Every market is measured by the exact same yardstick:
  > 
  > 1. \*\*Password Hygiene:\*\* \*Are credentials rotated on time?\* This measures privileged accounts whose password age falls inside our agreed operational window.
  > 2. \*\*Password Exposure:\*\* \*Are passwords protected from human eyes?\* This tracks accounts where direct \*\*Show, Copy, or Retrieve\*\* capabilities are fully controlled.
  > 3. \*\*Session Isolation:\*\* \*Are sessions brokered rather than direct?\* This measures accounts accessed safely through \*\*Click-to-Connect / PSM\*\* (Privileged Session Management).
  > 
  > Our overall compliance percentage formula is simple: accounts meeting the control divided by the total in-scope privileged accounts."

\---

### Slide 4: Metric 1 Deep Dive – Password Hygiene

* **Title:** Password Hygiene | Metric 1: Are credentials rotated on time?
* **Suggested Time:** 3 Minutes
* **Script:**

> "Let's zoom into Metric 1: Password Hygiene. 
  > 
  > \*\*Why does this matter technically?\*\* A static privileged password gives an attacker an extended window of opportunity if compromised. Regular, automated rotation shrinks that exposure window. 
  > 
  > \*\*How it's calculated:\*\* We take the count of accounts where password age is within the defined threshold and divide it by the total in-scope privileged accounts. In our Power BI dashboards, we segment password age into precise risk bands: \*\*less than or equal to 30 days\*\*, \*\*30 to 60 days\*\*, \*\*60 to 90 days\*\*, and critical stale credentials sitting at \*\*greater than 90 days\*\*."

\---

### Slide 5: Hygiene in Power BI (Aggregated View)

* **Title:** Aggregated | Market Level – Hygiene Dashboard
* **Suggested Time:** 4 Minutes
* **Script:**

> "Here is how Metric 1 translates directly into our Power BI reporting interface. 
  > 
  > On the left-hand panel, you can see total accounts in scope broken down by Market—ranging from large footprints like Vodafone India (1,143 accounts) down to single-digit operations. 
  > 
  > Looking at the \*\*Password Rotation Risk\*\* donut chart on the right: the vast majority—\*\*85.52%\*\*—sit safely in the green zone ($\\le 30$ days). However, we see a critical risk slice of \*\*14.1%\*\* sitting in the $> 90$ days bucket, which requires immediate remediation. 
  > 
  > The lower table maps out exact counts for Compliant, Exception, and Non-Compliant states per market, bringing our global total baseline to 2,696 accounts."

\---

### Slide 6: Metric 2 Deep Dive – Password Exposure

* **Title:** Password Exposure | Metric 2: Are passwords protected from people?
* **Suggested Time:** 3 Minutes
* **Script:**

> "Moving to Metric 2: Password Exposure. 
  > 
  > \*\*The core risk here:\*\* If a user can directly view, copy, or download a password from the CyberArk vault, that credential can be shared, pasted into scripts, or reused outside authorized channels. 
  > 
  > Therefore, our control objective is locking down direct retrieval permissions. The calculation is simple: accounts where direct retrieval is restricted, divided by in-scope privileged accounts. 
  > 
  > We specifically target three direct actions: \*\*Show\*\*, \*\*Copy\*\*, and \*\*Retrieve\*\*."

\---

### Slide 7: Exposure in Power BI

* **Title:** Exposure in Power BI | Aggregated Market Level
* **Suggested Time:** 3 Minutes
* **Script:**

> "This slide illustrates the Power BI 100% stacked bar view for Password Exposure across markets. 
  > 
  > \*\*How to read these bars:\*\* The green segment indicates retrieval is properly controlled (compliant), while the red segment indicates direct retrieval capability is still active (the security gap). 
  > 
  > What stands out immediately? Egypt shows the highest controlled share at \*\*25.98%\*\* green. Markets like India, Group, Portugal, Romania, and the UK display small green slices (3% to 8%), while 12 markets—from Germany down to Mozambique—are currently 100% red, highlighting our primary global remediation roadmap over the next quarters."

\---

### Slide 8: Metric 3 Deep Dive \& Power BI View – Session Isolation

* **Title:** Session Isolation | Metric 3: Are sessions brokered, not direct?
* **Suggested Time:** 4 Minutes
* **Script:**

> "Our third pillar is Session Isolation. 
  > 
  > \*\*Why it matters:\*\* Direct connections to target infrastructure bypass monitoring and expose raw credentials. By forcing sessions through \*\*Click-to-Connect\*\* and CyberArk \*\*PSM (Privileged Session Manager)\*\*, the user interacts with the target system without ever seeing the password, while the session itself is fully recorded and audited. 
  > 
  > Looking at the Power BI visual on Slide 8, the structural layout mirrors our exposure dashboard for easy cross-market comparison. Once again, Egypt leads with \*\*25.98%\*\* session isolation compliance, and our objective across the community is to systematically grow that green share, market by market."

\---

### Slide 9: Technical Data Flow \& Governance Architecture

* **Title:** Data flow and governance boundary summary
* **Suggested Time:** 2 Minutes
* **Script:**

> "To summarize our technical architecture pipeline:
  > 1. \*\*CyberArk Source:\*\* Raw vault data is queried locally within the market.
  > 2. \*\*Local SQL Logic:\*\* Local transformation scripts run against the dataset.
  > 3. \*\*Local Validation:\*\* Local security teams validate the findings and manage remediation.
  > 4. \*\*Aggregated Metrics:\*\* Only high-level KPI percentages and agreed totals are extracted.
  > 5. \*\*PAM Community Dashboard:\*\* Published globally into Power BI for transparent executive tracking—ensuring safe names, platform names, and account owners \*never\* leave the local boundary."

\---

### Slide 10: Transition to Live Demo

* **Title:** Next: Live demo – CHARM PAM+ Compliance Dashboard in Power BI
* **Suggested Time:** 1 Minute
* **Script:**

> "That concludes our architectural walkthrough of the metrics and governance model. I am now going to switch screens and open up the live Power BI dashboard so we can explore the interactive filters, drill-downs, and market comparisons in real-time. Let's jump into the demo."

\---

## Part 2: Power BI Live Demo Talking Points

When sharing your screen for the Power BI portion, highlight the following interactive features:

1. **Market Slicers / Filters:** Show how selecting a specific market (e.g., Vodafone India or Vodafone Group) dynamically updates the rotation risk rings and compliance summary tables.
2. **Drill-Throughs \& Tooltips:** Hover over the password rotation age bands ($\\le 30$ days up to $> 90$ days) to demonstrate how granular risk distribution is visualized without exposing underlying CyberArk object names.
3. **Cross-Highlighting:** Click on the green vs. red segments in the Password Exposure and Session Isolation stacked bar charts to show how the UI isolates compliant vs. non-compliant asset totals for regional leads.

