from pathlib import Path

readme_content = """# Hi, I'm Xixiong Wu 👋

I'm a software developer with a data science background, focused on building practical backend systems, data-processing tools, and automation workflows.

I mainly work with **Python**, **Django**, **PostgreSQL**, **Linux deployment**, and **document/data automation**. I enjoy turning messy business processes into structured, maintainable systems.

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/DRF-Django%20REST%20Framework-red?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

## 🔭 What I'm working on

- Building Django + PostgreSQL internal business systems
- Designing admin workflows for business records, operational documents, and reference data
- Developing data import, validation, duplicate-checking, and document-matching workflows
- Automating Excel, Word, PDF, and batch file-processing tasks with Python
- Maintaining Linux-based deployment environments with Nginx, Gunicorn, systemd, permissions, and access control

## 📌 Featured Work

### Deep Active Learning Benchmark Platform

I worked on a unified benchmark platform for Deep Active Learning research, supporting algorithm comparison across computer vision and NLP tasks.

Key areas involved:

- Deep active learning algorithm evaluation
- Cross-domain experiment design for CV and NLP datasets
- Open-set and class-imbalanced experimental settings
- Python-based experiment configuration, training, and result processing

Repository: [DALBenchmark](https://github.com/WuXixiong/DALBenchmark)

### Internal Business System Development

I have worked on practical internal systems for business operations, focusing on:

- Django admin workflows
- PostgreSQL data modeling
- Multi-source data import
- Duplicate-record validation
- Document tracking and file matching
- Python automation around Excel, Word, and PDF files
- Linux server deployment and service maintenance

## 🎯 Current Interests

- Backend development
- Data engineering
- Business process automation
- Internal tools and admin systems
- Applied machine learning and data analysis

## 📫 Contact

[![Email](https://img.shields.io/badge/Gmail-wuxixiong2020%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:wuxixiong2020@gmail.com)

---

Thanks for visiting my profile.
"""

output_path = Path("/mnt/data/GitHub_Profile_README.md")
output_path.write_text(readme_content, encoding="utf-8")

output_path.as_posix()
