---
link-citations: true
---

\section*{Bijlagen}
\addcontentsline{toc}{section}{Bijlagen}  

\appendix

#Bijlagen

##Methodologie

###Kwantitatieve Inhoudsanalyse (QCA) (deels)

(QCA als middel ter empirisch onderzoek in Japans populisme?)

@riffe_analyzing_2014, auteurs van "Analyzing Media Messages: Using Quantitative Content Analysis in Research" definiëren op volgende wijze kwantitatieve inhoudsanalyse als onderzoeksmethode sumier op:

>"the systematic assignment of communication content to categories according to rules, and the analysis of relationships involving those categories using statistical methods." [@riffe_analyzing_2014]

Die definitie legt de nadruk van QCA enerzijds op de centraliteit van de verworven data zelf, als op de objectiviteit en systematische methoden om zich te onderscheiden van een onwetenschappelijk "informeel proces waarbij men conclusies trekt gebaseerd op waarnemingen van inhoud" waar we allen dagelijks aan deelnemen [-@riffe_analyzing_2014, p.23]. Concreet levert dat binnen studies van massacommunicatie een versatiele methode op voor onderzoekers om bepaalde stellingen empirisch te bewijzen door in dit geval *big data* gehaald uit massacommunicatie te categoriseren en daar conclusies uit te trekken. Deze definitie is opzettelijk vaag juist door de breedheid van deze methodologie: de onderzoeker stelt een typologie op waartegen de dataset wordt getoetst, en geeft aldus verdere betekenis aan de inhoud van die data om zo statistische conclusies te trekken.

Uiteraard bestaan gegevens niet in het luchtledige en moeten ze gezien worden als het gevolg van een grote waaier aan voorafgaande processen en condities,  waarmee rekening gehouden wordt tijdens analyse en interpretatie. Net als Shoemaker & Reese stellen dat symboliek in media (e.g. allusies naar nationalisme of solidariteit tijdens oorlogsperiode) gevolgen zijn van een dominante cultuur en ideologie (1996), zal een twitterpagina van een rechts-populist als Makoto Sakurai, sterk actief in alternatief-rechtse gemeenschappen, zijn oorsprong vinden enerzijds op persoonlijk vlak en anderzijds door socio-historische ontwikkelingen, en hoogstwaarschijnlijk het discours van die gemeenschap reflecteren.

|            **Table 8.1 Conducting a Content Analysis**            |
|-------------------------------------------------------------------|
| **Conceptualization and purpose**                                 |
| &nbsp;&nbsp;Identify the problem                                  |
| &nbsp;&nbsp;Review theory and research                            |
| &nbsp;&nbsp;Pose specific research questions and hypotheses       |
| **Design**                                                        |
| &nbsp;&nbsp;Define relevant content                               |
| &nbsp;&nbsp;Specify formal design                                 |
| &nbsp;&nbsp;Create dummy tables                                   |
| &nbsp;&nbsp;Operationalize (coding protocol and sheets)           |
| &nbsp;&nbsp;Specify population and sampling plans                 |
| &nbsp;&nbsp;Pretest and establish reliability procedures          |
| **Analysis**                                                      |
| &nbsp;&nbsp;Process data (establish reliability and code content) |
| &nbsp;&nbsp;Apply statistical procedures                          |
| &nbsp;&nbsp;Interpret and report results                          |

Bron: @riffe_analyzing_2014

Aldus zal deze paper gebruik maken van kwantitatieve inhoudsanalyse, gebaseerd op Riff en Lacy's ontwerpvoorstel (**Tabel 8.1**), op een verzameling van berichten gehaald van de publieke Twitter pagina van Makoto Sakurai. Dat als middel om Sakurai's voornaamste politieke ideologieën te categoriseren, en aldus als hulpmiddel in het beantwoorden van de onderzoeksvraag van deze paper. Voor die reden werd een typologie gecodeerd die aan de hand van een aantal kernwoorden berichten plaatst in verschillende categorieën (zie deel 5.5). De zwakte van deze methodologie ligt, naast de mogelijkheid tot foutieve correlaties, in de subjectiviteit die het opstellen van een typologie als "*lone wolf*" - één enkele onderzoeker - oplevert. ...

###Twitter datasets

####Makato Sakurai

De dataset die gebruikt wordt in de kwantitatieve inhoudsanalyse bevat de laatste 3200 publieke berichten en *retweets* geplaatst door Makoto Sakurai op Twitter-account **&commat;Doronpa01** (https://twitter.com/doronpa01) en werd samengesteld op 4/04/2017 14:00. De dataset werd samengesteld door de Twitter (REST) API recursief aan te spreken met Python tot elk tweet-bestand verzameld werd in een JSON-bestand. De limitatie van 3200 berichten werd opgelegd door de API van Twitter - naast het webscrapen van elk individueel bericht is er nog geen mogelijkheid om deze te omzeilen. Het Python-script, de rauwe data, en de CSV aan Tweets zijn online als digitale bijlage te raadplegen op https://github.com/steviepoppe/bachelor_paper. Elk Tweet-object bevat naast het bericht zelf meta-informatie die meer inzicht geeft in het leven dat het bericht leidt vanaf dat het geplaatst werd.

De dataset werd vervolgens opgekuist met **Open Refine** door voor deze paper overbodige meta-informatie te verwijderen (welke?). De in deze paper gebruikte visualisaties werden vervolgens samengesteld door middel van **Tableau**. Een interactieve visuele weergave van de gebruikte dataset valt ten slotte te raadplegen op (hier komt nog een link).

####Netto-Uyoku

Hier komt uitleg over het dataminen van Twitterberichten met *netto-uyoku*-retoriek. Gebruik van streaming API. Probleem:

    The API does not only give you access to a couple of weeks of data if you are willing to wait for it. The streaming API gives you access to 1% of Tweets posted in a real time, or 10% if you have been granted elevated access. 

## Referenties