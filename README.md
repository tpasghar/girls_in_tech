# Lett nettside med medfølgende server

## Kom i gang

0. Sørg for å ha følgende installert:
* python 3.6 eller 3.7 installert: https://www.python.org/downloads/
* Visual Studio Code: https://code.visualstudio.com/ med extensions
  * Beautify
  * HTML Snippets
  * HTML CSS Support
  * Python
  * Python-autopep8
  
1. Klone repository lokalt
2. Åpne rotkatalogen "girls_in_tech"
3. Kjør følgende kommando for å lage virtuelt miljø: 

```cmd
python -m venv venv
```
4. Aktiver virtuelt miljø

```cmd 
venv/Scripts/activate
```

5. Installer flask
```cmd
pip install flask
```
6. Kjør applikasjonen
```cmd
python app.py
```
7. Kontroller at du får tilgang på 127.0.0.1:5000
8. Cache må slettes hver gang endringer i nettsiden gjøres - anbefaler Firefox og CTRL+Shift+del
