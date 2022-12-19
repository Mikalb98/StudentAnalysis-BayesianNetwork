# About this project
Within the repository we can find
- [the jupyter notebook containing the project](https://github.com/matteonestola/FAIKR3/blob/8fef56d578530d8a40ae613abd5746c0ddee9829/BayesianModel_Albarello_Nestola.ipynb);
- [the report summarising the key steps that led to its realisation](https://github.com/matteonestola/FAIKR3/blob/d26dea70c274b2558bd718b737d01ea76f93d7eb/REPORT_Albarello_Nestola.pdf).

## Structure of the jupyter notebook:

1. **Preprocessing of the data**:

    1.1 Dropping columns

    1.2 Discretizing age

    1.3 Discretizing G3

    1.4 Discretizing absences

    1.5 Discretizing results

2. **Data Exploration**:

    2.1 Pstatus &#8594; famrel

    2.2 Famrel &#8594; famsup

    2.3 Famrel &#8594; Dalc

    2.4 Medu/Fedu &#8594; famsup

    2.5 Famsup &#8594; paid

    2.6 Paid &#8594; G3

    2.7 Freetime &#8594; goout

    2.8 Freetime &#8594; activities

    2.9 Goout &#8594; studytime

    2.10 Activities &#8594; studytime

    2.11 Famsup &#8594; studytime

    2.12 Dalc &#8594; studytime

    2.13 Health &#8594; studytime

    2.14 Schoolsup &#8594; studytime

    2.15 Age &#8594; G3

    2.16 Sex &#8594; G3

    2.17 Absences &#8594; G3

    2.18 Famsup &#8594; G3

    2.19 Studytime &#8594; G3

3. **Bayesian Network Implementation and Analysis**:

    3.1 Dalc block

    3.2 Famsup block

    3.3 Freetime block

    3.4 Studytime block

    3.5 G3 block

    3.6 Resulting Network

    3.7 Analysis of the resulting network: flow of probabilistic influence

4. **Parameter Estimation**

5. **Inferences**:

    5.1 Exact inferences

    5.2 Approximate inferences

6. **Conclusions**
