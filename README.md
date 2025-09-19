# Paper Grading System

## Overview  
A simple web-based system for grading student answers by comparing them against teacher provided model answers. Teachers and students have separate dashboards.

## Features  
- Teacher dashboard to upload model answers  
- Student dashboard to upload answers for grading  
- Automatic answer comparison script (`process_answers.py`)  
- Role-based access: Teacher / Student  

## Tech Stack  
- Backend: PHP + Hack  
- Grading logic: Python  
- Web UI: HTML/CSS/JavaScript  
- File upload support  

## Installation & Setup  
1. Clone repository  
2. Setup a PHP-capable server (e.g. Apache)  
3. Install Python if not installed  
4. Configure file upload directories & permissions  
5. Run `process_answers.py` as needed or via web trigger  

## Usage  
- Teacher logs in → uploads model answers  
- Student logs in → uploads their answers  
- System processes and returns grades / feedback  

## Future Improvements (Ideas)  
- More robust evaluation (partial credit, similarity metrics, NLP)  
- Better UI/UX design  
- Security enhancements (validation, sanitization)  
- Report generation & statistics    
