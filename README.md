# Core Image Driven ML

Some experiments I did when I worked in PRORES AS - not part of any project. Algorithms were developed with Politecnico di Milano during Master's there. 

In PRORES AS, I developed an Image-driven Machine Learning for prediction of petrophysical properties from core photographs. The result was very satisfactory. Then, I extend this work for prediction in Thin Section and CT scans only for my curiosity. Data used are public from Kansas Geological Survey (KGS) and Volve field. 

![image](https://github.com/user-attachments/assets/cebbd0c0-42f4-4d32-84df-ac826721467b)

Figure: Image-driven ML for core photos

Adapting the same method, Thin sections were extracted from reports where they can have different magnifications. Then, different features were extracted, such as the Gray-Level Co-Occurrence Matrix (GLCM) and statistical values of RGB (average, min, and max). A pipeline setup that consists of Random Forest model and Recursive Feature Elimination (RFE) to automatically search important features. Stratified K-Fold Cross-Validation (SKCV) was based on porosity and permeability range. 

