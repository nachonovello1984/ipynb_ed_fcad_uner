# Jupyter Notebook + RISE presentaciones de Estructuras de Datos - FCAD UNER
## Comandos para exportar a pdf
Generate the slides and serve them using nbconvert:

jupyter nbconvert --to slides your_talk.ipynb --post serve

It opens up a webpage in the browser at http://127.0.0.1:8000/your_talk.slides.html#/

Add ?print-pdf to the query string as http://127.0.0.1:8000/your_talk.slides.html?print-pdf

Note that you need to remove the # at the end. The page will render the slides vertically.

Save to PDF in Chrome using the print option

Open the in-browser print dialog (Cmd/Ctrl + P).

Change the Destination setting to Save as PDF.

Change the Layout to Landscape.

Change the Margins to None.

Enable the Background graphics option.

Click Save.