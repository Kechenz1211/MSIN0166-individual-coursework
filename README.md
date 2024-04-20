# MSIN0166-individual-coursework
This DE project primarily focused on collecting data from various sources, constructing an ETL pipeline, and achieving Retriever-Answer Generator by integrating Langchain. The approach to data collection demonstrates the flexibility in acquiring real-world data and the diversity in methods of data storage. The AWS service was utilized to establish an infrastructure that facilitates easy access to and manipulation of large datasets. In addition, an NLP model was used to demonstrate the machine learning pipeline; because it does not include predictive analytics using large volumes of data, this serves as a simplified example of applying machine learning in practice but still illustrates how a machine learning pipeline is constructed. Finally, this project developed a prompt chaining mechanism to input queries and output replies when integrating with LLM, demonstrating the success of the RAG in providing more accurate answers based on the input documents.

# Repository Contents
- `news_webscraping.ipynb` -Python script for scraping news from BBC website.
- `Data_APIs.ipynb` -Python script for scraping news from mediastack APIs.
- `merged_data_new_insert.ipynb` -Python script for using tinydb to insert new data into original merged dataset.
-  `merged_news.csv` -CSV file containing merged news data from APIs,web scraping and uploaded file.
-  `merged_news_new_insert.csv` -Final dataset, CSV file containing 'merged_news.csv' and new inserted data
-  `ML_pipeline` -Python script for creating machine learning pipeline.
-  `DE_LLM+RAG.ipynb` -Python script for intergrating LLM with final dataset.
