# 🚀 Global Space Mission Analysis (1957 – 2020)

This project provides a comprehensive historical exploration of humanity's journey into space. By analyzing a dataset of over **4,300 launches** from the dawn of the Space Age to the modern era, the study tracks the evolution of aerospace technology, the economic shifts of exploration, and the changing geopolitical landscape—from the Cold War "Space Race" to the rise of commercial giants like SpaceX.

## 📊 Key Findings at a Glance

### 1. Operational Reliability & Rocket Status

* **Safety Maturity:** Spaceflight has transitioned from a high-risk experiment to a precise science. Failure rates plummeted from **over 70% in 1958** to consistently **under 10% by 2020**.
* **Mission Success:** The dataset records **3,879 successful missions** against 445 failures.
* **The Retired Fleet:** Approximately **82% of all rockets** in the dataset are now decommissioned, illustrating the rapid pace of technological obsolescence.

### 2. Economic Landscape

* **Spending Patterns:** Most launches cost **under $100 million**, though the data includes "heavy-lift" outliers reaching up to **$450 million**.
* **Organizational Investment:** The analysis identifies major spenders and reveals a shift from opaque, state-funded budgets to more transparent commercial pricing.

### 3. Temporal & Seasonal Trends

* **Launch Frequency:** Year-on-year charts demonstrate a steady evolution in activity, with clear spikes during periods of intense geopolitical competition.
* **The "December Peak":** Interestingly, **December** is historically the most popular month for launches, potentially driven by end-of-year fiscal cycles or specific orbital windows.
* **Price Volatility:** Average launch prices have fluctuated significantly over the decades as technology has both advanced and scaled.

### 4. Geopolitical & Organizational Evolution

* **Cold War Dominance:** A direct comparison between the **USA and USSR/Russia** highlights their early duopoly. While the USA led in the very first years, the **USSR/Russia held the cumulative lead** in total launches by 2020.
* **Shifting Leaders:** * **1970s–80s:** Dominated by the **RVSN USSR**.
* **Modern Era:** **CASC (China)** has emerged as a volume leader, alongside the disruptive entry of **SpaceX**.



---

## 🛠️ Technical Highlights

### Data Cleaning & Engineering

The project involved significant "under-the-hood" work to ensure historical data was usable:

* **Standardization:** Mapping historical launch sites (like the Baikonur Cosmodrome) to modern sovereign nations (Kazakhstan) using ISO-3166 country codes.
* **Financial Scrubbing:** Converting mixed-type price data into numeric formats and handling significant missing values.
* **Time-Series Analysis:** Implementing 9-month rolling averages to smooth out month-on-month variations in launch activity.

### Visualizations Used

* **Geospatial Maps:** Choropleth maps visualizing launch and failure distribution by country.
* **Hierarchical Charts:** Sunburst charts illustrating the relationship between countries, organizations, and mission outcomes.
* **Distribution Charts:** Histograms and box plots analyzing the spread of launch costs.
* **Comparative Charts:** Multi-line graphs tracking the dominance of the Top 10 organizations over time.

---

## 🧰 Tech Stack

* **Language:** Python
* **Analysis:** Pandas, NumPy
* **Visualization:** Plotly (Express & Graph Objects), Matplotlib, Seaborn
* **Utilities:** ISO3166, Datetime

---

*This analysis serves as a data-driven record of how space exploration moved from a high-stakes government gamble to a stable, globally collaborative, and commercially-driven industry.*
