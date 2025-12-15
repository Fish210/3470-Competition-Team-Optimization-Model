# 3470-Competition-Team-Optimization-Model
This project applies machine learning to support FTC (FIRST Tech Challenge) competition team selection using data-driven analysis.
A Random Forest classifier evaluates individuals based on attendance, dedication, and reliability to generate ranked recommendations for specific events. The system emphasizes fairness, transparency, and explainability, supporting (not replacing) human decision-making.

Model Inputs:
Attendance Average (0–1)
Dedication Rating (1–4)
Reliability Rating (1–3)

Target: label_selected (1 = selected, 0 = not selected)
If only one label class exists, the pipeline automatically regenerates balanced labels to ensure safe model training.

Key Features

-End-to-end ML pipeline in a single Colab cell
-Automatic data cleaning and validation
-Extreme handling of edge cases (single-class data)
-Event-specific ranking and probability scoring
-Exortable CSV / Excel file
-Seaborn visualizations for model validation

Outputs

Ranked list of candidates per event
Downloadable spreadsheets for Google Sheets
Visual comparisons of selected vs non-selected members

Technologies

Python, Pandas, NumPy
Scikit-learn (Random Forest)
Seaborn & Matplotlib
Google Colab

Impact:

Demonstrates real-world application of machine learning, data ethics, and decision support systems in a competitive STEM environment.

Developers: John Uy & Vishvak Gurram
