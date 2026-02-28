# Kaggle Seizure Prediction – Research Log

This repository documents my research process in reproducing and extending the American Epilepsy Society Seizure Prediction Challenge.

The goal is not only to achieve competitive performance, but to deeply understand the formulation of seizure prediction problems using intracranial EEG (iEEG) signals.

---

## 🎯 Objectives

- Reproduce baseline performance on the Kaggle seizure prediction dataset
- Analyze preictal vs interictal signal characteristics
- Investigate subject-specific vs generalized modeling approaches
- Understand data leakage and validation pitfalls in time-series EEG data
- Build a foundation for real-time seizure prediction systems

---

## 📊 Dataset

- Source: American Epilepsy Society Seizure Prediction Challenge (Kaggle)
- Data type: Intracranial EEG (iEEG)
- Subjects: Dogs (initial phase)
- Segment length: 10-minute clips
- Classes: Preictal vs Interictal

---

## 🧠 Research Philosophy

This project focuses on:

- Careful problem definition
- Strict validation design
- Transparent experiment logging
- Understanding model behavior beyond accuracy metrics

The long-term direction includes extending experiments to human datasets and eventually exploring real-time seizure prediction systems.

---

## 🚀 Current Stage

- Data exploration (Dog_1, Dog_2)
- Signal structure analysis
- Baseline model setup (PyTorch)

---

## 📌 Notes

This repository is structured for iterative experimentation.  
Major experiments and findings will be documented clearly in commits and experiment logs.
