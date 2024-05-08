# Optical Character Recognition

#### An API that allows us to upload a file and will return the text that is contains in that file, we will use Tesseract, Tesseract is an open-source OCR Engine that extracts printed or written text from images

##### Steps:

- Install Tesseract on local Machine:
  - Linux [Fedora]: `sudo dnf install tesseract && sudo dnf install tesseract-langpack-eng`
- clone the Repo
- create a virtualenv: `python -m venv env` and activate it: `source env/bin/activate`
- run `pip install -r requirements.txt`
- run uvicorn server `uvicorn main:app --reload`
- Open the documentation: <http://127.0.0.1:8000/docs>
