To install:

open wsl on windows or a linux terminal

python3 -m venv venv
venv/bin/activate
pip install -r requirements.txt

To launch the fast API server:
uvicorn main:app --reload

#running the webscraper
python3 collect_events.py