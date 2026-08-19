# CalcuStats — Free Sample Size Calculator & Statistical Analysis Software

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://shinyhealthtools.github.io/calcustats/)
[![Vercel Deployment](https://img.shields.io/badge/deployed%20on-vercel-black)](https://calcustats.vercel.app/)

**Calculate. Analyze. Publish.** — A complete, free, and modern web‑based sample size calculator and statistical suite for researchers, data analysts, and students.

**Live Application:**
- [CalcuStats on GitHub Pages](https://shinyhealthtools.github.io/calcustats/)
- [CalcuStats on Vercel](https://calcustats.vercel.app/)

![CalcuStats Hero Screenshot](https://raw.githubusercontent.com/mudassiribrahim12/Stats/main/CalcuStatslogo.png)

## Overview

CalcuStats is a powerful, ad‑free, and **completely free** statistical software that runs entirely in your browser. No installation is required, your data never needs to be uploaded to external servers, and there is no tracking. As a single HTML file hosted as a static page, CalcuStats provides a secure and accessible environment for rigorous quantitative analysis—from sample size planning and statistical testing to advanced inferential analysis and publication-ready visualizations.

Built by a health researcher for researchers, CalcuStats bridges the gap between complex statistical software (like SPSS, Stata, or SAS) and simple online sample size calculators. It brings essential statistical planning, analysis, and visualization tools together in one accessible, free, and browser-based platform.

## Key Features

### Sample Size Calculators
- **Proportional Allocation** — Distribute your total sample proportionally across population strata. Enter stratum populations and get exact sample sizes for each group with automatic non‑response adjustment. Supports Advanced Mode with sub-strata management for detailed reporting — add sub-groups under each major stratum.
- **Taro Yamane Formula** — Calculate sample size using the classic finite‑population formula for surveys. Simply enter your population size and margin of error — assumes 95% confidence level. Features Hierarchical Group Builder with unlimited nesting — build complex population hierarchies (e.g., Country → Region → District → Facility) and auto‑populate strata.
- **Cochran’s Formula** — Calculate sample size based on estimated population proportions. Supports flexible input formats (decimal, percent, or percentage) and finite population correction (FPC) for smaller populations. Includes option to allocate across strata.
- **Other Formulas** — Additional sample size methods including: Single proportion estimation.

### Descriptive Statistics
- **Automatic detection** - Numeric and categorical variables are automatically identified upon data upload. If the automatic detection misclassifies a variable, you can change its measurement scale at any time.
- **Computes**: Mean, median, standard deviation, variance, min, max, range,
  skewness, kurtosis, **95% CI for the mean**, quartiles, percentiles, and more.
- **Frequency tables** with cumulative counts/percentages and 95% CIs for proportions.
- **High‑quality, customizable graphs** (bar, pie, histogram, boxplot) with full display options.
- **Export and share results**: Copy formatted results to clipboard for pasting into Word, Excel, or any other application. Export your complete analysis to Excel or Word with full analysis details, including all statistics, tables, and graphs.

### Advanced Inferential Tests
- **t‑Tests** — one‑sample, independent (equal/unequal variance), and paired.
- **ANOVA** — one‑way and two‑way, with post‑hoc tests (Tukey HSD, Bonferroni).
- **Regression Models** — linear (OLS), binary logistic, and Poisson.
- **Correlation** — Pearson, Spearman, and Kendall Tau with confidence intervals and scatter plots.
- **Categorical Data** — Chi‑square (with expected frequencies, effect sizes, and linear‑by‑linear association) and Fisher’s exact test (2×2).
- **Non‑Parametric Tests** — Mann‑Whitney U, Wilcoxon signed‑rank, Kruskal‑Wallis H.
- **Multivariate Methods** — ANCOVA, MANOVA, and multinomial logistic regression.
- **All p‑values, confidence intervals, and effect sizes** (Cohen’s d, Cramér’s V, etc.) are displayed in a clear, publication‑ready format.

### User Experience
- **Dark / Light theme** toggle (remembers your preference).
- Fully **responsive** — works perfectly on desktop, tablet, and mobile.
- Zero ads, zero trackers, zero data sent to any server.
- Detailed **step‑by‑step** calculation logs for all formulas.
- Copy‑paste data directly from spreadsheets (Excel, Google Sheets, CSV).

## Technologies Used

- **HTML5 / CSS3** — Custom responsive layouts, CSS Grid, and Flexbox.
- **JavaScript (ES6+)** — All calculations are performed client‑side.
- **Charting** — Native Canvas API for high‑quality graphs and flowcharts.
- **Export** — SheetJS (XLSX) for Excel exports and Blob API for Word `.doc` files.
- **Deployment** — GitHub Pages & Vercel.

## 📥 Getting Started

### Using the Live Application
Simply navigate to [CalcuStats](https://shinyhealthtools.github.io/calcustats/) and start analysing.
