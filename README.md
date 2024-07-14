## BikeGenie: Tailored Two-Wheeler Buying Guide with AI

### Table of Contents
1. Problem Outline
2. Problem Statement
3. Application Overview
4. Solution Architecture
5. Implementation Details
6. Key Features
7. Benefits
8. Future Enhancements

### 1. Problem Outline

Choosing the right two-wheeler can be a daunting task for many consumers due to the vast number of options available in the market. Factors such as engine capacity (cc), price range, brand, and specific user requirements add to the complexity of making an informed decision. 

### 2. Problem Statement

Consumers often face challenges in:
- Selecting a two-wheeler that fits their specific needs and preferences.
- Finding reliable and tailored suggestions based on budget, engine capacity, and other criteria.
- Navigating through the extensive information available to make a well-informed purchase decision.

### 3. Application Overview

The generative AI 2-wheelers suggestion application is designed to address these challenges by providing personalized and accurate recommendations. It leverages advanced AI models to understand user queries and offer detailed guidance and suggestions for purchasing two-wheelers.

### 4. Solution Architecture

#### Components:
1. **LLM Router**: Routes user queries to the appropriate prompt based on the nature of the question.
2. **LangChain**: Facilitates the integration and chaining of large language models.
3. **Llama 3 Model**: Powers the natural language understanding and generation capabilities.

#### Workflow:
1. **User Input**: The user inputs a query regarding two-wheelers.
2. **Query Routing**: The LLM router analyzes the query and routes it to the appropriate prompt:
   - **Prompt 1**: For questions on how to select a bike.
   - **Prompt 2**: For suggestions on buying a bike under a certain cc or price.
3. **Response Generation**: The Llama 3 model processes the prompt and generates a detailed response.
4. **User Output**: The user receives tailored advice or suggestions based on their query.

### 5. Implementation Details

#### Technologies Used:
- **Python**: Core programming language for developing the application.
- **LangChain**: To manage and chain the language models effectively.
- **Llama 3 Model**: For advanced language processing and response generation.

### 6. Key Features

- **Intelligent Query Routing**: Differentiates between general bike selection queries and specific suggestion requests.
- **Personalized Recommendations**: Tailors responses based on user input, offering relevant and practical advice.
- **Comprehensive Guidance**: Covers various aspects of bike selection and purchasing, including engine capacity, budget, and more.

### 7. Benefits

- **Enhanced Decision-Making**: Helps users make informed decisions by providing accurate and detailed recommendations.
- **Time-Saving**: Reduces the time spent on researching and comparing different two-wheelers.
- **User-Friendly**: Simplifies the process of finding the right bike, making it accessible to users with varying levels of expertise.

### 8. Future Enhancements

- **Integration with Online Marketplaces**: Enable direct links to purchase or compare suggested bikes.
- **Expanded Criteria**: Include additional factors such as brand reputation, maintenance costs, and user reviews.
- **Multi-Language Support**: Extend the application to support queries in multiple languages for a broader user base.

## Acknowledgements

 - [Langchain](https://www.langchain.com/)
 - [Ollama](https://ollama.com/)
 - [Llama-3](https://ollama.com/library/llama3)


## Authors

- [@Github](https://www.github.com/KaRtHiK-56)
- [@LinkedIn](https://www.linkedin.com/in/l-karthik/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

![MIT License](https://img.shields.io/badge/License-MIT-green.svg)


## Demo

https://github.com/KaRtHiK-56/2-wheeler_guide

<img src="https://github.com/KaRtHiK-56/2-wheeler_guide/blob/main/guide.png">


## Documentation

 - [Langchain](https://www.langchain.com/)
 - [Ollama](https://ollama.com/)
 - [Llama-3](https://ollama.com/library/llama3)

## Technology used

### Backend
- **LangChain:** For chaining together various AI models and processing workflows.
- **Llama 3 Model:** A state-of-the-art language model used for generating human-like text.
- **Python:** The primary programming language for implementing the application logic.

### Frontend
- **Streamlit:** An open-source app framework used for creating the web interface.

## Installation


### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/KaRtHiK-56/Resume_Analyser
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage Guide

1. **Launching the Application:**
   - Open a terminal and navigate to the project directory.
   - Run `streamlit run app.py`.
   - Open the provided URL in a web browser.
