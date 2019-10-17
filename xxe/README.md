# XXE
To modify the OOB endpoint for the docx payload:
1. Extract the xml file: `unzip xxe.docx`
2. Modify the endpoint in `word/document.xml`
3. Zip it back up into docx format: `zip -u xxe.docx word/document.xml`
