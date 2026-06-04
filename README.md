# Harshit Saini

Data engineer and full-stack developer. Building production systems at the intersection of ML and software engineering. 

Experience with: SaaS platforms (Next.js, TypeScript), machine learning pipelines (ensemble methods, walk-forward validation), AI integration, and systems designed for scale.

## Featured Work

### Stock Signal Engine

ML-powered daily trading signals for NSE India equities. Predicts 5-day forward returns for 100 liquid large-cap stocks using LightGBM with walk-forward validation.

**Results:** 16.3% CAGR vs 11.5% buy-and-hold benchmark (2020-2024, out-of-sample)

**Stack:** Python, LightGBM, pandas, scikit-learn, FRED API, Streamlit

**Key technical decisions:** Walk-forward validation to prevent look-ahead bias, confidence scoring for risk-aware sizing, 50+ feature engineering pipeline. Full reproducibility from data download to backtest report.

[Repository](https://github.com/Harshit-sys169/stock-signal-engine) | [Architecture](https://github.com/Harshit-sys169/stock-signal-engine/blob/main/ARCHITECTURE.md)

### UC Investor Updates Platform

SaaS for founder communication. Allows drafting, scheduling, and tracking investor updates with AI assistance and team collaboration.

**Stack:** Next.js 14, TypeScript, PostgreSQL, Prisma, Clerk auth, Resend emails, OpenAI API

**Features:** AI-powered content generation, email delivery tracking, role-based access control, recurring updates, inbox management

[Repository](https://github.com/Harshit-sys169/uc-investor-updates-platform)

## Data Science & ML Projects

| Project | Problem & Solution |
|---------|-------------------|
| **Earthquake Damage Prediction** | Classifying earthquake damage extent across 260k+ buildings. Used stratified k-fold CV with F1 optimization and hyperparameter tuning via GridSearchCV. |
| **Bankruptcy Prediction** | Predicting bankruptcy risk for Polish companies. Implemented ensemble methods with cost-sensitive learning, SHAP analysis for feature interpretation. |
| **Buenos Aires Real Estate** | Predicting property prices with feature selection and model stacking. Compared Ridge, Lasso, ElasticNet regularization approaches. |
| **Credit Risk Clustering** | Segmenting credit risk profiles using K-Means with PCA dimensionality reduction. Used silhouette analysis for optimal cluster validation. |
| **Market Volatility Analysis** | Time series analysis of asset volatility using rolling statistics and exponential weighted moving averages. |
| **A/B Testing Framework** | Statistical testing framework with power analysis, Chi-square tests, and hypothesis validation. |
| **Latin America Real Estate** | Geographic price analysis and feature engineering with ColumnTransformer pipelines. |

## Technical Skills

**Languages:** Python, JavaScript/TypeScript, SQL

**Data & ML:** scikit-learn, XGBoost, LightGBM, SHAP, pandas, NumPy

**Backend:** Next.js API routes, Node.js, Express, PostgreSQL, Prisma ORM

**Frontend:** React, Next.js, TypeScript, TailwindCSS

**Specialties:** 
- Supervised learning: regression, classification, ensemble methods, hyperparameter optimization
- Imbalanced data: cost-sensitive learning, SMOTE, appropriate metrics (F1, ROC-AUC)
- Interpretability: SHAP values, feature importance analysis
- Statistical testing: hypothesis testing, power analysis, Chi-square
- Feature engineering: domain-specific extraction, encoding strategies, dimensionality reduction
- Time series: rolling statistics, walk-forward validation

## Principles

- Choose the right approach over the latest algorithm
- Impact matters more than academic elegance
- Interpretability and trust are essential for adoption
- Code quality and reproducibility are non-negotiable
- Test your assumptions with data

---

Email: f20240474@pilani.bits-pilani.ac.in

Last updated: June 2026