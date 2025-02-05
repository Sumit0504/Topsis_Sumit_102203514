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

## How to install this package:
```
>> pip install Topsis-Sumit-Garg-102203514
```


### In Command Prompt
```
>> python3 <package_name> data.csv "1,1,2,1,1" "+,+,-,+,-" "result.csv"
```
![alt text](run.png)

## Example Usage
### **Command**
python -m Topsis_Sumit_Garg_102203514 "path/data.csv" "1, 1, 2, 3, 1" "+,-,+,-,-" " "result.csv"
output.csv
### **Output CSV (result.csv)**
Fund Name,P1,P2,P3,P4,P5,Topsis Score,Rank
M1,0.91,0.83,6.0,53.0,15.19,0.5291896486216583,7
M2,0.88,0.77,4.1,61.1,16.71,0.23405453078004776,6
M3,0.67,0.45,3.5,59.4,16.01,0.2950515410938471,4
M4,0.83,0.69,4.8,44.9,12.81,0.5757075943328146,1
M5,0.74,0.55,6.7,66.3,18.57,0.4554328900694114,5
M6,0.6,0.36,4.0,37.8,10.69,0.6096687433166923,3
M7,0.72,0.52,4.4,40.7,11.59,0.6135283003946568,8
M8,0.73,0.53,4.4,66.8,18.12,0.24793165958287922,2

## License
This project is licensed under the MIT License. See the LICENSE file for details.
