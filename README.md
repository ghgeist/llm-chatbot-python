# Neo4j-backed Chatbot using Python
![Example GIF](llm-chatbot-python\demo_videos\chatbot.gif)

This repository contains the code for a chatbot that uses Neo4j to answer questions about movies and actors. The chatbot is built using Python and the Streamlit library. The chatbot uses a Neo4j database that contains information about movies and actors, and it uses Cypher queries to retrieve information from the database. The chatbot can answer questions about movies, actors, and the relationships between them. The chatbot uses a simple natural language processing (NLP) model to understand user queries and generate responses. The chatbot is deployed as a web application using Streamlit, and it can be accessed through a web browser. The chatbot provides a conversational interface that allows users to ask questions about movies and actors and receive answers in real time. The chatbot is designed to be easy to use and understand, and it provides a fun and interactive way to explore the world of movies and actors.

This repository accompanies the [Build an Neo4j-backed Chatbot using Python](https://graphacademy.neo4j.com/courses/llm-chatbot-python/?ref=github) course on [Neo4j GraphAcademy](https://graphacademy.neo4j.com/?ref=github).

# Running the application

To run the application, you must install the libraries listed in `requirements.txt`.

[source,sh]
pip install -r requirements.txt

Then run the `streamlit run` command to start the app on link:http://localhost:8501/[http://localhost:8501/^].

[source,sh]
streamlit run bot.py

The sandbox credentials for the Neo4j database will be automatically generated when you register for the course. You can find the credentials in the course materials.