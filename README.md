# Task Extraction & Categorization using NLP

## 📌 Overview
This project extracts and categorizes tasks from textual data using Natural Language Processing (NLP). It preprocesses text, identifies tasks based on action verbs, and groups them into categories using **Word2Vec** and **Latent Dirichlet Allocation (LDA)**. The system also extracts responsible persons and deadlines to provide structured task insights.

## 🚀 Features
- **Text Preprocessing**: Cleans text (lowercasing, punctuation removal, stopword removal).
- **Task Extraction**: Identifies tasks using action verbs (e.g., must, should, has to).
- **Categorization**: Groups tasks into meaningful categories using Word2Vec and LDA.
- **Named Entity Recognition (NER)**: Extracts responsible persons and deadlines.
- **Output Structuring**: Displays tasks in a structured format for better understanding.

## 📂 Installation
```bash
# Clone the repository
git clone https://github.com/Prabhakars367/task-extraction-nlp.git
cd task-extraction-nlp

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

## 🛠️ Usage
```bash
# Run the Jupyter Notebook
jupyter notebook
```
- Open `PART_A.ipynb` in Jupyter Notebook.
- Run each cell to extract and analyze tasks from input text.

## 📊 Example Input & Output
### **Input:**
"John must submit the report by Monday. Alice should review the document before Friday."

### **Output:**
| Task  | Person | Deadline |
|-------|--------|----------|
| Submit the report | John | Monday |
| Review the document | Alice | Friday |

## 🤖 Technologies Used
- **Python**
- **NLTK** (Tokenization, POS Tagging, Stopword Removal)
- **Gensim** (Word2Vec, LDA for Categorization)
- **Jupyter Notebook**

## 🏗️ Future Enhancements
- Improve Named Entity Recognition (NER) for better accuracy.
- Develop a web-based interface for easier task input.
- Integrate with email/chat tools for automated task extraction.

## 📜 License
This project is licensed under the MIT License.

## 🙌 Contributing
Feel free to open issues and pull requests to contribute to the project!

## 📞 Contact
For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/prabhakars367/) or email at prabhakars367@gmail.com.

