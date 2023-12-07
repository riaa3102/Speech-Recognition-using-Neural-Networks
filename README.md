# Speech Recognition with Neural Networks

## Project Overview

This project explores the classification of English numbers within audio recordings using a Multilayer Perceptron (MLP) model. The focus is on investigating and comparing three distinct speech signal representations: Time-domain Signal, Short-Time Fourier Transform (STFT), and Mel Frequency Cepstral Coefficients (MFCC). The goal is to analyze their effectiveness in optimizing the model's performance for speech recognition tasks.

## Project Structure

1. **Environment Setup:**
   - Import the necessary packages.

2. **Data Preparation:**
   - Retrieve required data from the dataset.

3. **Data Preprocessing:**
   - Examine dataset distribution plots.
   - Implement preprocessing steps, including removing silence periods, applying zero-padding, and normalization.

4. **Building Model:**
   - Develop and train a Multilayer Perceptron (MLP) model.
   - Emphasize three distinct speech signal representations:
      - 4.1. Time-domain Signal
      - 4.2. Short-Time Fourier Transform (STFT)
      - 4.3. Mel Frequency Cepstral Coefficients (MFCC)

5. **Conclusion:**
   - Summarize findings and insights gained from the comparison.

## Results

|                        | F1 Score  | Accuracy |
|----------------------- |:--------: |:--------:|
| Time-domain signal     |   0.628   |   0.63   |
| STFT                   |   0.951   |   0.951  |
| MFCC                   |   0.978   |   0.978  |

## Conclusion

The project concludes with a comparative analysis of the performance of the Multilayer Perceptron model across different input types. The findings highlight the significance of selecting appropriate signal representations for speech recognition tasks, with Mel Frequency Cepstral Coefficients (MFCC) proving to be particularly effective.

## Installation

Install the necessary Python packages by running the following command in your terminal:

```
pip install -r requirements.txt
```

## Usage

To run the Jupyter Notebook, execute the following command in your terminal:

```
jupyter lab
```

These commands will set up the required packages and launch Jupyter Lab for you to explore the project.