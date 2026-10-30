# Nidwalden: law history in git

The law of the canton of Nidwalden (Kanton Nidwalden, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-nw/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

266 acts with 482 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 150 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111/` | Verfassung des Kantons Nidwalden (NG 111) | 3 | oldest version available, then each consolidated version: 2 May 2010 to 1 January 2026 |
| `121-1-kantonales-burgerrechtsgesetz-kbug/` | Gesetz über das Kantons- und das Gemeindebürgerrecht (NG 121.1) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `122-1-nag/` | Gesetz über Niederlassung und Aufenthalt (NG 122.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 April 2025 |
| `122-2-eg-zum-auslanderrecht/` | Einführungsgesetz zum Ausländer- und Integrationsgesetz und zum Asylgesetz (NG 122.2) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 April 2025 |
| `131-1-eg-bpr/` | Einführungsgesetz zur Bundesgesetzgebung über die politischen Rechte (NG 131.1) | 1 | one version (the oldest available), 1 August 2017 |
| `132-1-proporzgesetz-propg/` | Gesetz über die Verhältniswahl des Landrates (NG 132.1) | 1 | one version (the oldest available), 1 August 2017 |
| `132-2-wahl-und-abstimmungsgesetz-wag/` | Gesetz über die politischen Rechte im Kanton (NG 132.2) | 1 | one version (the oldest available), 1 August 2017 |
| `141-1-publikationsgesetz-pug/` | Gesetz über die amtlichen Veröffentlichungen (NG 141.1) | 2 | as enacted, then each consolidated version: 1 October 2000 to 1 January 2025 |
| `151-1-landratsgesetz-lrg/` | Gesetz über die Organisation und die Geschäftsführung des Landrates (NG 151.1) | 5 | oldest version available, then each consolidated version: 1 January 2017 to 1 August 2026 |
| `152-1-regierungsratsgesetz/` | Gesetz über die Organisation des Regierungsrates und der Verwaltung (NG 152.1) | 1 | as enacted, 1 July 1998 |
| `152-5-notstandsgesetz/` | Gesetz für den Fall von Katastrophen und kriegerischen Ereignissen (NG 152.5) | 1 | one version (the oldest available), 1 January 2007 |
| `161-1-behordengesetz-behg/` | Gesetz über die kantonalen und kommunalen Behörden (NG 161.1) | 2 | oldest version available, then each consolidated version: 1 August 2017 to 1 January 2026 |
| `161-2-haftungsgesetz/` | Gesetz über die Haftung des Gemeinwesens und seiner Funktionäre (NG 161.2) | 1 | one version (the oldest available), 1 January 2011 |
| `161-3-entschadigungsgesetz-entschg/` | Gesetz über die Entschädigung der Behörden (NG 161.3) | 3 | oldest version available, then each consolidated version: 1 July 2018 to 1 January 2027 |
| `165-1-personalgesetz-persg/` | Gesetz über das öffentlich-rechtliche Arbeitsverhältnis (NG 165.1) | 5 | oldest version available, then each consolidated version: 1 January 2019 to 1 June 2026 |
| `165-2-pensionskassengesetz-pkg/` | Gesetz über die kantonale Pensionskasse (NG 165.2) | 2 | oldest version available, then each consolidated version: 1 January 2019 to 1 January 2025 |
| `171-1-gemeindegesetz-gemg/` | Gesetz über Organisation und Verwaltung der Gemeinden (NG 171.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `171-2-gemeindefinanzhaushaltgesetz-gemfhg/` | Gesetz über den Finanzhaushalt der Gemeinden (NG 171.2) | 1 | one version (the oldest available), 1 January 2016 |
| `181-1-korporationsgesetz/` | Gesetz über das Korporationsbürgerrecht, die Organisation und Verwaltung der Korporationen sowie die Nutzung des Korporationsvermögens (NG 181.1) | 1 | as enacted, 26 April 1992 |
| `191-12/` | Gesetz über die Besoldung der kantonalen Behörden, Beamten und Angestellten (Bestimmungen über den Beitrag an das Kapuzinerkloster und die Landeswallfahrten) (NG 191.12) | 1 | one version (the oldest available), 26 April 1970 |
| `211-1-einfuhrungsgesetz-zum-zivilgesetzbuch-eg-zgb/` | Gesetz über die Einführung des Schweizerischen Zivilgesetzbuches (NG 211.1) | 6 | oldest version available, then each consolidated version: 1 November 2020 to 1 July 2026 |
| `211-2-personlichkeitsschutzgesetz-pschg/` | Gesetz zum Schutz der Persönlichkeit (NG 211.2) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 March 2025 |
| `211-3-grundstuckerwerbsgesetz/` | Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (NG 211.3) | 1 | as enacted, 1 October 1999 |
| `211-4-flurgenossenschaftsgesetz-flurg/` | Gesetz über die Flurgenossenschaften (NG 211.4) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `214-1-grundbuchgesetz-gbg/` | Gesetz über das Grundbuch (NG 214.1) | 1 | one version (the oldest available), 1 July 2016 |
| `214-2-kantonales-geoinformationsgesetz-kgeoig/` | Gesetz über Geoinformation (NG 214.2) | 1 | one version (the oldest available), 1 January 2016 |
| `214-3/` | Hypothekar-Gesetz (NG 214.3) | 1 | one version (the oldest available), 1 January 1987 |
| `221-1-einfuhrungsgesetz-zum-obligationenrecht-eg-or/` | Einführungsgesetz zum Schweizerischen Obligationenrecht (NG 221.1) | 1 | as enacted, 1 July 2018 |
| `232-1-kantonales-datenschutzgesetz-kdsg/` | Gesetz über den Datenschutz (NG 232.1) | 1 | one version (the oldest available), 1 March 2010 |
| `232-2-kantonales-registerharmonisierungsgesetz-krhg/` | Gesetz über die Harmonisierung amtlicher Register (NG 232.2) | 1 | one version (the oldest available), 1 January 2013 |
| `232-3-kantonales-offentlichkeitsgesetz-kog/` | Gesetz über das Öffentlichkeitsprinzip (NG 232.3) | 1 | as enacted, 1 August 2026 |
| `251-1-kantonales-strafgesetz-kstg/` | Gesetz über das kantonale Strafrecht (NG 251.1) | 3 | as enacted, then each consolidated version: 1 January 2017 to 1 July 2025 |
| `261-1-gerichtsgesetz-gerg/` | Gesetz über die Gerichte und die Justizbehörden (NG 261.1) | 7 | oldest version available, then each consolidated version: 1 January 2021 to 1 July 2026 |
| `261-2-prozesskostengesetz-pkog/` | Gesetz über die Kosten im Verfahren vor den Gerichten und den Justizbehörden (NG 261.2) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2027 |
| `261-3-kantonales-ordnungsbussengesetz-kobg/` | Gesetz über das kantonale Ordnungsbussenverfahren (NG 261.3) | 2 | as enacted, then each consolidated version: 1 July 2025 to 1 September 2026 |
| `263-4-kantonales-opferhilfegesetz-kohg/` | Einführungsgesetz zum Bundesgesetz über die Hilfe an Opfer von Straftaten (NG 263.4) | 1 | as enacted, 1 January 2019 |
| `264-1-sozialversicherungsrechtspflegegesetz-srg/` | Gesetz über die Sozialversicherungsrechtspflege (NG 264.1) | 1 | as enacted, 1 January 2017 |
| `265-1-verwaltungsrechtspflegegesetz-vrg/` | Gesetz über das Verwaltungsverfahren und die Verwaltungsrechtspflege (NG 265.1) | 4 | oldest version available, then each consolidated version: 1 November 2020 to 1 August 2026 |
| `265-5-gebuhrengesetz-gebg/` | Gesetz über die amtlichen Kosten (NG 265.5) | 2 | oldest version available, then each consolidated version: 1 November 2020 to 1 January 2026 |
| `266-1-kantonales-enteignungsgesetz-kentg/` | Gesetz über die Enteignung (NG 266.1) | 1 | one version (the oldest available), 1 January 2015 |
| `267-1-kantonales-anwaltsgesetz-anwg/` | Gesetz über die Ausübung des Anwaltsberufes (NG 267.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2023 |
| `268-1-beurkundungsgesetz-beurkg/` | Gesetz über die öffentlichen Beurkundungen (NG 268.1) | 1 | one version (the oldest available), 1 January 2011 |
| `271-1-eg-schkg/` | Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (NG 271.1) | 1 | as enacted, 1 January 2013 |
| `271-5-eg-lugano-ubereinkommen-eg-lugu/` | Einführungsgesetz zum Übereinkommen über die gerichtliche Zuständigkeit und die Anerkennung und Vollstreckung von Entscheidungen in Zivil- und Handelssachen (NG 271.5) | 1 | as enacted, 1 January 2013 |
| `273-3-strafvollzugsgesetz-stvg/` | Gesetz über den Straf- und Massnahmenvollzug (NG 273.3) | 2 | oldest version available, then each consolidated version: 1 October 2019 to 1 January 2022 |
| `273-4-gefangnisgesetz-gefg/` | Gesetz über das kantonale Gefängnis (NG 273.4) | 1 | one version (the oldest available), 1 January 2016 |
| `311-1-bildungsgesetz-big/` | Gesetz über das Bildungswesen (NG 311.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `311-4-stipendiengesetz-stipg/` | Gesetz über die Ausbildungsbeiträge (NG 311.4) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `312-1-volksschulgesetz-vsg/` | Gesetz über die Volksschule (NG 312.1) | 3 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `313-1-kantonales-berufsbildungsgesetz-kbbg/` | Einführungsgesetz zur Bundesgesetzgebung über die Berufsbildung (NG 313.1) | 1 | one version (the oldest available), 1 January 2016 |
| `314-1-mittelschulgesetz/` | Gesetz über die kantonale Mittelschule (NG 314.1) | 1 | one version (the oldest available), 1 January 2016 |
| `319-1-sportgesetz-sportg/` | Gesetz über die Förderung von Turnen und Sport (NG 319.1) | 1 | one version (the oldest available), 1 January 2021 |
| `321-1-kulturforderungsgesetz-kfg/` | Gesetz über die Förderung des kulturellen Lebens (NG 321.1) | 1 | one version (the oldest available), 1 January 2021 |
| `322-1-kantonales-kulturguterschutzgesetz-kkgsg/` | Gesetz über den Schutz der Kulturgüter (NG 322.1) | 1 | as enacted, 1 January 2021 |
| `322-2-denkmalschutzgesetz-dschg/` | Gesetz über den Schutz der Kulturdenkmäler (NG 322.2) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 June 2024 |
| `323-1-archivierungsgesetz-archg/` | Gesetz über die Aktenführung und die Archivierung (NG 323.1) | 4 | oldest version available, then each consolidated version: 1 January 2021 to 1 August 2026 |
| `331-1-naturschutzgesetz-nschg/` | Gesetz über den Natur- und Landschaftsschutz (NG 331.1) | 1 | one version (the oldest available), 1 October 2018 |
| `421-1-kantonales-zivilschutzgesetz-kzsg/` | Einführungsgesetz zur Bundesgesetzgebung über den Zivilschutz (NG 421.1) | 1 | one version (the oldest available), 1 January 2016 |
| `431-1-kantonales-landesversorgungsgesetz-klvg/` | Einführungsgesetz zum Bundesgesetz über die wirtschaftliche Landesversorgung (NG 431.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2025 |
| `511-1-finanzhaushaltgesetz-kfhg/` | Gesetz über den Finanzhaushalt des Kantons (NG 511.1) | 2 | oldest version available, then each consolidated version: 1 October 2016 to 1 June 2026 |
| `512-1-finanzausgleichsgesetz-fag/` | Gesetz über den direkten Finanzausgleich (NG 512.1) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `513-1-kantonales-finanzkontrollgesetz-kfkg/` | Gesetz über die Finanzkontrolle (NG 513.1) | 2 | oldest version available, then each consolidated version: 1 March 2013 to 1 August 2026 |
| `521-1-steuergesetz-stg/` | Gesetz über die Steuern des Kantons und der Gemeinden (NG 521.1) | 4 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `531-1-einfuhrungsgesetz-zur-direkten-bundessteuer/` | Einführungsgesetz zum Bundesgesetz über die direkte Bundessteuer (NG 531.1) | 1 | as enacted, 1 January 2001 |
| `533-1/` | Einführungsgesetz zur Bundesgesetzgebung über die Vermeidung der internationalen Doppelbesteuerung (NG 533.1) | 1 | as enacted, 1 January 2003 |
| `611-01-baugesetz-baug/` | Gesetz über die Raumplanung und das öffentliche Baurecht (NG 611.01) | 3 | oldest version available, then each consolidated version: 1 October 2018 to 1 April 2026 |
| `611-1-planungs-und-baugesetz-pbg/` | Gesetz über die Raumplanung und das öffentliche Baurecht (NG 611.1) | 8 | oldest version available, then each consolidated version: 1 November 2020 to 1 July 2026 |
| `611-3-mehrwertabgabegesetz-mwag/` | Einführungsgesetz zum Raumplanungsgesetz betreffend Mehrwertabgabe (NG 611.3) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 January 2027 |
| `613-1-brandschutz-und-feuerwehrgesetz-bfg/` | Gesetz über den Brandschutz und die Feuerwehr (NG 613.1) | 1 | one version (the oldest available), 1 January 2019 |
| `614-1-fuss-wander-und-mountainbikeweggesetz-fwmg/` | Gesetz über die Fuss-, Wander-, und Mountainbikewege (NG 614.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 March 2026 |
| `622-1-strassengesetz-strg/` | Gesetz über den Bau und Unterhalt von Strassen und Velowegen (NG 622.1) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 July 2026 |
| `631-1-gewassergesetz-gewg/` | Gesetz über die Gewässer (NG 631.1) | 2 | as enacted, then each consolidated version: 1 November 2020 to 1 September 2024 |
| `641-1-kantonales-energiegesetz-keng/` | Gesetz über die sparsame Energienutzung und die Förderung erneuerbarer Energien (NG 641.1) | 3 | oldest version available, then each consolidated version: 1 November 2021 to 1 January 2026 |
| `641-2-kantonales-stromversorgungsgesetz-kstromvg/` | Einführungsgesetz zum Bundesgesetz über die Stromversorgung (NG 641.2) | 1 | as enacted, 1 January 2014 |
| `642-1-elektrizitatswerkgesetz-ewng/` | Gesetz über das Kantonale Elektrizitätswerk Nidwalden (NG 642.1) | 1 | one version (the oldest available), 1 November 2020 |
| `642-31/` | Gesetz betreffend die Erstellung von neuen Kraftwerkanlagen des Kantonalen Elektrizitätswerkes Nidwalden (NG 642.31) | 1 | as enacted, 29 April 1956 |
| `651-1-kantonales-strassenverkehrsgesetz-ksvg/` | Einführungsgesetz zur Bundesgesetzgebung über den Strassenverkehr (NG 651.1) | 3 | oldest version available, then each consolidated version: 1 January 2016 to 1 April 2026 |
| `651-3/` | Gesetz über die Strassenverkehrssteuern (NG 651.3) | 1 | as enacted, 1 January 2009 |
| `652-1-verkehrsgesetz-ovg/` | Gesetz über die Förderung des öffentlichen Verkehrs (NG 652.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 July 2026 |
| `654-1-schifffahrtsgesetz-kbsg/` | Einführungsgesetz zum Bundesgesetz über die Binnenschifffahrt (NG 654.1) | 1 | one version (the oldest available), 1 November 2020 |
| `711-1-gesundheitsgesetz-gesg/` | Gesetz zur Erhaltung und Förderung der Gesundheit (NG 711.1) | 4 | oldest version available, then each consolidated version: 1 January 2020 to 1 July 2026 |
| `712-1-pflegeausbildungsforderungsgesetz-pafg/` | Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (NG 712.1) | 1 | as enacted, 1 July 2024 |
| `714-1-spitalgesetz-spitg/` | Gesetz über das Kantonsspital (NG 714.1) | 1 | one version (the oldest available), 1 January 2021 |
| `717-1-lebensmittel-und-veterinargesetz-lvg/` | Gesetz über Lebensmittel und das Veterinärwesen (NG 717.1) | 1 | one version (the oldest available), 1 March 2019 |
| `721-1-kantonales-umweltschutzgesetz-kusg/` | Einführungsgesetz zum Bundesgesetz über den Umweltschutz (NG 721.1) | 1 | one version (the oldest available), 1 July 2018 |
| `732-4/` | Gesetz über die steuerbegünstigten Arbeitsbeschaffungsreserven (NG 732.4) | 1 | as enacted, 1 January 2001 |
| `741-1/` | Einführungsgesetz zum Bundesgesetz über die Alters- und Hinterlassenenversicherung (NG 741.1) | 1 | one version (the oldest available), 1 January 2008 |
| `741-3-erganzungsleistungsgesetz-kelg/` | Einführungsgesetz zum Bundesgesetz über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (NG 741.3) | 1 | one version (the oldest available), 1 January 2011 |
| `742-1-krankenversicherungsgesetz-kkvg/` | Einführungsgesetz zum Bundesgesetz über die Krankenversicherung (NG 742.1) | 4 | oldest version available, then each consolidated version: 1 January 2021 to 31 December 2025 |
| `745-1-kantonales-arbeitsvermittlungsgesetz-kavg/` | Einführungsgesetz zum Bundesgesetz über die Arbeitsvermittlung und den Personalverleih (NG 745.1) | 1 | one version (the oldest available), 1 January 2016 |
| `751-2/` | Gesetz über die Wohnbau- und Eigentumsförderung (NG 751.2) | 1 | as enacted, 1 January 1995 |
| `751-3-wohnraumforderungsgesetz-wrfg/` | Gesetz über die Förderung des preisgünstigen Wohnraumes (NG 751.3) | 1 | as enacted, 1 August 2017 |
| `761-1-sozialhilfegesetz-shg/` | Gesetz über die Sozialhilfe (NG 761.1) | 3 | oldest version available, then each consolidated version: 1 March 2019 to 1 April 2025 |
| `761-2-betreuungsgesetz-betrg/` | Gesetz über die Angebote für Personen mit besonderen Betreuungsbedürfnissen (NG 761.2) | 2 | oldest version available, then each consolidated version: 1 January 2019 to 1 February 2022 |
| `762-1-kantonales-familienzulagengesetz-kfamzg/` | Einführungsgesetz zum Gesetz über die Familienzulagen (NG 762.1) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2025 |
| `764-1-kinderbetreuungsgesetz-kibg/` | Gesetz über die familienergänzende Kinderbetreuung (NG 764.1) | 1 | one version (the oldest available), 1 January 2016 |
| `811-1-wirtschaftsforderungsgesetz-wfg/` | Gesetz über die Förderung der Wirtschaft (NG 811.1) | 1 | one version (the oldest available), 1 January 2016 |
| `821-1-kantonales-landwirtschaftsgesetz-klwg/` | Einführungsgesetz zum Bundesgesetz über die Landwirtschaft (NG 821.1) | 2 | oldest version available, then each consolidated version: 1 February 2018 to 1 January 2024 |
| `825-1-bauerliches-grundbesitzgesetz-bgbg/` | Einführungsgesetz zur Bundesgesetzgebung über den bäuerlichen Grundbesitz (NG 825.1) | 1 | as enacted, 1 February 2018 |
| `826-2-viehversicherungsgesetz-viehvg/` | Gesetz über die Viehversicherung (NG 826.2) | 1 | one version (the oldest available), 1 January 2012 |
| `826-3-hundegesetz-hug/` | Gesetz über das Halten von Hunden (NG 826.3) | 1 | one version (the oldest available), 1 January 2016 |
| `831-1-kantonales-waldgesetz-kwag/` | Einführungsgesetz zum Bundesgesetz über den Wald (NG 831.1) | 2 | oldest version available, then each consolidated version: 1 November 2020 to 1 April 2025 |
| `841-1-kantonales-jagdgesetz-kjsg/` | Einführungsgesetz zum Bundesgesetz über die Jagd und den Schutz wildlebender Säugetiere und Vögel (NG 841.1) | 1 | one version (the oldest available), 1 January 2016 |
| `842-1-fischereigesetz-kfg/` | Einführungsgesetz zum Bundesgesetz über die Fischerei (NG 842.1) | 3 | as enacted, then each consolidated version: 1 January 1969 to 1 July 2025 |
| `852-1-bergregalgesetz-brg/` | Gesetz über die Gewinnung mineralischer Rohstoffe (NG 852.1) | 1 | one version (the oldest available), 1 January 2016 |
| `853-1/` | Gesetz über die Einfuhr und den Verkauf von Salz (NG 853.1) | 1 | one version (the oldest available), 1 January 2007 |
| `854-1-gastgewerbegesetz-ggg/` | Gesetz über das Gastgewerbe und den Handel mit alkoholischen Getränken (NG 854.1) | 1 | as enacted, 1 January 2020 |
| `863-1-markt-und-reisendengesetz-mrg/` | Gesetz über die Märkte und das Reisendengewerbe (NG 863.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 July 2026 |
| `865-1-tourismusforderungsgesetz-tfg/` | Gesetz über die Förderung des Tourismus (NG 865.1) | 1 | one version (the oldest available), 1 January 2021 |
| `866-1-kantonalbankgesetz-nkbg/` | Gesetz über die Nidwaldner Kantonalbank (NG 866.1) | 1 | one version (the oldest available), 1 January 2016 |
| `867-1-sachversicherungsgesetz-nsvg/` | Gesetz über die Nidwaldner Sachversicherung (NG 867.1) | 1 | one version (the oldest available), 1 October 2020 |
| `867-3-hilfsfondsgesetz-hifg/` | Gesetz über die Vergütung nicht versicherbarer Elementarschäden (NG 867.3) | 1 | one version (the oldest available), 1 January 2019 |
| `911-0-katastropheneinsatzgesetz-kateg/` | Gesetz über den Katastropheneinsatz (NG 911.0) | 1 | one version (the oldest available), 1 July 2018 |
| `911-1-polizeigesetz-polg/` | Gesetz über das Polizeiwesen (NG 911.1) | 4 | oldest version available, then each consolidated version: 1 January 2016 to 1 April 2026 |
| `921-1-ruhetagsgesetz-rtg/` | Gesetz über die öffentlichen Ruhetage (NG 921.1) | 1 | one version (the oldest available), 1 January 2016 |
| `932-1-kantonales-geldspielgesetz-kgspg/` | Einführungsgesetz zum Bundesgesetz über Geldspiele (NG 932.1) | 1 | as enacted, 1 January 2021 |
| `121-11-kantonale-burgerrechtsverordnung-kbuv/` | Verordnung zum kantonalen Bürgerrechtsgesetz (NG 121.11) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 January 2026 |
| `122-11-nav/` | Verordnung zum Gesetz über Niederlassung und Aufenthalt (NG 122.11) | 2 | oldest version available, then each consolidated version: 1 March 2018 to 1 April 2025 |
| `122-21-auslanderverordnung-ausv/` | Verordnung zum Einführungsgesetz zum Ausländerrecht (NG 122.21) | 2 | oldest version available, then each consolidated version: 1 January 2020 to 1 April 2025 |
| `132-11-proporzverordnung-propv/` | Vollzugsverordnung zum Gesetz über die Verhältniswahl des Landrates (NG 132.11) | 2 | oldest version available, then each consolidated version: 1 August 2017 to 1 January 2026 |
| `133-12-urnenabstimmungsverordnung-uav/` | Vollzugsverordnung über Urnenabstimmungen in kommunalen Angelegenheiten (NG 133.12) | 2 | oldest version available, then each consolidated version: 1 August 2017 to 1 January 2026 |
| `141-11-publikationsverordnung-puv/` | Verordnung zum Publikationsgesetz (NG 141.11) | 3 | oldest version available, then each consolidated version: 15 May 2017 to 1 January 2025 |
| `151-11-landratsreglement-lrr/` | Reglement über die Geschäftsordnung des Landrates (NG 151.11) | 4 | oldest version available, then each consolidated version: 15 March 2018 to 1 January 2025 |
| `152-11-regierungsratsverordnung-rrv/` | Vollzugsverordnung zum Gesetz über die Organisation des Regierungsrates und der Verwaltung (NG 152.11) | 8 | oldest version available, then each consolidated version: 1 January 2021 to 1 September 2026 |
| `152-12-informationsreglement-infor/` | Reglement über die Information der Öffentlichkeit durch den Regierungsrat und die Verwaltung (NG 152.12) | 1 | one version (the oldest available), 1 January 2020 |
| `152-51-notstandsverordnung/` | Verordnung zum Gesetz für den Fall von Katastrophen und kriegerischen Ereignissen (NG 152.51) | 2 | oldest version available, then each consolidated version: 1 July 2018 to 1 January 2026 |
| `152-511-notorganisationsreglement/` | Reglement über die Notorganisation des Kantons Nidwalden (NG 152.511) | 1 | as enacted, 1 July 2004 |
| `152-512-care-reglement/` | Reglement über die Organisation CARE Nidwalden (NG 152.512) | 1 | as enacted, 1 January 2007 |
| `165-111-personalverordnung-persv/` | Verordnung zum Personalgesetz (NG 165.111) | 3 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `165-115-parkplatzbenutzungsverordnung-parkbv/` | Vollzugsverordnung zum Personalgesetz betreffend die Benützung von Parkplätzen (NG 165.115) | 1 | one version (the oldest available), 1 January 2016 |
| `165-116-verordnung-uber-das-vorschlagswesen/` | Vollzugsverordnung zum Personalgesetz betreffend das Vorschlagswesen (NG 165.116) | 1 | one version (the oldest available), 1 January 2008 |
| `165-117-lehrpersonalverordnung-lpv/` | Verordnung betreffend die Lehrpersonen (NG 165.117) | 6 | oldest version available, then each consolidated version: 1 August 2021 to 1 August 2026 |
| `171-21-gemeindefinanzhaushaltverordnung-gemfhv/` | Vollzugsverordnung zum Gesetz über den Finanzhaushalt der Gemeinden (NG 171.21) | 1 | one version (the oldest available), 1 January 2015 |
| `191-11/` | Verordnung über die Verwaltung des Diözesanfonds (NG 191.11) | 1 | one version (the oldest available), 12 January 1983 |
| `211-12-beistandsentschadigungsverordnung-bev/` | Vollzugsverordnung zum Einführungsgesetz zum Zivilgesetzbuch über die Entschädigung für Beiständinnen und Beistände (NG 211.12) | 1 | as enacted, 1 January 2013 |
| `211-15-vollziehungsverordnung-2-zum-eg-zgb/` | Vollziehungsverordnung zum Gesetz über die Einführung des Schweizerischen Zivilgesetzbuches betreffend das herrenlose Land und den Untergrund (NG 211.15) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 September 2023 |
| `211-31-grundstuckerwerbsverordnung/` | Vollzugsverordnung zum Grundstückerwerbsgesetz (NG 211.31) | 1 | one version (the oldest available), 1 March 2018 |
| `211-41-flurgenossenschaftsverordnung-flurv/` | Vollzugsverordnung zum Gesetz über die Flurgenossenschaften (NG 211.41) | 1 | as enacted, 1 November 2013 |
| `214-11-kantonale-grundbuchverordnung-kgbv/` | Vollziehungsverordnung zum Gesetz über das Grundbuch (NG 214.11) | 1 | one version (the oldest available), 1 January 2016 |
| `214-21-kantonale-geoinformationsverordnung-kgeoiv/` | Vollzugsverordnung zum kantonalen Geoinformationsgesetz (NG 214.21) | 5 | as enacted, then each consolidated version: 1 December 2012 to 1 September 2026 |
| `214-222/` | Reglement über das Meldewesen der amtlichen Vermessung (NG 214.222) | 2 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `232-21-kantonale-registerharmonisierungsverordnung-krhv/` | Vollzugsverordnung zum kantonalen Registerharmonisierungsgesetz (NG 232.21) | 1 | as enacted, 1 January 2013 |
| `261-31-kantonale-ordnungsbussenverordnung-kobv/` | Verordnung zum Kantonalen Ordnungsbussengesetz (NG 261.31) | 3 | as enacted, then each consolidated version: 1 July 2025 to 1 September 2026 |
| `263-11-kantonale-strafregisterverordnung-kstrv/` | Verordnung zur Bundesgesetzgebung über das Strafregister (NG 263.11) | 2 | oldest version available, then each consolidated version: 1 July 2015 to 1 December 2023 |
| `263-13-kantonale-dna-profil-verordnung-kdnapv/` | Einführungsverordnung zur Bundesgesetzgebung über die Verwendung von DNA-Profilen im Strafverfahren und zur Identifizierung von unbekannten oder vermissten Personen (NG 263.13) | 1 | as enacted, 1 July 2015 |
| `263-14/` | Einführungsverordnung zur Bundesgesetzgebung über die Bearbeitung biometrischer erkennungsdienstlicher Daten (NG 263.14) | 1 | as enacted, 1 July 2015 |
| `265-2-verfassungsgerichtsverordnung-vgv/` | Verordnung über das Verfahren vor dem Verfassungsgericht (NG 265.2) | 1 | one version (the oldest available), 1 January 2016 |
| `265-51-gebuhrenverordnung-gebv/` | Verordnung zum Gesetz über die amtlichen Kosten (NG 265.51) | 3 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2025 |
| `266-11-kantonale-enteignungsverordnung-kentv/` | Vollzugsverordnung zum Gesetz über die Enteignung (NG 266.11) | 1 | one version (the oldest available), 1 January 2015 |
| `267-11-anwaltsverordnung/` | Vollzugsverordnung zum Gesetz über die Ausübung des Anwaltsberufes (NG 267.11) | 2 | oldest version available, then each consolidated version: 1 March 2018 to 1 August 2023 |
| `268-11-beurkundungsverordnung-beurkv/` | Vollziehungsverordnung zum Gesetz über die öffentliche Beurkundung (NG 268.11) | 1 | one version (the oldest available), 1 January 2016 |
| `268-12-beurkundungsgebuhrenverordnung-beurkgebv/` | Verordnung über die Beurkundungsgebühren (NG 268.12) | 1 | one version (the oldest available), 1 January 2016 |
| `268-111-beurkundungsreglement-beurkr/` | Reglement über die öffentliche Beurkundung (NG 268.111) | 1 | one version (the oldest available), 1 January 2015 |
| `311-41-stipendienverordnung-stipv/` | Verordnung zum Gesetz über die Ausbildungsbeiträge (NG 311.41) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `311-52-nareg-vo/` | Verordnung zum Register über die Gesundheitsfachpersonen NAREG (NG 311.52) | 2 | oldest version available, then each consolidated version: 28 June 2018 to 1 February 2022 |
| `311-53-maturitatsanerkennungsreglement-mar/` | Reglement der EDK über die Anerkennung von gymnasialen Maturitätszeugnissen (NG 311.53) | 1 | as enacted, 1 August 2024 |
| `312-11-volksschulverordnung-vsv/` | Verordnung zum Gesetz über die Volksschule (NG 312.11) | 3 | oldest version available, then each consolidated version: 1 August 2020 to 1 August 2026 |
| `313-11-kantonale-berufsbildungsverordnung-kbbv/` | Vollzugsverordnung zum Einführungsgesetz zur Bundesgesetzgebung über die Berufsbildung (NG 313.11) | 1 | one version (the oldest available), 1 January 2020 |
| `313-12-bruckenangebotsverordnung-brav/` | Vollzugsverordnung über die Brückenangebote für schulentlassene Jugendliche (NG 313.12) | 1 | one version (the oldest available), 1 August 2018 |
| `313-13-kantonale-berufsmaturitatsverordnung-kbmv/` | Verordnung über die Berufsmaturität (NG 313.13) | 3 | oldest version available, then each consolidated version: 1 March 2018 to 1 August 2024 |
| `313-113-aufnahmeverordnung-sog-fms-avsog/` | Verordnung über die Aufnahme in schulisch organisierte Grundbildungen sowie in Fachmittelschulen (NG 313.113) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 August 2024 |
| `314-11-mittelschulverordnung-msv/` | Vollzugsverordnung zum Gesetz über die kantonale Mittelschule (NG 314.11) | 3 | oldest version available, then each consolidated version: 1 August 2020 to 1 August 2025 |
| `314-12-kantonale-maturitatsverordnung/` | Vollzugsverordnung betreffend die Maturitätsprüfung (NG 314.12) | 1 | one version (the oldest available), 1 August 2008 |
| `314-111-maturitatsarbeitsreglement-mr/` | Reglement über die Maturitätsarbeit an der kantonalen Mittelschule (NG 314.111) | 2 | as enacted, then each consolidated version: 1 August 2014 to 1 November 2025 |
| `319-11-sportverordnung/` | Vollzugsverordnung zum Gesetz über die Förderung von Turnen und Sport (NG 319.11) | 1 | as enacted, 1 January 2006 |
| `321-11-kulturforderungsverordnung/` | Vollzugsverordnung zum Gesetz über die Förderung des kulturellen Lebens (NG 321.11) | 1 | as enacted, 1 July 2004 |
| `321-111-bibliotheksreglement/` | Reglement über die Benutzung der Kantonsbibliothek (NG 321.111) | 2 | as enacted, then each consolidated version: 1 August 1996 to 1 July 2022 |
| `322-11-kantonale-kulturguterschutzverordnung-kkgsv/` | Vollzugsverordnung zum Gesetz über den Schutz der Kulturgüter (NG 322.11) | 1 | as enacted, 1 January 2021 |
| `322-21-denkmalschutzverordnung-dschv/` | Vollzugsverordnung zum Gesetz über den Schutz der Kulturdenkmäler (NG 322.21) | 2 | oldest version available, then each consolidated version: 1 March 2018 to 1 June 2024 |
| `323-11-archivierungsverordnung-archv/` | Vollzugsverordnung zum Archivierungsgesetz (NG 323.11) | 1 | one version (the oldest available), 1 March 2018 |
| `331-11-naturschutzverordnung-nschv/` | Vollzugsverordnung zum Gesetz über den Natur- und Landschaftsschutz (NG 331.11) | 1 | one version (the oldest available), 1 May 2010 |
| `331-12-pschv/` | Verordnung über Pflegebeiträge in Schutzgebieten (NG 331.12) | 1 | one version (the oldest available), 1 October 2014 |
| `331-13/` | Verordnung über den Schutz bedrohter Tiere und Pflanzen (NG 331.13) | 2 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2026 |
| `332-11-biotopschutzverordnung-bschv/` | Verordnung über den Schutz der Moore und Trockenstandorte (NG 332.11) | 2 | as enacted, then each consolidated version: 17 May 2017 to 1 September 2023 |
| `332-12/` | Verordnung über den Schutz des Gnappiriedes in der Gemeinde Stans (NG 332.12) | 1 | one version (the oldest available), 1 January 2016 |
| `332-14/` | Verordnung über den Schutz des Stansstaderriedes (NG 332.14) | 1 | one version (the oldest available), 1 January 2016 |
| `332-21-landschaftsschutzverordnung-lschv/` | Verordnung über die Landschaftsschutzzonen (NG 332.21) | 1 | one version (the oldest available), 1 January 2016 |
| `411-1-militarverordnung/` | Einführungsverordnung zum Militärgesetz und zum Militärstrafgesetz (NG 411.1) | 1 | as enacted, 1 September 2008 |
| `413-1-wehrpflichtersatzverordnung-kwpev/` | Verordnung zum Bundesgesetz über die Wehrpflichtersatzabgabe (NG 413.1) | 2 | oldest version available, then each consolidated version: 1 October 2011 to 1 January 2026 |
| `421-11-kantonale-zivilschutzverordnung/` | Vollzugsverordnung zum kantonalen Zivilschutzgesetz (NG 421.11) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `431-11-landesversorgungsverordnung-klvv/` | Vollzugsverordnung zum Kantonalen Landesversorgungsgesetz (NG 431.11) | 2 | oldest version available, then each consolidated version: 1 July 2020 to 1 January 2025 |
| `511-11-finanzhaushaltverordnung-kfhv/` | Vollzugsverordnung zum Gesetz über den Finanzhaushalt des Kantons (NG 511.11) | 1 | one version (the oldest available), 1 January 2015 |
| `511-12-iks-verordnung-iksv/` | Verordnung über das Interne Kontrollsystem (NG 511.12) | 1 | as enacted, 1 January 2021 |
| `521-11-steuerverordnung-stv/` | Verordnung zum Gesetz über die Steuern des Kantons und der Gemeinden (NG 521.11) | 6 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `531-11/` | Vollzugsverordnung zum Einführungsgesetz zur direkten Bundessteuer (NG 531.11) | 1 | one version (the oldest available), 1 January 2021 |
| `532-1-kantonale-verrechnungssteuerverordnung/` | Einführungsverordnung zum Bundesgesetz über die Verrechnungssteuer (NG 532.1) | 1 | as enacted, 1 September 2001 |
| `611-4-kantonale-zweitwohnungsverordnung-kzwv/` | Einführungsverordnung zur Bundesgesetzgebung über Zweitwohnungen (NG 611.4) | 1 | as enacted, 1 January 2016 |
| `611-011-bauverordnung/` | Vollziehungsverordnung zum Gesetz über die Raumplanung und das öffentliche Baurecht (NG 611.011) | 2 | oldest version available, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `611-11-planungs-und-bauverordnung-pbv/` | Verordnung zum Planungs- und Baugesetz (NG 611.11) | 4 | oldest version available, then each consolidated version: 1 November 2020 to 1 October 2025 |
| `611-12-reklamenverordnung-reklv/` | Verordnung über Aussen- und Strassenreklamen (NG 611.12) | 3 | oldest version available, then each consolidated version: 1 October 2018 to 1 April 2026 |
| `612-11-ivobv/` | Verordnung zum Gesetz zur Interkantonalen Vereinbarung über das öffentliche Beschaffungswesen (NG 612.11) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 May 2024 |
| `613-11-brandschutz-und-feuerwehrverordnung-bfv/` | Vollzugsverordnung zum Gesetz über den Brandschutz und die Feuerwehr (NG 613.11) | 1 | as enacted, 1 July 2018 |
| `613-12-feuerwehrentschadigungsverordnung-fev/` | Vollzugsverordnung betreffend die Entschädigung für die Angehörigen der Feuerwehr (NG 613.12) | 1 | one version (the oldest available), 1 January 2020 |
| `613-112-beitragsreglement-brandbekampfung/` | Reglement über Beitragsleistungen an die Brandbekämpfung (NG 613.112) | 1 | as enacted, 1 January 2019 |
| `614-11-mountainbikeweg-entschadigungsverordnung-mev/` | Verordnung zur Entschädigung bei der Ersterstellung von Mountainbikewegen (NG 614.11) | 1 | as enacted, 1 September 2026 |
| `621-11-kantonale-nationalstrassenverordnung-knsv/` | Einführungsverordnung zum Bundesgesetz über die Nationalstrassen (NG 621.11) | 2 | as enacted, then each consolidated version: 1 November 2021 to 1 July 2026 |
| `622-11-strassenverordnung-strv/` | Verordnung zum Strassengesetz (NG 622.11) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 July 2026 |
| `622-14-perimeterverordnung-periv/` | Vollzugsverordnung über das Perimeterverfahren (NG 622.14) | 1 | as enacted, 1 June 2016 |
| `631-11-gewasserverordnung-gewv/` | Vollzugsverordnung zum Gewässergesetz (NG 631.11) | 4 | as enacted, then each consolidated version: 1 November 2020 to 1 November 2024 |
| `641-11-kantonale-energieverordnung-kenv/` | Vollzugsverordnung zum Gesetz über die sparsame Energienutzung und die Förderung erneuerbarer Energien (NG 641.11) | 2 | as enacted, then each consolidated version: 1 November 2021 to 1 January 2022 |
| `642-12/` | Reglement über die allgemeinen Bedingungen für die Netznutzung und die Lieferung elektrischer Energie (NG 642.12) | 1 | as enacted, 1 January 2015 |
| `642-121/` | Reglement für Anschlüsse an das Verteilnetz des EWN (NG 642.121) | 1 | as enacted, 1 January 2015 |
| `651-112-parkplatzreglement/` | Reglement betreffend das Parkieren von Motorfahrzeugen auf kantonseigenen oder vom Kanton gemieteten Liegenschaften (NG 651.112) | 4 | oldest version available, then each consolidated version: 1 January 2010 to 1 March 2024 |
| `653-1/` | Verordnung über den Beitritt des Kantons Nidwalden zum Konkordat über die nicht eidgenössisch konzessionierten Luftseilbahnen und Skilifte (NG 653.1) | 1 | as enacted, 15 January 1966 |
| `653-111-reglement-ikss/` | Reglement über Bau und Betrieb der nicht eidgenössisch konzessionierten Seilbahnen und Skilifte (NG 653.111) | 1 | as enacted, 2 June 2022 |
| `654-11-schifffahrtsverordnung/` | Vollzugsverordnung zum Schifffahrtsgesetz (NG 654.11) | 2 | oldest version available, then each consolidated version: 1 March 2018 to 1 October 2024 |
| `654-12-vmrb/` | Verordnung über die Melde-, Reinigungs- und Bewilligungspflicht für Schiffe (NG 654.12) | 1 | as enacted, 1 August 2024 |
| `655-11-kantonale-luftfahrtsverordnung-klfv/` | Einführungsverordnung zur Bundesgesetzgebung über die Luftfahrt (NG 655.11) | 2 | as enacted, then each consolidated version: 1 July 2019 to 1 September 2023 |
| `711-11-gesundheitsverordnung-gesv/` | Verordnung zum Gesundheitsgesetz (NG 711.11) | 3 | oldest version available, then each consolidated version: 1 January 2020 to 1 July 2026 |
| `711-15-kantonale-passivrauchschutzverordnung-kprsv/` | Einführungsverordnung zur Bundesgesetzgebung zum Schutz vor Passivrauchen (NG 711.15) | 1 | one version (the oldest available), 1 January 2020 |
| `712-11-pflegeausbildungsforderungsverordnung-pafv/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (NG 712.11) | 1 | as enacted, 1 July 2024 |
| `714-13/` | Verordnung über den Patientenfonds des Kantonsspitals (NG 714.13) | 1 | as enacted, 1 April 2010 |
| `715-2-friedhofs-und-bestattungsverordnung-fbv/` | Vollzugsverordnung über die Friedhöfe und Bestattungen (NG 715.2) | 1 | one version (the oldest available), 1 March 2019 |
| `716-1-kantonale-betaubungsmittelverordnung-kbetmv/` | Einführungsverordnung zur Bundesgesetzgebung über die Betäubungsmittel (NG 716.1) | 2 | as enacted, then each consolidated version: 1 July 2016 to 1 July 2025 |
| `717-11-lebensmittel-und-veterinarverordnung-lvv/` | Vollzugsverordnung zum Lebensmittel- und Veterinärgesetz (NG 717.11) | 1 | as enacted, 1 January 2012 |
| `721-11-kantonale-umweltschutzverordnung-kusv/` | Vollzugsverordnung zum kantonalen Umweltschutzgesetz (NG 721.11) | 3 | oldest version available, then each consolidated version: 1 November 2020 to 1 July 2026 |
| `721-12-kantonale-chemikalienverordnung-kchemv/` | Einführungsverordnung zur Bundesgesetzgebung über den Schutz vor gefährlichen Stoffen und Zubereitungen (NG 721.12) | 2 | oldest version available, then each consolidated version: 1 January 2020 to 1 September 2023 |
| `721-13-smog-verordnung/` | Vollzugsverordnung zur kurzfristigen Bekämpfung übermässiger Luftschadstoff-Immissionen (NG 721.13) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 September 2023 |
| `731-1-kantonale-arbeitsverordnung-karv/` | Einführungsverordnung zum Bundesgesetz über die Arbeit in Industrie, Gewerbe und Handel (NG 731.1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `731-2/` | Einführungsverordnung zur Bundesgesetzgebung über die Heimarbeit (NG 731.2) | 1 | one version (the oldest available), 1 January 2016 |
| `741-2/` | Einführungsverordnung zur Bundesgesetzgebung über die Invalidenversicherung (NG 741.2) | 1 | one version (the oldest available), 1 January 2017 |
| `741-11-ausgleichskassenverordnung-akv/` | Vollziehungsverordnung zum Einführungsgesetz zum Bundesgesetz über die Alters- und Hinterlassenenversicherung (NG 741.11) | 1 | one version (the oldest available), 1 January 2016 |
| `741-31-kantonale-erganzungsleistungsverordnung-kelv/` | Vollzugsverordnung zum Einführungsgesetz zum Bundesgesetz über die Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (NG 741.31) | 1 | one version (the oldest available), 1 January 2014 |
| `741-32/` | Verordnung zur Begrenzung der anrechenbaren Pflegeheimkosten im Bereich der Ergänzungsleistungen für das Jahr 2026 (NG 741.32) | 6 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `742-2-ev-uvg/` | Einführungsverordnung zum Bundesgesetz über die Unfallversicherung (NG 742.2) | 1 | one version (the oldest available), 1 January 2017 |
| `742-12/` | Einführungsverordnung betreffend die Kostenübernahme bei Hospitalisation (NG 742.12) | 1 | as enacted, 1 January 2017 |
| `742-15/` | Vollzugsverordnung über den Datenaustausch für die Prämienverbilligung (NG 742.15) | 1 | as enacted, 1 January 2014 |
| `742-16-zulassungsverordnung-zulv/` | Verordnung betreffend die Zulassung zur Tätigkeit zulasten der obligatorischen Krankenpflegeversicherung (NG 742.16) | 3 | oldest version available, then each consolidated version: 1 January 2022 to 1 July 2025 |
| `742-111/` | Verordnung zur Prämienverbilligung für das Jahr 2026 (NG 742.111) | 6 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `742-112-pflegefinanzierungsverordnung-pfv/` | Verordnung zur Pflegefinanzierung (NG 742.112) | 4 | oldest version available, then each consolidated version: 1 January 2019 to 31 December 2025 |
| `742-116-verlustscheinverordnung-vschv/` | Vollzugsverordnung über die Verlustscheine in der obligatorischen Krankenpflegeversicherung (NG 742.116) | 1 | as enacted, 1 January 2013 |
| `744-1-arbeitslosenversicherungsverordnung-ev-avig/` | Einführungsverordnung zur Bundesgesetzgebung über die obligatorische Arbeitslosenversicherung und die Insolvenzentschädigung (NG 744.1) | 1 | one version (the oldest available), 1 January 2016 |
| `751-21-kantonale-wohnbauverordnung-kwev/` | Verordnung zum Gesetz über die Wohnbau- und Eigentumsförderung (NG 751.21) | 1 | one version (the oldest available), 1 January 2016 |
| `761-11-sozialhilfeverordnung-shv/` | Verordnung zum Gesetz über die Sozialhilfe (NG 761.11) | 7 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `761-21-betreuungsverordnung-betrv/` | Vollzugsverordnung zum Gesetz über die Angebote für Personen mit besonderen Betreuungsbedürfnissen (NG 761.21) | 2 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `762-11-kantonale-familienzulagenverordnung-kfamzv/` | Vollzugsverordnung zum kantonalen Familienzulagengesetz (NG 762.11) | 1 | one version (the oldest available), 1 January 2013 |
| `764-11-kantonale-kinderbetreuungsverordnung-kkibv/` | Vollzugsverordnung zum Kinderbetreuungsgesetz (NG 764.11) | 1 | as enacted, 1 January 2013 |
| `821-11-kantonale-landwirtschaftsverordnung-klwv/` | Verordnung zum Kantonalen Landwirtschaftsgesetz (NG 821.11) | 3 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2024 |
| `821-12-weinverordnung/` | Vollzugsverordnung über die kontrollierte Ursprungsbezeichnung für Weine (NG 821.12) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 June 2024 |
| `825-11-bauerliche-grundbesitzverordnung-bgbv/` | Verordnung zum Einführungsgesetz zur Bundesgesetzgebung über den bäuerlichen Grundbesitz (NG 825.11) | 1 | as enacted, 1 February 2018 |
| `826-31-hundeverordnung-huv/` | Vollzugsverordnung zum Gesetz über das Halten von Hunden (NG 826.31) | 1 | one version (the oldest available), 1 January 2012 |
| `831-11-kantonale-waldverordnung-kwav/` | Vollzugsverordnung zum kantonalen Waldgesetz (NG 831.11) | 4 | oldest version available, then each consolidated version: 1 November 2020 to 1 April 2025 |
| `841-11-kantonale-jagdverordnung-kjsv/` | Vollzugsverordnung zum kantonalen Jagdgesetz (NG 841.11) | 4 | oldest version available, then each consolidated version: 1 January 2020 to 15 May 2024 |
| `841-12-jagdprufungsverordnung-jpv/` | Vollzugsverordnung über den Jagdlehrgang und die Jagdprüfung (NG 841.12) | 1 | one version (the oldest available), 1 March 2018 |
| `841-13-wildschadenverordnung/` | Vollzugsverordnung über die Beiträge an Abwehrmassnahmen sowie die Schatzung und Vergütung von Wildschäden (NG 841.13) | 2 | as enacted, then each consolidated version: 15 June 2008 to 1 September 2023 |
| `841-14-kantonale-steinwildverordnung-kstwv/` | Verordnung über die Regulierung von Steinwildbeständen (NG 841.14) | 2 | oldest version available, then each consolidated version: 1 May 2016 to 15 May 2024 |
| `841-15/` | Verordnung über die Wildruhegebiete (NG 841.15) | 1 | one version (the oldest available), 1 January 2020 |
| `841-16-wsgv/` | Verordnung über die zeitlich befristeten Wildschutzgebiete (NG 841.16) | 1 | as enacted, 1 June 2013 |
| `842-11-fischereiverordnung-kfv/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Fischerei (NG 842.11) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2024 |
| `852-11-bergregalverordnung-brv/` | Vollziehungsverordnung zum Gesetz über die Gewinnung mineralischer Rohstoffe (NG 852.11) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 September 2023 |
| `854-11-gastgewerbeverordnung-ggv/` | Vollzugsverordnung zum Gesetz über das Gastgwerbe und den Handel mit alkoholischen Getränken (NG 854.11) | 1 | as enacted, 1 January 2020 |
| `855-11-kantonale-risikoaktivitatenverordnung-kriskv/` | Einführungsverordnung zum Bundesgesetz über das Bergführerwesen und Anbieten weiterer Risikoaktivitäten (NG 855.11) | 1 | one version (the oldest available), 1 January 2016 |
| `862-1-kantonale-messwesenverordnung-kmwv/` | Einführungsverordnung zur Bundesgesetzgebung über das Messwesen (NG 862.1) | 1 | one version (the oldest available), 1 January 2016 |
| `866-31-konsumkreditverordnung/` | Einführungsverordnung zum Bundesgesetz über den Konsumkredit (NG 866.31) | 1 | as enacted, 1 January 2004 |
| `866-112-partizipations-reglement/` | Reglement über die Ausgabe von Partizipationsscheinen der Nidwaldner Kantonalbank (NG 866.112) | 1 | as enacted, 1 January 2013 |
| `867-11-sachversicherungsverordnung-nsvv/` | Vollzugsverordnung zum Gesetz über die Nidwaldner Sachversicherung (NG 867.11) | 1 | one version (the oldest available), 1 January 2020 |
| `867-111-pramienreglement/` | Reglement über die Prämien und Abgaben sowie den Selbstbehalt in der obligatorischen Versicherung (NG 867.111) | 1 | as enacted, 1 January 2019 |
| `867-112/` | Reglement über die freiwillige Versicherung (NG 867.112) | 1 | as enacted, 1 January 2019 |
| `867-113-schatzungs-und-schadenreglement/` | Reglement über die Schätzung und Schadenregelung (NG 867.113) | 1 | as enacted, 1 January 2019 |
| `867-114-elementarschadenpraventionsreglement/` | Reglement über die Beitragsleistungen an die Elementarschadenprävention (NG 867.114) | 1 | as enacted, 1 January 2019 |
| `911-11-polizeiverordnung-polv/` | Verordnung zum Gesetz über das Polizeiwesen (NG 911.11) | 2 | as enacted, then each consolidated version: 1 November 2014 to 1 March 2025 |
| `922-1/` | Verordnung über das Baden in öffentlichen Gewässern (NG 922.1) | 1 | one version (the oldest available), 1 January 2016 |
| `923-11/` | Einführungsverordnung zur Gesetzgebung über Massnahmen zur Wahrung der inneren Sicherheit (NG 923.11) | 1 | as enacted, 1 January 2010 |
| `931-1-kantonale-waffenverordnung-kwv/` | Einführungsverordnung zum Bundesgesetz über Waffen, Waffenzubehör und Munition (NG 931.1) | 1 | one version (the oldest available), 1 January 2016 |
| `931-21-kantonale-sprengstoffverordnung-ksprstv/` | Verordnung zum Bundesgesetz über Sprengstoffe (NG 931.21) | 1 | as enacted, 1 April 2026 |
| `932-11-kantonale-geldspielverordnung-kgspv/` | Vollzugsverordnung zum Einführungsgesetz zum Bundesgesetz über Geldspiele (NG 932.11) | 1 | as enacted, 1 January 2021 |

## Source

The NG (systematic collection) of the canton, published by the canton at <https://gesetze.nw.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CNG). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CNG), with an e-mail address that cannot exist (`<act key>@gesetze.nw.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
