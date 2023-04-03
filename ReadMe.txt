Mein Ehemann und ich haben kurz gesprochen, ob es sich lohnt, eine Wohnung in Berlin oder in Hamburg zu suchen. 
Unsere Wohnung hat drei Zimmer, Balkon, kein Kellner und ungefähr 90 m^2 groß. 
Und wir würden gerne entweder eine ähnliche Wohnung oder aber eine größere Wohnung mit Kellner mieten.
Dafür habe ich mir ein paar Fragen gestellt:
1. Wie hoch ist die Miete für eine ähnliche Wohnung in anderen Bezirken von Berlin (vor allem Schöneberg, Prenzlauer Berg, Charlottenburg)?
2. Wie hoch ist die Miete für eine ähnliche Wohnung in Hamburg?
3. Wenn wir Modulationen haben wollen (z.B. vier Zimmer und/oder Kellner), wie verändert sich der Mietpreis?

Aus diesen Fragen haben sich mehrere Aufgaben formuliert, die ich in diesem Projekt bearbeite und analysiere:
1. Web Scraping vom immobilienscout (Datei Web_Scrapping). Daraus sind zwei Datensätze entstanden: für Berlin und für Hamburg.
2. Datenvorbereitung (Datei Data_Preparation).
3. Datenanalyse (Datei Data_Analysis), wo ich die oben gestellten Fragen beantwortet habe.

Beide Datensätze haben gleiche Struktur und enthalten die Informationen über die Adresse (Straße und Bezirk), Stadt (Berlin vs. Hamburg), Preis und Größe.
Zusätzlich wurden die Einzelheiten von Wohnungsbeschreibungen als binominale Variablen (enthält = 1, nicht enthält = 0) gespeichert: Balkon, Terasse, 
Garten, Einbau-Küche, Aufzug, Gäste-Badezimmer, Keller, WG-geeignet. Diese Merkmale können zusammen mit den vorherigen den Mietpreis beeinflussen.
