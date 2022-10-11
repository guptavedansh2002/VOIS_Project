<h1>Repository for the project Provider Invoice Text Curation.<h1>
<h2>By- Sanket Telunagi, Varad Unhale, Vedansh Gupta, Soham Ravindran.<h2>

<h2> Description <h2> 
We created a model to extract meaningful information from provided bill image by,
1) extracting text from image using a OCR (optical character recognition) model like Pytesseract.
2) Creating a NLP model to extract information from text using Spacy’s NER (named entity recognition) model.
3) Use Regex expressions for extracting emails, phone numbers etc where it can be used
4) Convert the output into extractable form
5) Finally, export the data into json format for further use.

<h2>Techstack<h2>
Technologies we used to make this project are:

Pytesseract - OCR engine for OCR

Open CV - reading and manipulating image

Spacy - NLP library for NER model\n

JSON module - output the file in JSON format\n

Python - programming language
