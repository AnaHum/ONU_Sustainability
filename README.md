# UN_Sustainability
UN Sustainability of Countries Development

In this project, I conducted an analysis of UN sustainability reports spanning the years 2002 to 2021, focusing on multiple countries. The dataset contains a variety of sustainability measurement indices, including total greenhouse gas emissions (GHG) per year, annual growth rate percentage, and FDI inflows, among others. The primary objective of this project was to assess the sustainability levels within these countries and to evaluate the model's accuracy in predicting a country's level of development.

The project commenced with an initial data exploration and preparation phase. This phase involved selecting relevant features (variables), addressing missing data, and splitting the dataset for subsequent model training and evaluation. Following this, I trained the model and compared the actual data to the model's predictions to uncover any disparities. In the final stages, I conducted a comprehensive evaluation and validation of the model, all the while providing interpretations and insights derived from the outcomes of the analysis.

The machine learning model I built, is a Random Forest Classifier, and the model helps us analyse sustainability in countries in several ways and the methods I deployed in this analysis are :

- The model has classified countries into different classes or categories based on their level of development or sustainability. These classes stand for the different degrees of sustainability, such as "Developed Economies," "Developing Economies," "Economies in Transition," "Least Developed," and "Not Specified."

- We generated a classification report, the model has provided us with metrics like precision and recall for each class. These metrics helped us to understand how well the model's predictions align with the actual categories.

- The overall accuracy of the model (92%) indicates the percentage of correct predictions across all classes. It showed that model performed well in terms of correctly classifying countries into their respective sustainability levels.

- The confusion matrix and its associated heatmap provided us with a visual representation of how the model's predictions match the true values.

- Cross-validation scores (around 90%) indicated that the model's performance is consistent across multiple subsets of the data. 

- Grid search for hyperparameters has helpeded us to identify the best combination of hyperparameters for my Random Forest Classifier.

In summary, this machine learning model has helped us to analyze sustainability in countries by providing a systematic way to classify countries based on their sustainability levels. It offers quantitative metrics for evaluating the model's performance and understanding where it excels or needs improvement.
