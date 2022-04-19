# NLP
## Topic Modeling on customer contacts
![](/images/nlp_topic.png)

**Project description:** From the contacts transcripts, identify recurring and event-driven causes of customer contact to take action quickly that will improve the customer experience and reduce the cost associated with unwanted contact volume. In order to achieve this objective, provide a dashboard to allow easy exploration of causes, events and topics to facilitate understanding of reasons and trends regarding customer contacts.

### 1. Data
* Batch ETL pipeline to refresh customer contacts daily.
* Contacts transcripts associated with date and customer details.

### 2. Model
* UMAP on TF-IDF transcripts and customer/transcripts features.
* Clustering UMAP 2D projection using HDBSCAN.
* Extracting rules from each cluster to determine a name by topic.
* Calculating coocurrence matrix to plot a graph of relation between words.
* Anomaly detection on time series to spot rapidly disrupting events.
* Prepare multiple aggregations of data / time series to feed the dashboard.

### 3. Web Interface (Dashboard)
* Deploy an interactive Streamlit application to explore topics, time series, COOC graph and other calcualted data using custom filters.

[Back](https://cotedave.github.io/)

