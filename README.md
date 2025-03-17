DiGA Recommender Web Application
Project Setup

Prerequisites:

    1. Ubuntu or any other linux distribution (WSL2 also works) (sentence-transformers does not work properly on Windows).
    2. Python 3.10 or higher

Steps:

    1. Create and activate virtualenv inside WSL2 or native linux distribution.
    2. Navigate inside diga_web_app directory and install dependencies using pip install -r requirements.txt
    3. Navigate inside diga_web_app directory where manage.py file is located.
    4. Run command python manage.py runserver

Note:
Semantic search section is accessible via http://127.0.0.1:8000/semantic_search/ . See urls.py for more details.
