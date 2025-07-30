
# 🧠 Knowledge-Based Conversational AI System

This is a hybrid web-based chatbot that integrates rule-based dialogue, logic programming, and graph-based memory for intelligent conversations. It combines multiple AI paradigms to simulate both static and inferential responses.

## 🌟 Features

- 💬 **AIML-based conversation** for handling general queries and patterns
- 🧠 **Prolog logic engine** (via pyswip) for reasoning about relationships and facts
- 🌐 **Flask web interface** for real-time user interaction
- 🧩 **NLTK-powered NLP** for POS tagging and sentence parsing
- 🔗 **Neo4j graph support** (extendable for storing user memories and facts)
- 🎨 Responsive frontend with HTML templates and favicon support

## 🧰 Tech Stack

- **Python 3.8+**
- **Flask** – web framework
- **AIML** – chatbot pattern rules
- **Prolog (via pyswip)** – for logical reasoning
- **NLTK** – natural language processing
- **Neo4j** – graph-based memory (optional extension)
- **HTML/CSS** – user interface

## 📁 Project Structure

```
├── aiml files/               # AIML knowledge base files
├── prolog/                   # Prolog .pl files (e.g., relationship logic)
├── templates/                # HTML frontend templates
├── Favicon/                  # UI icons for the web interface
├── main.py                   # Main Flask app (entry point)
├── download.py               # Utility or file management script
├── pos_tags.py               # NLP tagging logic with NLTK
├── requirements.txt          # Project dependencies
```

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app**
   ```bash
   python main.py
   ```

5. Open your browser and go to:  
   [http://localhost:5000](http://localhost:5000)

## 🧪 Example Use Cases

- Ask general knowledge questions:  
  _"What is AI?"_, _"Tell me a joke"_

- Ask relationship queries (Prolog):  
  _"Who is Ali's brother?"_, _"Is Sara married?"_

- Explore dynamic answers using NLTK and Prolog combined.

## 🔒 License

This project is open-source and available under the **MIT License**.

## 🙋‍♂️ Author

**Aaliyan Arif**  
Reach out via [LinkedIn](https://www.linkedin.com/) or open an issue for support.
