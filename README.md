# AI-Based-Customer-Support-Chatbot


A **customer support chatbot** for an e-commerce electronics store, built using **Streamlit**, **LangChain**, and **MySQL**. This AI-powered chatbot assists users in browsing products (e.g., mobiles, laptops), checking prices, updating user details, and more, by generating SQL queries and providing natural language responses in a customer-friendly manner.


## 📖 Project Overview

This project is an **AI-based customer support chatbot** designed for an e-commerce electronics store. It leverages **LangChain** to process user queries, generate MySQL queries, and fetch relevant data from a database. The chatbot provides responses in a warm, customer-service-oriented tone, making it ideal for assisting users with product inquiries, order status checks, and user profile updates.


### Key Features
- **User Authentication**: Login and signup functionality for users.
- **Product Browsing**: Search for products (e.g., mobiles under ₹15,000, Best gaming laptop) with detailed specifications and pricing.
- **Dynamic Responses**: Uses LangChain to generate SQL queries and transform raw data into customer-friendly responses.
- **Conversation History**: Stores and displays previous conversations for user reference.
- **User Profile Management**: Allows users to update their details (e.g., address).
- **Responsive UI**: Built with Streamlit for a clean, user-friendly interface.
- **Track Order**: You can track your order.



## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python, LangChain, MySQL
- **Database**: MySQL (for storing users, products, discounts, etc.)
- **AI/LLM**: Google Generative AI (via LangChain)
- **Embedding Model**: HuggingFace Embeddings (`BAAI/bge-large-en`)
- **Vector Store**: Chroma (for few-shot example selection)


## Output Screens

- **Login Page**

![image](https://github.com/user-attachments/assets/4740d086-8940-4d98-bde8-b85b2759f374)

- **Account creation page**

![image](https://github.com/user-attachments/assets/dabc5e9f-27a3-48f9-85b5-965f545bc807)

- **Response for User Question**

  ![image](https://github.com/user-attachments/assets/3d7b74d8-c94b-4f8b-a92b-6ff0c628487c)

- **Updatinng user details in Database(MySQL)**

![image](https://github.com/user-attachments/assets/3d4078fc-ba0c-4217-be2a-0a444a9d4e5e)

- **Response for specific product**

![image](https://github.com/user-attachments/assets/85381314-78a7-467b-826a-aa1ab219c0c6)

- **Comparing two products**

![image](https://github.com/user-attachments/assets/f18802cc-1957-48f4-8fa3-c3cdb9069fb2)

![image](https://github.com/user-attachments/assets/68a7fbb3-ad31-450d-8fb2-8588b13b3f01)



## 📋 Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.8 or higher
- MySQL 8.0 or higher
- A Google API Key for Google Generative AI (used by LangChain)


