{\rtf1\ansi\ansicpg1251\cocoartf2708
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww27700\viewh16380\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 Mein Ehemann und ich haben kurz gesprochen, ob es sich lohnt, eine Wohnung in Berlin oder in Hamburg zu suchen. Da laut den Ger\'e4uschen sei es fast unm\'f6glich, habe ich entschieden, die Situation in beiden St\'e4dten ein bisschen genauer zu analysieren. Daf\'fcr habe ich mir ein paar Fragen gestellt:\
1. Wie viel kostet sich ein Analog von unserer Wohnung (drei Zimmer, kein Kellner, mit Balkon ca. 90 m^2, Tempelhof-Sch\'f6neberg) in anderen Bezirken von Berlin (vor allem Sch\'f6neberg, Prenzlauer Berg, Charlottenburg)?\
2. Wie viel kostet sich ein Analog von unserer Wohnung in Hamburg je Bezirk?\
3. Wenn wir Modulationen haben wollen (z.B. vier Zimmer oder Kellner), wie \'e4ndert sich der Mietpreis?\
\
\
Aus diesen Fragen haben sich mehrere Aufgaben formuliert, die ich im Weiteren bearbeite und analysiere:\
1. Web Scraping: daf\'fcr habe ich mich f\'fcr immobilienscout24 entschieden (wurde im ersten Part gemacht)\
2. Datenanalyse\
\
Zwei Datens\'e4tze wurden f\'fcr diese Analyse benutzt. Die Daten wurden im August 2022 von ImmobilienScout24 gescrappt. Hier ist die kurze Info zu den beiden Datens\'e4tze. Beide Datens\'e4tze haben gleiche Struktur und enthalten die Informationen \'fcber die Adresse (Stra\'dfe und Bezirk), Stadt (Berlin vs. Hamburg), Preis und Gr\'f6\'dfe. Zus\'e4tzlich wurden die Einzelheiten von Wohnungsbeschreibungen als binominale Variablen (enth\'e4lt = 1, nicht enth\'e4lt = 0) gespeichert: Balkon, Terasse, Garten, Einbau-K\'fcche, Aufzug, G\'e4ste-Badezimmer, Keller, WG-geeignet. Diese Merkmale k\'f6nnen zusammen mit den vorherigen den Mietpreis beeinflussen.\
\
}