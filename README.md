# Chatbot-for-querying-SQL-database


Requirements: -
SQLAlchemy==1.4.30
llama_index 
openai==0.12.7
tiktoken  

Explanation:
SQLAlchemy: Required for interacting with the SQLite database using SQLAlchemy's ORM capabilities.
llama_index: Assuming this is a custom library or an internal project dependency related to your SQLDatabase and NLSQLTableQueryEngine implementations.
openai: Required for interacting with the OpenAI API, particularly for using the GPT-3.5 model.
tiktoken: Assuming this is related to tokenization or encoding for the GPT-3.5 model, as inferred from your usage.


Note: - I used a classified dataset(.csv file) that my organisation does not allow to share on the internet, you can change the path of the .csv file and provide any SQL database. Also, make changes to the 3rd code cell accordingly to mention the relevant columns(in the dictionary "table_details = "). 

For querying, go to the 24th code cell and type your question in "query_str". Print the response after that to get the answer from the Chatbot
