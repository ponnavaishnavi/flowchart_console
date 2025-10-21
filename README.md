# flowchart_console
A Python-based NLP tool that converts plain English text into a visual flowchart using spaCy, NetworkX, and Matplotlib. Ideal for representing processes, workflows, and logic sequences automatically.
# 🧩 Text-to-Flowchart Generator

A simple yet powerful Python tool that converts plain English text into a **visual flowchart** using **Natural Language Processing (NLP)**.  
It extracts **verbs** and **nouns** from your text to create step-by-step logical flow connections — perfect for representing processes, workflows, or algorithms visually.

---

## 🚀 Features
✅ Converts normal text into a connected flowchart  
✅ Uses **spaCy** for text analysis (NLP)  
✅ Uses **NetworkX** and **Matplotlib** for visualization  
✅ Lightweight console-based app — no GUI needed  
✅ Great for students, data scientists, and workflow designers  

---

## 📁 Project Structure
flowchart-generator/
│
├── flowchart_console.py # Main script
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── .gitignore # Ignored files

yaml
Copy code

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/flowchart-generator.git
cd flowchart-generator
2️⃣ Create Virtual Environment (optional)
bash
Copy code
python -m venv venv
venv\Scripts\activate       # On Windows
# OR
source venv/bin/activate    # On Mac/Linux
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
python -m spacy download en_core_web_sm
▶️ Usage
Run the program:

bash
Copy code
python flowchart_console.py
When prompted, enter or paste any text — for example:

pgsql
Copy code
Start the process. Check input data. Validate data. Generate report. End process.
🧠 The program will:

Extract verbs and nouns

Build logical relationships

Show a flowchart using Matplotlib

🧩 Example Output
For the above text, you’ll get a flowchart connecting:

pgsql
Copy code
Start process → Check input data → Validate data → Generate report → End process
And it will appear as a visual graph like this:

🖼️ (Matplotlib window will open with a connected node diagram.)

🧠 Tech Stack
Python 3

spaCy – NLP processing

NetworkX – Graph creation

Matplotlib – Visualization
