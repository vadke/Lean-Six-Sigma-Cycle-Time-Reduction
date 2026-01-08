# 📉 Lean Six Sigma: Proposal Cycle Time Reduction

## 📌 Business Overview
**Gentech**, a multinational technology firm ($60B Revenue), faced stagnating growth due to inefficiencies in its sales operations. The "Quote-to-Tender" process was sluggish, leading to lost deals and customer dissatisfaction.
* **Goal:** Reduce the Sales Proposal Cycle Time by **15%**.
* **Methodology:** Lean Six Sigma (**DMAIC** Framework).

## 🔄 The DMAIC Approach

### 1. Define
* **Problem:** Average proposal creation time was **31.6 days**, with a high variation (Standard Deviation ~14 days).
* **SIPOC Analysis:** Mapped the end-to-end flow from "Customer Request" to "Proposal Submission."
* **Artifact:** [Process Swimlane Map](Final%20Swimlane.drawio%20(2).pdf) identifying bottlenecks in hand-offs between Sales and Bid Support.

<img width="965" height="525" alt="image" src="https://github.com/user-attachments/assets/23358fbc-1d1e-43ad-9808-cca5d1fcaf44" />

### 2. Measure
* **Baseline Metrics:**
    * **DPMO (Defects Per Million Opportunities):** 281,053
    * **Process Sigma Level:** 2.08 (Low capability).
    * **Defect Definition:** Any proposal taking >35 days.

      <img width="477" height="309" alt="image" src="https://github.com/user-attachments/assets/36b17567-3226-43a4-8949-2c05e1733943" />

* **Visualization:** Created a **Tableau Dashboard** to track cycle time distribution by "Brand" and "Region."

<img width="536" height="267" alt="image" src="https://github.com/user-attachments/assets/9048def8-d6fb-4731-a9f9-35e6290d1cb2" />

### 3. Analyze
* **Root Cause Analysis:** Used **Fishbone (Ishikawa) Diagram** to identify key contributors:
    * *Process:* Redundant approval loops for small bids.
    * *People:* Lack of standardized training for new sellers.
    * *Technology:* Manual data entry errors causing rework.

<img width="986" height="622" alt="image" src="https://github.com/user-attachments/assets/8d19aa38-3e1d-413a-9216-509858a4920b" />

### 4. Improve
* **Solutions Implemented:**
    * **RPA (Robotic Process Automation):** Automated data entry for "Standard" bids, removing manual delays.
    * **Poka-Yoke (Mistake Proofing):** Added validation rules in the CRM to prevent incomplete submissions.
    * **Parallel Processing:** Shifted legal and pricing reviews to run simultaneously rather than sequentially.
* **Projected Impact:**
    * **Cycle Time:** Reduced from 31.6 days → **~26.9 days** (15% reduction).
    * **Sigma Level:** Improved from 2.08 → **~2.78**.

<img width="530" height="420" alt="image" src="https://github.com/user-attachments/assets/57ad31d0-8493-4b8e-bb8a-279254995574" />

### 5. Control
* **Sustainment:** Implemented a "Control Plan" with automated alerts for SLA breaches (proposals >30 days).
* **Dashboarding:** Live monitoring of "Average Days to Close" via Tableau.

<img width="1114" height="577" alt="image" src="https://github.com/user-attachments/assets/1752e410-586e-4b22-9619-6f2825fafb90" />
  

## 🛠 Tools Used
* **Methodology:** Lean Six Sigma (Green Belt level)
* **Visualization:** Tableau, Draw.io (Process Mapping)
* **Analysis:** Minitab (Normality Tests, Sigma Calculation), Excel

## 📂 Project Structure
* `Gentech Presentation.pptx` - Full Executive Presentation.
* `Tableau Gentech Case Study.twbx` - Interactive Dashboard.
* `Final Swimlane.pdf` - As-Is vs. To-Be Process Maps.
