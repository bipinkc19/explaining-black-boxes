# Explaining black boxes

## Using SHAP (SHapely Additive exPlanation)

### Random Forest

- Overall weight <br>
![Overall](./images/shap.png) <br>
## Shap values of all the records representing which variable play what kind of role in predicting the output. Eg: Sex when High (Male) playe a negative role in survival but female have very high chances of survival spread across other factors too
![Overall](./images/shap_overall.png) <br>
![Overall](./images/shap_bar.png) <br>
![Overall](./images/shap_s.png) <br>
![Overall](./images/shap_s1.png) <br>

- Per prediction <br>
![Overall](./images/shap_single.png)

## Using eli5 (Explain like I'm 5)

### Logistic Regression

- Overall weight <br>
![Overall](./images/logistic_overall.png) <br>
- Per prediction <br>
![Overall](./images/logistic_single.png)


### Random Forest

- Overall weight <br>
![Overall](./images/forest_overall.png) <br>
- Per prediction <br>
![Overall](./images/random_custom.png)

## Lime

- Per prediction as it is local <br>
![Overall](./images/lime.png)
