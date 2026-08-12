LangChain + Gemini Movie Recommendation

A small project I built while learning LangChain and Generative AI.

The project uses Google Gemini with LangChain to generate a movie recommendation based on a language and genre, and then generate a short summary of the selected movie.

What it does

The workflow is simple:

Language + Genre
       ↓
Movie Recommendation
       ↓
Movie Summary
       ↓
Final Response

For example:

Language: English
Genre: Horror

The application asks Gemini to suggest a movie and then generates a short summary.

Tech Stack
Python
LangChain
Google Gemini
Jupyter Notebook
python-dotenv
LangChain Concepts Used

This project helped me understand some of the core LangChain concepts:

ChatGoogleGenerativeAI
PromptTemplate
ChatPromptTemplate
RunnableLambda
RunnableSequence
RunnableParallel
StrOutputParser

The main idea is to connect different steps together instead of handling every LLM call separately.

Why I Built This

I'm learning LangChain by building small projects instead of only studying the concepts.

This project is one of my first steps toward building more advanced LLM, RAG, and Agentic AI applications.

Future Improvements
Add a simple UI
Add movie database integration
Add movie posters
Add RAG
Add conversation memory
Convert the workflow into an AI agent
Author

Nithish Kumar

Learning and building in Generative AI, LangChain, and AI/ML.
