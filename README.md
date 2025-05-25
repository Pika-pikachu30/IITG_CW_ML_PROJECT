# TASK 1
## Approach
1. Using pandas loading data , Data cleaning and preprocessing
2. Model Training for Logistic Regression, Random Forest and Decision Trees
3. Visualization of results with matplotlib and seaborn.

## Structure of the Notebook
Data Loading: Import and inspect the dataset.
Data visualisation Used to tell what features 1,2,3 are.
Preprocessing: Handle missing values and impuate accordingly.
Modeling: Train regression models and evaluate accuracy.
Model Interpretation with SHAP(NOt done due to error)

# TASK 2
A project designed to use LangGraph for creating a chatbot agent.

## Features
Specialized agents for math, weather, research, and more Memory: Persistent chat history using LangGraph’s MemorySaver Tool integration: Supports calculations, weather queries, and web search Dynamic routing: Supervisor agent intelligently delegates tasks to the right agent Extensible: Add new tools or agents with minimal code changes

## Structure of the Notebook
Experimentation
 1. Defined chatbot_node (LLM) & calculator_node (tool).
 2. Assembled graph, attempted visualisation with Mermaid.
 3. Planned a weather agent and supervisor chain.

Set your API keys as environment variables:
GOOGLE_API_KEY for Gemini , OPENWEATHERMAP_API_KEY for weather queries
