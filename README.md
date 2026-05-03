#  Application Development Tasks 

##  Project Overview

This repository contains solutions for Tasks **1–9** from the *Application Development* course. The tasks focus on understanding web APIs, JSON data processing, and building interactive applications using Python.

The project includes:
- Data processing with Pandas
- Web data collection
- Building UI with Gradio
- AI integration using Gemini API

---

##  Tasks Description

###  Task 1: Compare Server Headers

- Compare server headers from:
  - Naver
  - Google

---

###  Task 2: JSON → DataFrame

- Load data from:
  https://jsonplaceholder.typicode.com/users
- Convert JSON to Pandas DataFrame
- Extract `"address"` column and convert it into structured DataFrame

---

###  Task 3: Filter & Save Data

- Load data from:
  https://jsonplaceholder.typicode.com/posts
- Select only rows with even index
- Save as Excel file

---

###  Task 4: API + Gradio UI

- Fetch data from:
  https://jsonplaceholder.typicode.com/posts
- Use:
  ```python
  requests.get(url, params=params)
  ```
- Input userId via Gradio
- Display filtered data as DataFrame
  
---

### Task 5: Data Analysis Project

- Download 3 datasets (Seoul bike data)
- Merge datasets
- Perform basic analysis
- Build multi-page Gradio UI

---

### Task 6: Gemini API (AI Integration)

Create translation UI
Translate Task 7 text
Translate only the first line

---

### Technologies Used

Python
Requests
Pandas
Gradio
Google Gemini API
