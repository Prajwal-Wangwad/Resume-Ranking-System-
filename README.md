# AI Resume Ranking System

## Overview
The **AI Resume Ranking System** is a web-based application built using **Streamlit**. It utilizes **Natural Language Processing (NLP)** techniques to rank resumes based on their similarity to a given job description using **TF-IDF (Term Frequency-Inverse Document Frequency)** and **cosine similarity**.

## Features
- Upload multiple **PDF resumes**.
- Extract text from resumes using **PyPDF2**.
- Rank resumes based on their similarity to the job description.
- Display ranked results in a tabular format.
- Modern UI with a **customizable background image**.

## Technologies Used
- **Python**
- **Streamlit**
- **PyPDF2**
- **Scikit-learn** (TF-IDF, Cosine Similarity)
- **Pandas**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-Prajwal-Wangwad/ai-resume-ranking.git
   cd ai-resume-ranking
   ```

2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Run the application:
   ```sh
   streamlit run resume_app.py
   ```

## Usage
1. Enter a **job description**.
2. Upload multiple **PDF resumes**.
3. Click on the **Rank Resumes** button.
4. View the ranked resumes based on similarity scores.

## License
This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to fork the repository, create a new branch, and submit a **pull request**. Contributions are welcome!

## Contact
For any queries or suggestions, reach out via:
- Email:prajwalwangwad26@gmail.com
- GitHub Issues

---
Made with ❤️ using **Streamlit & Python**

