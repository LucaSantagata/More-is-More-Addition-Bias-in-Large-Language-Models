# More is More: Addition Bias in Large Language Models

This repository contains the data used in the paper "More is More: Addition Bias in Large Language Models" by [Luca Santagata](https://www.linkedin.com/in/luca-santagata-b06501147/) and [Cristiano De Nobili](https://denocris.com/).

## Overview

This dataset supports our investigation into the presence of additive bias in Large Language Models (LLMs). We conducted a series of controlled experiments to test various LLMs, including GPT-3.5 Turbo, Claude 3.5 Sonnet, MathΣtral, and Llama 3.1, on tasks designed to measure their propensity for additive versus subtractive modifications.

## Data Description

The repository includes raw data from the following experiments:

1. Palindrome sequence task
2. Lego towers task
3. Elementary operation task
4. Anomalous sandwich task
5. Increasing ingredients in soup task
6. Summarization task

Each dataset is stored in CSV format and includes the responses from different LLMs for each task.

## File Structure

- `/palindrome_data/`: CSV files containing responses for the palindrome task
- `/lego_towers_data/`: CSV files containing responses for the Lego towers task
- `/elementary_operation_data/`: CSV files containing responses for the elementary operation task
- `/anomalous_sandwich_data/`: CSV files containing responses for the anomalous sandwich task
- `/soup_ingredients_data/`: CSV files containing responses for the increasing ingredients in soup task
- `/summarization_data/`: CSV files containing responses for the summarization task

## Usage

Researchers interested in replicating our results or conducting further analysis can use these datasets. Each CSV file is labeled with the corresponding LLM and task.

## Citation

If you use our findings or methodology in your research, please cite our paper:

## Contact

For any questions, please contact:

- Luca Santagata: luca.santagata@studenti.unitn.it
- Cristiano De Nobili: cdenobi@sissa.it
