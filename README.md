## webScraping-MetroCuadrado
Este proyecto se realizo con fines académicos, se trata de un algoritmo que recorre las búsquedas de casas o apartamentos en la pagina M3troCuadrado según algún criterio y toma los datos de las publicaciones los cuales se usaran en ciencia de datos 
// This project was done for academic purposes, it is an algorithm that goes through the searches for houses or apartments in the M3troCuadrado.com site according to some criteria and takes the data from the publications which will be used in data science.

### Requsitos // Requirements
- Entorno Python // Environment Python
- Entorno para ejecutar jupyter notebooks // Environment for running jupyter notebooks https://jupyter.org/
- Instalar Selenium // Install Selenium https://selenium-python.readthedocs.io/installation.html
- Instalar el navegador Chrome // Install Chrome browser 
- Instalar ChromeDriverManager // Install ChromeDriverManager https://pypi.org/project/webdriver-manager/
- Instalar el driver de Chrome y alojarlo en la raiz del entorno jupyter // Install Chrome driver and place it in the root of the jupyter environment. https://chromedriver.chromium.org/getting-started

###Ejecutar //   Execute 

####En una terminar // En a terminal 

`$ !pip install selenium`
`$ !pip install webdriver-manager`
####Ejecutar NoteBook // Run NoteBook

1. clone el archivo 'ws_metrocuadradofiltrado.ipynb' de este repositorio y carguelo a su entorno Jupyter , Ejecute los bloques con `|> Run`.
// clone the file 'ws_metrocuadradofiltrado.ipynb' from this repository and upload it to your Jupyter environment, execute the blocks with `|> Run`.

2. Se abrira un navegador Chrome de pruebas, se movera solo ya que esta ejecutando el webscraping // A test Chrome browser will open, it will move by itself as it is running webscraping.

3. Le mostrará un log linea a linea // show a line by line log 

        **INICIANDO WEB SCRAPING A metrocuadrado.com**
        -Obteniendo pagina 1
        --total items x pagina 50
        -dato 1
        -dato 2
        -dato 3
        -dato 4
        -dato 5
        -dato 6
    	...

4. una vez finalizado, guardara los datos extraidos en un archivo llamado 'datos.csv' ubicado en la raiz. // Once finished, it will save the extracted data in a file named 'datos.csv' located in the root.

![](https://repositorio.itc.edu.co/bitstream/id/56b31ff7-992f-4f3a-b51e-30fc5f53c0d3/logo_es.png?sequence=-1)

###Muchas Gracias.
