# Taller-Open-Data-ESPC
Exercicis d'exemple amb dades obertes de l'Enquesta de seguretat pública de Catalunya

Com accedir a les dades? 

Les dades obertes de l'Enquesta de seguretat pública de Catalunya es troben al portal de dades obertes de Catalunya distribuïdes en tres conjunts de dades, corresponents als mòduls de Victimització, Multivictimització i Opinió. Els conjunts de dades es poden trobar als següents enllaços: 

https://analisi.transparenciacatalunya.cat/Seguretat/Enquesta-de-Seguretat-P-blica-de-Catalunya-M-dul-v/3jdt-62ht/about_data 

https://analisi.transparenciacatalunya.cat/Seguretat/Enquesta-de-Seguretat-P-blica-de-Catalunya-M-dul-m/saw4-mdg7/about_data 

https://analisi.transparenciacatalunya.cat/Seguretat/Enquesta-de-seguretat-p-blica-de-Catalunya-M-dul-o/jzj8-qbwj/about_data 

Es pot fer la descàrrega directa de totes les dades de cadascun dels conjunts de dades. Ara bé, cal tenir en compte la seva dimensió: 
* Victimització: 10,3 M files, 1,2 GB aprox
* Multivictimització: 1,97 M files, 200 MB aprox
* Opinió: 7,55 M files, 1,1 GB aprox

A la mateixa consulta de les dades es poden aplicar alguns filtres i descarregar les dades seleccionads. Ara bé, només es permet un màxim de 2 criteris per columna. 

La plataforma utilitzada pel portal de dades obertes, permet la descàrrega a través de API (https://dev.socrata.com/foundry/analisi.transparenciacatalunya.cat/3jdt-62ht). 

Existeixen paquets de Python (sodapy) i de R (RSocrata) que permeten utilitzar la API en aquests llenguatges de programació i gestionar les càrregues de dades. S'inclouen exercicis on es mostra el funcionament d'aquests paquets. 

També es permet la descàrrega directa a través de la URL (també s'incorpora algun exemple).

Tant en els casos de descàrrega amb API com a través de la URL, les consultes a les bases de dades es realitzen a partir de comandes del llenguatge SQL. 

En aquest projecte s'incorporen exercicis a mode d'exemple per replicar alguns resultats de les enquestes i, a partir d'ells realitzar alguna anàlisi complementària. 

Els exercicis es troben tant en Python com en R. 


