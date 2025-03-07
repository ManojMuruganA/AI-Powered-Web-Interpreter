# AI-Powered Web Interpreter

## 🌍 Breaking Barriers for Global Literacy
AI-Powered Web Interpreter is a smart tool that extracts, summarizes, and translates web content, making information accessible to everyone.

---

## 🚀 Features
- **Web Scraping**: Extracts clean text from any webpage.
- **AI Summarization**: Uses NLP to generate concise summaries.
- **Multilingual Translation**: Supports multiple languages for better accessibility.
- **User Authentication**: Secure login and registration with MongoDB.
- **Sentiment Analysis**: Detects and flags negative content.
- **AI Chatbot**: Answers user specific queries based on extracted content.

---

## 🛠️ Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- MongoDB
- Node.js (for frontend features)
- Pip (Python package manager)

### Clone Repository
```sh
$ git clone https://github.com/yourusername/ai-web-interpreter.git
$ cd ai-web-interpreter
```

### Backend Setup
1. Install required dependencies:
```sh
$ pip install -r requirements.txt
```
2. Run MongoDB:
```sh
$ mongod --dbpath /data/db
```
3. Start the Flask server:
```sh
$ python main.py
```

### Frontend Setup
1. Navigate to the `static` folder:
```sh
$ cd static
```
2. Install dependencies (if any):
```sh
$ npm install
```
3. Run the frontend (if using a separate development server):
```sh
$ npm start
```

---

## 🖥️ Usage
1. **Enter a URL** in the input field.
2. **Select a language** for translation.
3. **Choose an option** (Translate or Summarize & Translate).
4. **View the processed content** and download results.
5. **Ask AI-powered chatbot** for context-based queries.

---

## 📂 Project Structure
```
├── static/                # Frontend files (CSS, JS)
│   ├── style.css
│   ├── script.js
│   ├── images/
├── templates/             # HTML templates
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── result.html
│   ├── error.html
├── main.py                # Backend Flask application
├── setup_db.py            # MongoDB connection setup
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

---

## 🤝 Contributing
1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature-branch`)
3. **Commit changes** (`git commit -m "Added a new feature"`)
4. **Push to GitHub** (`git push origin feature-branch`)
5. **Submit a Pull Request**

---

## 🛡️ License
This project is licensed under the MIT License.

---

## 📬 Contact
For any queries, reach out via email: `manojmurugan66@gmail.com` or open an issue in the repository.

---

### ⭐ If you find this project useful, don't forget to give it a star on GitHub! ⭐
