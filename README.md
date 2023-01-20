⛈ Hi, I’m Xavier Nogueira! I’m a water resources/environmental data scientist interested in adding value to the world at the nexus of technology and natural resources stewardship. I am passionate about leveraging open-source Python libraries to level-up what is possible in the environmental sciences. I also dabble in quantitative finance. 

-----------------------
**My Projects**


⏳ `FCPGtools version 2.0` - Working for [LimnoTech](https://www.limno.com/) I was tasked with executing on a ground-up refactor and redesign of [USGS's Flow-Conditioned Parameter Grid software](https://www.usgs.gov/software/flow-conditioned-parameter-grid-tools). I implemented a `xarray` based workflow within a highly modular and extendable library architecture.  Compared to the previous version of the software, functionality has been vastly expanded, the need for saving local files has been eliminated, and processing speeds are nearly 10x faster. For more information, please reference the [repo](https://github.com/usgs/water-fcpg-tools) and/or our [documentation site]([https://github.com/usgs/water-fcpg-tools](https://usgs.github.io/water-fcpg-tools/)).

⏳ `value_investing_tools` - A python toolset for the modern value investor! This is a pet project of mine, but one I am quite proud of. *Release is expected in Winter 2023*. The toolset enables: 
 * **Rapid, flexible, and complete (no year limit!) data retrival** for a wide variety of financial metrics as `Stock` attributes (i.e. `Stock.earnings`) without sacrificing backdore access to complete balance sheets, cash flow statements, and income statements as pandas DataFrames (via `Stock.export_full_data()`).
 * **Interactive plotting in Jupyter Lab** with native [`plotly-express`](https://plotly.com/python/plotly-express/) functions.
 * **Publication-ready static plotting** power by [`seaborn`](https://seaborn.pydata.org/api.html).
 * **Scalability via "lazy" computation** - financial metric are only calculated when called upon. This allows for rapid initialization of `Stock` objects, allowing you to quickly build a list/portfolio of ticker symbols (maximum = 50 without a premium API key) with minimal computational overhead.
 * **Discounted Cash Flow (DCF)** valuation analyses using `ValueInvestingTools.DCF()`, as well as a variety of DCF visualizations.
 * **Calculate relevant statistics**, transform time-series data using rolling windows, and more!

🚀 `GCS-Analysis-Tools` - A Python executable Graphic User Interface (GUI) enabling a complete Geomorphic Covariance Structure analysis (GCS). This project was my main deliverable during my time working as a graduate reasearch assistant for the [Pasternack Lab @ UC Davis](http://pasternack.ucdavis.edu/research). GCS analysis may seem complicated at first, but is an incredibly powerful tool for understanding fluvial morphodynamics, with relevance for river restoration design as well as Environmental Flow (E-Flow) prescription. For more information on the GUI please reference the [repo](https://github.com/xaviernogueira/gcs_gui) or my [documentation site](https://gcs-gui-documentation.readthedocs.io/en/latest/#). For more information of GCS analysis, please reference my [MS thesis paper](https://escholarship.org/uc/item/5mm3q087).

Much of my work has unfortunoutly been private! However, within reason, I would be happy to dicuss some of the other projects I've contributed to. Dont' be a stranger! Feel free to reach out.

📫 How to reach me: xavier.rojas.nogueira@gmail.com.

<!---
xaviernogueira/xaviernogueira is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
