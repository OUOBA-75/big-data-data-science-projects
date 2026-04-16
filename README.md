\#  Data Science \& Big Data Projects Portfolio (R)



\## 👤 Author

\*\*DJANDJOA OUOBA\*\*



\---



\##  Overview



This repository gathers a set of advanced \*\*Data Science, Big Data, NLP, and Machine Learning projects developed in R\*\*.



It demonstrates practical expertise across the full data lifecycle:



\- Data ingestion (large-scale datasets)

\- Big Data processing (data.table \& Spark)

\- Machine Learning modeling (Random Forest)

\- Natural Language Processing (text mining, STM, sentiment analysis)

\- Data visualization \& storytelling

\- Interactive dashboards (Shiny)



These projects are designed to reflect \*\*real-world analytical workflows used in data science, research, and industry environments\*\*.



\---



\#  1. Big Data Analysis \& Machine Learning Project (Transactions Dataset)



\##  Dataset

`transactions.csv` – large-scale transactional dataset containing:

\- Customer transactions

\- Purchase amounts

\- Countries

\- Product categories

\- Payment methods

\- Dates



\---



\##  Objectives



\- Compare performance of data loading methods

\- Perform large-scale aggregation

\- Use distributed computing with Spark

\- Build predictive model for purchase behavior

\- Visualize business insights



\---



\##  Technologies Used



\- `data.table` (high-performance data manipulation)

\- `sparklyr` (distributed computing with Apache Spark)

\- `ranger` (fast Random Forest implementation)

\- `caret` (data splitting \& modeling)

\- `ggplot2` (visualization)

\- `tictoc` (performance benchmarking)



\---



\##  Key Steps



\### 1. Data Loading \& Performance Benchmarking

\- Comparison between `fread()` and `read.csv()`

\- Evaluation of execution time for large datasets



\### 2. Data Aggregation (data.table)

\- Transactions grouped by:

&#x20; - Country

&#x20; - Product category

\- Business KPIs computed:

&#x20; - Total revenue

&#x20; - Number of transactions

\- Identification of top customers



\### 3. Distributed Processing (Spark)

\- Spark session initialization

\- Distributed aggregation:

&#x20; - Monthly sales evolution

&#x20; - Payment method analysis

\- Export of processed results



\### 4. Machine Learning Model

\- Model: \*\*Random Forest (ranger)\*\*

\- Target variable: `purchase\_amount`



Steps:

\- Train/test split

\- Feature selection

\- Model training

\- Prediction



\###  Evaluation Metrics

\- RMSE (Root Mean Squared Error)

\- R² (Coefficient of determination)



\###  Feature Importance

\- Identification of key drivers of purchase behavior



\---



\##  Visualizations

\- Sales evolution over time

\- Revenue by country

\- Distribution of purchase amounts

\- Variable importance plot



\---



\#  2. NLP Project – African Academic Narratives (Constellate Corpus)



\##  Dataset

Large-scale academic corpus from JSTOR / Constellate platform



\---



\##  Objectives



\- Analyze academic discourse about Africa

\- Identify dominant research topics

\- Study sentiment evolution over time

\- Detect geographic and disciplinary biases

\- Compare endogenous vs exogenous narratives



\---



\##  Techniques Used



\- Text mining (`tidytext`)

\- Topic modeling (STM - Structural Topic Model)

\- Sentiment analysis (AFINN lexicon)

\- Word frequency analysis

\- Network analysis (`igraph`, `ggraph`)

\- Interactive visualization (`shiny`)



\---



\##  Data Processing Pipeline



\- JSONL ingestion

\- Text cleaning (lowercase, punctuation removal)

\- Tokenization

\- Lemmatization

\- Document-term matrix creation



\---



\##  Main Analyses



\### 1. Topic Modeling (STM)

\- Extraction of latent themes in academic literature

\- Analysis of topic evolution over time

\- Comparison of thematic distributions



\---



\### 2. Geographic Representation

\- Frequency of African countries mentioned

\- Identification of most studied regions



\---



\### 3. Author Representation Bias

\- Detection of African vs non-African author representation

\- Analysis across disciplines



\---



\### 4. Sentiment Analysis

\- Evolution of sentiment associated with:

&#x20; - Africa

&#x20; - Migration

&#x20; - Development

&#x20; - Democracy



Methods:

\- AFINN lexicon

\- Time-series analysis

\- Distribution analysis (violin, heatmaps)



\---



\### 5. Network Analysis

\- Document-discipline relationships

\- Author origin classification

\- Community detection (Louvain algorithm)

\- Centrality analysis



\---



\### 6. Interactive Dashboard

\- Built with \*\*Shiny\*\*

\- Dynamic filtering by:

&#x20; - keyword

&#x20; - time period

\- Real-time visualization of sentiment evolution



\---



\#  Key Insights (Summary)



\- Academic discourse on Africa is highly \*\*thematic and time-dependent\*\*

\- Strong evolution of topics from colonial-era narratives to development-focused research

\- Unequal representation of African authors across disciplines

\- Significant variation in sentiment depending on topic and period

\- Clear structure in academic collaboration networks



\---



\#  3. Skills Demonstrated



\## Data Science

\- Data cleaning \& preprocessing

\- Feature engineering

\- Statistical modeling

\- Predictive analytics



\## Big Data

\- Data.table optimization

\- Spark distributed computing

\- Large dataset processing



\## Machine Learning

\- Random Forest modeling

\- Model evaluation (RMSE, R²)

\- Feature importance analysis



\## NLP

\- Tokenization \& lemmatization

\- Topic modeling (STM)

\- Sentiment analysis

\- Text mining at scale



\## Visualization

\- ggplot2 advanced charts

\- time-series visualization

\- heatmaps \& violin plots

\- network graphs



\## Tools \& Ecosystem

\- R programming

\- Spark (sparklyr)

\- GitHub-ready workflows

\- Shiny dashboards



\---



\#  Conclusion



These projects demonstrate a \*\*complete end-to-end data science workflow\*\*, combining:



\- Big Data processing

\- Machine learning

\- Natural language processing

\- Statistical analysis

\- Interactive visualization



They reflect the ability to handle \*\*real-world datasets, extract insights, and communicate results effectively\*\*, which are essential skills for Data Scientist and Data Engineer roles.



\---



\#   Auteur



\- Name: OUOBA DJANDJOA

\- Field: Data Science / Big Data / AI

