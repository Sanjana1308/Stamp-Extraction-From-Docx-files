# Stamp-Extraction-From-Docx-files
Extracting a specific stamp if present in the document

Objective: To conclude whether my legal document is authenticated by finding the presence of LEGAL OK stamp from a docx file.

Building the model:
Using resnet architecture, build a model to identify the Legal OK stamps from junk images.

Get a legal docx file that may contain the stamp
Extract all possible images present in the document and store in a folder.
Run those images through the resnet model
Extract if Legal Ok stamp is present as an image.








