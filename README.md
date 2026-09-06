# Unemployment-Analysis-with-Python
# COVID-19 Economic Shock: Unemployment & Labor Dynamics Analysis

An empirical economic analysis investigating the impact of the COVID-19 national lockdown on regional unemployment rates, labor force participation (LFPR), 
and urban-rural resilience across India.

## 📌 Project Overview
In late March 2020, nationwide containment measures were enacted to curb the spread of COVID-19. This project analyzes the structural labor market shocks 
using high-frequency regional data. Rather than relying solely on headline figures, this study examines labor underutilization, the **discouraged worker effect**,
and sector-specific resilience gaps to propose actionable economic interventions.

## 📊 Key Findings
Before the lockdown (Jan–Mar 2020), national unemployment remained stable at ~9.2% alongside a consistent ~43–44% labor force participation rate (LFPR). The April–May 2020 peak lockdown triggered a severe shock, surging unemployment by 15.6 percentage points to ~24.8%, with urban areas suffering a steeper spike (~26.8%) than rural regions (23.4%). During the phased unlock (June 2020 onward), headline unemployment stabilized down to ~11.9% as agriculture absorbed reverse-migrant labor, though LFPR remained depressed due to prolonged worker discouragement.

### Key Analytical Takeaways:
1. **The Lockdown Cliff:** National unemployment experienced an immediate 15+ percentage-point surge following the March 24, 2020 containment measures.
2. **The Discouraged Worker Paradox:** In several regions, headline unemployment dropped faster than employment grew, caused by workers abandoning active job searches and exiting the labor force.
3. **Urban Volatility:** Urban labor markets exhibited higher volatility and greater upper-tail dispersion due to their reliance on contact-intensive service, retail, and construction sectors.

## 📈 Visualizations Built
- **National Trajectory (Plotly):** Dual-axis timeline mapping Unemployment Rate against LFPR with an annotated intervention callout for March 24, 2020.
- **State Vulnerability Ranking:** Horizontal bar chart highlighting the top 10 hardest-hit states during peak lockdown.
- **Urban vs. Rural Disparity:** Grouped box plots detailing variance and outlier behavior across policy phases.
- **Labor Slack Analysis:** Scatter plot evaluating LFPR erosion relative to spike magnitude.

## 🏛️ Policy Recommendations
1. **Targeted Urban Cash Transfers:** Introduce rapid-disbursement direct cash assistance and rent-relief mechanisms tailored to urban informal workers.
2. **Expand Rural Public Works:** Increase budget caps and guaranteed workdays for public employment schemes (such as MGNREGA) to absorb reverse-migrant labor flows.
3. **Dual-Metric Labor Monitoring:** Mandate joint reporting of LFPR and headline unemployment rates to eliminate distorted readings caused by labor force exits.
4. **Vulnerability-Indexed Fiscal Stimulus:** Disburse emergency relief funds based on state-level sector exposure rather than uniform per-capita grants.

### Prerequisites
- Python 3.9+
- Jupyter Notebook / Google Colab

### Installation
pip install pandas numpy matplotlib seaborn 
