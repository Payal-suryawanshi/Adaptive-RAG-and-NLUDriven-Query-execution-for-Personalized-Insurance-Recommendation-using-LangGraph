InsureSense: Personalized Insurance Recommendation System
Project Overview
InsureSense is an innovative project designed to simplify the process of selecting insurance policies by using Natural Language Understanding (NLU) and LangGraph to provide personalized recommendations. The system dynamically adapts to user inputs, offering real-time insurance advice and computations, such as premium calculations, using a Python-based agent.

Key Features
Real-Time Personalization: Adapts to user queries in real-time using LangGraph and NLU-driven SQL queries to pull data from structured and unstructured sources.
Dynamic Insurance Calculations: With a Python REPL agent, the system computes dynamic insurance-related queries, like instant premium calculations.
Scalable Architecture: Built to easily adapt to other financial products such as loans, investments, and savings plans.
User-Friendly Interface: Initially developed using Streamlit, but later transitioned to a Flask-based UI for better scalability and user experience.
Project Motivation
The Indian insurance market is largely underpenetrated, and many customers face decision fatigue due to the complexity of policy options. InsureSense addresses this challenge by offering a recommendation engine that simplifies insurance policy selection, enhances user engagement, and improves customer satisfaction.

How It Works
User Input: The user inputs queries about insurance policies or coverage options.
Processing: The system processes these queries using a combination of NLU and LangGraph, referencing both structured (database) and unstructured (documents) data sources.
Recommendation: A tailored insurance recommendation is generated in real-time, providing instant feedback to the user, such as policy details or premium estimates.
Advanced Queries: For more complex queries, such as calculating premiums, the system uses a Python REPL agent to provide accurate, real-time computations.

Technologies Used
LangGraph: For executing NLU-driven SQL queries and enabling dynamic responses.
Python REPL Agent: To compute insurance-related queries like premium calculations.
Flask: Front-end framework for the user interface.
NLU (Natural Language Understanding): For understanding and processing user inputs.
Vector Database: To store and retrieve policy information based on user preferences.
Cloud Platforms: Integration with GCP for data management and workflow orchestration.

Challenges Faced
Limited LangGraph Documentation: The implementation of LangGraph was initially hindered by insufficient documentation, which required additional effort in troubleshooting and experimenting with the library.
Node Management: Managing agent nodes for task assignments presented challenges, but these were overcome by optimizing task allocation strategies.
UI Integration: Initially, we faced difficulties integrating with Streamlit. We resolved these issues by switching to Flask, which offered more flexibility and ease of use for our front-end requirements.

Future Prospects
Expansion to Other Products: Adapt the recommendation system for loans, savings plans, and other financial products.
Regulatory Compliance: Incorporate real-time regulatory checks to ensure compliance with insurance regulations.
Enhanced User Interaction: Further develop the system to handle more complex user inputs and approvals.
Scalability: Plan to expand the system globally, allowing for larger and more complex graph-based insurance recommendation systems.
