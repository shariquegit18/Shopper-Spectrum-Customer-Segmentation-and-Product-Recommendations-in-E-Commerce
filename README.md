PROJECT TITLE:
Shopper Spectrum – Customer Segmentation & Product Recommendation System

--------------------------------------------------
PROJECT OVERVIEW
--------------------------------------------------
Shopper Spectrum is an end-to-end data analytics and machine learning project
focused on understanding customer behavior and recommending relevant products
in an e-commerce retail setting.

The project uses transactional retail data to:
1. Segment customers using the RFM (Recency, Frequency, Monetary) model.
2. Apply clustering algorithms to identify meaningful customer groups.
3. Build a product recommendation system using similarity-based techniques.
4. Deploy the solution using a Streamlit web application for real-world usage.

--------------------------------------------------
DATASET
--------------------------------------------------
Source: Online Retail Dataset  
Type: Transactional E-commerce Data  

Key Columns:
- CustomerID
- InvoiceNo
- InvoiceDate
- Quantity
- UnitPrice
- Description

A cleaned version of the dataset is used for analysis and modeling.

--------------------------------------------------
PROJECT MODULES
--------------------------------------------------

1. Exploratory Data Analysis (EDA)
- Transaction analysis by country
- Top-selling products
- Purchase trends over time
- Monetary distribution
- RFM metric distributions

2. Customer Segmentation
- RFM table creation
- Feature scaling
- KMeans clustering
- Hierarchical clustering
- Model comparison using Silhouette Score
- Business interpretation of customer segments

3. Product Recommendation System
- Customer–Product matrix
- Cosine similarity computation
- Top-N product recommendations
- Cross-selling insights

4. Streamlit Web Application
- Customer Segmentation interface using RFM inputs
- Product Recommendation interface using product selection
- Business-friendly outputs for non-technical users

--------------------------------------------------
MACHINE LEARNING MODELS USED
--------------------------------------------------
- KMeans Clustering (Customer Segmentation)
- Hierarchical Clustering (Model comparison)
- Cosine Similarity (Product Recommendation)

--------------------------------------------------
MODEL SELECTION JUSTIFICATION
--------------------------------------------------
KMeans was chosen due to:
- Clear cluster separation
- High silhouette score
- Scalability for large datasets
- Easy interpretability for business use

Hierarchical clustering was used for comparison and validation.

--------------------------------------------------
BUSINESS IMPACT
--------------------------------------------------
- Identifies high-value and loyal customers
- Enables targeted marketing strategies
- Improves customer retention
- Supports cross-selling and upselling
- Enhances decision-making using data-driven insights

--------------------------------------------------
HOW TO RUN THE PROJECT
--------------------------------------------------

Jupyter Notebook (Core Evaluation):
- Open shopper_spectrum.ipynb
- Run all cells sequentially
- All analysis and models are reproducible

Streamlit Web Application (Optional Demo):
1. Install dependencies:
   pip install -r requirements.txt

2. Run the app:
 python3 -m streamlit run app.py

--------------------------------------------------
NOTE FOR EVALUATORS
--------------------------------------------------
The complete data analysis, clustering models, and recommendation logic
are implemented and reproducible in the Jupyter Notebook.

The Streamlit application is provided as a deployment demonstration
and is intended to be executed locally.

--------------------------------------------------
AUTHOR
--------------------------------------------------
Sharique Khan
B.Tech Computer Science
