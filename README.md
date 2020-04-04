intalar dichas dependencias
* pytesseract
* PyMuPDF

tambien se tendrá que instalar el programa tesseract para poder realizar el text recognition
* !sudo apt install -q tesseract-ocr

Primer paso

Correr el archivo "1.Scraping_Proyectos_Ley.ipynb" , con este archivo se podrá extraer tanto la metadata
de cada proyecto de ley y los proyectos de ley en sí. 
Se obtuvieron alrededor de 4849 proyectos de ley , la metadata se almaceno en un dataframe y el proyecto de ley
en un pdf, para su posterior análisis.


Segundo Paso

Correr el archivo "2.Text_Recognition", con dicho notebook se podrá realizar el reconocimiento de texto. Se utilizo un modelo
pre-entrenado en español para reconocer las letras del pdf
