# AIXHW4
# Model Interpretability Analysis Using ResNet34 and CIFAR-10

This notebook explores model interpretability techniques including Partial Dependence Plots (PDP), Individual Conditional Expectation (ICE) plots, and Accumulated Local Effects (ALE) plots to understand how a pre-trained ResNet34 model processes CIFAR-10 images.

## Requirements
- PyTorch
- torchvision
- numpy
- matplotlib
- alibi
- pandas
- scikit-learn

## Setup
1. The notebook uses a pre-trained ResNet34 model
2. CIFAR-10 test dataset is used for analysis
3. Images are preprocessed to match ResNet34 input requirements

## Analysis Performed
- Feature correlation analysis of pixel values
- PDP analysis of color channel effects
- ICE plot analysis of individual image behaviors
- ALE plot analysis accounting for feature interactions

## Key Files
- `AIXHW4.ipynb`: Main notebook containing all analysis

## Usage
1. Install required dependencies
2. Run notebook cells sequentially
3. Each section contains clear explanations of the analysis being performed

## Notes
- Analysis focuses on pixel position (0,0) across RGB channels
- All visualizations include detailed interpretations
- Findings show varying impacts of different color channels on model predictions

