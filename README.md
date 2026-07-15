# H13-LPBF-Materials-Dataset

This project began with curation of dataset from multiple research papers followed by data preprocessing, synthetic data point generation, training and evaluation

The primary objective is to investigate **process–structure–property relationships** in additive manufacturing and provide a standardized dataset for regression and predictive modeling.

---

## Project Objectives

- Develop a machine learning-ready dataset for LPBF H13 steel.
- Predict material properties from manufacturing process parameters.
- Enable benchmarking of machine learning algorithms for additive manufacturing applications.
- Support research in materials informatics and digital manufacturing.
- Provide an extensible dataset that can be updated with future experimental data.

---

## Dataset Description



| Feature | Unit | Description |
|---------|------|-------------|
| Laser Power | W | Laser power used during fabrication |
| Scan Speed | mm/s | Laser scanning speed |
| Hatch Spacing | mm | Distance between adjacent scan tracks |
| Layer Thickness | mm | Thickness of each deposited powder layer |
| Energy Density | J/mm³ | Volumetric energy density calculated using the LPBF energy density equation |

### Output Properties

| Property | Unit |
|----------|------|
| Density | % Theoretical |
| Porosity | % |
| Hardness | HRC |
| Ultimate Tensile Strength (UTS) | MPa |
| Yield Strength | MPa |


---

## Dataset Structure

```text
.
│
├── dataset/
│   └── augmented_dataset.csv
├── prediction_model.ipynb
└── README.md
```




---

## Applications
- Multi-property prediction
- Additive Manufacturing
- Laser Powder Bed Fusion (LPBF)
- Materials Informatics




---

## Future Work
This model solely involved benchmarking on linear regression. Further improvements may be observed by experimenation with different algorithms as is not limited to ideas such as:
- Building a larger dataset
- Benchmark multiple machine learning algorithms
- Publish trained baseline models

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Installation

```bash
git clone https://github.com/arjun1151/Prediction-of-Mechanical-Properties-of-H13-Tool-Steel.git
cd Prediction-of-Mechanical-Properties-of-H13-Tool-Steel
```


