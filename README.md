# Car Price Prediction

## Content

This project has a dataset that contains the **car prices** for a Chinese automobile company Geely Auto.
Hence, using this dataset, I will predict the ***car price value*** for a particular car given the features of the car

Cars provide a level of convenience that is often unmatched by other transportation modes. However, while they provide this comfort, car ownership is expensive and this poses a challenge to buyers. A new car is financially unaffordable for 78.4% of the American population, as only 21.6% of Americans earned $100,000 annually in 2022, according to numbers from the US Census Bureau. The high cost of car ownership combined with the financial constraints faced by a significant portion of the population, underscores the importance of a car price prediction system. (Ochoa, 2023)

The need for a good prediction system is portrayed even further when one of many persisting issues found in the car sales market is that the sellers want the highest price possible; but, buyers and used car dealers bid the lowest price due to economic stability uncertainty. By helping buyers identify affordable car options within their budget constraints, a car price prediction system expands access to transportation and mobility. This is particularly important for individuals living in areas with limited public transportation options or unreliable infrastructure. By increasing transparency in the car market, a price prediction system fosters fair competition among sellers and dealerships. When buyers can access pricing information, they can compare prices across different sellers and negotiate better deals. This promotes a more competitive and equitable marketplace. Accurate car price prediction involves expert knowledge, because price usually depends on many distinctive features and factors. (Ochoa, 2023)

The primary objective of this project is to create a machine-learning model that can estimate used car prices with accuracy based on a variety of variables and qualities. Our goal is to enable potential automobile purchasers to make educated decisions by giving them useful information about the anticipated costs of various car models through the use of sophisticated predictive analytics. Our project not only aims to improve consumer decision-making but also market transparency in the automotive sector. By providing buyers with unbiased car price estimates generated by strong machine-learning algorithms, we hope to promote fair competition between dealerships and sellers. This transparency helps create a more fair and effective market for all consumers by allowing them to bargain for better prices and avoid overpaying for cars. Furthermore, by giving people and families with limited financial resources access to reasonably priced transportation options that satisfy their needs and financial constraints, our project hopes to promote financial inclusion. We aim to increase accessibility to transportation and enhance mobility for everyone by democratizing access to pricing information and equipping buyers with the know-how and self-assurance to successfully navigate the car-buying process.

## Conclusions and Discussions

### 4.1 Interpretation of Results and Findings

The implementation of the car price prediction model involved several steps, starting from data preprocessing to model building and evaluation. Through exploratory data analysis (EDA), we gained insights into the dataset's characteristics, identified important features, and visualized relationships between variables. Key findings from the EDA include the strong influence of categorical variables such as car model and trim on car prices, as well as correlations between certain numerical features.

The baseline model, constructed using linear regression with selected numerical features, provided a starting point for comparison. Subsequent models, including decision trees and XGBoost, aimed to improve prediction accuracy by capturing non-linear relationships and leveraging ensemble learning techniques.

The XGBoost model emerged as the most effective, achieving a root mean square error (RMSE) score of 0.246. This indicates that the model's predictions were, on average, within approximately 0.246 units of the true car prices. The XGBoost model outperformed other models, including linear regression and decision trees, suggesting its superior ability to capture complex patterns in the data and make accurate predictions.

### 4.2 Insights into the Accuracy and Reliability of the Car Price Prediction Model

The accuracy and reliability of the car price prediction model are evident from the RMSE scores obtained during model evaluation. Lower RMSE scores indicate better model performance, as they represent smaller discrepancies between predicted and actual car prices. The XGBoost model's low RMSE score of 0.246 demonstrates its effectiveness in accurately predicting car prices based on the dataset's features.

Furthermore, the inclusion of both numerical and categorical features in the model contributed to its accuracy. By capturing diverse aspects of car attributes, such as make, model, and trim, the model could better account for the factors influencing car prices.

### 4.3 Limitations and Challenges Encountered During the Project

Despite the successful implementation of the car price prediction model, several limitations and challenges were encountered. One major limitation was the inability to exhaustively explore all possible hyperparameters for the XGBoost model due to time and computational constraints. This limitation may have prevented us from identifying an even more optimal set of hyperparameters that could further improve model performance.

Additionally, the presence of null values in the dataset posed a challenge during data preprocessing. Although strategies such as filling null values with appropriate placeholders were employed, the potential impact of missing data on model accuracy cannot be completely eliminated.

### 4.4 Potential Applications and Future Research Directions

The car price prediction model developed in this project has several potential applications in the automotive industry and related sectors. It can be used by car dealerships, online marketplaces, and insurance companies to estimate car prices accurately, inform pricing strategies, and assess vehicle values.

Future research directions could involve enhancing the model's robustness and scalability by incorporating additional data sources, such as historical sales data, market trends, and economic indicators. Furthermore, exploring advanced machine learning techniques, such as deep learning and ensemble methods, may lead to further improvements in prediction accuracy and reliability. Additionally, conducting comparative studies with other predictive modelling approaches could provide valuable insights into the relative performance and effectiveness of different algorithms for car price prediction tasks.
