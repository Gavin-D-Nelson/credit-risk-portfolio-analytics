# Credit Risk Portfolio Analytics & Default Prediction
## Project Log

This document records major project decisions, assumptions, and changes made throughout the development of the Credit Risk Portfolio Analytics & Default Prediction project.

---

## Phase 1 — Define the Project

### Project Scope

**Decision:** Build a credit risk portfolio analytics and default prediction project from the perspective of a consumer lender.

**Primary Business Question:**  
Which borrowers and loan characteristics create the greatest default risk, and how can the portfolio be managed more effectively?

**Target Audience:**
- Credit risk managers
- Underwriting teams
- Business leaders

**Planned Deliverables:**
- Portfolio risk analysis
- Default prediction model
- Borrower risk tiers
- Scenario/stress testing
- Interactive dashboard
- Employer-facing GitHub case study

---

### Data Source

**Dataset:** LendingClub Accepted Loans 2007–2018 Q4

**Decision:** Use LendingClub accepted-loan data because it contains borrower characteristics, loan information, credit information, and final loan outcomes suitable for portfolio analysis and default prediction.

**Target Outcome:** Loan status will eventually be transformed into a binary default/non-default target.

**Important:** The exact target definition and treatment of individual loan statuses will be finalized during the target-definition stage of the project.

**Raw Data Storage:** The full raw dataset will not be uploaded to GitHub due to its size. Raw and processed data directories are excluded through `.gitignore`.

Additional dataset information is maintained in the dataset documentation and data dictionary.

---

### Project Structure

**Decision:** Organize the repository into dedicated directories for:

- Raw, processed, and output data
- Jupyter notebooks
- SQL
- Dashboard files
- Models
- Images
- Documentation

This structure separates source data, analytical work, model artifacts, dashboard development, and project documentation.

---

### Python Environment

**Python Version:** Python 3.13.15

**Environment:** Project-specific Python virtual environment (`.venv`)

**Primary Packages:**
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter
- SQLAlchemy
- SHAP
- joblib

**Development Environment:** Thonny will be used as the primary Python IDE, with Jupyter notebooks used for analytical workflows where appropriate.

**Gradient Boosting:** XGBoost was considered during environment setup but is not currently required. A gradient-boosting package may be added later if justified during model development.

---

### SQL vs. Python

**Python will be used for:**
- Data ingestion
- Data cleaning and transformation
- Target creation
- Data leakage prevention
- Exploratory data analysis
- Feature engineering
- Predictive modeling
- Model evaluation
- Model explainability

**SQL will be used for:**
- Portfolio-level summaries
- Segment-level credit risk analysis
- Default-rate analysis
- Loan exposure summaries
- Dashboard-ready portfolio tables

**Decision:** SQL will be used where it represents realistic portfolio reporting and aggregation work rather than being added unnecessarily to the project.

---

## Phase 2 — Prepare and Understand the Data

*Decisions and findings will be added as Phase 2 is completed.*

---

## Phase 3 — Build the Portfolio Analytics

*Decisions and findings will be added as Phase 3 is completed.*

---

## Phase 4 — Develop and Evaluate the Default Model

*Decisions and findings will be added as Phase 4 is completed.*

---

## Phase 5 — Turn the Model into a Business Tool

*Decisions and findings will be added as Phase 5 is completed.*

---

## Phase 6 — Package the Project for Employers

*Decisions and findings will be added as Phase 6 is completed.*
