# 🚀 PhishScope: 1-Week Execution & Research Paper Plan

To successfully develop the PhishScope framework and write the research paper in **just one week**, we must follow a strict, parallelized schedule. 

## 📅 Day-by-Day Roadmap

### Day 1: Data Pipeline & Static Analysis
* **Development Tasks:**
  * Setup Python virtual environment (`requirements.txt`).
  * Download URL datasets (e.g., PhishTank, OpenPhish, Kaggle Benign URLs).
  * Write the `static_extractor.py` to extract URL, HTML, and Domain/WHOIS features.
* **Paper Tasks:** 
  * Finalize the paper title and author details.
  * Write the **Abstract** and **Introduction** in LaTeX.

### Day 2: Dynamic Sandbox Execution
* **Development Tasks:**
  * Implement `dynamic_sandbox.py` using Selenium or Playwright.
  * Capture runtime behaviors: redirects, JavaScript execution, and DOM mutations.
  * Fuse static and dynamic datasets into a final CSV for training.
* **Paper Tasks:**
  * Write the **Related Work / Literature Review** section (migrating content from the synopsis).

### Day 3: Hybrid ML Model Training
* **Development Tasks:**
  * Split data into Train/Test sets.
  * Train the Hybrid Classification Model (Random Forest + XGBoost).
  * Generate performance metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC).
* **Paper Tasks:**
  * Write the **Methodology (System Architecture)** section.
  * Create system architecture diagrams for the paper.

### Day 4: Explainable AI (XAI) & Risk Scoring
* **Development Tasks:**
  * Integrate **SHAP** and **LIME** (`xai_explainer.py`).
  * Generate feature importance graphs and local explanation plots.
  * Develop the composite risk scoring formula.
* **Paper Tasks:**
  * Write the **Proposed XAI Framework** section.

### Day 5: Prototype API & Data Visualization
* **Development Tasks:**
  * Wrap the pipeline in a simple FastAPI or Flask application to serve predictions.
  * Save all charts (SHAP plots, ROC curves, confusion matrix) as `.png` or `.pdf` for LaTeX.
* **Paper Tasks:**
  * Write the **Experimental Setup & Dataset** section.

### Day 6: Results Documentation
* **Development Tasks:**
  * Run final tests and record all metrics.
* **Paper Tasks:**
  * Write the **Results and Discussion** section.
  * Insert tables comparing PhishScope against baseline models.
  * Insert generated plots (SHAP global importance).

### Day 7: Final Review & Compilation
* **Paper Tasks:**
  * Write the **Conclusion and Future Scope**.
  * Format all BibTeX references properly.
  * Compile the LaTeX document to PDF, check for formatting errors, and proofread.
