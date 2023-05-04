# Samsung Digital Wellbeing SQL-Parser (deutsch)

Die Samsung App **"Digital Wellbeing" (com.samsung.android.forest)** beinhaltet interessante forensische Informationen, die Rückschlüsse auf System- und Appaktivitäten, wie z.B. Ein- und Ausschalten, Sperren und Entsperren des Smartphones, Benachrichtigungen von Apps, usw. zu einem Samsung-Smartphone geben können.<br />
In der **dwbCommon.db** sind diese Einträge gespeichert.

Dieser Parser ermöglicht es, schnell an wichtige Daten dieser Datenbank auf einen Blick zu gelangen.<br />
Die angezeigten Zeitstempel werden in lokaler Ortzeit (also Echtzeit) ausgegeben.

Das Script wurde in Verbindung mit Infos von:<br />
https://thebinaryhick.blog/2020/02/22/walking-the-android-timeline-using-androids-digital-wellbeing-to-timeline-android-activity <br />
und<br />
https://developer.android.com/reference/android/app/usage/UsageEvents.Event<br />
erstellt.

Das Script ist in SQL geschrieben und auf deutsch. Es muss in SQL ausgeführt werden. <br />
<br />
<br />
**HowTo:**<br />
SQL Browser (DB Browser (SQLite)) im Internet herunterladen<br />
Datenbank "dwbCommon.db" öffnen<br />
Reiter "SQL ausführen" auswählen<br />
SQL-Datei öffnen (blauer Ordner, zweites Symbol von links)<br />
Mit dem "Playsymbol" (fünftes Symbol von links) das Script ausführen<br />
Das unten angezeigte Ergebnis kann als CSV exportiert werden (Diskettensymbol, achte von links)<br />
Anschließend kann die CSV-Datei beispielsweise in Excel eingeladen und ausgedruckt werden<br />

**Für Bugs, Ideen, Erweiterungen gerne melden.**<br />
<br />
<br />
Niklas Linder, 04.05.2023
