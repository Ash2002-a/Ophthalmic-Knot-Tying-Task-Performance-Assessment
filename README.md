# Ophthalmic Knot Tying Task Performance Assessment

This repository provides an analysis of ophthalmic knot tying performance using eye tracking data collected during a training course at the Royal College of Ophthalmologists. The goal is to evaluate various performance metrics derived from eye tracking data to discriminate between novice and expert ophthalmic surgeons.

## Project Overview

In this project, the performance of 20 volunteers (11 novices and 9 experts) is analyzed through a series of time parameters, error metrics, and fixation patterns observed during an ophthalmic knot-tying task. The data collected includes:

1. Time parameters (total task duration, needle passing subtask duration, and first knot tying subtask duration).
2. Annotated error sequences based on the ideal sequence of surgical gestures.
3. Heatmap images representing the spatial distribution of eye fixations during the knot-tying task.

## Objective

The primary objective is to assess which performance metrics are best at discriminating between novice and expert ophthalmic surgeons based on their eye tracking data. The analysis includes:
- Descriptive statistics (mean, median, variance, skewness, kurtosis) for time parameters.
- Statistical tests to evaluate the significance of differences between novice and expert groups for each metric.
- Error analysis based on deviations from the ideal sequence of surgical gestures.
- Spatial analysis of fixation patterns and their ability to discriminate between the two groups.

## Data

The dataset contains the following:
- **Time data**: Provided in CSV files (`time_experts.csv`, `time_novices.csv`).
- **Error data**: Provided in an Excel file (`error_data.xlsx`).
- **Heatmap images**: Greyscale bitmap images representing eye fixations during the task, provided as `.png` files.

### Data Sources
- **Time Data**: Available as CSV files with the task duration and subtask times for experts and novices.
- **Error Data**: Available as an Excel file with annotations on the participants' subtask sequences and error analysis.
- **Fixation Heatmaps**: Available as PNG images representing the gaze fixation heatmaps during the knot-tying task.

## Setup

### Requirements
- Python 3.x
- Required libraries:
  - `pandas`
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `seaborn`
  - `opencv`
  - `PIL`

### Installation
You can install the required libraries using `pip`:

```bash
pip install pandas numpy scipy matplotlib seaborn opencv-python pillow
