# HypoDataCare: Analysis of Hypotensive Events in Intensive Care

This repository contains the code and analysis for the **HypoDataCare** project, which focuses on the analysis of hypotension (low blood pressure) in intensive care unit (ICU) patients using clinical data. The primary goal is to leverage medical data analysis to improve patient care and optimize blood pressure management on ICUs.

-----

## Table of Contents

1.  [Problem Statement](https://www.google.com/search?q=%23problem-statement)
2.  [Project Aims](https://www.google.com/search?q=%23project-aims)
3.  [Methodology](https://www.google.com/search?q=%23methodology)
4.  [Data](https://www.google.com/search?q=%23data)
5.  Coming soon..

-----

## Problem Statement

Hypotension is a critical issue in intensive care, but its events remain difficult to anticipate and prevent in clinical practice. A reliable assessment of organ perfusion is crucial for patient outcomes, and the **Mean Arterial Pressure (MAP)** is commonly used as a surrogate parameter for this.

  * A **MAP below 65 mmHg** is considered a hypotensive event.
  * Such events are directly linked to severe adverse outcomes, including **acute kidney injury, increased morbidity, and mortality**.
  * Despite the availability of continuous monitoring data, preventing these episodes is a significant clinical challenge.

This project addresses this challenge by performing a deep analysis of routinely collected ICU data to uncover patterns and provide insights for better clinical management.

-----

## Project Aims

The main objectives of the HypoDataCare project are:

  * **Quantify Hypotension:** Analyze MAP data from different ICUs to quantify the incidence and severity of hypotensive events using established numeric indicators like Time-Weighted Average (TWA), duration, and episode frequency.
  * **Identify Critical Time Windows:** Determine if there are specific periods, such as day or night shifts, with an increased occurrence of hypotension.
  * **Perform Cluster Analysis:** Use unsupervised learning to detect typical hypotension trajectories and group patients with similar hemodynamic profiles.
  * **Investigate Clinical Associations:** Explore the relationship between identified hypotension patterns and clinical outcomes, such as the length of an ICU stay.
  * **Improve Care Quality:** Compare different ICU units regarding their hypotension metrics to support targeted optimization of blood pressure management strategies.

-----

## Methodology

The project follows a structured medical data analysis approach:

1.  **Cohort Definition:** The study cohort includes all patients from specific ICU units with available MAP data for a defined period.
2.  **Metric Calculation:** For each patient, individual hypotension events are calculated based on different MAP thresholds (depths of hypotension). Key metrics include AUT/Day (Area Under Threshold), Length Stay/Day, and TWA/Day.
3.  **Unsupervised Learning:** Cluster analysis is performed on the calculated metrics and patient trajectories to reveal hidden patterns and group patients into meaningful clusters based on their hemodynamic profiles.
4.  **Comparative Analysis:** The results are used to compare care quality between different units and identify areas for clinical improvement.

-----

## Data

The data for this project consists of routinely collected patient data from various clinical information systems within an Intensive Care Unit (ICU). The primary data source is the continuous **Mean Arterial Pressure (MAP)** monitoring data. The project uses a curated dataset extracted from the clinical data warehouse after receiving appropriate ethical and data usage approvals.



-----

## Contact

Laura Pauline Scherf, M.Sc. - [email@example.com](mailto:email@example.com)

Project Link: [https://github.com/your\_username/HypoDataCare](https://www.google.com/search?q=https://github.com/your_username/HypoDataCare)
