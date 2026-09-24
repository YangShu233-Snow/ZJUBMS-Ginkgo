---
title: 医学大数据与应用 2024-2025 学年夏学期期末回忆卷
author: 李建树
description:
---

## mcqs

> 单项选择题（40 分，共 20 题，每题 2 分）

- What is the primary goal of personalized medicine?
  - Reduce costs
  - [x] Provide individual medical care
  - Increase efficiency
  - Standardize treatment

---

- What is the primary function of CDSS?
  - [x] Support doctors in clinical decision-making and treatment
  - Automate diagnosis
  - Replace doctors
  - Manage hospital finances

---

- What is the best initial purpose of "A Learning Health System"?
  - [x] A system that can continuously learn from data updates
  - A system for one-time analysis
  - An electronic medical record storage system
  - An educational system for medical professional training

---

- Which of the following is the most commonly used standard in data interchange?
  - XML
  - [x] HL7
  - TCP/IP
  - HTTP

---

- Which of the following represents the five elements of individual clinical datum in order?
  - [x] Patient-Parameter-Value-Units-Time
  - Patient-Parameter-Value-Units-Method
  - Patient-Parameter-Value Method-Time
  - Patient-Parameter-Value-Time-Method

---

- Which of the following are characteristics of medical big data?
  - [x] High variety
  - Low velocity
  - Low speed
  - Low volume

---

- If a missed diagnosis is fatal, which type of error should healthcare professionals aim to minimize?
  - Type I error
  - Statistical error
  - FP
  - [x] FN

---

- Decreasing the cutoff level (moving it to the left) would decrease ____ tests but also would increase ____ tests. Thus, the test would have become more ____ but less ____.
  - [x] FP, FN, sensitivity, specific
  - FN, FP, sensitivity, specific
  - FP, FN, specific, sensitivity
  - FN, FP, specific, sensitivity

---

- What is meant by data normalization?
  - Encrypted data
  - Clean outliers
  - [x] Scale data to a standard range
  - Remove missing values

---

- Which of the following is **NOT** a system for classification and coding of diseases?
  - ICD-9-CM
  - ICD-10
  - [x] ICD-12
  - ICD-9

---

- Which function is used to calculate the number of elements in a vector in `R`?
  - `size()`
  - [x] `length()`
  - `count()`
  - `nrow()`

---

- How to generate the sequence 1, 2, 3, 4, 5, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5?
  - `seq(1:5, 3)`
  - `rep(1:5, rep(3:3))`
  - [x] `rep(1:5, 3)`
  - `seq(1:5, seq(3:3))`

---

- What are the properties of a `list` in `R`?
  - Supports only a single data type, ordered
  - [x] Contains multiple element types, ordered

---

- How to name the components of a `list`?
  - `list()`
  - [x] `name()`
  - `colnames()`
  - `rownames()`

---

- How to access the secondary name in a `list`?
  - `list[2, ]`
  - [x] `list[[2]]`

---

- Which of the following is the function to combine matrices or lists by column?
  - `rbind()`
  - `merge()`
  - [x] `cbind()`
  - `append()`

---

- Which data format uses a delimiter "," to separate fields in each record, and ensures that every record follows the same field sequence?
  - `.txt`
  - `.xlsx`
  - `.json`
  - [x] `.csv`

---

- What does the `R` expression `mean(c(10, 20, 30))` return?
  - `10`
  - [x] `20`
  - `15`
  - `30`

---

- Which of the following is **NOT** a loop structure in `R`?
  - `for`
  - `while`
  - [x] `do-loop`
  - `repeat`

---

- What function is used to draw a scatter plot?
  - `barplot()`
  - `hist()`
  - `summary()`
  - [x] `plot()`

## flashcards

> 简答题（共 11 题：第 1—7 题每题 6 分，第 8—9 题每题 4 分，第 10—11 题每题 5 分）

- Please describe the role of computer systems in biomedical data storage, retrieval, and interpretation.
  - Computer systems enable efficient storage of large-scale biomedical data (e.g., EHRs, omics), provide fast retrieval via query languages and indexing, and support interpretation through data analysis, visualization, and decision support tools, facilitating clinical research and personalized care.

---

- Please describe the goal of "A learning Health Care System".
  - The goal is to continuously generate and apply evidence from routine clinical data to improve patient outcomes, accelerate discovery, and optimize care delivery, creating a feedback loop where data informs practice and practice generates new data.

---

- Compare the advantages and disadvantages of "The Hypothetico-Deductive Approach" and "The traditional empirical approach" in clinical diagnosis.
  - Hypothetico-deductive: advantages – systematic, hypothesis-driven, reduces bias, adaptable to new evidence; disadvantages – time-consuming, requires expertise, may miss rare conditions. Traditional empirical: advantages – based on experience, quick for common patterns; disadvantages – subjective, prone to cognitive biases, less generalizable.

---

- How do standardized terminology and data exchange formats support interoperability of healthcare.
  - Standardized terminology (e.g., SNOMED CT, LOINC) ensures consistent meaning of clinical concepts, while exchange formats (e.g., HL7, FHIR) enable structured transmission of data across systems. Together they allow different systems to communicate, share, and interpret patient information accurately, improving coordination and quality of care.

---

- Please explain the following:
        1. Sensitivity vs Specificity
        2. A gold standard test
        3. Area Under the Curve (AUC)
  - (1) Sensitivity: proportion of true positives correctly identified (TP/(TP+FN)); Specificity: proportion of true negatives correctly identified (TN/(TN+FP)). (2) Gold standard test: the best available reference standard for diagnosing a condition, against which new tests are evaluated. (3) AUC: the area under the ROC curve, measuring overall diagnostic accuracy; 0.5 = no discrimination, 1.0 = perfect.

---

- Please list three biases in the assessment of test performance and propose mitigation strategies.
  - (1) Verification bias (work-up bias): mitigate by applying reference standard to all patients regardless of test results. 2. Spectrum bias: mitigate by including diverse patient populations (mild to severe disease, different comorbidities). 3. Incorporation bias: mitigate by ensuring reference standard does not include the test being evaluated.

---

- Compare the objectives of "T1" and "T2" translational research and their challenges.
  - T1: translation from basic science to clinical application (bench to bedside); challenges: preclinical models not always predictive, safety/efficacy issues. T2: translation from clinical research to practice (bedside to community); challenges: implementation barriers, workflow integration, cost-effectiveness.

---

- What is the significance of biomarkers in personalized medicine?
  - Biomarkers help predict disease risk, diagnosis, prognosis, and treatment response, enabling tailored therapies for individual patients, reducing adverse effects, and improving outcomes by selecting the right drug at the right dose for the right patient.

---

- Please give one example of artificial intelligence assist in evidence-based medical decision-making.
  - AI-powered clinical decision support systems can analyze large electronic health record datasets to suggest personalized treatment recommendations (e.g., antibiotic selection based on local resistance patterns) or predict patient deterioration (e.g., sepsis alerts) using machine learning models trained on historical data.

---

- Please explain the significance of expectation-value decision models in uncertain clinical situations.
  - These models quantify the expected utility of each decision option by multiplying the probability of each outcome by its value (e.g., quality-adjusted life years). They help clinicians choose the option with the highest expected benefit under uncertainty, balancing risks and benefits in a rational, transparent way.

---

- Please describe the definition of Translational Bioinformatics.
  - Translational bioinformatics is the development of storage, analytic, and interpretive methods to optimize the transformation of increasingly voluminous biomedical data into proactive, predictive, preventive, and participatory health outcomes, bridging genomics and clinical informatics to accelerate research and improve patient care.