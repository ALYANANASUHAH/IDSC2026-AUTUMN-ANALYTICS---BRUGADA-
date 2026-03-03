# IDSC 2026: Mathematics for Hope in Healthcare
**Team Name:** Aurum Analytics  
**Project Title:** Automated Brugada Syndrome Detection & Treatment Strategy Optimization using Deep Learning and Reinforcement Learning.

---

## Project Overview
This project aims to provide **hope** to patients at risk of Sudden Arrhythmic Death Syndrome (SADS) by leveraging AI for early detection of **Brugada Syndrome**. Using the Brugada-HUCA dataset, we focus on:
1. **Automated Diagnosis:** High-precision classification of Brugada ECG patterns.
2. **Treatment Optimization:** Utilizing Reinforcement Learning to suggest clinical decision-making strategies (e.g., ICD implantation vs. monitoring).

---

## Dataset & Citations
This study utilizes the official **Brugada-HUCA Dataset** from PhysioNet.
* **Dataset Citation:** *[salin teks link dari website Brugada-HUCA PhysioNet and paste]*
* **Platform Citation:** Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

---

## Methodology
* **Preprocessing:** Noise removal via Band-pass filtering (0.5 - 45 Hz).
* **Model Architecture:** Convolutional Neural Networks (CNN) for spatial feature extraction in Lead V1 & V2.
* **Decision Making:** A Reinforcement Learning (RL) agent trained to optimize treatment outcomes based on patient risk profiles.

---

## Ethical AI & Interpretability
To ensure **safety validation** and **model interpretability**, we implement:
* **Saliency Maps:** Visualizing which parts of the ECG signal (e.g., ST-segment) influenced the AI's diagnosis.
* **Evidence-Based Results:** Ensuring every AI suggestion is backed by clinical markers.

---

## How to Run Code
1. open file `AURUM_ANALYTICS.ipynb`.
2. click button **"Open in Colab"**.
3. RUN ALL to download data set and see output.
  
