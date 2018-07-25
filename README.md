# Cybersecurity @ Cambridge

Scripts used for OSINT and phish attempt.

All identifying information, URLs, and credentials have been stripped.

## phish_app

Download files

```
git clone https://github.com/sarimabbas/cybersecurity-cambridge
```

Virtual environment setup

```
mkdir ~/.virtualenv
cd ~/.virtualenvs
python3 -m venv cybersecurity
source ~/.virtualenvs/cybersecurity/bin/activate
```

Dependencies installation

```
cd /path/to/cybersecurity-cambridge/phish_app
pip3 install -r requirements.txt
```

Running Flask development server

```
export FLASK_APP=app.py
flask run
```