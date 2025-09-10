# Semantic Book Recommender using LangChain and Gradio

A book recommender system that uses semantic search to recommend books based on user input. This project is built using LangChain and Gradio.

---

## 📖 About the Project

This project is a book recommender system that goes beyond simple keyword matching. It uses semantic search to understand the user's query and recommend books that are contextually similar. The user can input a query, and the system will return a list of recommended books with their covers and other details.

---

## ✨ Features

* **Semantic Search:** Understands the user's query contextually to provide relevant recommendations.
* **Gradio Interface:** A simple and intuitive user interface built with Gradio to interact with the recommender system.
* **Sentiment Analysis:** Analyzes the sentiment of book descriptions.
* **Text Classification:** Classifies books into different categories.
* **Vector-based Search:** Uses vector embeddings for efficient and accurate book retrieval.

---

## 📸 Screenshots

<img width="1920" height="889" alt="Screenshot (79)" src="https://github.com/user-attachments/assets/1ca00991-c243-417c-bdc8-a1319d9c5e6d" />

<img width="1920" height="807" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/6e11dcbe-7125-43fe-b582-bad604f1886e" />

## 💻 Technologies Used

* [LangChain](https://www.langchain.com/)
* [Gradio](https://www.gradio.app/)
* [Pandas](https://pandas.pydata.org/)
* [Jupyter Notebook](https://jupyter.org/)
* [Scikit-learn](https://scikit-learn.org/stable/)

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Python 3.7 or higher
* pip

### Installation

1.  Clone the repo:
    ```sh
    git clone [https://github.com/shreyyeahh/Semantic_Book_Recommender_using_langchain_gradio.git](https://github.com/shreyyeahh/Semantic_Book_Recommender_using_langchain_gradio.git)
    ```
2.  Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

---

## 🏃‍♀️ Usage

1.  Run the Gradio app:
    ```sh
    python gradio_dashboard.py
    ```
2.  Open your browser and navigate to the local URL provided by Gradio.
3.  Enter your query in the input box and get book recommendations.

---

## 📂 File Descriptions

* `gradio_dashboard.py`: The main file to run the Gradio application.
* `data_exploration.ipynb`: Jupyter notebook for exploring the book dataset.
* `sentiment_analysis.ipynb`: Jupyter notebook for performing sentiment analysis on book descriptions.
* `text_classification.ipynb`: Jupyter notebook for classifying books into categories.
* `vector_search.ipynb`: Jupyter notebook for implementing the vector search functionality.
* `books_cleaned1.csv`, `books_with_categories.csv`, `books_with_emotions_scores.csv`: CSV files containing the book data.
* `requirements.txt`: A list of all the Python packages required to run the project.
* `.gitignore`: A file to specify which files and directories to ignore in a Git repository.
* `cover-not-found.jpg`: A placeholder image for books without a cover.
* `tagged_description.txt`, `theory.txt`: Text files with additional information.
