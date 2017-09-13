GCMDB 0.7.1 for cmangos tbc-db
based on GMDB 0.7

Milestone 0.7.1:

Wir bieten euch mit jedem Milestone zwei Möglichkeiten eure Datenbank zu patchen!

1. Ersetzen der englischen DB-Einträge: (GMDB_ver_0.7.1 _template.sql)
---------------------------------------
	Jeder englischer DB-Eintrag wird durch einen deutschen ersetzt.
	Die englische Sprache ist nach dem Patchvorgang nicht mehr verfügbar.
	Auch Spieler, die z. B. mit einem englischen Client connecten, finden nur die deutsche Sprache vor.
	

2. Nutzung der "locales_*" Tabellen: (/german_only/GMDB_ver_0.7.1 locales_.sql)
------------------------------------------
	Hierbei werden die "locales_*" Tabellen gefüllt!
	Nach dem Patchvorgang ist es Clientabhängig welche Sprache euch angezeigt wird!
	Z.B. wenn ihr einen englischen Client habt, wird euch alles in englischer Sprache angezeigt, 
	     habt ihr jedoch einen deutschen Client werden euch die Texte in deutscher Sprache angezeigt!
	INFO: Weitere Sprachen (wie Französisch oder Spanisch) sind nur verfügbar wenn ihr euch die entsprechenden 
	      Patchfiles besorgt (wir sind nur das Projekt für die deutsche Sprache).



Die Extra-Übersetzungen ("areatrigger_tavern", "areatrigger_teleport", "command", "transports") findet ihr in einer 
extra Datei unter /german_only/GMCDB_ver_0.7.1 extras.sql. Keine dieser Übersetzungen hat multilanguagesupport. 
Es werden also beim patchen alle englischen Einträge überschrieben!

Der Datei "GMDB_ver_0.7.1 scriptdev2.sql" übersetzt die Texte von Bossen und NPCs, die von SD2 bzw. ACID gescripted wurden.
Solltet ihr auch diese Texte übersetzt haben wollen, so müsst ihr die Datei in eure ScriptDev2 Datenbank patchen!
(Hier ist die spätere Anzeige auf Deutsch clientabhängig: 
Englischer Client = englische Sprache, deutscher Client = deutsche Sprache)

GCMDB 0.7.1 for cmangos tbc-db
based on GMDB 0.7
