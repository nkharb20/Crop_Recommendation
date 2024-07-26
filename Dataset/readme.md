# Dataset Description

This dataset is used for the crop recommendation application. It consists of several features that are essential for determining the suitability of a crop for a particular set of environmental conditions. Each row in the dataset represents a unique set of conditions and the corresponding recommended crop.

## Features

1. **N**: Nitrogen content in the soil (in kg/ha).
2. **P**: Phosphorus content in the soil (in kg/ha).
3. **K**: Potassium content in the soil (in kg/ha).
4. **temperature**: Temperature in degrees Celsius.
5. **humidity**: Humidity percentage.
6. **ph**: pH value of the soil.
7. **rainfall**: Rainfall in mm.
8. **label**: The recommended crop based on the given conditions.

## Sample Data

| N  | P  | K  | temperature | humidity | ph    | rainfall   | label |
|----|----|----|-------------|----------|-------|------------|-------|
| 90 | 42 | 43 | 20.88       | 82.00    | 6.50  | 202.94     | rice  |

## Feature Details

1. **N (Nitrogen)**: Nitrogen is a crucial nutrient for plant growth. It is a part of chlorophyll, which is essential for photosynthesis. This feature measures the nitrogen content in the soil.

2. **P (Phosphorus)**: Phosphorus is important for energy transfer and photosynthesis in plants. It also contributes to the development of roots and flowers.

3. **K (Potassium)**: Potassium helps in the regulation of various physiological processes in plants, including water uptake, enzyme activation, and photosynthesis.

4. **Temperature**: This feature represents the ambient temperature. Different crops have optimal temperature ranges for growth.

5. **Humidity**: Humidity is the amount of water vapor present in the air. It affects the transpiration rate of plants and overall growth.

6. **pH**: The pH value indicates the acidity or alkalinity of the soil. Different crops thrive in different pH ranges.

7. **Rainfall**: This feature represents the amount of rainfall. Adequate rainfall is essential for crop growth, but too much or too little can adversely affect the crops.

8. **Label**: The label is the recommended crop for the given set of conditions. It is the target variable in the dataset.

## Usage

This dataset can be used to train machine learning models for crop recommendation. By analyzing the relationship between the features and the target variable (label), the model can predict the most suitable crop for any given set of environmental conditions.


## Heatmap showing less correlation between different parameters
![image](https://github.com/user-attachments/assets/3bdb0ca9-0a2c-4f85-add0-82459ae6ed62)
