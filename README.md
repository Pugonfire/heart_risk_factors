# heart_risk_factors

### About

This is a mini project for CZ1115 (Intro to Data Science and Artificial Intelligence). We will be using a heart disease dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease) to find the important factors used to predict the presence of heart disease in an individual

---

### Problem Definition
* Heart disease is one of the leading causes of death
* Early detection and targeted treatment is key to alleviating the adverse impact of heart disease on people, physically and financially
* By identifying important factors used to predict the presence of heart disease using data and analytics, these factors can then be passed on to researchers for further analysis with the proper domain knowledge

***Note: Correlation does not imply causation. We cannot conclude that the important variables found from our anlysis of data causes heart disease without applying medical domain knowledge*** 

---

### Models Used

1. CART
2. Random Forest

---

### Conclusion
Comparing both models, we concluded that the Random Forest model performed better, achieving a higher accuracy and lower rates of error. Therefore, we will look at the variable importance under the Random Forest model.
<br/>
The top indicators are as follows:
1. **Thalassemia:** An inherited blood disorder that causes an individual's blood to have less haemoglobin than normal
2. **No. of major vessels (0-3) coloured by fluoroscopy** 
3. **Maximum heart rate achieved**
<br/>
Using our findings as a starting point, medical researchers can refocus their studies into the identified risk factors to determine their exact relationship to heart disease, and the outcomes of the research will prove beneficial to numerous parties.
For medical practitioners, the research findings can help them to better designed treatment plans which would improve the quality of patient care and recovery.
For the pharmaceutical industry, drug-use and development can be tailored to focus on the key risk factors, addressing the disease more effectively.
For the members of the public, advisories and health tips can be shared to encourage healthy living and promote the mantra of “prevention over cure”.

---

### New Learning Points

* CART Pruning the optimal tree using cp
* Random Forest
* Getting variable importance

---

### Contributors

[@Jiajunn](https://github.com/Jiajunn)
[@Pugonfire](https://github.com/Pugonfire)
[@NgTzeSheng](https://github.com/NgTzeSheng)

---

### References
<https://archive.ics.uci.edu/ml/datasets/heart+disease> <br/>
<https://www.analyticsvidhya.com/blog/2020/10/cost-complexity-pruning-decision-trees/>
