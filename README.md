# Resume Parser with NER & Entity Linking

A Python-based resume parser leveraging spaCy for NER, regex for entity retrieval, and structured section parsing (PDF, DOCX, TXT).

## Features
- Extracts name, email, phone
- Section extraction: skills, projects, education, certifications, achievements
- Cleans and deduplicates content

## Usage

```bash
git clone https://github.com/pranavpatil2316/Resume-Parser
cd Resume-Parser
pip install -r requirements.txt
python -m spacy download en_core_web_sm
python resume_parser.py sample_resume.pdf
