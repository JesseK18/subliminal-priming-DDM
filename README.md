# Subliminal Priming Analysis with Drift Diffusion Model

This repository contains the resources and code for analyzing the effects of subliminal priming on decision-making using a Drift Diffusion Model (DDM). The project includes a Python notebook for statistical analysis and model construction/fitting, as well as the experimental data in TSV format.

## Repository Contents

- **`data.tsv`**: Contains the experimental data, including stimulus-prime-response (SPR) sequences and reaction times.
- **`analysis.ipynb`**: Jupyter Notebook with code for:
  - Data preprocessing
  - Statistical analysis (e.g., t-tests on reaction times)
  - Construction and fitting of the DDM to experimental data
  - Visualization of results

## Project Overview

### Experiment Description

Participants were tasked with categorizing photos as either a "cat" or "dog." Each trial began with a subliminal prime (either "WOOF" or "MEOW"), masked by white noise. The main objective was to examine whether subliminal primes influenced performance in terms of:

1. **Sensory Evidence Accumulation** (drift rate)
2. **Response Cautiousness** (decision threshold)
3. **Response Bias** (starting point)

### Data Collection

- **Participants**: 12
- **Trials per Participant**: 460
- **Total Trials**: 5520
- **Outcome Measures**: 
  - Decision accuracy
  - Reaction times (in seconds)

## Installation Instructions

### Dependencies

The project requires the following Python packages:
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
- `pyddm`

Install the required libraries via `pip`:

`bash`
pip install pandas numpy matplotlib scipy pyddm



## Methods

The analysis includes:

1. **Data Preprocessing**: 
   - Filtering and cleaning the dataset, including outlier removal and coding categorical variables.

2. **Statistical Analysis**: 
   - T-tests comparing reaction times for correct vs. incorrect responses and between SPR configurations.
   - Analysis of response biases (e.g., frequency of "cat" vs. "dog" responses).

3. **Model Construction**: 
   - Building a Drift Diffusion Model with parameter fitting to assess the influence of priming.

## Hypotheses

1. **Hypothesis 1**: Subliminal primes bias the starting point of evidence accumulation, reflecting a response tendency toward the primed category.
2. **Hypothesis 2**: Reaction times are unaffected by the semantic content of congruent primes and stimuli.

## Results

The analysis evaluates the influence of subliminal priming on decision-making parameters (drift rate, decision threshold, and starting point) and provides statistical and visual insights into the data.

## How to Cite

If you use this project, please cite the repository or contact the authors for further details.
