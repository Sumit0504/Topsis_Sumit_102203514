# TOPSIS


Submitted By: **Sumit Garg**

***

# TOPSIS: Technique for Order of Preference by Similarity to Ideal Solution

TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) is a multi-criteria decision-making method developed in the 1980s. It identifies the best alternative by minimizing the Euclidean distance from the ideal solution and maximizing the distance from the negative-ideal solution.

---

## Key Features

### **Robust TOPSIS Algorithm**
This package provides an efficient and reliable implementation of the TOPSIS algorithm. It considers both positive and negative ideal solutions to calculate the relative closeness of alternatives to the ideal solution.

### **User-Friendly Interface**
Designed for ease of use, the package allows users to input decision matrices effortlessly. Its simple API abstracts the complexity of the TOPSIS method, making it accessible for all users.

### **Flexible Weight Customization**
Users can assign weights to each criterion, reflecting their relative importance in the decision-making process. This ensures flexibility and adaptability across different scenarios.

### **Sensitivity Analysis**
The package includes tools for conducting sensitivity analysis, enabling users to understand how changes in criteria weights influence the final decision. This feature allows for deeper insights and informed decision-making.

### **Clear and Intuitive Results**
Results are presented with ranked alternatives based on their closeness to the ideal solution. The package also generates detailed reports and visualizations to aid in interpreting the decision-making process.

### **Seamless Python Integration**
Fully compatible with Python 3.x, the package integrates seamlessly into data science and analytics workflows. It can be used in Jupyter notebooks, scripts, or incorporated into larger applications.

---
## How to Use
Run the Package
You can run the TOPSIS package directly from the command line using:

python -m Topsis_Sumit_Garg_102203514 <input_file> <weights> <impacts> <output_file>
Parameters
<input_file>: Path to the CSV file containing the decision matrix.
<weights>: Comma-separated weights for each criterion (e.g., 1, 1, 2, 3, 1).
<impacts>: Comma-separated impacts for each criterion (e.g., +,-,+,-,- where + indicates a benefit criterion and - indicates a cost criterion).
<output_file>: Path to the output CSV file where the results will be saved.
## How to install this package:
```
>> pip install Topsis-Sumit-Garg-102203514==0.1.1
```


### In Command Prompt
```
>> python3 <package_name> data.csv "1,1,2,1,1" "+,+,-,+,-" "result.csv"
```
![alt text](run.png)