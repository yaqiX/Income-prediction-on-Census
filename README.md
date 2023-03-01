# Income-prediction-on-Census

This report is based on the [Adult (Census Income)](https://archive.ics.uci.edu/ml/datasets/Adult "Adult (Census Income)") dataset, which was extracted by Ronny Kohavi and Barry Becker from the 1994 Census bureau database. The dataset contains the demographic features of each adult sample, including their *age, work class, occupation, marital status, education level,* etc.

The main objective of this report is to predict the annual income of individuals based on their demographic features. The purpose is to explore **what factors affect a person’s income level** and build reliable models to classify individuals into two categories: those who earn less than 50,000 per year and those who earn more than 50,000 per year.

There are 15 variables. For dimensionality, we applied the** L1- regularized logistic regression, the PCA (Principal Component Analysis), SVD (Singular Value Decomposition)and Random Forest.** To improve prediction, we further applied **decision tree** and **Artificial Neural Networks** on our selected variables.

## Conclusion

## Reference
- James, G., Witten, D., Hastie, T., and Tibshirani, R. (2013) An Introduction to Statistical Learning with applications in R, https://www.statlearning.com, Springer-Verlag, New Y ork
- Géron, A. (2022). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems (3rd ed.). O’Reilly Media.
- Ho, Tin Kam (1995). Random Decision Forests (PDF). Proceedings of the 3rd International Conference on Document Analysis and Recognition, Montreal, QC, 14–16 August 1995. pp. 278–282.
- Kim, S. M., Kim, Y., Jeong, K., Jeong, H., & Kim, J. (2018). Logistic LASSO regression for the diagnosis of breast cancer using clinical demographic data and the BI-RADS lexicon for ultrasonography. Ultrasonography (Seoul, Korea), 37(1), 36–42. https://doi.org/10.14366/usg.16045
- Tsiatis, A. A. (2006). Semiparametric Theory and Missing Data. Springer New York EBooks. https://doi.org/10.1007/0-387-37345-4
- Muchlinski, D., Siroky, D. S., He, J., & Kocher, M. A. (2016). Comparing Random Forest with Logistic Regression for Predicting Class-Imbalanced Civil War Onset Data. Political Analysis, 24(1), 87–103. https://doi.org/10.1093/pan/mpv024
- Kohavi, R., & Becker, B. (1996). Adult Data Set. Retrieved from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/adult
