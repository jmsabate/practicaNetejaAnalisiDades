# practicaNetejaAnalisiDades
Repositori amb tots els components que s'han construït per a realitzar la pràctica '2. Neteja i Anàlisi de Dades'  de l'assignatura 'Tipologia i cicle de Vida de les dades' del Màster en Data Science de la UOC. Gener 2020

## Pràctica Neteja i Anàlisi de les Dades: estudi sobre el fitxer **books.csv** obtingut de kaggle
El fitxer s'ha obtingut de https://www.kaggle.com/jealousleopard/goodreadsbooks i s'ha completat amb informació procedent de la web de **Goodreads** així com de l'organització **ISBN** i **Wikipedia**. Conté:
* Informació d'edicions de llibres avaluats a Goodreads (web dedicada a la recomanació de llibres) amb dades com ara l'autor, el codi ISBN, la mitjana de valoracions realitzades pels usuaris de *goodreads*, nombre de valoracions i de comentaris, ...
* Nova informació recuperada com a part de la pràctica realitzada: 
  * de **goodreads** o **ISBN**: any de publicació del llibre, longitud de la descripció del llibre a **goodreads**
  * de **Wikipedia**: any de naixement i sexe de l'autor

## Membres de l'equip
El treball ha estat realitzat per l'alumne jsabatei

## Documentació
* *README.md*: Aquest propi document

* *Carpeta documents*: Carpeta amb els documents de la pràctica:
    * *Pràctica_2_jsabatei_Neteja_i_Anàlisi.ipynb* notebook Jupiter amb la resolució de la pràctica amb codi Python
    * *Pràctica_2_jsabatei_Neteja_i_Anàlisi.html* el notebook Jupiter anterior imprès com a html
    
* *Carpeta dades*: 3 fitxers csv com a resultat de la pràctca:
  * *books.csv*: Fitxer original descarregat de https://www.kaggle.com/jealousleopard/goodreadsbooks.
  * *booksbase.csv*: D'acord amb el desenvolupament de la pràctica, conté la informació inicial més la informació que s'ha recuperat de **Goodreads** i **ISBN**: Any de publicació del llibre i longitud de la descripció del llibre a **Goodreads** 
  * *booksbase3.csv*: Conté la informació anterior més informació procedent de **Wikipedia**: Any de naixement de l'autor i sexe. Aquest fitxer clou l'etapa de neteja de dades i és el punt de partida per a l'etapa d'anàlisi. 

## *Developer Key* per a accés a Goodreads
Per a reproduir el notebook d'aquesta pràctica, cal una *API Key* subministrada per **Goodreads**: 
* Es pot aconseguir aquesta *API Key* registrant-se a https://www.goodreads.com/api. 
* Emmagatzemar la clau en un fitxer csv de nom *clauGoodread.csv*, que contingui una única columna *clau* i com a única fila la *Developer Key* subministrada per **Goodreads**.

## Bibliografia
Aquest exercici es basa majoritàriament en els documents suggerits a l’assignatura de “Tipologia i cicle de vida de les dades”, Pràctica 2:

[1] Introducció a la neteja i anàlisi de dades. Mireia Calvo González, Diego Oswaldo Pérez Trenard, Laia Subirats Maté. Editorial UOC. PID_00265701

[2] Squire, Megan (2015). Clean Data. Packt Publishing Ltd


