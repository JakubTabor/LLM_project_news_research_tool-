# In this project I intend to create a research tool, that can be used by equity research analysts to conduct their research
* I plan to use technologies such as Langchain, OpenAI API and Streamlit 

# First i gonna build data base ingestion system 
* Go to news article website
* Write webscrapper in python
* Then run it on cron job, which will pull the data and convert it into embedding vectors
* Next it go into vector database

# And next will be Chat Bot
* We build chat bot similar to ChatGPT
* Type a question
* Question get converted into embedding
* And from vector database it pull relevant chunk which matches with the question
* Base on this chunks form the prompt, and put back the answer to chat bot
