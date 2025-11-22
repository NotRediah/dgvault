---
{"dg-publish":true,"permalink":"/500-fun/guides/pdf-to-md-py/","tags":["guide"],"created":"2025-11-14T15:44:45.297+05:00","updated":"2025-11-16T21:28:50.597+05:00"}
---

- [x] make a script that does it for you ✅ 2025-11-16

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