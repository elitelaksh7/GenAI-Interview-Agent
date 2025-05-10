# GenAI-Interview-Agent
This Kaggle notebook implements a Generative AI-based system to analyze candidate interview answers and provide automated feedback. It uses a built-in dataset and is ready to run without any manual uploads.

🔍 Overview
Evaluates candidate responses using language models

Generates structured feedback: strengths, weaknesses, and suggestions

Works on a preloaded dataset—no setup required!

📦 Dataset
The notebook uses a default dataset (feedback_dataset_with_feedback.csv) containing:

question_id

question

candidate_answer

ideal_answer

difficulty

answer_type

feedback

🛠️ Built With
Python

Pandas

YAKE (for keyword extraction)

Scikit-learn (for classification)

Optional: Hugging Face LLMs for advanced feedback generation

▶️ How to Run
Open the notebook on Kaggle

Run all cells sequentially

View:

AI-generated feedback per answer

Answer quality classification (Low / Medium / High)

Feature importance & keyword highlights

✅ Outputs
feedback column: AI-generated comments

label: Performance category (if classification is included)

Visual insights (charts, confusion matrix, etc.)

📝 Notes
No file uploads required — ready to run out of the box

Can be extended with API-based LLMs if desired
