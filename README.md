# App Store Performance Analysis (MANM526 Project)

This project explores the determinants of app revenue using Stata and an app store dataset. Econometric analyses include OLS regressions, diagnostic tests, and robustness checks based on real-world data.

## 📊 Dataset

- Panel dataset of app performance from 2022–2023.
- Key variables include: `monthly_revenue`, `active_users`, `downloads`, `app_type`, `in_app_purchases`.

## 📈 Analysis Conducted

- Correlation analysis and descriptive statistics
- OLS regressions (baseline and modified)
- Graphical exploration of relationships (scatter plots, histograms)
- Multicollinearity and heteroskedasticity diagnostics
- Robustness checks

## 🛠 Tools Used

- Stata MP
- Microsoft Word (report formatting)

## 📂 Project Structure

- `report/` – Final report in DOCX
- `stata_code/` – Stata `.do` files used for the analysis
- `data/` – Raw dataset (not shared if confidential)
- `output/` – Exported regression tables and figures

## 📌 Highlights

- 1% increase in active users leads to ~0.32% increase in revenue (log-log model)
- Included robust standard errors and tested for heteroskedasticity
- Investigated interaction effects between country and active user impact on revenue

## 📝 License

MIT License