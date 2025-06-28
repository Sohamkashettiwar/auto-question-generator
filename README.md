
# 🧠 Auto Question Answer Generator

The **Auto Question Answer Generator** is a modular Python-based system designed to generate dynamic questions and answers for key computer science topics like Dynamic Programming, Fibonacci Series, Knapsack Problem, and more.
# auto-question-generator
The Auto Question Generator is a smart educational tool designed to automatically generate various types of assessment questions from input text or learning materials. It aims to support teachers, trainers, and e-learning platforms by saving time and ensuring comprehensive coverage of topics through intelligent question creation.


It classifies questions into **three levels** (Conceptual, Application, and Level-wise difficulty) and provides **detailed theory** behind the answers to support learning.

---

## 📌 Features

- ✅ Topic-wise structured answers: Fibonacci, Knapsack, LCS, MCM, Memoization
- ✅ Three-level categorization of questions:
  - **Level 1:** Basic Conceptual Questions
  - **Level 2:** Application-based Questions
  - **Level 3:** Complex/Advanced Problems
- ✅ Separate answer engines for each algorithm/topic
- ✅ Theory explanation integration to help users understand before attempting questions
- ✅ Dispatcher logic to route question types to the appropriate answer engine

---

## 🗂️ Project Structure
```
extracted_project/
└── Question_ans/
    ├── answer_dispatcher.py
    ├── main.py
    ├── answer_engine/
    │   ├── fibonacci_answers.py
    │   ├── knapsack_answers.py
    │   ├── lcslvl3.py
    │   ├── lcs_answers.py
    │   ├── mcm_answer.py
    │   ├── memoization_answer.py
    │   ├── conceptual_answers/
    │   │   ├── fibonacci_conceptual_answers.py
    │   │   ├── knapsack_conceptual_answers.py
    │   │   ├── lcs_conceptual_answers.py
    │   │   ├── memoization_conceptual_answers.py
    │   │   ├── __init__.py
    │   │   └── __pycache__/
    │   │       ├── *.cpython-311.pyc
    │   │       └── *.cpython-312.pyc
    │   └── __pycache__/
    │       ├── *.cpython-311.pyc
    │       └── *.cpython-312.pyc
    ├── data/
    │   ├── fibonacci.json
    │   ├── knapsack.json
    │   ├── lcs.json
    │   └── memoization.json
    ├── info/
    │   ├── fibonacci_algorithmic.py
    │   ├── fibonacci_application.py
    │   ├── fibonacci_conceptual.py
    │   ├── fibonacci_optimization.py
    │   ├── knapsack_algorithmic.py
    │   ├── knapsack_conceptual.py
    │   ├── knapsack_implementation.py
    │   ├── lcs_algorithmic.py
    │   ├── lcs_application.py
    │   ├── lcs_conceptual.py
    │   ├── lcs_implementation.py
    │   └── lcs_optimization.py
    │   └── __pycache__/
    │       └── *.cpython-312.pyc
    └── objective/
        ├── fibonacci_algorithmic.py
        ├── fibonacci_application.py
        ├── fibonacci_conceptual.py
        ├── fibonacci_optimization.py
        ├── knapsack_algorithmic.py
        ├── knapsack_application.py
        ├── knapsack_conceptual.py
        ├── knapsack_implementation.py
        ├── knapsack_optimization.py
        ├── lcs_algorithmic.py
        ├── lcs_application.py
        ├── lcs_conceptual.py
        ├── lcs_implementation.py
        └── lcs_optimization.py
```

---

## ⚙️ Technologies Used

- **Language:** Python 3
- **Concepts:** Dynamic Programming, Recursion, Problem Solving
- **Design:** Modular Architecture with dispatcher and engine separation

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Ganesh30052003/auto-question-generator.git
cd auto-question-generator/Question_ans
```

📌 Authors
Soham Kashettiwar

Team Members: Ganesh Kondamwar, Tejas Kotalwar


