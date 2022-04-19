# NLP
## Topic Modeling on customer contacts

**Project description:** From the contacts transcripts, identify recurring and event-driven causes of customer contact to take action quickly that will improve the customer experience and reduce the cost associated with unwanted contact volume. In order to achieve this objective, provide a dashboard to allow easy exploration of causes, events and topics to facilitate understanding of reasons and trends regarding customer contacts.

### 1. Data
ETL pipeline to refresh customer contacts daily.
Contacts transcripts associated with dates and customer details.

### 2. Model
UMAP on TF-IDF transcripts and customer/transcripts features.
Clustering UMAP 2D projection using HDBSCAN.
Extracting rules from each cluster to determine a name by topic.
Calculating coocurrence matrix to plot a graph of relation between words.
Prepare multiple aggregations of data / time series to feed the dashboard.

### 3. Web Interface (Dashboard)
Deploy an interactive Streamlit application to epxlore the calcualted data with filters.