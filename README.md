# Student-Academic-Performance

This repository contains an end-to-end data exploration, cleaning, machine learning, and interactive analysis pipeline for student performance in secondary education (Mathematics and Portuguese). The project was completed as part of the Maincraft internship.

Project Overview
Student performance in secondary education is influenced by a complex interplay of demographic factors, study habits, social behaviors, and past academic records. This project analyzes educational datasets across Mathematics (student-mat.csv) and Portuguese (student-por.csv) to uncover key determinants of student success and build predictive early warning systems for educational institutions.

Key Features & Pipeline Steps
1. Data Exploration & Cleaning
Missing Value Checks: Verified zero missing values across both datasets using .isnull().

Duplicate Handling: Identified and removed duplicate entries using .drop_duplicates().

Dataset Shape & Types: Inspected data distributions and types across demographic, behavioral, and academic variables.

Conclusion
Prior period grades ($G1$ and $G2$) serve as the strongest predictors of final student success ($G3$). However, behavioral factors—specifically weekly study time, past failures, class attendance, and lifestyle habits—play a critical role in determining performance trajectories. Machine learning models demonstrate that even on Day 1, behavioral indicators can reliably classify at-risk students, enabling educators to move from reactive grading to proactive student support.
