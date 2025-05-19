# The Future of Creativity: Harnessing Eye-Tracking Technology to Optimize Human-AI Ideation Interfaces

## Overview
This project investigates the interplay between human fixation movement and AI-generated stimuli in creative ideation. By using eye-tracking technology, we measure how different types of stimuli (text, image, or both) influence user pupil behavior and creative output. The goal is to optimize interfaces for Human-AI co-creation by understanding how attention metrics relate to enhanced creativity.

## Research Hypotheses

- **Hypothesis 1**: Ideators exposed to visual stimuli will exhibit a lesser number of fixations than those exposed to verbal stimuli.  
  - *Tested using*: Independent samples t-test

- **Hypothesis 2**: In a dual-stimulus scenario, ideators will tend to ignore either the verbal or the visual stimuli.  
  - *Tested using*: Independent samples t-test comparing fixation patterns across modalities

- **Hypothesis 3**: Verbal stimuli will enhance the novelty of ideators’ refined ideas compared to visual stimuli.  
  - *Tested using*: Ordinary Least Squares (OLS) regression

## Methodology

Participants were randomly assigned to one of the following conditions:
- **Text-based stimuli**
- **Image-based stimuli**
- **Dual-stimuli** (text and image)

All stimuli were generated using a large language model. Participants’ eye movements were tracked during the ideation task, and their creative outputs were scored before and after exposure to the stimulus. The difference in scores represents the **creativity enhancement**.

### Data Collection
Eye-tracking data captured the following metrics:
- **Dwell Time After First Fixation**
- **Fixation Count**
- **Dwell Time per Fixation**
- **Average Duration per Fixation**

These metrics serve as **independent variables**, while the **dependent variable** is:
- **Creativity Score Enhancement** (i.e., improvement in novelty score post-stimulus)

## File Structure

pilot1/ # Eye-tracking and creativity scores
h1_and_h2.Rmd # T-tests for Hypotheses 1 and 2
h3.Rmd # OLS regression for Hypothesis 3
README.md # Project description (this file)


## Statistical Methods

- **T-tests**: Used to compare fixation metrics between different stimulus types (Hypotheses 1 & 2)
- **OLS Regression**: Used to predict creativity enhancement based on attention metrics and stimulus condition (Hypothesis 3)

## License

This work is licensed for **non-commercial use only**. Please credit the authors if using this material for academic or research purposes.
