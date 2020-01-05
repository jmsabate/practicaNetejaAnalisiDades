# practicaNetejaAnalisiDades
Repositori amb tots els components que s'han construït per a realitzar la pràctica '2. Neteja i Anàlisi de Dades'  de l'assignatura 'Tipologia i cicle de Vida de les dades' del Màster en Data Science de la UOC. Gener 2020

## Pràctica Neteja i Anàlisi de les Dades: estudi sobre un fitxer obtingut de kaggle
El fitxer s'ha obtingut de https://www.kaggle.com/jealousleopard/goodreadsbooks i s'ha completat amb informació procedent de la pròpia web de **Goodreads** així com de l'organització **ISBN** i **Wikipedia**. Contè:
* Informació d'edicions de llibres avaluats a Goodreadsles amb dades com ara l'autor, el codi ISBN, la mitjana de valoracions, nombre de valoracions i de comentaris, ...
* Nova informació recuperada com a part de la pràctica realitzada: 
  * de **goodreads** o **ISBN**: any de publicació del llibre, longitud de la descripció del llibre a **goodreads**
  * de **Wikipedia**: any de naixement i sexe de l'autor

## Membres de l'equip
El treball ha estat realitzat per l'alumne jsabatei

## Documentació
* *README.md*: Aquest propi document

* *Carpeta docs*: Carpeta amb els documents de la pràctica:
    * *Pràctica_2_jsabatei_Neteja_i_Anàlisi.ipynb* notebook Jupiter amb la resolució de la pràctica amb codi Python
    * *Pràctica_2_jsabatei_Neteja_i_Anàlisi.html* el notebook Jupiter anterior imprès com a html
    * *Pràctica_2_jsabatei_Neteja_i_Anàlisi.pdf* el notebook Jupiter anterior imprès com a pdf.


* *Pràctica_1_jsabatei_Web_Scraping.pdf*: document que descriu la pràctica realitzada.
* *Pràctica_1_jsabatei_Web_Scraping.py*: script Python amb el codi del web scraping realitzat per a obtenir les dades.
* *Carpeta csv's*: 6 fitxers csv com a resultat de la pràctca:
  * *Eleccions_locals_Barcelona_20190526_Resultats.csv*: Resulats eleccions locals ciutat de Barcelona 26 de maig del 2019
  * *Eleccions_locals_Barcelona_20190526_Candidatures.csv*: Llista de candidatures eleccions locals ciutat de Barcelona 26 de maig del 2019
  * *Eleccions_locals_Barcelona_20150524_Resultats.csv*: Resulats eleccions locals ciutat de Barcelona 24 de maig del 2015
  * *Eleccions_locals_Barcelona_20150524_Candidatures.csv*: Llista de candidatures eleccions locals ciutat de Barcelona 24 de maig del 2015
  * *Eleccions_locals_Barcelona_20110522_Resultats.csv*: Resulats eleccions locals ciutat de Barcelona 22 de maig del 2011
  * *Eleccions_locals_Barcelona_20110522_Candidatures.csv*: Llista de candidatures eleccions locals ciutat de Barcelona 22 de maig del 2011
* *Carpeta gràfics*: Carpeta amb 18 gràfics relatius als resultats electorals any 2019:
    * -1- Mapes de participació
      * `part_barris.png`      Mapa de participació per barris 
      * `part_sc.png`          Mapa de participació per seccions censals
    * -2- 1r. partir més votat
      * `pguany_barris.png`    Mapa de partit més votat per barris
      * `pguany_sc.png`        Mapa de partit més votat per seccions censals
    * -3- Segon partit més votat
      * `pguany_barris2.png`   Mapa de segon partit més votat per barris
      * `pguany_sc2.png`       Mapa de segon partit més votat per seccions censals
    * -4- Implantació de les principals candidatures
      * `xxx_barris.png`       Mapa d'implantació de la candidatura xxx (erc, bc, psc, ...) per barris
      * `xxx_sc.png`           Mapa d'implantació de la candidatura xxx per seccions censals 

## Bibliografia
Aquest exercici es basa majoritàriament en els documents suggerits a l’assignatura de “Tipologia i cicle de vida de les dades”, Bloc 2:

[1] Subirats, L., Pérez, D., Calvo, M. (2019). Introducció al cicle de vida de les dades. Editorial UOC

[2] Subirats, L., Calvo, M. (2019). Web scraping. Editorial UOC.

Addicionalment, s'ha consultat:

[3] Lawson, R. (2015). Web Scraping with Python. Packt Publishing Ltd. Chapter 1. Introduction to Web Scraping


