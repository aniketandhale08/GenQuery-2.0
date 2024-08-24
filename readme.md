# GenQuery 2.0 : Simplify Your SQL Journey
Welcome to GenQuery! 🚀 This project aims to simplify data access and manipulation in SQL databases through natural language commands, educational examples, and powerful AI integration.
GIF link----------

# Features
## 1. Natural Language SQL Query Generation
Query Simplification: Generate SQL queries by simply typing your request in plain language.
Output Understanding: Receive explanations for each query, breaking down the syntax and logic used.
## 2. SQL Formatter
Code Organization: Format and clean up your SQL code for better readability and maintenance.
## 3. Query Explainer
Detailed Breakdown: Analyze complex SQL queries with explanations for each component, making them easier to understand.
## 4. Data Analysis & Visualization
Visual Insights: Generate charts and visualizations directly from your queries to better understand your data.
## 5. TiDB Serverless Integration
Scalable Database Management: Utilize TiDB Serverless, a fully-managed, MySQL-compatible database service with built-in Vector Search on AWS, to handle both traditional and AI workloads efficiently.
Advanced Features: Leverage TiDB's Vector Search capabilities to enhance retrieval-augmented generation (RAG) and other AI-driven functionalities.

## Built With
**1. Languages:** Python

**2. Frameworks:** Streamlit

**3. Cloud Services:** TiDB Serverless, Google Cloud Platform (GCP)

**4. Databases:** TiDB Serverless (MySQL-compatible, with Vector Search)

**5. APIs:** Gemini 1.5 Pro API

**6. Data Visualization:** Plotly Express

**7. AI & NLP:** Google’s Generative AI tools

## Project Architecture
The project is structured as follows:

1. Frontend: Built with Streamlit for a user-friendly interface.
2. Backend: Powered by Python and integrated with the Gemini 1.5 Pro API for AI capabilities.
3. Database: Managed by TiDB Serverless, ensuring scalability, high performance, and seamless integration with our AI features.

Setup Instructions
1. Clone the Repository
bash
Copy code
git clone https://github.com/aniketandhale08/GenQuery.git
cd GenQuery
2. Install Dependencies
bash
Copy code
pip install -r requirements.txt
3. Set Up TiDB Serverless
Sign Up: Register for a TiDB Cloud account.
Database Configuration: Set up your database instance in TiDB Serverless and import your data.
4. Run the Application
bash
Copy code
streamlit run app.py





## Testing Instructions
To test GenQuery:

**1. Access the Application:** Follow the setup instructions to run the application locally or access the hosted version by given links.
**2. Database Connection:** Ensure that the TiDB Serverless instance is connected.
**3. Run Queries:** Input natural language commands and observe the generated SQL queries and their explanations.
**4. Test Features:** Use the SQL Formatter and Query Explainer to test formatting and query explanation functionalities.

# Challenges and Learnings
**1. Integration:** Successfully integrated TiDB Serverless with the AI-powered GenQuery to manage data efficiently and scale effortlessly.
**2. User Experience:** Focused on making the tool beginner-friendly while maintaining powerful features for advanced users.

# Future Enhancements
**1. User Feedback Integration:** Gather user feedback to further improve the tool.
**2. Expanded Features:** Plan to add more data visualization options and AI-driven insights.