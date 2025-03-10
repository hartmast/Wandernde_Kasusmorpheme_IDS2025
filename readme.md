# "Wandernde" Kasusmorpheme: Varianten, Fehler oder Vorboten des Sprachwandels?

Dieses Repository dokumentiert eine Nacherhebung zu der unter Hartmann (2023) verfügbaren Analyse. (Dort finden sich auch genauere Angaben zu den einzelnen Annotationskategorien in den Spreadsheets.) Für die Nacherhebung wurde gezielt nach postnominalem *wegen* gesucht, die Ergebnisse finden sich in der Datei `wegen_postnom_DECOW16A_NANO_filtered.csv` (im Ordner "wegens"). Für die Nacherhebung wurde DECOW16A-NANO genutzt, ein 990,283,505 Tokens umfassendes Subset des Korpus [DECOW16A][1] (Schäfer & Bildhauer 2012, Schäfer 2015). Um die Zahl der Fehltreffer gering zu halten, wurde nur nach Indefinit- und Definitartikeln gefolgt von einem Nomen und *wegen*, mit einem optionalen als Adjektiv getaggten Wort dazwischen, gesucht; die Suchanfrage lautete `[word="des|der|einer|eines"] [tag="A.*"]? [tag="N.*"] "wegen"`. Gegenüber den anderen in Hartmann (2023) analysierten Datensätzen hat diese Konkordanz damit den Nachteil, dass NP-Erweiterungen des Typs *des beliebten Begrüßungsabends am IDS Mannheim wegen* nicht erfasst werden.

## Dateien und Ordner

- index.qmd: Analyseskript im Quarto-Markdown-Format.
- index.html: Aus index.qmd generiertes HTML-Dokument.
- wegens: Ordner mit drei annotierten Spreadsheets im CSV-Format. Zwei sind im Repository Hartmann (2023) enthalten und dokumentiert, die dritte ist oben näher beschrieben. 


## Literatur


Hartmann, Stefan. 2023. Wandering case morphemes. Open Science Framework. https://doi.org/10.17605/OSF.IO/AUMG2.

Schäfer, Roland. 2015. Processing and querying large corpora with the COW14 architecture. In Piotr Bański, Hanno Biber, Evelyn Breiteneder, Marc Kupietz, Harald Lüngen & Andreas Witt (eds.), Challenges in the Management of Large Corpora (CMLC-3), 28–34. http://corpora.ids-mannheim.de/cmlc.html.

Schäfer, Roland & Felix Bildhauer. 2012. Building Large Corpora from the Web Using a New Efficient Tool Chain. In Nicoletta Calzolari, Khalid Choukri, Terry Declerck, Mehmet Uğur Doğan, Bente Maegaard, Joseph Mariani, Asuncion Moreno, Jan Odijk & Stelios Piperidis (eds.), Proceedings of LREC 2012, 486–493.




  [1]: https://web.archive.org/web/20170818214657/http://corporafromtheweb.org/decow16/