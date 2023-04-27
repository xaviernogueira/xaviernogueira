⛈ Hi, I’m Xavier Nogueira! I’m a data scientist/developer interested in adding value to the world at the nexus of technology and environmental science. I also dabble in quantitative finance. 

-----------------------
**My Public Projects**

⏳ [`Xarray-DataAccessor`](https://github.com/LimnoTech/Xarray-DataAccessor) - Working for [LimnoTech](https://www.limno.com/) I was tasked with creating a Python library that faciliates rapid read-in of remote climate, topographic, land cover, and soils data into standardized `xarray.Dataset` objects. The library was built using a [factory architecture pattern](https://en.wikipedia.org/wiki/Factory_method_pattern) in order to create a unified "user interface" that abstracts dataset provider specific details as well as to encourage open-source contributions/plugins. `Xarray-DataAccessor` also enables a variety of data transformations and utility functions to meet a variety of hydrologic modelling need. This library is still a work in progress...more features are planned!

🚀 [`FCPGtools version 2.0`](https://github.com/usgs/water-fcpg-tools) - Working for [LimnoTech](https://www.limno.com/) I was tasked with executing on a ground-up refactor and redesign of [USGS's Flow-Conditioned Parameter Grid software](https://www.usgs.gov/software/flow-conditioned-parameter-grid-tools). I implemented a `xarray` based workflow within a highly modular and extendable library architecture.  Compared to the previous version of the software, functionality has been vastly expanded, the need for saving local files has been eliminated, and processing speeds are nearly 10x faster. For more information, please reference the [repo](https://github.com/usgs/water-fcpg-tools) and/or our [documentation site](https://usgs.github.io/water-fcpg-tools/build/html/index.html).

⏳ `value_investing_tools` - A python toolset for the modern value investor! This is a pet project of mine, but one I am quite proud of. *Release is expected in Winter 2023*. The toolset enables: 
 * **Rapid, flexible, and complete (no year limit!) data retrival** for a wide variety of financial metrics as `Stock` attributes (i.e. `Stock.earnings`) without sacrificing backdore access to complete balance sheets, cash flow statements, and income statements as pandas DataFrames (via `Stock.export_full_data()`).
 * **Interactive plotting in Jupyter Lab** with native [`plotly-express`](https://plotly.com/python/plotly-express/) functions.
 * **Scalability via "lazy" computation** - financial metric are only calculated when called upon. This allows for rapid initialization of `Stock` objects, allowing you to quickly build a list/portfolio of ticker symbols (maximum = 50 without a premium API key) with minimal computational overhead.
 * **Discounted Cash Flow (DCF)** valuation analyses using `ValueInvestingTools.DCF()`, as well as a variety of DCF visualizations.
 * **Calculate relevant statistics**, transform time-series data using rolling windows, and more!

🚀 [`GCS-Analysis-Tools`](https://github.com/xaviernogueira/GCS-Analysis-Tools) - A Python executable Graphic User Interface (GUI) enabling a complete Geomorphic Covariance Structure analysis (GCS). This project was a core deliverable from time working as a graduate reasearch assistant for the [Pasternack Lab @ UC Davis](http://pasternack.ucdavis.edu/research) and has been used by others in the lab since my departure. GCS analysis may seem complicated at first, but is an incredibly powerful tool for understanding fluvial morphodynamics, with relevance for river restoration design as well as Environmental Flow (E-Flow) prescription. For more information on the GUI please reference the [repo](https://github.com/xaviernogueira/gcs_gui) or my [documentation site](https://gcs-gui-documentation.readthedocs.io/en/latest/#). For more information of GCS analysis, please reference my [MS thesis paper](https://escholarship.org/uc/item/5mm3q087).

Much of my work has unfortunoutly been private! However, within reason, I would be happy to dicuss some of the other projects I've contributed to. Dont' be a stranger! Feel free to reach out.

📫 How to reach me: xavier.rojas.nogueira@gmail.com.

<!---
xaviernogueira/xaviernogueira is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
