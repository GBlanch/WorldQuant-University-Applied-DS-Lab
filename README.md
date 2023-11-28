# Syllabus summary of the courses

N.b.: Due to the Copyright Licenses and Policies of WQU, no piece of IDE content/code ran or deployed in any courses is permitted to be published.

&nbsp;
&nbsp;       

![image](https://github.com/GBlanch/WorldQuant-University-Applied-DS-Lab/assets/136500426/59eec928-32be-4594-a1bf-5a5311568237)

&nbsp;
&nbsp;       

1. Housing in Mexico:
   
   + Imported multiple CSV files into a pandas DataFrame using for loops
   + Created insightful visualizations like histograms, scatter plots, and bar charts
   + Examined the relationship between variables by assessing **Pearson correlation** coefficients

2. Apartment sales in Buenos Aires
   
   +	Cleaned and munged raw data by creating a custom wrangle function
   +	Built ML pipelines by means of *Ridge, OneHotEncoder, SimpleImputer, LinearRegression* and *make_pipeline* built-in *sklearn* functions
   +	Applied **L2 Regularization** in order to prevent **overfitting or underfitting** in **Linear Regression** models
   +	Created an **interactive dashboard** utilizing *ipywidgets* library to module predictions based on different input features

3. Air quality forecast in Nairobi 
	+ Connected to a MongoDB server using *pymongo* library to localize and fetch the required data.
	+ Applied rolling average, autocorrelation and lag operations to Times Series data variables
	+ Utilized **Train Test Split** procedures to create proper train and test datasets for a **Linear Regression** model
	+ Built, explored and interpreted **Partial/Auto Correlation Functions** plots
	+ Using statsmodels modules, constructed **Auto Regressive** and **ARMA** models and validated them via **Walk Forward** optimization.
	+ Tuned the number of **lagged observations** and **moving avg. window size** via *GridSearchCV*
	+ Detected an optimal balance between Model Performance and Computational Costs

4. Earthquake damage prediction in Nepal
	+ Connected to a SQL database and wrangled data using *magic commands* and *sqlite3* library
   + Executed randomized **Train Test Split** to create proper training, testing and validation datasets
	+ Elaborated ML pipelines utilizing *OrdinalEncoder, DecisionTreeClassifier, LogisticRegression* and *make_pipeline* built-in *sklearn* functions
	+ Besides computing and evaluating training and validation accuracy scores:
	   	+ For **DT models**, tuned the **Tree’s depth** and assessed its predictions by assessing the **Gini importance** of its features
	   	+ For **LR models**, evaluated **Odds ratios** to explain its predictions
	+ Reviewed the ethics of environmental and social impact that ML models may lead to because of data biases

5. Bankruptcy in Poland:
	+ Applied **Undersampling** and **Oversampling** to adjust the **class distribution** of the dataset
	+ Computed **confusion matrices** to summarize how DT models performed and find areas of improvement
	+ Construct ML pipelines by means of *SimpleImputer, RandomForestClassifier, GradientBoostingClassifier* and *make_pipeline* built-in *sklearn* functions
	+ Performed **k-fold Cross-Validation** to evaluate **model performance**
	+ Utilized *GridSearchCV* to compute different **hyperparameters** and found their optimal ranges for the selected ones
	+ Built **interactive confusion matrices** to asses how the model's probability threshold affects **accuracy, precision and recall scores**

6. Customer segmentation in the US:
	+ Performed preliminary EDA on a dataset from Survey of Consumer Finances (SCF) compound by **28k observations** and **350 features** after subsetting it
	+ Build and fit **k-means models** to create **multi-feature clustering** after computing and standardizing their feature matrix
	+ Assessed the optimal clustering selection by evaluating **variance, inertia and silhouette scores**
	+ Reduced the dimension of feature matrices by means of **PCA transformation**
	+ Developed and deployed a **Dash web app architected in 3 layers** (Business, Service and Presentation) where **interactive** scatter plots and barcharts were modified via sliders

7. A/B Testing at WorldQuant University
	+ Fetched synthetic data from a Mongo DB and performed data wrangling using *pymongo* queries
	+ Designed, built and developed **OOP class definitions** containing the database attributes and ETL methods based on the experimental hypothesis
	+ Performed **cross-tabulation** to the wrangled dataset in order to create a contingency table and obtain odds ratios
	+ Designed and conducted a chi square test using *statsmodels* module and analyzed its results
	+ Built and launched an **interactive and 3-tier decoupled web application** to deploy and display barcharts and choropleth maps. The layer distribution and their OOP classes and functions were the compound by the following objects:
	  + Database: customized *MongoRepository* class
	  + Business : *GraphBuilder* and *StatsBuilder* classes from *statsmodels* module
 	  + Design/Layout: Demographic, Experiments and Result sections with dropdowns and sliders

8. Volatility forecasting in India
	+ Applied **Defensive programming** when designing a function to access APIs through an URL and Requests
	+ By means of **Test Driven Development** practices, built the following OOP classes:
	 	+ *AlphaVantageAPI* class, to fetch programmatically data from an API 
		+ *SQLRepository* class, to load and extract data into and from a SQLite database 
	+ Built a wrangling function to create a training Series for the **GARCH** model
	+ Built and fit the **GARCH** model and evaluate its detailed summary and performace 
	+ Created a *GarchModel* class compound by methods for data wrangling, model training, prediction generation and model load/saving
	+ Built a **web API** and launch the server by means of *FastAPI* and *uvicorn*, respectively
	+ Built data classes in order to forestall client-server communication errors
	+ Created API paths for model fitting and predictions serving 
