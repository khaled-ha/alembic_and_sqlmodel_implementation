## How to try it :

    - python -m venv venv
    - source venv/bin/activate
    - pip install -r requirements.txt
    - delete the versions inside migrations/versions
    - alembic revision --autogenerate 
    - alembic upgrade gead
    - python create_heroes.py