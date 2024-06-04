# Onderzoek Studentengeluk

Dit onderzoek gaat over het geluk van studenten in verschillende studenten steden. De steden die wij hebben onderzocht zijn: Amsterdam, Groningen, Leiden en Utrecht. We hebben in dit onderzoek een enquête gebruikt om data te verzamelen. Dit onderzoek is belangrijk omdat mentale gezondheid onder de studenten tegenwoordig veel in het nieuws is. Geluk is een groot deel van iemands mentale gezondheid daarom is het interessant om te weten in welke stad voor de studenten geluk het hoogste ligt. De factoren die in dit onderzoek worden gebruikt gaan van persoonlijk naar omgevingsfactoren zodat er een duidelijk beeld kan worden geschetst waarin ook langdurige problemen worden meegenomen die invloed hebben.

## Projectomschrijving

Wij gaan het geluk van studenten in verschillende studentensteden meten om te kijken in welke stad ze het gelukkigst zijn. Dit doen wij door een enquête te versturen naar MBO, HBO en universiteiten. met verschillende vragen die te maken hebben met het geluk van een persoon. De data uit de enquête gaan we analyseren om te kijken hoe gelukkig de studenten zijn.

### Resultaten
(INSERT RESULTATEN MET GRAFIEK BELANGRIJKSTE DATA)


## Conclusie

De data die wij verzameld hebben is niet genoeg om een antwoord te geven op de hypothese. Dit komt omdat er niet genoeg data is voor elke stad. De stad met het grootste aantal antwoorden is Groningen deze heeft echter ook maar 70 antwoorden dit is te zien in figuur 1. De 70 antwoorden zijn niet genoeg om met 95% zekerheid een antwoord te geven. Hierdoor zullen wij alleen naar factoren kunnen kijken zoals verschillen tussen de seksen in de stad Groningen. Hier kunnen we uit halen dat mannen het gelukkigste zijn en de anders sekse het ongelukkigste dit is te zien in figuur 4. Ook hebben wij gevonden dat er misschien een relatie zit tussen de studenten die een kunst opleiding volgen en bij de sekse "Anders"\ 
Verder is te zien dat studenten die uitwonend zijn over het algemeen aan de gelukkigere kant zitten dat is te zien in figuur 5. De data die verzameld is zegt ook dat de studenten in Groningen gemiddeld niet zeer gelukkig zijn. Dit is tevens een trend in de data die het cbs heeft gevonden dit is te zien in figuur 8. Hier is ook een neerwaartse trend te zien. Wat wij dus uit deze data kunnen halen is dat een student in de stad Groningen redelijk gelukkig is maar er is zeker ruimte voor verbetering. 



Deze data zal niet kunnen worden gebruikt in het werkveld. Het is niet genoeg om vertrouwen op de gegeven resultaten. Hierdoor is het een speculatieve data waardoor het niet betrouwbaar is.

## Discussie

De volgende keer moeten wij een betere manier verzinnen om de data te verzamelen. Wij hadden bijna, en voor Utrecht zelfs helemaal geen data. Door deze belemmering konden wij ons onderzoek niet goed uitvoeren. Dit zouden wij de volgende keer kunnen oplossen door directer naar de studenten te marketen. Wij kunnen dit oplossen door meerdere dagen per stad te besteden en fysiek studenten vragen om mee te doen met ons onderzoek. 


### Benodigdheden

* Een werkende OS

| Tool                	| Referentie                                              	| Versie                               	| Waarom                                                                                                                                                                                       	|
|---------------------	|---------------------------------------------------------	|--------------------------------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| Google forms        	| https://docs.google.com/forms/                          	|                                      	| Gebruikt om een enquête te maken die gebruikers vriendelijk is en een netjes csv bestand geeft als output.                                                                                   	|
| Git                 	| https://www.git-scm.com                                 	| git version 2.44.0                   	| Git wordt gebruikt voor version control                                                                                                                                                      	|
| Github              	| http://github.com                                       	|                                      	| De gehele data set, logboeken en protocol staan op github omdat dit een netjese en goed navigeerbare omgeving maakt zodat iemand ook alles in 1 keer kan downloaden en bekijken.             	|
| RStudio             	| https://posit.co/download/rstudio-desktop/              	| Versie 2023.12.1+402 (2023.12.1+402) 	| Dit programma gebruiken we om ons RMarkdown document te maken wat uiteindelijk ons eindproduct is geworden.                                                                                  	|
| R                   	| https://www.r-project.org                               	| R version 4.3.3 (2024-02-29)         	| R staat mensen toe om vaardig grote hoeveelheden gegevens te verwerken, publicatie-waardige visualisaties te genereren, en een reeks statistische en analytische computertaken uit te voeren 	|
| fmsb                	| https://cran.r-project.org/web/packages/fmsb/index.html 	| 0.7.6 (03-06-2024)                   	| Wij gebruiken deze voor het maken van radar plots                                                                                                                                            	|
| ggplot2             	| https://ggplot2.tidyverse.org                           	| 3.5.1 (03-06-2024)                   	| Deze package wordt om plotjes in dit document duidelijker en netjeser te maken                                                                                                               	|
| pwr                 	| https://github.com/heliosdrm/pwr                        	| 1.3-0 (October 14, 2022)             	| per wordt gebruikt om statistische analyze te doen zoals een t test                                                                                                                          	|
| dplyr               	| https://dplyr.tidyverse.org                             	| 1.1.4 (03-06-2024)                   	| dplyr geeft andere commando's die niet in de standaard versie van R zit.                                                                                                                     	|
| knitr               	| https://yihui.org/knitr/                                	| knitr 1.47 (03-06-2024)              	| Knitr is gebruikt om dingen aan te passen die in de geknitte versie komen                                                                                                                    	|
| tidyverse           	|  https://www.tidyverse.org                              	| tidyverse 1.3.0 (03-06-2024)         	| Tidyverse wordt gebruikt om verschillende dingen aan te passen in potjes                                                                                                                     	|
| Canva               	| https://www.canva.com                                   	|                                      	| Canva is gebruikt om posters te maken met qr codes die de enquete openen                                                                                                                     	|
| Google  Spreadsheet  	|    https://docs.google.com/spreadsheets/                	|                                      	| De antwoorden van de Google forms worden hier in een spreadsheet gezet en deze kan via een download knop omgezet worden in een csv file.                                                     	|
| Mendeley refrence manager   	| [https://docs.google.com/forms/ ](https://www.mendeley.com/reference-management/reference-manager/)    |   2.112.2                     	| Gebruikt om een alle literatuur netjes te ordenen en goed te refrencen                                                                                   	|

Met de volgende commands zijn de packages te instaleren in RStudio
```
install.packages("knitr")
install.packages("ggplot2")
install.packages("fmsb")
install.packages("tidyverse")
install.packages("dplyr")
```
## Help

Voor vragen kan je ons contacteren op https://github.com/sstormpie/Onderzoek-Studentengeluk


## Auteurs

* J.J. Duiker - Github: azzipxonraj
* S. Steller - Github: sstormpie


## Acknowledgments

* Ronald Wedema
* Michiel Noback
* Emile Apol
