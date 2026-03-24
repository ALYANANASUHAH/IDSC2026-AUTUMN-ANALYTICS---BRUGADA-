# IDSC 2026: Mathematics for Hope in Healthcare
**Team Name:** Aurum Analytics  
**Project Title:** BRUGADA-HUCA:12 - LEAD ECG RECORDINGS FOR THE STUDY OF BRUGADA SYNDROME

---

## Project Overview
This study uses the Brugada-HUCA dataset, a collection of 12-lead ECG recordings from Central University Hospital of Asturias available on PhysioNet, to analyze Brugada Syndrome. We focus on:
1. **Automated Diagnosis:** High-precision classification of Brugada ECG patterns.
2. **Treatment Optimization:** Utilizing Reinforcement Learning to suggest clinical decision-making strategies.

---

## Dataset and Citations
This study utilizes the official **Brugada-HUCA Dataset** from PhysioNet.
* **Dataset Citation:** Costa Cortez, N., & Garcia Iglesias, D. (2026). Brugada-HUCA: 12-Lead ECG Recordings for the Study of Brugada Syndrome (version 1.0.0). PhysioNet. https://doi.org/10.13026/0m2w-dy83
* **Platform Citation:** Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220. https://doi.org/10.1161/01.CIR.101.23.e215rate

---

## Methodology
* **Preprocessing:** Addressed severe class imbalance using SMOTE and handled missing values through median imputation to ensure data integrity.
* **Model Architecture:** Selected XGBoost as the primary classifier for its superior ability to model complex, non-linear relationships in tabular ECG data.
* **Decision Making:** Lowered the classification threshold to 0.3 to prioritize Recall (sensitivity) and minimize the risk of missed Brugada diagnoses.

---

## Ethical AI and Interpretability
To ensure **safety validation** and **model interpretability**, we implement:
* **Clinical Transparency:** Focuses on interpretable features to ensure clinicians can verify the AI’s logic.
* **Human Support:** Positions the AI as a decision-support tool rather than a replacement, keeping final clinical control with the doctor.

---

## Steps to Run Code
1. open file `AURUM_ANALYTICS.ipynb`.
2. click button **"Open in Colab"**.
3. Upload Data: Click the Folder icon on the left sidebar, choose content folder and upload:
   - files.zip (contains all patient folders with their respective .hea and .dat files.)
     
     (Note: ZIP file name must be EXACTLY as shown)
   - metadata.csv file
4. Run Code: select "Run all".
5. Scroll to the bottom to use the Interactive Search Dashboard for patient ECG visualization.
  
