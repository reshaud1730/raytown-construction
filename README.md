# 🏗️ Raytown Construction: Builder Portal
**Powered by FASTTRACK TOOLs**

Welcome to the official repository for the **Raytown Construction Depo**. This portal is designed to streamline metaverse development in Upland by providing high-precision progress analytics for construction projects.

## 🛠️ The RTC Progress Calculator
The core feature of this portal is the **Reverse Spark Hour (SH) Analyzer**. In Upland, tracking exactly how many Spark Hours have been *completed* on a live build can be difficult without manual logs. Our tool solves this by calculating completed work based on real-time "Time Remaining" data.

### 📐 The Formula
To find your **Completed Spark Hours (CSH)**, we use the following architectural logic:

$$CSH = R - ((D \times 24 + H) \times S)$$

**Variables:**
* **$R$**: Total Project Requirement (Total Spark Hours needed for the building).
* **$D$**: Days remaining shown in the Upland UI.
* **$H$**: Hours remaining shown in the Upland UI.
* **$S$**: Current amount of Spark staked on the property.

---

## 🚀 Quick Start
1.  **Open the Portal:** Navigate to the `index.html` (or the Insights tab).
2.  **Input Project Specs:** Enter the total SH requirement for your building.
3.  **Sync UI Data:** Type in the Days and Hours exactly as they appear on your property in Upland.
4.  **Enter Stake:** Input your current Spark contribution ($S$).
5.  **Analyze:** Click **Run Progress Analysis** to get your banked Spark Hours.

## 📊 About Raytown Construction
Raytown Construction doesn’t just build; we engineer. All of our neighborhood developments, strategic acquisitions, and node master plans are backed by the **FASTTRACK TOOLs** data-driven ecosystem.

---
*© 2026 Raytown Construction. Engineered for the Metaverse.*
