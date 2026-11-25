---
{"dg-publish":true,"tags":["type/guide"],"source":"https://github.com/M1ck4/pdf_to_md","permalink":"/notes/guides/pdf-to-md-py/","dgPassFrontmatter":true,"created":"2026-07-26T08:39:07.479+05:00","updated":"2026-11-24T14:06:36.486+05:00","ctime":"2026-07-26T08:39:07.479+05:00","mtime":"2026-11-24T14:06:36.486+05:00","dg-note-properties":{"tags":["type/guide"],"source":"https://github.com/M1ck4/pdf_to_md"}}
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
