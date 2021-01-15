# Data-Preprocessing
Repository with projects of Data Preprocessing.

Some paths inside the code might have not work for path issues put in Data and Images folders, as appropiate.

Universidad Politecnica de Yucatán.

For this project, I am to make an analysis of Tweets related with the main hashtag #OctubreRosa, which makes reference to the Breast Cancer Awareness month commemorated in October 19th.


Data Import

The dataset has been obtained from two different tools. The first attempt was made on Twitter Archiver where, due to technical problems each time the rule was run, the records obtained was only 100 per file.

The hashtags used on the query for the extraction of the data in this tool were the following:
- #oncoayuda
- #donacabello
- #pelucasoncologicas
- #DiaMundialdelCancerdeMama
- #19deoctubre
- #bancodetapitas
- #cabezaenalto
- #octubrerosa

Thus, I decided to change the tool. Within IFTTT I could create and configured what is called an Applet where I had the opportunity to connect Twitter and Google Sheets in Drive to create, in a Spreadsheet, a row for each time Twitter could register a new Tweet that fulfiled with my query. In this case, I added more and more hastags, as the Applet were running, for the tool to register as much records as possible:

- #DiaMundialdelCancerdeMama
- #octubrerosa
- #breastcancerawareness
- #PinkOctober
- #donacabello
- #oncoayuda
- #pelucasoncologicas
- #PinkOktober
- #PinkMonth
- #BreastCancerAwarenessMonth
- #BreastCancer
- #FightForACure
- #BreastCancerWarrior
- #TocateParaQueNoTeToque
- #Tocate
- #FightCancer
- #cancersurvivor
- #LuchaContraElCáncerDeMama

As it can be seen, I used both English and Spanish hashtags to get the more information possible. Plus, in this tool. it is possible to write the query as long as Twitter could have done it with the Advanced Search option. Therefore, I decided to add the "since:2020-08-01" part. However, the tool only register records in real time and not as Historical Records.

'Project - Twitter.ipynb' includes Data Preprocessing.
'Project 2 - Twitter Visualization.ipynb' includes Data Visualization.
