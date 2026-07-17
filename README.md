# Male Elephant Tusk Size Analysis (Pre-Poaching vs. Post-Recovery)

This repository contains a Jupyter Notebook that analyzes the impact of selective poaching on the physical characteristics (specifically tusk length and shoulder height) of male elephants. It compares historical data from the pre-poaching period (1966–1968) to the post-recovery period (2005–2013).

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Key Findings](#key-findings)
- [Visualization](#visualization)
- [Requirements](#requirements)
- [How to Run](#how-to-run)

---

## Project Overview
Selective poaching for ivory often targets elephants with larger tusks. This project analyzes a dataset of male elephants to determine if there has been a statistically noticeable decrease in average tusk sizes between the mid-20th century and the early 21st century[cite: 1].

## Dataset Description
The analysis uses a CSV file named `male-elephant-tusk-size.csv`[cite: 1]. The dataset contains 299 records with the following columns[cite: 1]:
* **`period`**: The time frame of the observation (e.g., `1966-68` or `2005-13`)[cite: 1].
* **`elephant_id`**: Unique identifier for each elephant[cite: 1].
* **`age`**: Age of the elephant (in years)[cite: 1].
* **`shoulder_height`**: Shoulder height of the elephant (in cm)[cite: 1].
* **`tusk_length`**: Length of the elephant's tusk (in cm)[cite: 1].

## Key Findings
By calculating the mean tusk length of male elephants in both periods, we observe a noticeable decrease in tusk sizes[cite: 1]:
* **Average Tusk Length (Pre-Poaching: 1966-68)**: **~67.44 cm**[cite: 1]
* **Average Tusk Length (Post-Recovery: 2005-13)**: **~57.97 cm**[cite: 1]

This reduction suggests that heavy poaching pressures may have selected against genes responsible for larger tusks[cite: 1].

## Visualization
The notebook generates a scatter plot using `matplotlib` to compare the relationship between **Shoulder Height** and **Tusk Length** across the two time periods[cite: 1]:
* **Triangles (▲)** represent elephants from the **Pre-Poaching (1966-68)** period[cite: 1].
* **Squares (■)** represent elephants from the **Post-Recovery (2005-13)** period[cite: 1].



