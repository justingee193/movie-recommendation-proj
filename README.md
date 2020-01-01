# movie-recommendation-proj
## Comparing the Effectiveness of Different Imputation Methods
Movie rating imputation and prediction using Gaussian-Mixture Models with Expectation Maximization algorithm and Mean Imputation

After cleaning and separating training and test sets, we used both imputation methods to fill in missing rating values. Most genres in the data set have fewer observations than others, so we wanted to narrow down to genres with the most observations. That being Action, Comedy, and Drama.

#### Comparing GMM and Mean Imputation predictions

![method_error_pred_values](https://user-images.githubusercontent.com/56926170/71645469-0992d600-2ca7-11ea-801f-bf48df81c8e8.png)![method_error_values](https://user-images.githubusercontent.com/56926170/71645471-0bf53000-2ca7-11ea-8ec4-c97254c69dfc.png)

![method_error_scatter](https://user-images.githubusercontent.com/56926170/71645470-0ac40300-2ca7-11ea-9383-93d569500494.png)![method_error](https://user-images.githubusercontent.com/56926170/71645468-07c91280-2ca7-11ea-9075-751c009efb0c.png)

#### Descriptive Statistics of variables before and after imputation

![stats](https://user-images.githubusercontent.com/56926170/71645967-e4ee2c80-2cad-11ea-9601-299ffd31e7c8.PNG)

The cross-validation score GMM imputation and mean imputation is 0.6626 and 0.6718, respectively. While the mean absolute error for predictions with mean imputation was 0.8161 and 0.7876 with GMM imputation. 
