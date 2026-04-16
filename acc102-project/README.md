# Customer Shopping Behavior Analysis

A data analysis project for ACC102 Mini Assignment (Track 2).

## 1. Problem & User

**Problem**: What factors significantly influence customers' single-transaction purchase amount?

**User**: Marketing teams in small-to-medium retail enterprises.

## 2. Data

- **Source**: Customer Shopping Behavior Dataset (`shopping_behavior_updated.csv`)
- **Original link**: https://blog.csdn.net/2401_87245171/article/details/154134519
- **Access date**: 15 April 2026
- **Description**: 3,900 records covering customer demographics, purchase details, and transaction information.

## 3. Methods

- Data cleaning and age grouping using pandas
- Exploratory analysis by gender, age group, payment method, frequency, and category
- Visualisation with matplotlib

## 4. Key Findings

- Female customers spend more than male customers.
- The 31–45 age group is the highest-spending segment.
- Venmo and PayPal users have higher average transaction values.
- Weekly shoppers spend more per transaction than annual shoppers.
- Electronics is the top product category by average purchase amount.

## 5. How to Run

```bash
git clone https://github.com/[your-username]/acc102-shopping-analysis.git
cd acc102-shopping-analysis
pip install -r requirements.txt
jupyter notebook shopping_analysis.ipynb

## 6. Product Link / Demo

- **GitHub Repository**: https://github.com/yuyaozhang05-sudo/acc102-shopping-analysis
- **Demo Video**: [点击这里观看演示视频](https://mediasite.xxx/您的视频链接)

## 7. Limitations

- The dataset is synthetic and may not fully represent real-world retail patterns.
- Analysis uses only descriptive statistics; no hypothesis testing was performed.
- Sample size (3,900 records) is relatively small.
- No temporal data available to analyse seasonal or promotional effects.

**Author**: Zhang Yuyao | **Student ID**: 2473441 | **Date**: 15 April 2026