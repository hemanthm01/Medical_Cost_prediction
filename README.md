# Medical_Cost_prediction

In the health insurance industry, insurance companies often face challenges in determining accurate premiums for each policyholder. Errors in assessing health risks can result in significant financial losses. Therefore, accurate health insurance premium determination is crucial to maintain financial stability for insurance companies and provide fair services to policyholders.

In this project, we will use a dataset containing information about health insurance policyholders, including age, gender, Body Mass Index (BMI), number of children, smoking habits, residential region, and individual medical charges billed by insurance. This dataset serves as a valuable data source to develop predictive models that can assist health insurance companies in assessing risks and determining more accurate insurance premiums.

<img src = 'https://akm-img-a-in.tosshub.com/indiatoday/images/story/202204/insurance-7065113_1920_1200x768.png?VersionId=3A0sGCxdR8o36_z8Do9HLrHXBHUtYAJY&size=690:388'>

The aim of this analysis is to predict the medical expense based on the patients'information. The dataset used for this analysis is Insurance dataset from [Kaggle](https://www.kaggle.com/mirichoi0218/insurance). The dataset contains 1338 observations and 7 variables. The variables are as follows:

--------------------------------------------------------------
## Dataset Information

| Variable | Description |
| --- | --- |
| age | age of primary beneficiary |
|bmi | body mass index |
|children | number of children covered by health insurance |
|smoker | smoking |
|region | the beneficiary's residential area in the US |
|charges | individual medical costs billed by health insurance |

---------------------------------------------------------------------------
## Conclusion

From the models applied in the notebook, we can see that Linear Regressor and Random Forest Regressor are giving the best results. But, Random Forest Regressor is giving the best results with the least RMSE value. Therefore, I will use Random Forest Regressor to predict the medical expense of patients.

Moreover, the medical expense of smokers is higher than that of non-smokers. The medical expense of patients with BMI greater than 30 is higher than that of patients with BMI less than 30. The medical expense of older patients is higher than that of younger patients.

Thus, from the overall analysis, we can conclude that the <b> medical expense of patients depends on their age, BMI, smoking habits</b>.
