# Global Space Mission Analysis (1957 - 2020)

This project is a comprehensive, data-driven exploration of global space exploration, beginning with the launch of Sputnik in 1957 and extending through August 2020. By analyzing a dataset of **4,324 launches**, the study documents the transition of spaceflight from a high-stakes Cold War rivalry to a commercialized, global industry.

---

## 🚀 Analysis Overview

The project is structured into four core areas of investigation:

### 1. Data Cleaning & Preparation

To ensure historical accuracy, the raw dataset underwent rigorous preprocessing:

* **Price Standardization:** Addressed 3,360 missing price entries to maintain dataset integrity.
* **Geospatial Mapping:** Standardized launch locations (e.g., converting "Baikonur Cosmodrome" to Kazakhstan) and applied ISO-3166 Alpha-3 country codes.
* **Temporal Formatting:** Converted date strings to UTC datetime objects for precise year-over-year and month-on-month time-series analysis.

### 2. Operational Reliability & Safety Trends

The analysis highlights the "maturation" of aerospace engineering over the last 60 years:

* **Failure Rate Reduction:** Early missions (1958–1960) faced failure rates between **50% and 78%**. Modern missions now consistently maintain a success rate of **over 90%**.
* **Fleet Status:** Approximately **81.7%** (3,534) of historical rocket models are now retired, illustrating the rapid pace of technological iteration.

### 3. Geopolitical Leadership & The Space Race

The study visualizes the shifting centers of global power:

* **The Superpower Era:** Detailed comparison of the USA vs. the USSR/Russia, documenting their absolute dominance throughout the 20th century.
* **The Modern Shift:** Highlights the recent emergence of **CASC (China)** as a volume leader and the significant impact of **SpaceX**, which began outperforming traditional national agencies in launch frequency by the late 2010s.

### 4. Economic & Seasonal Patterns

Insights into the logistics and finances of space exploration:

* **Launch Costs:** While many early budgets were opaque, the data reflects modern launch costs reaching up to **$450 million**.
* **Seasonal Trends:** Identified **December** as the most popular month for launches historically, likely driven by end-of-year budgetary cycles and orbital window alignments.

---

## 📈 Key Inferences

* **From Experiment to Industry:** Spaceflight has successfully transitioned from a high-risk government experiment into a stable, industrial-grade sector.
* **Multipolarity:** Leadership has moved from a two-player game (USA/USSR) to a crowded arena featuring private commercial firms and new national powers.
* **Commercial Transparency:** The availability of modern pricing data suggests a shift toward a more transparent, market-driven space economy compared to the classified spending of the Cold War era.

---

## 🛠️ Technologies Used

* **Python** (Pandas, NumPy)
* **Plotly** (Choropleth Maps, Sunburst Charts, Pie Charts)
* **Matplotlib & Seaborn** (Time-series and Distribution analysis)
* **ISO3166** (Country code standardization)

---

*This analysis serves as a narrative of humanity’s journey into the stars, illustrating our growing ability to minimize risk and expand our reach.*
