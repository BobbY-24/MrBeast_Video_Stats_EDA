# MrBeast YouTube Video Statistics EDA

## Overview
I cleaned and explored a dataset of MrBeast YouTube video statistics. I focus on exploratory data analysis, outlier detection, and preparing a cleaned version of the dataset.

## Motivation
I used this project to practice working with media analytics data. YouTube performance data is naturally noisy and outlier-heavy, which makes it useful for learning careful EDA.

## Dataset
- **Source:** Kaggle MrBeast YouTube statistics dataset.
- **File:** `data/mr_beast_youtube_stats.csv`
- **Target variable:** I did not define a supervised target for this version.
- **Known limitations:** Video performance depends on timing, platform algorithms, audience behavior, and content strategy, so I treat the analysis as descriptive.

## Methods
- I loaded and inspected YouTube statistics data.
- I cleaned selected fields.
- I identified unusual data points.
- I prepared processed output in `results/`.

## Results
I use this repo for data cleaning and exploratory analysis rather than a model metric. The main result is a cleaner dataset and an initial understanding of outliers in video performance.

## Key Insights
- Viral video data naturally contains extreme values.
- Outliers should be explained, not automatically removed.
- I treat the project as strongest as an EDA and data-cleaning example.

## Limitations
- The analysis is descriptive only.
- The dataset may not include all relevant platform or timing variables.
- I do not make causal claims about why videos perform well.

## How to Run
```bash
git clone https://github.com/BobbY-24/MrBeast_Video_Stats_EDA.git
cd MrBeast_Video_Stats_EDA
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/mrbeast_video_stats_eda.ipynb
```
