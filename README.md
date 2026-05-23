# MrBeast YouTube Video Statistics EDA

## Overview
This project cleans and explores a dataset of MrBeast YouTube video statistics. It focuses on exploratory data analysis, outlier detection, and preparing a cleaned version of the dataset. The project is a compact EDA example using media analytics data.

## Motivation
YouTube analytics data provides a practical setting for cleaning messy real-world data and identifying outliers. This project demonstrates early data analysis skills: loading a dataset, inspecting distributions, detecting unusual points, and preparing data for further analysis.

## Dataset
- **Source:** Kaggle MrBeast YouTube statistics dataset.
- **File:** `data/mr_beast_youtube_stats.csv`
- **Target variable:** Not applicable for the current EDA version.
- **Important features:** TODO: add important columns after rerunning notebook.
- **Dataset size:** TODO: add dataset size after rerunning notebook.
- **Known limitations:** Video performance is affected by timing, platform algorithms, audience behavior, and content strategy; EDA does not prove causality.

## Methods
- Loaded and inspected YouTube statistics data.
- Cleaned selected fields.
- Identified outlier data points.
- Prepared processed output in `results/`.

## Results
TODO: add metric after rerunning notebook.

## Key Insights
- TODO: add insight after rerunning notebook.
- TODO: add insight after rerunning notebook.
- TODO: add insight after rerunning notebook.

## Limitations
- The analysis is descriptive only.
- Outliers should be interpreted carefully because viral content naturally creates extreme values.
- The dataset may not include all relevant platform or timing variables.

## Future Improvements
- Add clear visualizations of views, likes, comments, and upload timing.
- Add outlier-method documentation.
- Compare results against other YouTube channels.
- Add a short media analytics summary.

## How to Run
```bash
git clone https://github.com/BobbY-24/MrBeast_Video_Stats_EDA.git
cd MrBeast_Video_Stats_EDA
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/mrbeast_video_stats_eda.ipynb
```
