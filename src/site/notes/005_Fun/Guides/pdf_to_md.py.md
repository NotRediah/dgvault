---
{"dg-publish":true,"permalink":"/005-fun/guides/pdf-to-md-py/","tags":["guide"],"created":"2025-11-14T20:08:14.347+05:00","updated":"2025-11-12T14:26:37.082+05:00"}
---

- [ ] make a script that does it for you

# Create the virtual environment so pip is allowed to run
```
cd ~/pdf_to_md
python -m venv venv
source venv/bin/activate
pip install pymupdf
python pdf_to_md.py
```

>*note pipx doesn't work in this context because it's isolated and pdf_to_md.py is just a file not available on pipx

# Stopping
```
deactivate
```
# Reusing it afterwards
```
cd ~/pdf_to_md
source venv/bin/activate
python pdf_to_md.py
```