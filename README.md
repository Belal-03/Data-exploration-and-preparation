# 📊 Data Exploration, Preparation, and Association Rule Mining

This project involves in-depth data analysis, preprocessing, and association rule mining on structured datasets. It aims to uncover patterns, clean and transform data, and derive meaningful insights using various statistical and machine learning techniques.

---

## 🧪 A. Data Exploration

### A1. Attribute Type Identification
Each of the 10 attributes is analyzed to determine its data type:
- **Nominal**: Categories without inherent order (e.g., Gender)
- **Ordinal**: Categories with a ranked order
- **Interval**: Numerical values without a true zero (rare)
- **Ratio**: Numerical values with a true zero point (e.g., Age, Income)

### A2. Statistical Summarization
For each attribute:
- **Central tendency**: Mean, Median, Mode
- **Spread**: Range, Variance, Standard Deviation, Percentiles
- **Distribution**: Histograms and Boxplots to visualize distributions
- **Frequency**: Count and distribution of nominal attributes

### A3. Pattern Identification using Weka
Using Weka, the dataset is visualized and analyzed for:
- **Outliers**
- **Clusters of similar instances**
- **Interesting attribute combinations**
- **Scatter plots and attribute correlation snapshots**

> All insights are captured and documented with visual outputs.

---

## 🧹 B. Data Preprocessing

Preprocessing operations applied on the dataset for standardization and preparation include:

### B1. Binning of “Age” Attribute
- **Equi-width Binning**: Divides the range into 3 equal-width intervals.
- **Equi-depth Binning**: Ensures each bin has an equal number of records.

### B2. Normalization Techniques for “Age”
- **Min-Max Normalization**: Rescales values to the [0.0, 1.0] range.
- **Z-Score Normalization**: Standardizes values based on mean and standard deviation.

### B3. Discretization of “Age” into Categories
Categories are defined as:
- Teenager: 1–16
- Young: 17–35
- Mid_Age: 36–55
- Mature: 56–70
- Old: 71+

> Frequencies for each category are computed and visualized.

### B4. Binary Encoding of Gender
The "Gender" attribute is converted to binary:
- **Male** → 1
- **Female** → 0

> Results are documented in clearly labeled Excel sheets and tables.

---

## 🔍 C. Association Rule Mining on Community Participation Data

### Dataset Description
A dataset of 2,000 participants with 12 attributes representing survey responses regarding various community organization involvements.

### Key Features:
- Elapsed time in survey
- Duration of community residency
- Demographics (Age, Gender, Employment)
- Membership in community groups (Family, Hobbies, Political, Religious, etc.)

### Objectives:
1. **Pattern Discovery**:
   - Use association rule learning to uncover frequent itemsets and discover rules.
   - Identify strong associations such as co-occurrence between community group memberships.

2. **Evaluation of Rules**:
   - Analyze rules based on:
     - **Support**
     - **Confidence**
     - **Lift**
   - Highlight the most interesting and statistically significant rules.

3. **Insights**:
   - Identify correlations (e.g., individuals in hobby groups are also likely to be in social clubs).
   - Discuss potential implications or applications of the findings.

---

## 📁 Deliverables

- **Structured Report**:
  - Comprehensive documentation of all three major parts: data exploration, preprocessing, and association rule mining.
  - Tables, visuals, and interpretations are included for clarity.

- **Excel Workbook**:
  - Multiple spreadsheets named by task (e.g., "A", "B1", "B2", etc.)
  - Clearly labeled columns representing intermediate and final results.
