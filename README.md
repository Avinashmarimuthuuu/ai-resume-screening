# Resume-Job Matcher

**Student:** Avinash M


**College:** Periyar Maniammai Institute of Science and Technology


**Year:** Final Year BSc Computer Science



**Based on:** https://github.com/PhamVuThuNguyet/ai-resume-screening (original author: PhamVuThuNguyet)



**My changes:**
- Renamed the app title to "Resume-Job Matcher by Avinash" and added credit to the original author in the sidebar
- Added a sidebar summary showing the number of resumes and job descriptions loaded
- Added Download buttons to save the BERT and Doc2Vec results as JSON

**Live demo:** https://avinash-resume-job-matcher.streamlit.app/


















---# Description
We have built a Resume & Job Description Matching System using Deep Learning.

# Installation

```shell
pip install -q requirements.txt
```

# Demo
Run demo with Streamlit

```shell 
streamlit run test.py
```

The demo app will be opened at http://localhost:8501/

(Optional): FastAPI 

```shell
python app.py
```

You can view the docs at http://localhost:8008/docs

# Usage/Example
Step 1: Choose the resume to upload to system.

![img.png](./image/img.png)

Step 2: Choose to get recommendation with BERT model or Doc2Vec model.

![img2.png](./image/img2.png)

Step 3: Show the results.

![img3.png](./image/img3.png)
