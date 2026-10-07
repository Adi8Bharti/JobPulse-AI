# JobPulse AI — Google Colab

1. Open Google Colab.
2. Upload `JobPulse_AI_Colab.ipynb`.
3. Upload `job_postings.csv` using the Colab Files panel.
4. Run notebook cells from top to bottom.
5. The OpenAI section is the only part requiring an internet connection and API key.
6. Never save the API key directly inside the notebook.

The dataset is synthetic and generated for reproducibility. It contains job role, company, location, education, experience, salary and skills. Salary is generated with relationships to role, location, education, experience and skill count so the regression model has learnable signal.

Project flow:
CSV → Pandas cleaning → skill extraction → EDA → SQLite SQL → Random Forest regression → skill gap → OpenAI API → structured insights
