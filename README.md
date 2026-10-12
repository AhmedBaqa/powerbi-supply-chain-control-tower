# Supply Chain Control Tower | Executive Power BI Dashboard

A professional, executive-ready **2-page Supply Chain Control Tower** built in Power BI to provide end-to-end SLA visibility, carrier cost efficiency tracking, and micro-level root cause exception analysis.

---

## 📊 Executive Summary & Key Metrics
* **Total Shipments:** 2.5K[cite: 1, 2]
* **Overall OTIF (On-Time In-Full):** 76% (Target: 85%)[cite: 1, 2]
* **On-Time Delivery Rate:** 80%[cite: 1]
* **Total Freight Spend:** $1.70M[cite: 1]
* **Core Transport Modes:** Road Freight, Air Freight, Sea Freight[cite: 1, 2]

---

## 📐 Dashboard Architecture & Layout

### Page 1: Executive Overview (Macro SLA & Freight Performance)
* **Monthly SLA Performance & Volume Trend:** Tracks total shipment volumes alongside an OTIF percentage trend curve against the 85% SLA target line[cite: 1].
* **Volume Share by Transport Mode:** A clean donut chart breaking down distribution across Road, Air, and Sea freight[cite: 1].
* **Carrier Cost Efficiency ($/KG):** Evaluates logistics partners (Desert Trans, Swift Logistics, Apex Freight, Express Cargo) by cost efficiency and mode[cite: 1].
* **Operational Exception & Performance Matrix:** A detailed interactive table displaying warehouse origins, destination cities, carriers, shipment counts, on-time percentages, and delayed shipment counts[cite: 1].

### Page 2: Root Cause & Exception Analysis (Micro Diagnostic Toolkit)
* **Hero OTIF Target Gauge:** High-impact visual displaying actual performance vs. the 85% corporate SLA benchmark[cite: 2].
* **Regional Delay Risk Map:** Geographic visualization highlighting high-risk destination cities and delivery bottlenecks[cite: 2].
* **Delay Root Cause Distribution:** Donut chart isolating primary disruption drivers (Customs Clearance, Traffic/Weather, Vehicle Breakdown, Warehouse Bottleneck)[cite: 2].
* **Delay Severity Breakdown (Days Late):** Categorizes late deliveries into actionable severity buckets (*1–2 Days Minor*, *3–5 Days Moderate*, *5+ Days Critical*)[cite: 2].
* **AI Decomposition Tree:** Interactive root-cause diagnostic tool enabling executives to drill down dynamically by transport mode, origin warehouse, carrier, and delay reason[cite: 2].

---

## 🛠️ Technical Stack & Implementation
* **Tool:** Power BI Desktop
* **Data Modeling & Calculations:** Custom DAX measures for OTIF %, delay rates, cost impacts, and conditional color-formatting logic.
* **Design System:** 
  * **Layout:** Executive 1920x1080 canvas layout with card containers (`8px` border radius, drop shadows).
  * **Typography:** `Segoe UI` across all headers, cards, and data labels.
  * **Color Palette:** Slate Navy (`#0F172A`), Light Slate Background (`#F8FAFC`), Soft Amber (`#FBBF24`), and Crimson Red (`#EF4444`) for SLA breaches.

---

## 🚀 How to Explore
1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Explore the interactive cross-filtering by clicking on various transport modes, destination cities, or delay categories to watch the diagnostic triad update dynamically.
