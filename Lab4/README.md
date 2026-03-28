The AI Job Market Trends dataset was explored and prepared using several data preprocessing techniques. It contains job-related records with features such as salary, years of experience, and job openings.

The dataset was first examined to check for data quality issues, including missing values, duplicate rows, and data types. Since no missing values were found, artificial missing values were introduced and handled using median imputation to demonstrate the preprocessing process.

Outliers were then identified in the salary feature using the IQR method and removed to reduce the effect of extreme values. After that, numerical features were normalized using both Min-Max scaling and Z-score standardization.

The relationships between numerical features were also analyzed using a correlation matrix. As the correlation was weak, PCA was not applied.

Overall, these steps helped in cleaning the dataset and preparing it for further analysis.
