# Texte für den Baby-Wochenbot

Diese Datei ist die Textquelle des Bots. Sie kann direkt auf GitHub im Browser bearbeitet werden.

Regeln für Änderungen:
- Jeder Abschnitt beginnt mit einer Überschrift mit zwei Rauten (`## `). Die Form der Überschrift bitte nicht ändern.
- `## Woche N · Titel` = Entwicklungstext für Woche N (bei Frühchen: korrigiertes Alter).
- `## Termine Woche N · bis Woche M` = Termine und Gesundheitshinweise ab Woche N (immer nach echtem Alter). Wer später einsteigt oder pausiert hat, bekommt den Hinweis bis Woche M nachgeliefert. Ohne „bis Woche“ gilt er 2 Wochen. Mit `· nur Frühgeborene` am Ende geht er nur an Familien, die einen errechneten Termin angegeben haben. Pro Woche sind mehrere Blöcke erlaubt.
- `## Einstieg` = das Wichtigste aus den ersten Wochen; geht einmalig an Familien, die sich erst nach der ersten Lebenswoche anmelden.
- `## Saison ID · Monate X, Y · bis Woche N` = jahreszeitlicher Hinweis, einmal pro Jahr, solange das Baby höchstens N Wochen alt ist.
  Optional mit `· geboren Monate A, B, …` am Ende: dann nur für Babys, die in diesen Monaten geboren wurden, und nur einmal pro Kind.
- `**fett**` wird in Telegram fett dargestellt. Andere Formatierungen werden als normaler Text gezeigt.
- Alles oberhalb der ersten Überschrift (dieser Absatz) wird ignoriert.
- `## Oberfläche` enthält die kurzen Texte des Bots (Anmeldung, Knöpfe, Hilfe). Format: `schluessel: Text`. Die Schlüssel links vom Doppelpunkt nicht ändern, nur den Text rechts. `\n` erzeugt einen Zeilenumbruch, Platzhalter wie `{n}` oder `{url}` bitte stehen lassen.
- Für eine neue Sprache wird diese Datei kopiert und übersetzt (z. B. als `tr.md`). Die Überschriften (`## Woche 5 · …`, `## Termine Woche 8`, `## Oberfläche` usw.) bleiben dabei auf Deutsch, nur die Titel hinter dem Punkt und die Texte werden übersetzt.

Aufbau der Wochennachrichten: ein Hauptthema, danach „Was sonst gerade läuft“ mit Punkten aus den Bereichen Beziehung, Motorik, Schlaf, Schreien, Spiel, Sprache, Trinken & Essen, Wachstum sowie Trocken & sauber.

Zusätzliche Quellen für diese Bereiche (Auswahl): Iglowstein, Jenni, Molinari & Largo, Sleep duration from infancy to adolescence, Pediatrics 2003 · Largo & Stützle, Longitudinal study of bowel and bladder control, Dev Med Child Neurol 1977 · Largo et al., Development of bladder and bowel control (Zürcher Longitudinalstudien) · Schaffer & Emerson, The development of social attachments in infancy, 1964 · Mampe et al., Newborns' cry melody is shaped by their native language, Curr Biol 2009 · Fernald, Approval and disapproval: infant responsiveness to vocal affect, Child Dev 1993 · Price et al., Five-year follow-up of harms and benefits of behavioral infant sleep intervention, Pediatrics 2012 · Sosa, Association of the type of toy used during play with the quantity and quality of parent-infant communication, JAMA Pediatr 2016 · Taveras et al., Crossing growth percentiles in infancy, Arch Pediatr Adolesc Med 2011 · Netzwerk Gesund ins Leben, Handlungsempfehlungen zur Säuglingsernährung.

Quellen für die Praxis- und Faktencheck-Punkte (Auswahl): DeLoache et al., Do babies learn from baby media?, Psychol Sci 2010 · Kirk et al., To sign or not to sign?, Child Dev 2013 · Dowdall et al., Shared picture book reading interventions, Child Dev 2020 · Needham et al., Sticky mittens, Infant Behav Dev 2002; Libertus et al., Dev Sci 2016 · Hunziker & Barr, Increased carrying reduces infant crying, Pediatrics 1986; St James-Roberts et al., Pediatrics 1995 · Johnson et al., Infantile colic: recognition and treatment, Am Fam Physician 2015 · Sung et al., L. reuteri meta-analysis, Pediatrics 2018 · van Wijk et al., Helmet therapy RCT, BMJ 2014 · Bennett et al., Massage for infants, Cochrane 2013 · Corbeil, Trehub & Peretz, Singing delays the onset of infant distress, Infancy 2016 · Gerry, Unrau & Trainor, Active music classes in infancy, Dev Sci 2012 · Dauch et al., Fewer toys, Infant Behav Dev 2018 · Romeo et al., Beyond the 30-million-word gap, Psychol Sci 2018 · Tamis-LeMonda et al., Maternal responsiveness and language milestones, Child Dev 2001 · Kramer et al., PROBIT, Arch Gen Psychiatry 2008 und Folgestudie mit 16 Jahren · Neuman et al., Can babies learn to read?, J Educ Psychol 2014 · Taylor et al. / Fangupo et al., BLISS-Studie, JAMA Pediatr 2017 / Pediatrics 2016.

Quellen zu Stilldauer, Beikost und Babyschlaf (Stand 2026): AWMF S3-Leitlinie „Stilldauer und Interventionen zur Stillförderung“ (027-072, Februar 2026) mit Sondervoten von DGEM und BVKJ · Blair et al., Bed-sharing in the absence of hazardous circumstances, PLoS One 2014 · Blair, Ball, Pease & Fleming, Bed-sharing and SIDS: an evidence-based approach, Arch Dis Child 2023 · Tappin et al., Bed-sharing is a risk for sudden unexpected death in infancy, Arch Dis Child 2023 · Academy of Breastfeeding Medicine, Protokoll Nr. 6 (Bedsharing and Breastfeeding, 2019) · BIÖG/kindergesundheit-info.de, Sicher schlafen und Schlafumgebung · Europäisches Institut für Stillen und Laktation, Sicherer Babyschlaf (03/2026).

## Willkommen

Hallo! Ich bin euer Baby-Wochenbot. Ab jetzt melde ich mich einmal pro Woche, und zwar am Wochentag, an dem euer Baby geboren wurde. Ihr bekommt dann, was entwicklungsmäßig gerade typischerweise passiert, wie gut das wissenschaftlich belegt ist, eine kleine Idee für den Alltag und Hinweise auf anstehende U-Untersuchungen und Impfungen.

**Drei Dinge vorab:**

**1. Jedes Kind hat sein eigenes Tempo.** Wenn ich schreibe, dass etwas „jetzt“ passiert, heißt das: um diese Zeit herum, bei vielen Kindern. Die normale Spannbreite ist oft riesig. Beim freien Laufen liegt sie zum Beispiel zwischen gut 8 und fast 18 Monaten (WHO-Studie). Die Meilenstein-Listen, die ich zitiere (US-Gesundheitsbehörde CDC, 2022), beschreiben, was etwa 75 % der Kinder in einem Alter können. Jedes vierte Kind ist also noch nicht so weit, und das ist normal.

**2. Wann ihr nicht abwarten solltet:** wenn euer Baby Fähigkeiten wieder verliert, die es schon sicher konnte, oder wenn ihr ein anhaltend ungutes Gefühl habt. Körperlich gilt: Fieber ab 38 °C in den ersten drei Lebensmonaten, trinkt kaum, ist auffallend schlapp oder schwer weckbar, atmet angestrengt → am selben Tag zur Kinderärztin. Nachts und am Wochenende hilft der ärztliche Bereitschaftsdienst unter 116 117, im Notfall die 112.

**3. Ich bin nur ein Bot** und kann nicht antworten. Hebamme und Kinderarztpraxis ersetze ich nicht.

**Zur Beleglage** schreibe ich jeweils dazu, wie sicher etwas ist: „gut belegt“ (mehrere gute Studien oder Übersichtsarbeiten), „einzelne Studie“, „Studienlage gemischt“ (Studien widersprechen sich) oder „Erfahrungswissen, kaum untersucht“ (plausibel, aber nicht wissenschaftlich geprüft).

## Oberfläche

sprache_name: 🇩🇪 Deutsch
bot_beschreibung: Einmal pro Woche eine kurze Nachricht zur Entwicklung eures Babys im ersten Lebensjahr: was gerade passiert, wie gut das belegt ist, Ideen für den Alltag und anstehende Vorsorgetermine. Kostenlos, ohne Werbung. Tippt unten auf „Starten“.
bot_kurzbeschreibung: Wöchentliche Infos zur Entwicklung eures Babys im ersten Lebensjahr.
frage_sprache: 🌍 Bitte wählt eure Sprache.
datenschutz: Schön, dass ihr da seid! Kurz zum Datenschutz, bevor es losgeht: Ich speichere nur eure Chat-ID, die gewählte Sprache, das Geburtsdatum eures Babys und, falls ihr ihn angebt, den errechneten Geburtstermin. Mehr braucht der Bot nicht. Mit /delete könnt ihr jederzeit alles vollständig löschen.\n\nAlle Details: {url}
knopf_einverstanden: ✅ Einverstanden
frage_geburtsdatum: Wann wurde euer Baby geboren? Schreibt das Datum bitte so: 14.08.2026
datum_ungueltig: Das Datum konnte ich leider nicht lesen. Bitte schreibt es so: 14.08.2026
datum_zukunft: Dieses Datum liegt in der Zukunft. Der Bot startet ab der Geburt. Meldet euch gern wieder, wenn euer Baby da ist!
datum_zu_alt: Euer Baby ist schon älter als ein Jahr. Der Bot begleitet nur das erste Lebensjahr. Herzlichen Glückwunsch zu diesem Meilenstein!
frage_frueh: Kam euer Baby mehr als drei Wochen vor dem errechneten Geburtstermin zur Welt?
knopf_ja: Ja
knopf_nein: Nein
frage_et: Wann war der errechnete Geburtstermin? Schreibt das Datum bitte so: 14.08.2026
et_ungueltig: Der errechnete Termin muss nach dem Geburtsdatum liegen, höchstens 20 Wochen später. Bitte prüft das Datum noch einmal.
fertig: Alles eingerichtet! Ab jetzt kommt jeden {wochentag} morgens eine Nachricht. Mit /help seht ihr, was ich sonst noch kann.
geaendert: Die Daten sind aktualisiert. Hier ist die Nachricht zur aktuellen Woche.
wochentage: Sonntag, Montag, Dienstag, Mittwoch, Donnerstag, Freitag, Samstag
kopf_woche0: 👶 **Euer Baby ist in der ersten Lebenswoche**
kopf_woche1: 👶 **Euer Baby ist jetzt 1 Woche alt**
kopf_wochen: 👶 **Euer Baby ist jetzt {n} Wochen alt**
korrigiert: Korrigiertes Alter: {k} Wochen. Darauf beziehen sich die Entwicklungsinfos.
vor_et: Rechnerisch sind es noch {tage} Tage bis zum errechneten Geburtstermin. Die Entwicklungsinfos starten ab dem errechneten Termin, bis dahin gibt es nur Termine und Hinweise.
termine_titel: 📅 **Termine & Gesundheit**
hilfe: So könnt ihr mich steuern:\n/week – die aktuelle Wochennachricht noch einmal\n/change – Geburtsdatum ändern\n/language – Sprache wechseln\n/pause – Nachrichten pausieren\n/resume – Nachrichten fortsetzen\n/delete – alle Daten löschen\n\nIch bin ein Bot und kann auf Fragen leider nicht antworten. Bei Sorgen um euer Baby helfen Hebamme und Kinderarztpraxis, nachts und am Wochenende der Bereitschaftsdienst unter 116 117, im Notfall die 112.
befehl_week: Aktuelle Wochennachricht
befehl_change: Geburtsdatum ändern
befehl_language: Sprache wechseln
befehl_pause: Nachrichten pausieren
befehl_resume: Nachrichten fortsetzen
befehl_delete: Alle Daten löschen
befehl_help: Hilfe
schon_angemeldet: Ihr seid schon angemeldet. Mit /week kommt die aktuelle Nachricht noch einmal, mit /change ändert ihr das Geburtsdatum.
nicht_angemeldet: Ihr seid noch nicht angemeldet. Mit /start geht es los.
pausiert: Die Nachrichten sind pausiert. Mit /resume geht es weiter.
fortgesetzt: Es geht weiter! Die nächste Nachricht kommt wie gewohnt am {wochentag}.
loeschen_frage: Wirklich alle Daten löschen? Danach bekommt ihr keine Nachrichten mehr.
knopf_loeschen: 🗑️ Ja, alles löschen
knopf_abbrechen: Abbrechen
geloescht: Alle Daten sind gelöscht. Alles Gute für euch! Mit /start könnt ihr jederzeit neu beginnen.
abgebrochen: Alles bleibt, wie es war.
sprache_gewechselt: Die Sprache ist jetzt Deutsch.
unbekannt: Ich bin ein Bot und kann auf Nachrichten leider nicht antworten. Mit /help seht ihr, was ich kann.
abschluss: Die Begleitung durch das erste Lebensjahr ist abgeschlossen. Danke, dass ihr dabei wart!

## Einstieg

**Ihr steigt nicht ganz am Anfang ein.** Deshalb hier kurz das Wichtigste aus den ersten Wochen, das fürs ganze erste Jahr gilt:

• **Sicherer Schlaf:** Rückenlage, Schlafsack, feste Matratze ohne Kissen und Kuscheltiere, rauchfrei, nicht zu warm (16 bis 18 °C), Baby im Elternschlafzimmer. Nicht gemeinsam mit dem Baby auf Sofa oder Sessel einschlafen (gut belegt). Ob eigenes Bett, Beistellbett oder Familienbett, darüber sind sich Fachleute nicht einig. Deutlich gefährlicher ist gemeinsames Schlafen aber nach Rauchen, Alkohol, Drogen oder müde machenden Medikamenten und bei Frühgeborenen (gut belegt).
• **Niemals schütteln.** Wenn ihr an eure Grenze kommt: Baby sicher ins Bett legen, kurz rausgehen, jemanden anrufen. Unterstützung gibt es auch beim kostenlosen Elterntelefon unter 0800 111 0 550.
• **Stuhlfarbe:** Sehr heller, lehmfarbener oder grauweißer Stuhl kann auf eine seltene, aber eilige Erkrankung der Gallenwege hinweisen. Vergleicht mit der Stuhlkarte im gelben Heft und geht dann zeitnah zur Kinderärztin.
• **Und ihr?** Hält eine gedrückte Stimmung länger als etwa zwei Wochen an, sprecht mit Hebamme, Hausärztin oder Gynäkologin. Eine Depression nach der Geburt ist häufig und gut behandelbar.

Termine und Impfungen, die jetzt noch aktuell sind, stehen in der Nachricht gleich im Anschluss.

## Woche 0 · Ankommen

Die erste Lebenswoche ist vor allem Umstellung: Atmung, Kreislauf, Verdauung und Temperaturregulation laufen zum ersten Mal ganz ohne Plazenta. Dass Neugeborene in den ersten Tagen etwas Gewicht verlieren, ist normal. Meist ist das Geburtsgewicht nach 10 bis 14 Tagen wieder erreicht, die Hebamme behält das im Blick.

Die Sinne sind unterschiedlich weit. Hören funktioniert schon gut, und Neugeborene erkennen nachweislich die Stimme ihrer Mutter, die sie aus dem Bauch kennen. Sehen ist dagegen noch sehr unscharf. Am besten klappt es auf etwa 20 bis 30 Zentimeter, ziemlich genau der Abstand zum Gesicht beim Stillen oder Fläschchengeben.

Vieles, was euer Baby jetzt tut, sind angeborene Reflexe: Suchen und Saugen, das feste Umklammern eures Fingers, das Zusammenzucken mit ausgebreiteten Armen bei Geräuschen (Moro-Reflex). Diese Reflexe verschwinden in den nächsten Monaten und machen gezielten Bewegungen Platz.

⚠️ **Sicherer Schlaf** (gut belegt, gilt fürs ganze erste Jahr): immer in Rückenlage, im Schlafzimmer der Eltern, im Schlafsack statt unter einer Decke, auf einer festen Matratze ohne Kissen, Nestchen oder Kuscheltiere, rauchfrei und nicht zu warm (etwa 16 bis 18 °C). Außerdem wird empfohlen, nicht gemeinsam mit dem Baby auf dem Sofa oder im Sessel einzuschlafen, da es dort in eine Lücke zwischen Polster und Körper rutschen oder in eine Lage geraten kann, in der es schlecht Luft bekommt. Das gehört zu den am deutlichsten belegten Risiken (gut belegt). Wach mit dem Baby zu kuscheln oder es in der Trage oder auf dem Bauch zu haben, während ihr auf dem Sofa entspannt, ist dagegen kein Problem. Merkt ihr, dass euch die Augen zufallen, legt euer Baby in sein Bett oder geht zusammen ins Bett. Das ist die sicherere Wahl.

🔬 **Eigenes Bett oder Familienbett?** Hier sind sich Fachleute nicht einig, und das wollen wir offen sagen. Offizielle deutsche Stellen (BIÖG, DGKJ) empfehlen vorrangig ein eigenes Bett oder ein Beistellbett im Elternschlafzimmer. Viele Still- und Schlafforschende sehen es differenzierter: Gemeinsames Schlafen erleichtert das nächtliche Stillen deutlich, und Stillen senkt das Risiko für den plötzlichen Kindstod ungefähr um die Hälfte. In Auswertungen britischer Studien (Blair und Kollegen) war das gemeinsame Bett vor allem dann gefährlich, wenn weitere Risikofaktoren dazukamen. Ohne diese fand sich kein messbar erhöhtes Risiko. Andere Forschende (etwa Tappin, Mitchell und Kollegen) sehen vor allem bei Babys unter drei Monaten trotzdem ein kleines Restrisiko (Studienlage gemischt).

⚠️ Einig sind sich alle Seiten, wann gemeinsames Schlafen **deutlich gefährlicher** ist (gut belegt): wenn jemand im Bett raucht oder in der Schwangerschaft geraucht wurde, nach Alkohol, Drogen oder müde machenden Medikamenten, bei völliger Übermüdung, wenn euer Baby zu früh oder sehr leicht geboren wurde oder wenn es nicht gestillt wird.

**Wenn ihr gemeinsam schlaft:** feste Matratze ohne Spalt zur Wand, Baby auf dem Rücken neben der stillenden Mutter und nicht zwischen den Eltern, im eigenen Schlafsack ohne Erwachsenendecke und Kissen in der Nähe, keine Geschwister oder Haustiere mit im Bett. Ein Beistellbett verbindet Nähe und eigenen Schlafplatz. Entscheidet bewusst, was zu euch passt, und sprecht gern mit eurer Hebamme darüber.

💡 Mehr braucht es gerade nicht: Nähe, Hautkontakt, euer Gesicht und eure Stimme. „Förderprogramme“ sind in diesem Alter überflüssig.

📚 **Was sonst gerade läuft**

• **Trinken & Essen:** In den ersten Wochen trinken Babys meist 8 bis 12 Mal in 24 Stunden, oft unregelmäßig. Frühe Hungerzeichen sind Suchen mit dem Mund, Schmatzen und die Hand zum Mund. Weinen ist ein eher spätes Signal.
• **Trocken & sauber:** Der erste Stuhl (Mekonium) ist schwarzgrün und klebrig. In den ersten Tagen wird er grünlich und dann, bei Muttermilch, senfgelb.
• **Wachstum:** Gesunde reife Neugeborene wiegen meist zwischen 2,5 und 4 Kilo und sind um die 50 Zentimeter lang. Die Geburtsmaße sagen vor allem etwas über die Bedingungen im Bauch aus, weniger über die spätere Größe.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Reagiert auf die Signale eures Babys, also Hunger, Müdigkeit und den Wunsch nach Nähe. Nach heutigem Forschungsstand verwöhnt schnelles Trösten nicht.
• **Spielidee:** Hautkontakt, euer Gesicht auf 20 bis 30 cm, leise sprechen oder summen. Mehr „Programm“ braucht es nicht.
• **Kaufen?** Zum Fördern nichts. Wichtig sind ein sicherer Schlafplatz, ein Schlafsack in passender Größe und eine Babyschale fürs Auto.

## Woche 1 · Rhythmus? Noch nicht.

Neugeborene schlafen viel, grob 14 bis 17 Stunden am Tag, aber in kurzen Etappen, verteilt über Tag und Nacht. Eine innere Uhr mit Tag-Nacht-Rhythmus entwickelt sich erst über die nächsten Wochen und Monate. Dass euer Baby nachts genauso oft wach ist wie tagsüber, ist also kein Fehler, sondern Biologie.

Häufig in diesen Tagen ist die **Neugeborenengelbsucht**. Sie beginnt meist ab dem zweiten oder dritten Tag und ist in der Regel harmlos. Ärztlich abklären lassen solltet ihr sie, wenn euer Baby sehr gelb wird, die Gelbfärbung nach der ersten Woche zunimmt oder es auffallend schläfrig ist und schlecht trinkt.

⚠️ Schaut euch die **Stuhlkarte** im gelben Kinderuntersuchungsheft an. Sehr heller, lehmfarbener oder grauweißer Stuhl kann auf eine seltene, aber eilige Erkrankung der Gallenwege hinweisen. Dann bitte zeitnah zur Kinderärztin.

💡 Tagsüber Tageslicht und Alltagsgeräusche, nachts gedämpftes Licht und wenig Unterhaltung: Das hilft der inneren Uhr beim Einstellen.

📚 **Was sonst gerade läuft**

• **Beziehung:** Bindung entsteht nicht in einem kurzen Zeitfenster direkt nach der Geburt. Die Annahme einer entscheidenden „Prägungsphase“ hat sich nicht bestätigt. War der Start holprig, etwa nach Kaiserschnitt oder Klinikaufenthalt, wächst die Bindung trotzdem über Wochen und Monate im Alltag.
• **Trocken & sauber:** Ab etwa dem fünften Tag sind fünf bis sechs oder mehr richtig nasse Windeln pro Tag ein gutes Zeichen dafür, dass euer Baby genug trinkt. Der Urin sollte hell sein.
• **Motorik:** Die zappeligen, fließenden Ganzkörperbewegungen von Neugeborenen heißen „General Movements“. Ihre Qualität ist so aussagekräftig, dass Fachleute sie zur Früherkennung von Bewegungsstörungen nutzen.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Lernt die „Sprache“ eures Babys: Gähnen, Wegschauen, Zappeln oder Überstrecken heißen oft „genug für jetzt“ (Erfahrungswissen, kaum untersucht).
• **Kaufen?** Ein Tragetuch oder eine Trage ist praktisch für Nähe mit freien Händen. Achtet darauf, dass das Gesicht frei ist, das Kinn nicht auf der Brust liegt und euer Baby aufrecht und eng am Körper sitzt.

## Woche 2 · Dauernuckeln am Abend

Viele Babys haben jetzt Phasen, meist abends, in denen sie gefühlt stundenlang trinken wollen, kurz schlafen und wieder trinken („Clusterfeeding“). Das ist verbreitet und kein Zeichen dafür, dass die Milch nicht reicht. Ob euer Baby genug bekommt, zeigen eher nasse Windeln, die Gewichtszunahme und ein zufriedener Eindruck zwischendurch. Die Hebamme kann das gut beurteilen.

🔬 **Wachstumsschübe?** Oft hört man von festen Schub-Wochen. Messstudien zeigen tatsächlich, dass Babys eher sprunghaft als gleichmäßig wachsen. Wann ein Schub kommt, lässt sich aber nicht an festen Wochen vorhersagen.

**Und ihr?** Ein Stimmungstief mit viel Weinen in den ersten Tagen nach der Geburt („Babyblues“) ist sehr häufig und vergeht meist nach einigen Tagen. Hält die Niedergeschlagenheit länger als etwa zwei Wochen an oder ist sie sehr stark, kann eine postpartale Depression dahinterstecken. Sie betrifft etwa 10 bis 15 % der Mütter, auch Väter können erkranken, und sie ist gut behandelbar. Sprecht dann mit Hebamme, Hausärztin oder Gynäkologin. Informationen gibt es bei schatten-und-licht.de

💡 Hilfe annehmen ist kein Luxus: Essen vorbeibringen lassen, Besuch begrenzen, schlafen, wann immer es geht.

📚 **Was sonst gerade läuft**

• **Sprache:** Neugeborene weinen mit der Sprachmelodie ihrer Umgebung. In einer Studie (Mampe und Kollegen, 2009) hatten deutsche Neugeborene eher fallende, französische eher steigende Schreimelodien. Sprachlernen beginnt also schon im Bauch.
• **Wachstum:** Ist das Geburtsgewicht wieder erreicht, legen Babys in den ersten Monaten häufig 150 bis 250 Gramm pro Woche zu. Einzelne Wochen können deutlich darüber oder darunter liegen.
• **Trocken & sauber:** Muttermilchstuhl ist gelb, weich bis flüssig und kommt anfangs oft nach fast jeder Mahlzeit. Bei Säuglingsnahrung ist er meist fester und bräunlicher.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Singt! Welche Lieder, ist egal, und schief ist auch in Ordnung. Babys mögen die vertraute Stimme mehr als perfekte Musik.
• **Darauf eingehen:** Bei langen Trinkabenden: bequemen Platz einrichten, Wasser und Snack für euch griffbereit, Serie oder Hörbuch an. Euer Wohlbefinden zählt mit.

## Woche 3 · Gesichter sind das Spannendste

Schon Neugeborene schauen bevorzugt auf gesichtsähnliche Muster, also zwei Punkte oben und einen darunter. Jetzt werden die Blicke länger und gezielter. Viele Babys fixieren euer Gesicht und folgen kurz, wenn ihr euch langsam bewegt.

🔬 **Ein Beispiel dafür, warum Einordnung wichtig ist:** 1977 berichteten Forscher, dass Neugeborene es nachmachen, wenn man ihnen die Zunge herausstreckt. Das stand jahrzehntelang in Lehrbüchern. Eine große Studie von 2016 mit über 100 Babys konnte den Effekt aber nicht bestätigen. Ob Neugeborene wirklich nachahmen, ist heute offen.

💡 Probiert es trotzdem: Gesicht auf 20 bis 30 cm, Zunge raus, Mund auf, lächeln, und dann warten. Ob euer Baby nachmacht oder nicht, es findet euch faszinierend.

📚 **Was sonst gerade läuft**

• **Schreien:** Viele Eltern hoffen, am Klang zu erkennen, ob ihr Baby Hunger hat oder Bauchweh. Studien zeigen, dass das nur begrenzt gelingt. Hilfreicher ist der Zusammenhang: Wann wurde zuletzt getrunken, geschlafen, gewickelt?
• **Trinken & Essen:** Wasser oder Tee braucht ein Baby, das gestillt wird oder Säuglingsnahrung bekommt, nicht, auch nicht bei Hitze. Die Milch deckt den Flüssigkeitsbedarf vollständig.
• **Beziehung:** Auch der zweite Elternteil wird schnell zur vertrauten Person. Hautkontakt, Tragen, Baden und Wickeln sind gute Gelegenheiten, ganz unabhängig davon, wer füttert.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Bewegt euer Gesicht oder ein kontrastreiches Tuch langsam von einer Seite zur anderen, damit euer Baby mit den Augen folgen kann. Ein bis zwei Minuten reichen.
• **Kaufen?** Schwarz-weiße Kontrastkarten schaden nicht, einen belegten Förderwert haben sie aber nicht (Erfahrungswissen, kaum untersucht). Euer Gesicht ist spannender.
• **Darauf eingehen:** Schaut euer Baby weg, ist das kein Desinteresse, sondern eine Pause. Wartet, bis es von selbst wieder Blickkontakt sucht.

## Woche 4 · Bauchzeit

Auf dem Rücken schlafen, auf dem Bauch spielen: Das ist die Faustregel. In Bauchlage üben Babys, den Kopf zu heben, und kräftigen Nacken, Schultern und Rücken. Außerdem beugt Bauchzeit einem abgeflachten Hinterkopf vor, der durch viel Rückenlage entstehen kann.

Die WHO empfiehlt für Babys, die sich noch nicht selbst fortbewegen, über den Tag verteilt mindestens 30 Minuten Bauchlage, im Wachzustand und unter Aufsicht. Das darf gern in vielen Mini-Portionen passieren.

Viele Babys protestieren anfangs. Das ist normal, und ein, zwei Minuten reichen am Anfang völlig.

💡 Der einfachste Einstieg: Legt euch halb zurückgelehnt hin und euer Baby bäuchlings auf eure Brust. Euer Gesicht ist die beste Motivation, den Kopf zu heben.

📚 **Was sonst gerade läuft**

• **Schlaf:** Die Zürcher Longitudinalstudien (Iglowstein, Largo und Kollegen, 2003) zeigen, wie verschieden der Schlafbedarf ist. Selbst zwischen den Kindern der mittleren Hälfte lagen mit sechs Monaten zweieinhalb Stunden Unterschied. Euer Baby braucht also vielleicht deutlich mehr oder weniger Schlaf als andere.
• **Spiel:** Spielen heißt in diesem Alter vor allem schauen, lauschen, Gesichter entdecken. Babys zeigen, wenn es genug ist, etwa durch Wegschauen, Gähnen oder Quengeln. Dann hilft eine Pause.
• **Wachstum:** Der Kopf wächst jetzt besonders schnell, in den ersten Monaten um etwa zwei Zentimeter pro Monat. Deshalb wird der Kopfumfang bei jeder U-Untersuchung gemessen.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Bauchzeit geht nicht nur auf dem Boden: auf eurer Brust, quer über euren Oberschenkeln oder im „Fliegergriff“ beim Herumtragen.
• **Gegenstände:** Ein zusammengerolltes Handtuch unter der Brust erleichtert manchen Babys das Kopfheben, natürlich nur unter Aufsicht (Erfahrungswissen, kaum untersucht).
• **Kaufen?** Spielbogen oder Krabbeldecke sind nett, aber nicht nötig. Eine Decke am Boden reicht.

## Woche 5 · Viel Weinen: Was ist normal?

In diesen Wochen weinen und quengeln Babys im Durchschnitt am meisten. Eine große Auswertung von 28 Studien mit rund 8.700 Babys (Wolke und Kollegen, 2017) fand: In den ersten sechs Wochen sind es im Schnitt etwa zwei Stunden pro Tag, mit einer enormen Spannbreite von einer halben bis über fünf Stunden. Nach etwa acht bis neun Wochen geht es deutlich zurück, mit drei Monaten hat es sich im Schnitt ungefähr halbiert.

🔬 **Und die „Sprünge“?** Das Buch „Oje, ich wachse!“ verortet hier den ersten Entwicklungssprung. Unruhige Phasen gibt es wirklich. Dass sie bei allen Babys in festen Wochen kommen, wurde aber nur an kleinen Gruppen untersucht und ist nicht verlässlich belegt. Die große Auswertung oben fand zum Beispiel keinen einheitlichen Schreigipfel in genau derselben Woche.

⚠️ **Niemals schütteln.** Schon kurzes Schütteln kann lebensgefährliche Hirnverletzungen verursachen. Wenn ihr merkt, dass ihr an eure Grenze kommt: Baby sicher in sein Bett legen, kurz rausgehen, durchatmen, jemanden anrufen. Unterstützung gibt es in Schreiambulanzen (die Kinderarztpraxis kennt welche) und beim kostenlosen Elterntelefon unter 0800 111 0 550.

💡 Weniger ist oft mehr: Tragen, gedämpftes Licht, gleichmäßiges Rauschen oder Summen, statt ständig Neues auszuprobieren.

📚 **Was sonst gerade läuft**

• **Trinken & Essen:** Viele Babys spucken nach dem Trinken etwas Milch aus. Das ist harmlos, solange das Baby gut zunimmt. Ärztlich abklären solltet ihr schwallartiges Erbrechen nach den Mahlzeiten, grünliches oder blutiges Erbrochenes oder wenn euer Baby nicht zunimmt.
• **Beziehung:** Viel Weinen in den ersten Wochen ist kein Zeichen dafür, dass ihr etwas falsch macht. Wie viel ein Baby schreit, hängt vor allem vom Kind selbst ab.
• **Motorik:** Dreht euer Baby in Rückenlage den Kopf zur Seite, streckt es oft den Arm auf dieser Seite und beugt den anderen („Fechterstellung“). Dieser Reflex verschwindet meist in den nächsten Monaten.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Bewährte Reihenfolge beim Weinen: erst Grundbedürfnisse prüfen (Hunger, Windel, zu warm oder kalt), dann Reize reduzieren, tragen, gleichmäßig wiegen, summen (Erfahrungswissen, kaum untersucht). Nicht jedes Weinen lässt sich stoppen, und Dabeibleiben ist auch Trösten.
• **Faktencheck Koliken:** Entschäumende Tropfen (Simeticon) wirken laut Studien nicht besser als Placebo. Für gestillte Babys mit Koliken gibt es Hinweise, dass ein bestimmtes Probiotikum (L. reuteri DSM 17938) das Weinen verringert, bei Flaschenkindern nicht (Studienlage gemischt). Das bitte mit der Kinderarztpraxis besprechen. Für Osteopathie, Chiropraktik und Babymassage gegen Koliken fehlen gute Belege.
• **Faktencheck Tragen:** In einer Studie (Hunziker und Barr, 1986) weinten Babys, die zusätzlich viel getragen wurden, deutlich weniger. Zwei spätere Studien fanden diesen Effekt nicht (Studienlage gemischt). Schaden tut Tragen nicht.
• **Kaufen?** Rauschgeräte, wenn überhaupt, leise stellen und nicht direkt neben den Kopf. Pucken ist umstritten: wenn, dann nur in Rückenlage, mit frei beweglichen Hüften und nicht mehr, sobald sich euer Baby drehen könnte (Erfahrungswissen, kaum untersucht).

## Woche 6 · Das erste echte Lächeln

Irgendwann in diesen Wochen passiert es meist: Euer Baby schaut euch an und lächelt. Nicht im Schlaf, nicht zufällig, sondern als Antwort auf euer Gesicht oder eure Stimme. Dieses „soziale Lächeln“ zeigen die meisten Babys bis zum Alter von etwa zwei Monaten.

Dazu kommen erste Laute, die kein Weinen sind: kleine Gurr- und Kehllaute. Babys beginnen damit, auf Ansprache zu reagieren.

🔬 Für die Forschung ist das Lächeln ein Wendepunkt: Ab jetzt ist die Beziehung sichtbar wechselseitig.

💡 Lächelt zurück, sprecht, und macht dann eine Pause. Euer Baby braucht Zeit, um zu „antworten“.

📚 **Was sonst gerade läuft**

• **Trocken & sauber:** Bei Muttermilchkindern wird der Stuhlgang nach etwa sechs Wochen oft seltener. Von mehrmals täglich bis zu einmal in sieben bis zehn Tagen ist alles normal, solange der Stuhl weich ist und das Baby gut gedeiht. Bei Flaschenkindern sind lange Pausen und harter Stuhl eher ein Grund nachzufragen.
• **Schlaf:** Ein Schnuller zum Einschlafen senkt laut Studien das Risiko für den plötzlichen Kindstod. Bei Stillkindern bietet man ihn am besten erst an, wenn das Stillen gut eingespielt ist, und drängt ihn nicht auf, wenn das Baby ihn nicht will.
• **Sprache:** Die ersten Gurrlaute sind vor allem Vokale wie „aah“ und „ooh“. Konsonanten kommen erst später dazu.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Lächel-Dialog: anlächeln, warten, zurücklächeln. Babys lieben kleine Überraschungen wie große Augen oder ein „Oh!“, aber in kleinen Dosen.
• **Darauf eingehen:** Macht Laute und Mimik eures Babys nach. Dieses „Spiegeln“ zeigt ihm, dass es gesehen wird.

## Woche 7 · Kleine Gespräche

Schon jetzt entstehen Wechselspiele: Ihr sprecht, das Baby schaut und gurrt, ihr antwortet. Fachleute nennen das „Protokonversation“, also Gesprächsstruktur, lange bevor es Wörter gibt.

🔬 **Das Still-Face-Experiment** (Tronick, 1978): Wenn Mütter im Spiel plötzlich regungslos ins Leere blicken, versuchen wenige Monate alte Babys erst, sie mit Lächeln und Lauten „zurückzuholen“, und werden dann unruhig. Babys erwarten also eine Reaktion. Wichtig dabei: Alltägliche Unterbrechungen schaden nicht. Entscheidend ist, dass der Kontakt immer wieder zustande kommt.

💡 Die typische hohe, melodische Sprechweise mit Babys ist kein Unsinn. Babys hören ihr nachweislich lieber zu, und sie unterstützt das Sprachlernen.

📚 **Was sonst gerade läuft**

• **Spiel:** Babys wenden sich Neuem zu und schauen weniger lang auf Bekanntes. Forschende nutzen genau das, um herauszufinden, was Babys unterscheiden können. Für euch heißt das: Abwechslung ist gut, aber in kleinen Dosen.
• **Wachstum:** Im gelben Heft werden Gewicht, Länge und Kopfumfang in Perzentilenkurven eingetragen. Die 50. Perzentile ist der Durchschnitt, alles zwischen der 3. und der 97. gilt als normaler Bereich. Wichtiger als die Lage ist, dass das Kind ungefähr seiner eigenen Kurve folgt.
• **Trinken & Essen:** Auch bei der Flasche gilt: nach Bedarf füttern und Sattzeichen respektieren, etwa Kopf wegdrehen oder langsamer saugen. Anfangsnahrung (Pre oder 1) kann das ganze erste Jahr gegeben werden, Folgenahrung ist laut Netzwerk Gesund ins Leben nicht nötig.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Wickel-Reportage: Erzählt, was ihr tut („Jetzt kommt die frische Windel“), und lasst Pausen für „Antworten“.
• **Faktencheck Mozart:** Der berühmte „Mozart-Effekt“ stammt aus einer Studie mit Studierenden, war kurzlebig und ließ sich kaum wiederholen. Für Babys gibt es keinen Beleg, dass klassische Musik schlauer macht (gut belegt). Musik ist trotzdem schön, am besten mit eurer eigenen Stimme.

## Woche 8 · Zwei Monate: kleine Bilanz

Was die meisten Babys (etwa 75 %) mit zwei Monaten können, laut den Meilenstein-Listen der CDC (2022):

• beruhigt sich, wenn man es anspricht oder hochnimmt
• schaut Gesichter an und lächelt, wenn man es anlächelt
• macht Laute, die kein Weinen sind, und reagiert auf laute Geräusche
• folgt euch mit den Augen und schaut ein Spielzeug einige Sekunden an
• hebt in Bauchlage kurz den Kopf, bewegt Arme und Beine, öffnet kurz die Hände

**So lest ihr das:** 75 % heißt, dass jedes vierte Baby einzelne Punkte noch nicht kann. Ein fehlender Punkt ist kein Alarmsignal, aber ein gutes Thema für die nächste U-Untersuchung. Anders ist es, wenn ein Baby Fähigkeiten, die es schon sicher hatte, wieder verliert. Das bitte zeitnah ärztlich abklären lassen.

📚 **Was sonst gerade läuft**

• **Beziehung:** Babys unterscheiden sich von Anfang an im Temperament, etwa darin, wie aktiv, reizempfindlich oder anpassungsfähig sie sind. Die Forscher Thomas und Chess prägten dafür den Begriff „Passung“: Es kommt weniger auf ein „richtiges“ Temperament an als darauf, wie gut Kind und Umgebung zusammenpassen.
• **Trocken & sauber:** Ein wunder, roter Po ist häufig. Hilfreich sind häufiges Wickeln, Luft an den Po und eine Zinksalbe. Ist die Rötung scharf begrenzt und hat kleine Pünktchen am Rand, kann ein Pilz dahinterstecken. Dann zur Kinderärztin.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Passt Reize ans Temperament an: Ruhige Babys brauchen oft etwas mehr Einladung zum Spielen, empfindliche eher weniger Trubel (Erfahrungswissen, kaum untersucht).
• **Gegenstände:** Leichte Greiflinge oder Rasseln, die euer Baby nicht verletzen, wenn sie ihm ins Gesicht fallen.
• **Kaufen?** Spielzeug muss ein CE-Zeichen tragen. Das GS-Zeichen („geprüfte Sicherheit“) ist freiwillig und ein zusätzlicher Anhaltspunkt.

## Woche 9 · Hände entdecken

Euer Baby entdeckt, dass es Hände hat. Viele Babys schauen sie jetzt lange an, bewegen die Finger vor den Augen und stecken sie in den Mund. Der angeborene Greifreflex lässt nach, und die Hände sind öfter locker geöffnet. Das ist die Voraussetzung dafür, später gezielt zu greifen.

Der Mund ist dabei ein wichtiges Werkzeug. Lippen und Zunge sind in diesem Alter die feinfühligsten Tastorgane, die ein Baby hat.

💡 Legt eurem Baby eine leichte Rassel oder einen Stoffring in die Hand. Es hält ihn noch eher zufällig, lernt dabei aber, was seine Hand bewirkt.

📚 **Was sonst gerade läuft**

• **Sprache:** Schon Neugeborene unterscheiden Sprachen mit unterschiedlichem Rhythmus, etwa Englisch und Japanisch. Die Sprachmelodie ist das Erste, was Babys von ihrer Sprache lernen.
• **Schlaf:** Tagsüber gibt es meist noch keinen festen Rhythmus, sondern mehrere Nickerchen unterschiedlicher Länge. Regelmäßigere Schlafzeiten entwickeln sich in den nächsten Monaten.
• **Trinken & Essen:** Wie viel ein Baby trinkt, schwankt von Mahlzeit zu Mahlzeit und von Tag zu Tag. Gesunde Babys regulieren ihren Bedarf gut selbst. Entscheidend ist die Entwicklung über Wochen, nicht die einzelne Mahlzeit.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Fingerspiele und sanftes Händezusammenführen: Hände vor der Brust zusammenklatschen, Finger einzeln antippen.
• **Gegenstände:** Leichter Stoffring, Waschlappen, Stoffstreifen zum Festhalten. Keine langen Bänder oder Schnüre.
• **Faktencheck Stillen:** Stillen schützt nachweislich vor manchen Infektionen. Ob es auch die Intelligenz erhöht, ist umstritten: Die große PROBIT-Studie fand mit sechseinhalb Jahren einen Vorteil, mit 16 Jahren nicht mehr, und Geschwistervergleiche finden kaum Unterschiede (Studienlage gemischt). Wer nicht stillt oder nicht stillen kann, muss sich um die Entwicklung keine Sorgen machen.

## Woche 10 · Die Welt wird bunter

Das Sehen macht jetzt große Fortschritte. Farben unterscheiden Babys mit etwa drei Monaten schon weitgehend wie Erwachsene, und ungefähr in dieser Zeit beginnt auch das räumliche Sehen: Das Gehirn lernt, die Bilder beider Augen zu einem dreidimensionalen Eindruck zusammenzusetzen. Bewegte Dinge verfolgen Babys jetzt flüssiger mit den Augen.

🔬 So scharf wie Erwachsene sehen Babys aber noch lange nicht. Die Sehschärfe reift über die ersten Lebensjahre weiter.

💡 Teure Kontrastkarten braucht es nicht. Draußen gibt es genug zu sehen: Blätter im Wind, Licht und Schatten, Gesichter.

📚 **Was sonst gerade läuft**

• **Beziehung:** Babys binden sich nicht nur an eine Person. In einer klassischen Studie (Schaffer und Emerson, 1964) hatten die meisten Kinder mit anderthalb Jahren mehrere Bindungspersonen. Am stärksten banden sie sich an die Menschen, die feinfühlig auf ihre Signale reagierten und mit ihnen spielten, nicht unbedingt an die, die am meisten fütterten und wickelten.
• **Motorik:** In den nächsten Wochen bringen viele Babys ihre Hände vor der Brust zusammen und betrachten sie. Die Körpermitte wird zum Treffpunkt für Hände und Augen.
• **Trocken & sauber:** Babys pinkeln sehr häufig, die Blase entleert sich noch automatisch. Die bewusste Kontrolle darüber ist noch Jahre entfernt.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Blickfolgen: Ein Spielzeug langsam hin und her bewegen. Oder Schattenspiele mit der Hand an der Wand.
• **Darauf eingehen:** Draußen gibt es das beste Sehtraining: Bäume, Wolken, bewegte Blätter.
• **Kaufen?** Ein Mobile ist in Ordnung, wenn es sicher befestigt und außer Reichweite hängt. Nötig ist es nicht.

## Woche 11 · Es wird ruhiger (meistens)

Für viele Familien eine gute Nachricht: Nach acht bis neun Wochen nimmt das Weinen im Durchschnitt deutlich ab. Gleichzeitig entwickelt sich der Tag-Nacht-Rhythmus. Etwa ab dem dritten Monat bildet der Körper das Schlafhormon Melatonin zunehmend im Tagesrhythmus, und längere Schlafphasen in der Nacht werden häufiger.

Schreit euer Baby dagegen weiter sehr viel, sprecht mit der Kinderarztpraxis. Nicht, weil etwas „falsch“ sein muss, sondern weil es Unterstützung gibt, etwa in Schreiambulanzen. Sofort ärztlich abklären lassen solltet ihr Schreien zusammen mit Fieber, Trinkschwäche oder Erbrechen, oder wenn das Weinen ganz anders klingt als sonst.

💡 Wenn es ruhiger wird, gönnt euch bewusst Pausen. Auch Eltern müssen sich von den ersten Wochen erholen.

📚 **Was sonst gerade läuft**

• **Spiel:** Babys spielen mit ihrem eigenen Körper: Hände, Füße, Stimme. Das ist echtes Spiel, denn sie wiederholen Bewegungen, weil sie Spaß machen.
• **Wachstum:** Viele Babys haben mit etwa vier bis sechs Monaten ihr Geburtsgewicht verdoppelt und mit einem Jahr ungefähr verdreifacht. Die Länge nimmt im ersten Jahr um etwa die Hälfte zu. Das sind grobe Richtwerte mit großer Streuung.
• **Trinken & Essen:** Nächtliche Mahlzeiten sind in diesem Alter normal. Wann ein Baby nachts ohne Mahlzeit auskommt, ist von Kind zu Kind sehr verschieden.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Körperspiele: sanftes „Radfahren“ mit den Beinen, Füße anpusten, Hände zum Gesicht führen.
• **Darauf eingehen:** Wenn es ruhiger wird, kann ein gleichbleibender Abendablauf beginnen, auch wenn er noch nicht immer klappt (Erfahrungswissen, kaum untersucht).

## Woche 12 · Kopf hoch!

Die Kopfkontrolle wird besser. In Bauchlage stützen sich viele Babys jetzt auf die Unterarme und halten den Kopf länger oben. Mit etwa vier Monaten halten die meisten Babys den Kopf stabil, wenn man sie aufrecht hält.

Gleichzeitig verschwinden angeborene Reflexe. Der Moro-Reflex (Zusammenzucken mit ausgebreiteten Armen) verblasst typischerweise zwischen drei und sechs Monaten. Das ist ein Zeichen dafür, dass das Großhirn zunehmend die Kontrolle übernimmt.

💡 Legt in der Bauchzeit ein interessantes Spielzeug oder einen bruchsicheren Spiegel vor euer Baby. Dann lohnt sich das Kopfheben.

📚 **Was sonst gerade läuft**

• **Schreien:** Babys, die viel weinen, sind oft auch übermüdet. Manchen Familien helfen ein gleichmäßiger Tagesablauf und bewusst angebotene Schlafpausen, bevor das Baby völlig überdreht ist.
• **Beziehung:** Das Lächeln wird gezielter. Vertraute Menschen bekommen jetzt oft ein strahlenderes Lächeln als Fremde.
• **Trocken & sauber:** Stuhl sieht je nach Ernährung sehr unterschiedlich aus. Grünlicher Stuhl ist bei einem sonst gesunden, zufriedenen Baby meist harmlos. Wichtig bleibt nur die Warnung vor sehr hellem, lehmfarbenem Stuhl.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Greif-Angebote: Einen leichten Stoffring so vor die Hände halten, dass euer Baby ihn beim Zappeln trifft und irgendwann festhält.
• **Faktencheck Klettfäustlinge:** In Experimenten (Needham, 2002; Libertus, 2016) bekamen drei Monate alte Babys Fäustlinge mit Klett, an denen leichte Spielsachen hafteten. Nach zwei Wochen mit zehn Minuten täglich erkundeten sie Gegenstände mehr, und das war sogar ein Jahr später noch messbar (einzelne Studie). Übertragen heißt das: Gelegenheiten zum erfolgreichen Greifen schaffen hilft vermutlich.
• **Faktencheck Kopfform:** Ein abgeflachter Hinterkopf ist häufig. Dagegen helfen Bauchzeit, wechselnde Kopfpositionen und Ansprache von beiden Seiten. Eine randomisierte Studie (van Wijk, 2014) fand bei gesunden Babys mit fünf bis sechs Monaten durch eine Helmtherapie keinen Vorteil gegenüber dem natürlichen Verlauf, dafür viele Nebenwirkungen (einzelne Studie). Dreht euer Baby den Kopf fast nur zu einer Seite, lasst das in der Kinderarztpraxis ansehen.

## Woche 13 · Drei Monate: Gurren und Glucksen

Euer Baby wird gesprächiger. Gurrlaute wie „ooh“ und „aah“ und erste glucksende Lacher, wenn ihr es zum Lachen bringt, beschreibt die CDC für die meisten Babys mit etwa vier Monaten. Viele Babys antworten jetzt mit Lauten, wenn man mit ihnen spricht, und drehen den Kopf in Richtung eurer Stimme.

🔬 Lachen ist in diesem Alter vor allem ein soziales Signal und passiert meist im Austausch mit anderen. Echter „Humor“, also über Überraschendes und Unsinniges zu lachen, kommt erst später.

⚠️ **Kurze Erinnerung zum sicheren Schlaf:** Zwischen dem zweiten und vierten Monat ist das Risiko für den plötzlichen Kindstod am höchsten. Deshalb noch einmal das Wichtigste: Rückenlage, Schlafsack, feste Unterlage ohne Kissen und Kuscheltiere, rauchfrei, nicht zu warm, Baby im Elternschlafzimmer. Ob im eigenen Bett, im Beistellbett oder im Familienbett, darüber sind sich Fachleute nicht einig (Studienlage gemischt). Klar gefährlich ist gemeinsames Schlafen aber nach Rauchen, Alkohol, Drogen oder müde machenden Medikamenten, bei Frühgeborenen sowie auf dem Sofa oder im Sessel (gut belegt).

💡 Macht die Laute eures Babys nach und wartet auf die Antwort. Solche Wechselspiele sind echte Sprachvorbereitung.

📚 **Was sonst gerade läuft**

• **Motorik:** Sitzen lässt sich jetzt noch nicht üben. Aufrecht getragen halten viele Babys aber schon den Kopf und schauen sich neugierig um.
• **Schlaf:** Längere Schlafphasen in der Nacht werden häufiger, aber kaum ein Baby schläft schon „durch“. Gemeint ist damit in Studien übrigens meist nur sechs Stunden am Stück.
• **Wachstum:** Nach den ersten drei Monaten nehmen Babys pro Woche meist weniger zu als am Anfang. Das Wachstum verlangsamt sich über das ganze erste Jahr allmählich.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Lachspiele: sanft pusten, „Ich krieg dich!“, Nase an Nase. Aufhören, bevor euer Baby überdreht.
• **Kaufen?** Nichts. Ihr seid gerade das Lieblingsspielzeug.

## Woche 14 · Erst hauen, dann greifen

Babys beginnen, gezielt nach Dingen zu schlagen, erst noch ungelenk, eher ein Wischen mit dem ganzen Arm. Innerhalb der nächsten Wochen wird daraus ein echtes Greifen. Was gefasst ist, wandert in den Mund. So erkunden Babys Form, Material und Geschmack.

⚠️ Ab jetzt gilt: Alles in Reichweite kann im Mund landen. Faustregel: Was durch eine Klopapierrolle passt, kann verschluckt werden. Besonders gefährlich sind **Knopfzellen**, die innerhalb von Stunden schwere Verätzungen verursachen können, und starke **Magnete**. Bei Verdacht auf Verschlucken sofort ärztliche Hilfe holen, im Notfall 112.

💡 Haltet Spielzeug so, dass euer Baby sich danach strecken muss, statt es direkt in die Hand zu geben.

📚 **Was sonst gerade läuft**

• **Spiel:** Babys spielen jetzt mit allem, was sie greifen können: schütteln, drehen, in den Mund stecken. Verschiedene Materialien (Holz, Stoff, Silikon) sind spannender als viele gleichartige Spielsachen.
• **Trinken & Essen:** Beim Stillen oder Fläschchen lassen sich viele Babys jetzt leicht ablenken, gucken sich um und trinken unruhig. Das liegt daran, dass die Welt interessanter wird. Ein ruhiger, reizarmer Ort hilft.
• **Sprache:** Babys lachen und quietschen mehr und probieren aus, wie laut sie sein können.

🧸 **Was ihr jetzt tun könnt**

• **Gegenstände:** Aus der Küche: Holzlöffel, ein Silikonschaber, ein Stoffbeutel mit Knoten. Keine Plastiktüten, nichts Zerbrechliches und nichts, was durch eine Klopapierrolle passt.
• **Spielidee:** In Bauchlage ein Spielzeug knapp außer Reichweite legen, damit sich Strecken lohnt.
• **Kaufen?** Wenige Greiflinge aus verschiedenen Materialien reichen. Eine Studie mit Kleinkindern (Dauch, 2018) fand, dass sie mit wenigen Spielsachen länger und vielfältiger spielten als mit vielen (einzelne Studie). Für Babys ist das nicht untersucht, aber „weniger, dafür abwechselnd“ ist eine gute Faustregel.

## Woche 15 · Vorsicht, Wickeltisch

Viele Babys drehen sich zwischen vier und sechs Monaten zum ersten Mal, meist zuerst vom Bauch auf den Rücken. Das passiert oft völlig überraschend, auch für das Baby selbst.

⚠️ Stürze vom Wickeltisch, Sofa oder Bett gehören zu den häufigsten Unfällen in diesem Alter. Deshalb: immer eine Hand am Baby lassen oder gleich auf dem Boden wickeln.

Zum Schlafen legt ihr euer Baby weiterhin immer auf den Rücken. Wenn es sich selbst auf den Bauch dreht und auch wieder zurück kann, darf es so liegen bleiben.

💡 Viel Zeit auf einer Decke am Boden gibt Platz zum Ausprobieren, mehr als Wippe oder Babyschale.

📚 **Was sonst gerade läuft**

• **Beziehung:** Babys erkennen jetzt deutlich, wer zur Familie gehört, und begrüßen vertraute Menschen mit Strahlen und Strampeln.
• **Schlaf:** Einschlafhilfen wie Stillen, Tragen oder Wiegen sind in diesem Alter völlig normal. Wie ihr das handhabt, ist Familiensache.
• **Wachstum:** Beim Wiegen zu Hause schwanken Waage, Tageszeit und Windelinhalt stark. Einzelne Messungen sagen wenig aus. Bei gesunden Babys reichen die U-Untersuchungen meist aus.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Drehen anregen: Spielzeug seitlich neben euer Baby halten, sodass es Blick und Körper hinterherdreht.
• **Darauf eingehen:** Spielen am besten am Boden statt auf Sofa oder Bett. Da kann nichts passieren, wenn es sich plötzlich dreht.

## Woche 16 · Der eigene Name

🔬 In einem bekannten Experiment (Mandel und Kollegen, 1995) hörten Babys mit etwa viereinhalb Monaten länger zu, wenn ihr eigener Name gerufen wurde, als bei ähnlich klingenden Namen. Sie erkennen dieses Klangmuster also schon, vermutlich weil sie es so oft hören.

Verlässlich auf den eigenen Namen reagieren, also hinschauen, wenn man ruft, tun die meisten Babys laut CDC erst mit etwa neun Monaten. Wiedererkennen und darauf reagieren sind zwei unterschiedliche Schritte.

💡 Erzählt eurem Baby, was ihr gerade tut, beim Wickeln, Kochen, Anziehen. Wie viel Eltern direkt mit ihrem Kind sprechen, hängt in Studien mit der späteren Sprachentwicklung zusammen.

📚 **Was sonst gerade läuft**

• **Motorik:** Viele Babys greifen in den nächsten Wochen in Rückenlage nach ihren Knien und Füßen. Füße sind ein tolles Spielzeug.
• **Schreien:** Nach dem dritten Monat weinen Babys seltener ohne erkennbaren Grund. Das Weinen wird gezielter: aus Frust, Langeweile oder Müdigkeit.
• **Trocken & sauber:** Ein Baby, das beim Stuhlgang rot anläuft, drückt und stöhnt, ist nicht automatisch verstopft. Das Zusammenspiel von Bauchpresse und Beckenboden muss erst gelernt werden. Entscheidend ist, ob der Stuhl weich ist.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Baut den Namen eures Babys in Lieder und Reime ein.
• **Faktencheck Wortmenge:** Die berühmte „30-Millionen-Wörter-Lücke“ (Hart und Risley, 1995) beruht auf einer kleinen Stichprobe und ist umstritten. Neuere Studien (etwa Romeo, 2018) deuten darauf hin, dass echtes Hin und Her wichtiger ist als die reine Wortmenge (Studienlage gemischt). Es geht also nicht ums Dauerreden, sondern ums Miteinander.
• **Gegenstände:** Bilderbücher mit Fotos von Babygesichtern sind jetzt oft besonders spannend.

## Woche 17 · Vier Monate und die Brei-Frage

Lange galt in Deutschland: Beikost frühestens mit Beginn des 5. und spätestens mit Beginn des 7. Monats. Seit Februar 2026 gibt es erstmals eine S3-Leitlinie zur Stilldauer. Sie empfiehlt, reif geborene Kinder bis zum Ende des sechsten Lebensmonats ausschließlich oder überwiegend zu stillen, und schließt sich damit der WHO an. Beikost kommt danach ab Beginn des 7. Monats dazu, also in etwa neun Wochen. Bis dahin reichen Muttermilch oder Säuglingsnahrung vollständig.

🔬 **Wie sicher ist das?** Die Leitlinie stützt sich auf Beobachtungsstudien, in denen Kinder mit sechs Monaten Vollstillen zum Beispiel seltener Mittelohrentzündungen und Magen-Darm-Infekte hatten. Die Leitlinie selbst bewertet die Beleglage als niedrig bis sehr niedrig. Zwei Fachgesellschaften, die Ernährungsmediziner (DGEM) und der Berufsverband der Kinder- und Jugendärzte (BVKJ), haben deshalb widersprochen und halten 4 bis 6 Monate weiterhin für angemessen, unter anderem mit Blick auf Allergien und die Eisenversorgung (Studienlage gemischt). Die Leitlinie betont ausdrücklich, dass niemand unter Druck gesetzt werden darf, weder zum Stillen noch zum Abstillen noch zu früher Beikost. Gibt es Allergien in der Familie oder bekommt euer Baby Säuglingsnahrung, besprecht den Zeitpunkt am besten mit der Kinderarztpraxis.

Woran ihr später merkt, dass euer Baby bereit ist (Reifezeichen):

• sitzt mit etwas Unterstützung aufrecht und hält den Kopf sicher
• interessiert sich sichtbar für euer Essen
• öffnet den Mund, wenn ein Löffel kommt
• schiebt Nahrung nicht mehr reflexhaft mit der Zunge heraus

Nebenbei, laut CDC können die meisten Babys mit vier Monaten Folgendes: von sich aus lächeln, um Aufmerksamkeit zu bekommen, glucksen, gurren, den Kopf zur Stimme drehen, den Kopf stabil halten, ein Spielzeug festhalten, die Hände zum Mund führen und sich in Bauchlage auf die Unterarme stützen.

📚 **Was sonst gerade läuft**

• **Wachstum:** Gestillte Kinder wachsen in der zweiten Hälfte des ersten Jahres oft etwas langsamer als Kinder mit Säuglingsnahrung. Die Wachstumskurven der WHO beruhen deshalb auf gestillten Kindern.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Lasst euer Baby beim Familienessen auf dem Schoß dabei sein: zuschauen, riechen, dazugehören.
• **Kaufen?** Einen Hochstuhl erst, wenn euer Baby mit wenig Hilfe aufrecht sitzt. Bis dahin ist der Schoß der beste Platz. Für den Brei reicht ein weicher, flacher Babylöffel. Selbst kochen und Gläschen sind beide in Ordnung.

## Woche 18 · Schlaf: Was ist eigentlich normal?

Für Babys zwischen vier und zwölf Monaten nennt die amerikanische Schlafmedizin-Fachgesellschaft (AASM) etwa 12 bis 16 Stunden Schlaf in 24 Stunden, Tagschläfchen eingerechnet, mit großen individuellen Unterschieden.

🔬 **Die „4-Monats-Schlafregression“** ist ein populärer Begriff. Richtig ist, dass sich der Schlaf in diesen Monaten tatsächlich verändert: Die Schlafzyklen werden erwachsenenähnlicher, und kurzes Aufwachen zwischen den Zyklen wird deutlicher. Dass alle Babys in einem festen Alter plötzlich schlechter schlafen, ist aber nicht gut belegt.

Nächtliches Aufwachen ist in diesem Alter die Regel, nicht die Ausnahme.

💡 Ein kurzes, immer gleiches Abendritual (zum Beispiel Wickeln, Schlafsack, Lied, Licht aus) gibt Orientierung.

📚 **Was sonst gerade läuft**

• **Sprache:** Babys drehen sich jetzt zu Geräuschen um und orten sie immer genauer.
• **Trinken & Essen:** Großes Interesse an eurem Essen ist allein noch kein Zeichen für Beikost-Reife. Viele Babys verfolgen jeden Bissen mit den Augen, lange bevor sie so weit sind.
• **Motorik:** In Bauchlage stützen sich viele Babys jetzt auf die Hände und heben die Brust. Manche „fliegen“, also heben Arme und Beine gleichzeitig vom Boden.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Müdigkeitszeichen früh erkennen, also Augenreiben, Gähnen, starrer Blick, und dann ins Bett, bevor euer Baby überdreht (Erfahrungswissen, kaum untersucht).
• **Kaufen?** Schlafsack in passender Größe und Dicke für die Raumtemperatur. Nachtlicht oder Babyphone sind Geschmackssache, nötig sind sie nicht.

## Woche 19 · Ich bewirke etwas!

Euer Baby entdeckt Ursache und Wirkung: Wenn ich die Rassel schüttle, macht es ein Geräusch. Wenn ich lache, lacht Papa zurück.

🔬 In klassischen Experimenten der Psychologin Carolyn Rovee-Collier bekamen drei Monate alte Babys ein Band ans Bein, das mit einem Mobile verbunden war. Sie lernten schnell, das Mobile durch Strampeln zu bewegen, und erinnerten sich Tage später noch daran. Babys lernen also früh, dass sie selbst etwas bewirken können.

💡 Spielzeug, das reagiert (raschelt, klingelt, sich bewegt), ist jetzt besonders spannend. Das reaktionsfreudigste Spielzeug von allen seid aber ihr.

📚 **Was sonst gerade läuft**

• **Schreien:** Babys weinen jetzt auch, wenn etwas nicht klappt, zum Beispiel wenn das Spielzeug außer Reichweite rollt. Frust treibt das Lernen an, solange ihr helft, wenn es zu viel wird.
• **Wachstum:** Der Kopf wächst jetzt langsamer, etwa einen Zentimeter pro Monat.
• **Trocken & sauber:** Manche Familien achten auf die Signale ihres Babys vor dem Pinkeln und halten es ab („windelfrei“). Das ist möglich, beschleunigt laut den Zürcher Studien (Largo und Stützle, 1977) aber nicht das spätere Trockenwerden. Frühes Töpfchentraining hatte dort nur kurzfristige Effekte beim Stuhlgang und keinen auf die Blasenkontrolle.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Alles, was auf eine Aktion reagiert: Knisterpapier (Backpapier), eine Rassel, eine gut verschlossene und zugeklebte Plastikflasche mit Reis. Immer unter Aufsicht.
• **Darauf eingehen:** Reagiert selbst gut sichtbar auf das, was euer Baby tut. So lernt es: „Ich bewirke etwas.“
• **Kaufen?** Elektronisches Spielzeug mit Knöpfen, Licht und Musik ist nicht nötig. Mehr dazu in einigen Wochen.

## Woche 20 · Gefühle lesen lernen

In den kommenden Monaten lernen Babys immer besser, Gefühle zu unterscheiden: freundliche und ärgerliche Stimmen, lachende und traurige Gesichter. Viele lachen jetzt richtig laut.

Laut CDC schauen sich die meisten Babys mit sechs Monaten gern im Spiegel an. Dass sie sich darin selbst erkennen, ist aber erst viel später so weit, in Tests meist ab etwa 18 Monaten.

💡 Ein bruchsicherer Spiegel am Boden ist ein spannender Spielpartner für die Bauchzeit.

📚 **Was sonst gerade läuft**

• **Schlaf:** Mit sechs Monaten schliefen Kinder in den Zürcher Studien im Durchschnitt gut 14 Stunden in 24 Stunden, mit großer Spannbreite.
• **Motorik:** Viele Babys drehen sich jetzt auch vom Rücken auf den Bauch. Vorsicht auf erhöhten Flächen gilt weiterhin.
• **Trinken & Essen:** Für die Beikost ist Eisen besonders wichtig, denn die Eisenspeicher aus der Schwangerschaft gehen im zweiten Halbjahr zur Neige. Deshalb enthält der erste Brei Fleisch oder, vegetarisch, eisenreiches Getreide wie Hafer oder Hirse zusammen mit Vitamin-C-haltigem Obst oder Gemüse.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Singt, wenn euer Baby quengelig wird. In einer Studie (Corbeil und Kollegen, 2016) blieben sechs bis neun Monate alte Babys bei Gesang etwa doppelt so lange ruhig wie bei Sprache (einzelne Studie).
• **Gegenstände:** Ein bruchsicherer Spiegel auf Augenhöhe am Boden.
• **Darauf eingehen:** Gefühle in Worte fassen: „Oh, da hast du dich erschrocken.“ Euer Baby versteht die Worte noch nicht, aber den Ton.

## Woche 21 · Quietschen, Prusten, Blubbern

Euer Baby experimentiert mit seiner Stimme: Quietschen, Brummen, Prusten mit den Lippen. Das ist kein Unsinn, sondern Stimmtraining. Babys finden heraus, was Kehlkopf, Zunge und Lippen alles können. Laut CDC „unterhalten“ sich die meisten Babys mit sechs Monaten abwechselnd mit euch in Lauten.

💡 Macht mit! Prustet zurück, quietscht, wartet auf die Antwort. Albernheit ist hier pädagogisch wertvoll.

📚 **Was sonst gerade läuft**

• **Beziehung:** Babys beginnen, bei Spielen den Höhepunkt vorwegzunehmen. Macht ihr ein Kitzelspiel mehrmals gleich, freuen sie sich schon, bevor es losgeht.
• **Spiel:** Spielzeug wandert von Hand zu Hand und in den Mund. Babys drehen und betrachten Gegenstände jetzt systematischer.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Laut-Ping-Pong: Euer Baby quietscht, ihr quietscht zurück, Pause. Prusten auf den Bauch.
• **Faktencheck Babymassage:** Viele Babys genießen Massagen. Eine Cochrane-Übersicht (2013) fand bei gesunden Babys aber keine belastbaren Belege für Vorteile bei Entwicklung, Schlaf oder Schreien, auch weil viele Studien methodisch schwach waren (Studienlage gemischt). Also: gern machen, wenn es euch beiden guttut.
• **Kaufen?** Babykurse wie PEKiP, Babymassage oder Babyschwimmen sind für die Entwicklung kaum untersucht. Ihr Wert liegt vermutlich eher im Kontakt zu anderen Eltern und im gemeinsamen Erleben (Erfahrungswissen, kaum untersucht).

## Woche 22 · Sabbern, Zähne und Fieber

Viele Babys sabbern jetzt viel. Das liegt vor allem daran, dass die Speichelproduktion in diesem Alter steigt, und ist nicht automatisch ein Zeichen für Zähne. Der erste Zahn kommt meist irgendwann zwischen etwa 6 und 12 Monaten. Manche Babys haben schon früher einen, manche erst nach dem ersten Geburtstag.

🔬 Studien zeigen: Zahnen kann Babys quengelig machen und die Temperatur leicht erhöhen, verursacht aber kein richtiges Fieber. Ist euer Baby richtig krank, schiebt es bitte nicht aufs Zahnen.

💡 Ein gekühlter (nicht gefrorener) Beißring kann helfen. Von Bernsteinketten raten Kinderärzte wegen Strangulations- und Verschluckungsgefahr ab.

📚 **Was sonst gerade läuft**

• **Schlaf:** Viele Babys kommen jetzt mit zwei bis drei Tagschläfchen aus.
• **Sprache:** Die Melodie verstehen Babys vor den Wörtern. In einer Studie (Fernald, 1993) reagierten fünf Monate alte Babys auf lobende und verbietende Sprachmelodien sogar in fremden Sprachen mit passendem Gesichtsausdruck.

🧸 **Was ihr jetzt tun könnt**

• **Gegenstände:** „Das Gleiche in anders“: nacheinander einen Löffel aus Holz, Metall und Silikon anbieten. Babys vergleichen Gewicht, Temperatur und Geräusch.
• **Kaufen?** Ein kühlbarer Beißring genügt. Zahnungsgels mit Betäubungsmitteln sind für Babys nicht empfohlen, fragt im Zweifel in der Apotheke oder Kinderarztpraxis.

## Woche 23 · Sitzen will gelernt sein

Viele Babys stützen sich jetzt im Sitzen mit den Händen ab, die CDC nennt das für sechs Monate. Frei sitzen kommt etwas später. Die große WHO-Studie mit Kindern aus fünf Ländern fand für das Sitzen ohne Unterstützung ein Normalfenster von 3,8 bis 9,2 Monaten.

🔬 Interessant: Sitzen hatte in dieser Studie das engste Zeitfenster aller untersuchten Meilensteine. Beim freien Stehen und Laufen liegen zwischen den frühesten und den spätesten gesunden Kindern fast zehn Monate.

💡 Ihr müsst Sitzen nicht „üben“, indem ihr euer Baby hinsetzt. Viel freie Bewegungszeit am Boden trainiert genau die Muskeln, die es dafür braucht.

📚 **Was sonst gerade läuft**

• **Spiel:** Sitzt euer Baby mit Unterstützung, sind beide Hände frei. Jetzt wird zweihändiges Erkunden möglich.
• **Trinken & Essen:** Zum Essen sollte euer Baby aufrecht und gut gestützt sitzen, zum Beispiel auf dem Schoß oder im Hochstuhl mit Sitzverkleinerung, und nicht halb liegend in der Wippe.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Sitzen zwischen euren Beinen, Spielzeug mal links, mal rechts anbieten. So übt euer Baby Gleichgewicht, ohne umzukippen.
• **Gegenstände:** Ein „Schatzkorb“: ein flacher Korb mit drei, vier Alltagsdingen aus unterschiedlichen Materialien, etwa Holzlöffel, Metallschüssel, großer Pinienzapfen, Stofftuch. Das Konzept stammt aus der Kleinkindpädagogik (Erfahrungswissen, kaum untersucht). Nichts, was kleiner als etwa eine Kinderfaust ist.
• **Kaufen?** Sitzringe und Babysitze sind nicht nötig. Physiotherapeuten raten meist davon ab, Babys lange hinzusetzen, bevor sie es selbst können (Erfahrungswissen, kaum untersucht).

## Woche 24 · Kleine Sprachgenies

🔬 Babys kommen als „Weltbürger“ zur Welt. In den ersten Monaten können sie Sprachlaute aus allen Sprachen unterscheiden, auch solche, die Erwachsene gar nicht mehr hören. Zwischen etwa 6 und 12 Monaten spezialisieren sie sich auf die Sprache oder Sprachen, die sie hören, und verlieren die Empfindlichkeit für fremde Laute (Werker und Tees, 1984). Das Gehirn stellt sich auf die eigene Umgebung ein.

Wenn ihr zu Hause mehrere Sprachen sprecht: Mehrsprachigkeit verwirrt Babys nicht und ist kein Grund für eine Sprachentwicklungsstörung.

💡 Sprecht mit eurem Baby in der Sprache, in der ihr euch am wohlsten fühlt. Echte Menschen sind dabei durch nichts zu ersetzen. In Studien lernten Babys fremde Sprachlaute von einer Person im Raum, aber kaum von derselben Person auf Video.

📚 **Was sonst gerade läuft**

• **Schreien:** Schreit ein Baby nach dem dritten Monat weiterhin sehr viel oder schläft sehr schlecht, sprechen Fachleute von einer Regulationsstörung. Gute Anlaufstellen sind Schreiambulanzen und die Frühen Hilfen, die die ganze Familie beraten.
• **Motorik:** Viele Babys stemmen sich jetzt gern auf eurem Schoß in den Stand und federn. Das ist Spaß und Krafttraining zugleich.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Bilderbuch-Zeit: zeigen, benennen, warten. Eine Meta-Analyse (Dowdall, 2020) fand, dass gemeinsames Bilderbuchanschauen die Sprache von Kindern zwischen einem und sechs Jahren fördert (gut belegt). Für Babys ist es weniger untersucht, aber ein guter Anfang für eine Gewohnheit.
• **Kaufen?** Pappbilderbücher mit klaren Bildern oder Fotos. Die Stadtbibliothek hat oft eine Babyecke.

## Woche 25 · Aus den Augen, aus dem Sinn?

🔬 Ein Klassiker der Entwicklungspsychologie: Jean Piaget meinte, dass Babys erst mit etwa acht Monaten wissen, dass Dinge weiterexistieren, wenn man sie nicht sieht („Objektpermanenz“). Spätere Experimente von Renée Baillargeon legten nahe, dass schon drei bis fünf Monate alte Babys verblüfft schauen, wenn ein verstecktes Objekt auf „unmögliche“ Weise verschwindet. Wie viel Babys dabei wirklich verstehen, wird bis heute diskutiert.

Sicher ist: Aktiv nach versteckten Dingen suchen, etwa nach einem heruntergefallenen Löffel, tun die meisten Babys laut CDC mit etwa neun Monaten.

💡 Guck-guck-Spiele machen jetzt richtig Spaß: Tuch vors Gesicht, und … da!

📚 **Was sonst gerade läuft**

• **Trinken & Essen:** Wenn es bald mit der Beikost losgeht: Die ersten Löffel Brei landen oft wieder draußen. Das ist keine Ablehnung, die Zunge muss erst lernen, Brei nach hinten zu befördern. Neue Geschmäcker brauchen oft 8 bis 10 Versuche, bis sie akzeptiert werden.
• **Wachstum:** Größe und Gewicht bei Geburt spiegeln vor allem die Bedingungen im Bauch. In den ersten 12 bis 18 Monaten schwenken deshalb viele Kinder auf eine andere Perzentilenkurve ein, die eher ihrer Veranlagung entspricht. Kleine holen auf, Große wachsen etwas langsamer.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Guck-guck in Varianten: Tuch über ein Spielzeug legen, das Spielzeug halb unter der Decke verstecken, euch selbst hinter dem Vorhang verstecken.
• **Darauf eingehen:** Nehmt euch für den Beikoststart Gelassenheit vor: Neues immer wieder anbieten, ohne Druck, auch wenn das Gesicht erst einmal verzogen wird.

## Woche 26 · Ein halbes Jahr!

Was die meisten Babys (etwa 75 %) mit sechs Monaten können, laut CDC:

• erkennt vertraute Menschen, lacht, schaut sich gern im Spiegel an
• „unterhält“ sich abwechselnd mit Lauten, prustet, quietscht
• steckt Dinge zum Erkunden in den Mund und greift nach Spielzeug
• macht den Mund zu, wenn es nichts mehr essen will
• dreht sich vom Bauch auf den Rücken und stützt sich in Bauchlage auf gestreckte Arme

🔬 **Durchschlafen?** Eine Studie mit knapp 400 Babys (Pennestri und Kollegen, 2018) fand: Mit sechs Monaten schliefen 38 % noch nicht sechs Stunden am Stück und 57 % nicht acht Stunden. Das hatte keinen Zusammenhang mit ihrer Entwicklung oder der Stimmung der Mütter. Nächtliches Aufwachen ist in diesem Alter normal.

**Beikost:** Nach der neuen S3-Leitlinie (2026) ist jetzt, mit Beginn des 7. Monats, der empfohlene Zeitpunkt für den Start. Habt ihr auf Rat der Kinderarztpraxis schon früher begonnen, ist das ebenfalls in Ordnung. Zeigt euer Baby in den nächsten Wochen noch gar kein Interesse am Essen, sprecht das bei der Kinderärztin an.

📚 **Was sonst gerade läuft**

• **Trocken & sauber:** Mit der Beikost verändert sich der Stuhl: Er wird fester, brauner und riecht stärker. Unverdaute Stückchen, etwa von Möhren, sind normal.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Halbjahres-Aufräumen: Spielzeug zur Hälfte wegräumen und alle ein, zwei Wochen tauschen. Das hält Dinge neu, belegt ist es für Babys aber nicht (Erfahrungswissen, kaum untersucht).
• **Kaufen?** Ein kleiner offener Becher und Lätzchen. Mehr braucht es für den Essensstart nicht.

## Woche 27 · Essen lernen

Beikost ist mehr als Ernährung. Euer Baby lernt Geschmäcker, Konsistenzen, Kauen und Schlucken. Der klassische Aufbau nach dem Netzwerk Gesund ins Leben: zuerst mittags ein Gemüse-Kartoffel-Fleisch-Brei, etwa einen Monat später abends ein Milch-Getreide-Brei und wieder einen Monat später nachmittags ein Getreide-Obst-Brei. Weiche Fingerfood-Stücke („Baby-led Weaning“) sind eine Alternative oder Ergänzung.

Allergene Lebensmittel wie gut durchgegartes Ei oder Fisch müsst ihr nicht meiden. Das Weglassen schützt nicht vor Allergien.

⚠️ **Tabu im ersten Jahr:** Honig (Risiko für Säuglingsbotulismus) sowie zugesetztes Salz und Zucker. Kuhmilch als Getränk gibt es erst ab etwa einem Jahr, im Brei ist sie in Ordnung. **Erstickungsgefahr** besteht bei ganzen Nüssen, ganzen Trauben oder Kirschtomaten (vierteln!) und harten rohen Karotten- oder Apfelstücken.

🔬 Würgen gehört zum Essenlernen dazu. Es ist ein Schutzreflex und laut. Echtes Verschlucken ist dagegen oft still. Esst deshalb immer am Tisch und bleibt dabei.

💡 Bietet zu den Breimahlzeiten Wasser aus einem Becher an.

📚 **Was sonst gerade läuft**

• **Schlaf:** Mit Beikost schlafen Babys nicht automatisch besser. In einer großen britischen Studie führte ein früherer Beikoststart nur zu gut einer Viertelstunde mehr Nachtschlaf.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Sattzeichen respektieren: Kopf wegdrehen, Mund zu, Löffel wegschieben. Kein „Flieger“ und keine Tricks. Fachgesellschaften empfehlen dieses „responsive Füttern“, weil gesunde Babys ihre Menge gut selbst regulieren.
• **Faktencheck Baby-led Weaning:** Eine große Studie aus Neuseeland (BLISS) fand, dass angepasstes Baby-led Weaning (weiche, große Stücke, eisenreiches Essen bei jeder Mahlzeit) das Verschluckungsrisiko nicht erhöhte. Einen Vorteil beim Gewicht fand sie aber auch nicht (einzelne Studie). Brei, Fingerfood oder beides gemischt sind alle in Ordnung.
• **Kaufen?** Ein Hochstuhl mit Fußstütze. Stabile Füße erleichtern vielen Kindern das Sitzen und Kauen (Erfahrungswissen, kaum untersucht).

## Woche 28 · Fremdeln kündigt sich an

Zwischen etwa sechs und zehn Monaten beginnen viele Babys zu fremdeln. Sie schauen Unbekannte skeptisch an, klammern sich an euch oder weinen, wenn jemand Fremdes sie auf den Arm nehmen will. Laut CDC zeigen die meisten Babys mit neun Monaten dieses Verhalten.

🔬 Fremdeln ist kein Rückschritt, sondern ein Entwicklungsschritt. Euer Baby kann jetzt vertraute und fremde Menschen klar unterscheiden, und es hat eine Bindung zu euch aufgebaut. Wie stark gefremdelt wird, ist sehr unterschiedlich. Manche Babys fremdeln kaum.

💡 Gebt euer Baby nicht einfach weiter. Lasst Besuch sich erst langsam nähern, während euer Baby sicher bei euch ist.

📚 **Was sonst gerade läuft**

• **Spiel:** Babys lassen jetzt Dinge absichtlich fallen und schauen, wo sie landen. Wiederholung ist dabei der Kern: Was zwanzigmal gleich passiert, wird verstanden.
• **Trinken & Essen:** Trinken aus einem offenen Becher kann jetzt geübt werden, anfangs mit viel Kleckern. Ein offener Becher ist besser für Zähne und Mundmotorik als dauerndes Nuckeln an Flasche oder Schnabelbecher.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Neue Menschen langsam einführen: Babysitter oder Großeltern erst in eurer Anwesenheit kennenlernen lassen.
• **Spielidee:** Fallenlassen erlauben: Dinge vom Hochstuhl in eine Schüssel fallen lassen, aufheben, wieder von vorn.

## Woche 29 · In Bewegung

Viele Babys werden jetzt mobil, und zwar auf ganz verschiedene Arten: robben, sich im Kreis drehen, rollen, auf dem Po rutschen. Für das Krabbeln auf Händen und Knien fand die WHO-Studie ein Normalfenster von 5,2 bis 13,5 Monaten. Ein kleiner Teil der gesunden Kinder krabbelt nie und läuft später trotzdem ganz normal.

⚠️ **Zeit für Kindersicherung.** Am besten geht ihr einmal auf Knien durch die Wohnung: Treppenschutzgitter, Putzmittel und Medikamente hoch und verschlossen, Steckdosen, lose Kabel, giftige Pflanzen. Bei Vergiftungsverdacht hilft der Giftnotruf eures Bundeslandes (für Norddeutschland der Giftnotruf Nord unter 0551 19240), im Notfall die 112.

💡 Ein Erste-Hilfe-Kurs am Säugling gibt enorm viel Sicherheit. Viele Hebammen und Hilfsorganisationen bieten welche an.

📚 **Was sonst gerade läuft**

• **Schlaf:** Neue Bewegungen werden oft nachts „geübt“. Manche Babys setzen sich im Halbschlaf auf oder krabbeln durchs Bett. Studien fanden rund um den Krabbelbeginn tatsächlich häufiger nächtliches Aufwachen, meist vorübergehend.
• **Beziehung:** Mobile Babys entfernen sich, schauen zurück und kommen wieder. Die Bindungsforschung nennt das die „sichere Basis“: Weil ihr da seid, trauen sie sich auf Entdeckungstour.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Kleiner Parcours aus Kissen und Decken am Boden. Spielzeug knapp außer Reichweite legen.
• **Kaufen?** Jetzt lohnt sich Sicherheitsausstattung, aber nur, was ihr wirklich braucht: Treppenschutzgitter, eventuell Steckdosen- und Kantenschutz, Schrankverschlüsse für Putzmittel.

## Woche 30 · Gehfrei? Lieber nicht.

Wenn Babys mobiler werden, liegt die Idee nahe, ihnen mit einer Lauflernhilfe mit Sitz („Gehfrei“, „Baby-Walker“) zu helfen. Kinder- und Jugendärzte raten davon ab. Mit diesen Geräten passieren viele Unfälle, vor allem Treppenstürze, und sie helfen nicht beim Laufenlernen.

Auch für Hopser und langes Sitzen in Wippen gilt: kurz ist okay, aber Bewegung auf dem Boden ist für die motorische Entwicklung am wertvollsten.

💡 Barfuß oder mit rutschfesten Socken auf dem Boden: Das ist das beste Trainingsgerät.

📚 **Was sonst gerade läuft**

• **Schlaf:** Ob ihr sanfte Schlafprogramme nutzt oder nicht, ist eine Familienentscheidung. Eine australische Langzeitstudie (Price und Kollegen, 2012) fand fünf Jahre später weder Schäden noch Vorteile für die Kinder.
• **Trocken & sauber:** Mit Beikost kommt Verstopfung häufiger vor. Harte, kugelige Stühle und Schmerzen beim Stuhlgang sind ein Grund, mit der Kinderarztpraxis zu sprechen. Oft helfen ballaststoffreiche Breie, zum Beispiel mit Birne, und ausreichend Flüssigkeit.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Tunnel aus einem großen Karton (ohne Klammern) oder unter dem Tisch durchkrabbeln.
• **Gegenstände:** Kartons, Kissen, eine Matratze am Boden als Kletterberg.

## Woche 31 · Ba-ba-ba, da-da-da

Jetzt beginnt bei vielen Babys das Silbenplappern: Ketten aus Konsonant und Vokal wie „ba-ba-ba“ oder „da-da-da“. Fachleute sprechen von kanonischem Plappern. Aus diesen Silben werden später die ersten Wörter.

🔬 Dieser Meilenstein ist erstaunlich verlässlich: Die meisten Babys beginnen zwischen 6 und 10 Monaten damit. Forschung um den Sprachwissenschaftler D. Kimbrough Oller zeigte, dass ein Beginn erst nach 10 Monaten auf spätere Sprachschwierigkeiten oder eine Hörstörung hinweisen kann. Plappert euer Baby mit etwa zehn Monaten noch nicht in Silben, lasst das Gehör prüfen, auch wenn das Hörscreening nach der Geburt unauffällig war.

💡 Plappert zurück, singt, macht Fingerspiele. „Mamama“ ist übrigens meist noch kein Wort für Mama. Das kommt später.

📚 **Was sonst gerade läuft**

• **Wachstum:** In der zweiten Hälfte des ersten Jahres werden viele Babys schlanker. Der Body-Mass-Index erreicht um den 9. Monat seinen Höhepunkt und sinkt dann bis ins Vorschulalter. Der „Babyspeck“ verschwindet also ganz von selbst.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Silben-Ping-Pong: „Ba-ba?“ „Ba-ba!“ Dazu Kniereiter wie „Hoppe, hoppe Reiter“ und Fingerspiele.
• **Faktencheck Babyzeichen:** In der ersten randomisierten Studie dazu (Kirk und Kollegen, 2013) sprachen Kinder, deren Eltern Babyzeichen nutzten, weder früher noch mehr. Die Mütter reagierten aber feinfühliger auf nichtsprachliche Signale (einzelne Studie). Wenn es euch Spaß macht: gern, aber als Sprachturbo taugt es nicht.

## Woche 32 · Vom Rechen zur Pinzette

Die Feinmotorik entwickelt sich weiter. Kleine Dinge werden erst mit der ganzen Hand herangeholt, als würde man sie „rechen“ (laut CDC typisch mit neun Monaten). Nach und nach entsteht der Pinzettengriff mit Daumen und Zeigefinger, den die meisten Kinder mit etwa einem Jahr beherrschen.

Ebenfalls typisch: Dinge von einer Hand in die andere geben und zwei Gegenstände aneinanderschlagen. Großartig laut!

💡 Weiche Fingerfood-Stücke (gedünstete Möhre, Banane) sind Feinmotorik-Training und Essen zugleich. ⚠️ Kleinteile jetzt besonders konsequent wegräumen.

📚 **Was sonst gerade läuft**

• **Schlaf:** Die meisten Babys schlafen jetzt zweimal am Tag, vormittags und nachmittags.
• **Schreien:** Weinen wird zunehmend an euch gerichtet. Babys schauen beim Weinen zu euch und beruhigen sich oft schon, wenn ihr in Sichtweite kommt.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Dinge in Behälter mit großer Öffnung werfen: Bälle in einen Eimer, Klötze in eine Kiste.
• **Gegenstände:** Weiche, gegarte Erbsen oder Maiskörner auf dem Tablett sind perfektes Pinzettengriff-Training, gegessen wird unter Aufsicht.

## Woche 33 · Hochziehen und festhalten

Viele Babys ziehen sich jetzt an Möbeln, Gitterstäben oder euren Beinen hoch. Für das Stehen mit Festhalten fand die WHO-Studie ein Normalfenster von 4,8 bis 11,4 Monaten.

⚠️ Was als Klettergerüst taugt, wird eins. Befestigt Regale und Kommoden an der Wand, denn kippende Möbel verursachen schwere Unfälle. Stellt heiße Getränke nicht an die Tischkante und verzichtet auf herunterhängende Tischdecken. Verbrühungen gehören bei Babys und Kleinkindern zu den häufigsten schweren Verletzungen.

💡 Einige stabile, niedrige Möbel nebeneinander sind ein ideales Übungsgelände.

📚 **Was sonst gerade läuft**

• **Sprache:** Gesten kommen vor Wörtern: Arme hochstrecken, Kopfschütteln, Winken. Kinder, die früh viele Gesten nutzen, haben in Studien später tendenziell einen größeren Wortschatz.
• **Trinken & Essen:** Der Appetit schwankt jetzt stärker. An manchen Tagen essen Babys viel, an anderen kaum. Über mehrere Tage gleicht sich das meist aus.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Musik machen: Topf und Kochlöffel als Trommel, Rasseln, zusammen singen und dazu wippen.
• **Faktencheck Musikkurse:** In einer kanadischen Studie (Gerry und Kollegen, 2012) zeigten Babys, die ab sechs Monaten ein halbes Jahr lang aktiv mit ihren Eltern Musik machten, früher bestimmte Gesten und lächelten mehr als Babys, die nur Musik hörten (einzelne Studie). Entscheidend war das gemeinsame Mitmachen, nicht der Kurs an sich.

## Woche 34 · Protest beim Abschied

Viele Babys protestieren jetzt, wenn ihr den Raum verlasst. Sie weinen, krabbeln hinterher oder lassen sich schwer ablegen. Die CDC nennt „reagiert, wenn Sie gehen“ als Meilenstein mit neun Monaten. Dieser Trennungsprotest nimmt häufig bis ins zweite Lebensjahr hinein zu.

🔬 Dahinter steckt eine kognitive Leistung. Euer Baby weiß jetzt, dass ihr weiterexistiert, wenn ihr weg seid, kann aber noch nicht einschätzen, wann ihr wiederkommt.

💡 Verabschiedet euch kurz und klar, statt euch heimlich wegzuschleichen. So wird euer Wiederkommen vorhersehbar, und das schafft Vertrauen. Das hilft auch, wenn bald eine Kita-Eingewöhnung ansteht.

📚 **Was sonst gerade läuft**

• **Schlaf:** Trennungsprotest zeigt sich oft auch beim Einschlafen und nachts. Das ist ein vorübergehendes Entwicklungsthema und kein Zeichen, dass ihr etwas verlernt habt.
• **Trocken & sauber:** Wickeln wird zum Ringkampf, denn mobile Babys wollen weg. Wickeln auf dem Boden, ein besonderes Spielzeug nur fürs Wickeln oder ein Lied können helfen.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Trennung spielerisch üben: kurz hinter die Tür gehen, „Hier bin ich wieder!“ So wird Weggehen und Wiederkommen vorhersehbar (Erfahrungswissen, kaum untersucht).
• **Darauf eingehen:** Ein kurzes, immer gleiches Abschiedsritual, etwa Kuss, Winken und ein Satz, erleichtert Trennungen.

## Woche 35 · Dahin schauen, wo du hinschaust

Ein großer Schritt der kommenden Monate ist die „geteilte Aufmerksamkeit“. Euer Baby folgt zunehmend eurem Blick oder Zeigefinger und schaut zurück zu euch, um sich zu vergewissern, dass ihr dasselbe seht. In Studien entwickelt sich das vor allem zwischen etwa 9 und 15 Monaten.

🔬 Geteilte Aufmerksamkeit gilt als wichtige Grundlage für das Sprachlernen. Wörter lernen Babys besonders gut, wenn der Erwachsene benennt, was das Kind gerade anschaut.

💡 Folgt dem Blick eures Babys und benennt, was es sieht: „Ein Hund! Der Hund bellt.“

📚 **Was sonst gerade läuft**

• **Motorik:** Die Zürcher Studien um Remo Largo beschrieben sehr verschiedene Wege zum Laufen: neben Krabbeln auch Robben, Rollen oder Rutschen auf dem Po. Kinder, die auf dem Po rutschen, laufen oft etwas später frei, entwickeln sich aber sonst unauffällig.
• **Spiel:** Babys untersuchen jetzt, wie Dinge zusammengehören: Deckel auf die Dose, Löffel in den Becher. Dieses Kombinieren von Gegenständen beginnt meist zwischen etwa 9 und 18 Monaten.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Zeig-Spaziergang: am Fenster oder draußen auf Dinge zeigen, benennen, warten, ob euer Baby hinschaut.
• **Gegenstände:** Stapelbecher, Dosen mit Deckel, Topf mit Deckel.
• **Faktencheck Lesenlernen:** Programme, die Babys angeblich das Lesen beibringen, zeigten in einer kontrollierten Studie (Neuman und Kollegen, 2014) keine Wirkung. Die Eltern waren aber überzeugt, dass ihr Kind lesen lernte (einzelne Studie).

## Woche 36 · Verstehen kommt vor dem Sprechen

🔬 Babys verstehen viel mehr, als sie sagen können. In einer Studie (Bergelson und Swingley, 2012) schauten schon 6 bis 9 Monate alte Babys bei einfachen Wörtern wie „Apfel“ oder „Nase“ häufiger auf das passende Bild. Erste Wörter werden also verstanden, lange bevor das erste Wort gesprochen wird.

Viele Babys reagieren jetzt auf vertraute Wörter und Abläufe. „Wo ist der Papa?“, und der Kopf dreht sich.

💡 Schaut gemeinsam Bilderbücher an. Dabei geht es nicht ums Vorlesen des Textes, sondern ums Zeigen, Benennen und Warten.

📚 **Was sonst gerade läuft**

• **Trinken & Essen:** Selbst mit dem Löffel essen will geübt werden. Zwei Löffel helfen: einer für euer Baby, einer für euch.
• **Wachstum:** O-Beine und flache Füße sind bei Babys normal. Das Fußgewölbe bildet sich erst über die nächsten Jahre.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Im Bilderbuch fragen: „Wo ist der Hund?“, und dann warten, bis euer Baby schaut oder zeigt.
• **Kaufen?** Pappbücher, Stoffbücher und Fühlbücher. Tauschen mit anderen Eltern oder die Bibliothek sind günstige Alternativen.

## Woche 37 · Suchen am falschen Ort

🔬 Ein berühmtes Phänomen aus diesem Alter ist der „A-nicht-B-Fehler“. Versteckt man ein Spielzeug mehrmals unter Tuch A, findet das Baby es dort. Versteckt man es dann gut sichtbar unter Tuch B, sucht es trotzdem unter A. Das zeigt, dass Arbeitsgedächtnis und die Kontrolle über eingeübte Handlungen noch reifen. Diese Fähigkeiten hängen mit der Entwicklung des Stirnhirns zusammen und verbessern sich gegen Ende des ersten Lebensjahres.

💡 Versteckspiele unter Bechern oder Tüchern sind jetzt ideal. Probiert ruhig selbst aus, ob euer Baby in den A-nicht-B-Fehler tappt.

📚 **Was sonst gerade läuft**

• **Beziehung:** Ein Kuscheltier oder Schmusetuch wird für viele Kinder jetzt oder im zweiten Lebensjahr wichtig, als Stück Vertrautheit, wenn ihr nicht da seid. Im Schlafbett sollte es im ersten Jahr aber noch nicht liegen.
• **Trocken & sauber:** Die Windel bleibt noch lange nötig. In den Zürcher Studien waren tagsüber und nachts sicher trocken: mit zwei Jahren etwa 20 % der Kinder, mit vier Jahren etwa 90 %.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Becherspiel: Spielzeug unter einem von zwei umgedrehten Bechern verstecken und suchen lassen.
• **Gegenstände:** Zwei, drei Becher, Tücher, ein Lieblingsspielzeug.

## Woche 38 · Ein Blick zu euch: Ist das gefährlich?

Wenn euer Baby etwas Neues sieht, etwa einen lauten Staubsauger oder einen fremden Hund, schaut es jetzt zunehmend zuerst zu euch. Die Forschung nennt das „soziale Rückversicherung“.

🔬 In einem bekannten Experiment (Sorce und Kollegen, 1985) krabbelten einjährige Babys über eine scheinbare Kante auf einer Glasplatte, wenn die Mutter fröhlich schaute, aber kaum, wenn sie ängstlich schaute. Babys nutzen euren Gesichtsausdruck also als Information.

💡 Eure Gelassenheit ist ansteckend. Wenn ihr etwas Neues freundlich kommentiert, traut sich euer Baby mehr zu.

📚 **Was sonst gerade läuft**

• **Sprache:** Viele Babys verstehen jetzt einfache Aufforderungen im Zusammenhang, etwa „Gib mir den Ball“, wenn ihr dabei die Hand ausstreckt.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** „Gib mir“-Spiel: Hand ausstrecken, „Danke!“, zurückgeben, „Bitte!“
• **Darauf eingehen:** Begegnet Neuem freundlich und neugierig. Euer Gesichtsausdruck zeigt eurem Baby, ob es sicher ist.

## Woche 39 · Neun Monate: Bilanz

Was die meisten Babys (etwa 75 %) mit neun Monaten können, laut CDC:

• ist bei Fremden schüchtern oder ängstlich und reagiert, wenn ihr geht
• zeigt verschiedene Gesichtsausdrücke (fröhlich, traurig, wütend, überrascht)
• schaut, wenn man seinen Namen ruft, und lacht beim Guck-guck-Spiel
• plappert Silben wie „mamama“ und „bababa“ und streckt die Arme hoch, um hochgenommen zu werden
• sucht Dinge, die aus dem Blickfeld fallen, und schlägt zwei Dinge aneinander
• setzt sich selbst hin, sitzt ohne Stütze und gibt Dinge von einer Hand in die andere

Wie immer gilt: Einzelne fehlende Punkte sind kein Grund zur Sorge, aber gute Fragen für die U6. Reagiert euer Baby nicht auf seinen Namen **und** plappert es nicht in Silben, lasst das zeitnah ansehen. Dabei sollte unter anderem das Gehör geprüft werden.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Spielzeug rotieren und alte Lieblinge wieder hervorholen. Oft entdeckt euer Baby sie ganz neu.
• **Kaufen?** Für die nächsten Monate sinnvoll: Stapelbecher, ein weicher Ball, Pappbücher. Den Rest liefert der Haushalt.

## Woche 40 · Nachmachen mit Verzögerung

Euer Baby wird zum Nachahmer: Winken, Klatschen, „Backe, backe Kuchen“. Laut CDC spielen die meisten Kinder mit einem Jahr solche Spiele mit.

🔬 Babys können Handlungen sogar mit Zeitverzögerung nachmachen. In Experimenten von Andrew Meltzoff imitierten neun Monate alte Babys eine neue Handlung mit einem Spielzeug noch 24 Stunden, nachdem sie sie gesehen hatten. Das zeigt ein erstaunliches Gedächtnis.

💡 Macht einfache Handlungen deutlich vor: Deckel auf die Dose, Ball in die Kiste, Tschüss winken.

📚 **Was sonst gerade läuft**

• **Trinken & Essen:** Wie viel Kinder essen, ist sehr unterschiedlich und hängt mit Wachstum und Bewegung zusammen. Druck („Noch ein Löffel!“) führt in Studien eher dazu, dass Kinder weniger gern essen.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Alltag vormachen: Haare bürsten, mit dem Löffel rühren, Teddy füttern.
• **Gegenstände:** Echte, ungefährliche Alltagsgegenstände faszinieren oft mehr als Spielzeugversionen (Erfahrungswissen, kaum untersucht). Keine alten Handys oder Fernbedienungen mit Batterien in Reichweite.

## Woche 41 · Zeigen

In den nächsten Monaten kommt eine der wichtigsten Gesten: das Zeigen mit dem Zeigefinger. Zuerst meist, um etwas zu bekommen („Das will ich!“), etwas später auch, um etwas zu teilen („Schau mal, ein Vogel!“). Die CDC nennt das Zeigen, um Hilfe zu bekommen, als Meilenstein für 15 Monate und das Zeigen, um etwas Interessantes zu zeigen, für 18 Monate.

🔬 Das teilende Zeigen ist besonders spannend, weil es zeigt: Euer Kind will, dass ihr dasselbe seht wie es. Es ist eine der Grundlagen für Sprache und soziales Verstehen.

💡 Reagiert auf jedes Zeigen: hinschauen, benennen, gemeinsam staunen.

📚 **Was sonst gerade läuft**

• **Schlaf:** Die meisten Kinder brauchen jetzt noch zwei Tagschläfchen. Viele wechseln irgendwann zwischen 12 und 18 Monaten zu einem.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Fotoalbum mit Familienfotos: „Wo ist Oma?“ Zeigen, benennen, staunen.
• **Darauf eingehen:** Reagiert auf jedes Zeigen, auch wenn ihr gerade beschäftigt seid, zumindest mit einem Blick und einem Wort.

## Woche 42 · An den Möbeln entlang

Viele Babys hangeln sich jetzt seitlich an Sofa und Tisch entlang. Für das Laufen mit Festhalten fand die WHO-Studie ein Normalfenster von 5,9 bis 13,7 Monaten.

Schuhe braucht euer Baby dafür nicht. Barfuß spürt es den Boden am besten, und die Fußmuskulatur wird trainiert. Schuhe werden erst sinnvoll, wenn euer Kind draußen läuft.

💡 Schiebespielzeug ohne Sitz, etwa ein stabiler Lauflernwagen mit Griff (am besten mit Bremse), ist in Ordnung. Das ist etwas anderes als die „Gehfrei“-Geräte, in denen das Kind sitzt.

📚 **Was sonst gerade läuft**

• **Beziehung:** Andere Babys werden spannend: Säuglinge schauen einander an, lächeln und fassen sich an. Richtiges Miteinander-Spielen kommt aber erst viel später.
• **Wachstum:** Mit mehr Bewegung nehmen viele Babys langsamer zu. Das ist normal und kein Zeichen dafür, dass sie zu wenig essen.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Spielzeug auf dem Sofa verteilen, sodass euer Baby sich daran entlanghangelt.
• **Kaufen?** Lauflernschuhe braucht es nicht. Drinnen ist barfuß oder mit rutschfesten Socken am besten (Erfahrungswissen, kaum untersucht). Ein Schiebewagen mit Bremse ist optional.

## Woche 43 · Ran an den Familientisch

Laut Netzwerk Gesund ins Leben können Babys etwa ab dem 10. Monat langsam an die Familienkost herangeführt werden: weich gegarte Stücke, Brot, milde Familiengerichte, nur weniger salzig und scharf. Viele Babys wollen jetzt selbst essen, mit den Händen und mit dem Löffel.

🔬 Selbst zu essen ist motorisches und sensorisches Training. Dass es dabei chaotisch zugeht, gehört zum Lernen.

⚠️ Weiterhin gilt: kein Honig vor dem ersten Geburtstag, runde feste Lebensmittel (Trauben, Kirschtomaten) vierteln, keine ganzen Nüsse.

💡 Esst gemeinsam. Babys probieren eher Neues, wenn sie sehen, dass ihr es auch esst.

📚 **Was sonst gerade läuft**

• **Sprache:** Beim gemeinsamen Essen lässt sich viel sprechen: benennen, kommentieren, „Mehr?“ fragen und auf die Antwort warten.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Gemeinsam am Tisch essen, dieselben Lebensmittel, nur angepasst (weicher, weniger Salz).
• **Gegenstände:** Eigener Löffel, kleiner offener Becher, eine Schüssel mit Saugfuß.

## Woche 44 · „Nein“ verstehen und trotzdem machen

Laut CDC verstehen die meisten Kinder mit einem Jahr „Nein“ und halten kurz inne. Mehr aber noch nicht. Die Fähigkeit, einen Impuls zu unterdrücken, entwickelt sich erst über die nächsten Jahre. Dass euer Baby zum zehnten Mal zur Steckdose krabbelt, ist also kein Trotz, sondern Entwicklungsstand.

Auch das beliebte Spiel „Ich werfe den Löffel vom Hochstuhl“ ist Forschung: Was passiert, wenn ich loslasse? Und kommt der Löffel wieder?

💡 Die Umgebung zu gestalten wirkt besser als viele Verbote. Räumt weg, was nicht erlaubt ist, und bietet Alternativen an.

📚 **Was sonst gerade läuft**

• **Beziehung:** Grenzen und Bindung schließen sich nicht aus. Freundlich und beständig umzulenken gibt Kindern Sicherheit, auch wenn sie im Moment protestieren.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Umlenken statt vieler Neins: „Das ist Mamas Handy, hier ist deine Dose.“ Richtet „Ja-Zonen“ ein, in denen alles erlaubt ist.
• **Spielidee:** Werfen erlauben, wo es geht: weiche Bälle in einen Korb.

## Woche 45 · Erste Wörter in Sicht

Die ersten echten Wörter kommen bei vielen Kindern um den ersten Geburtstag herum, mit großer Spannbreite: manche früher, viele deutlich später. Laut CDC sagen die meisten Kinder mit einem Jahr „Mama“ oder „Papa“ (oder einen anderen besonderen Namen) gezielt zur richtigen Person. Auch „wauwau“ oder „ham“ zählen als Wörter, wenn sie immer dasselbe bedeuten.

💡 **Erweitern statt verbessern:** Sagt euer Kind „Ba!“ beim Ball, antwortet ihr „Ja, der Ball! Der rote Ball rollt.“ So hört es das richtige Wort, ohne korrigiert zu werden.

📚 **Was sonst gerade läuft**

• **Motorik:** Manche Babys krabbeln jetzt Treppen hoch. Runter ist schwieriger: rückwärts, auf dem Bauch, Füße zuerst. Das lässt sich unter Aufsicht üben.
• **Trocken & sauber:** Manche Kinder zeigen schon, dass sie eine volle Windel bemerken. Das Trockenwerden ist aber vor allem Reifung. In den Zürcher Studien (Largo und Kollegen) ließ es sich durch frühes oder intensives Training nicht beschleunigen.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Tierlaute-Spiel: „Wie macht der Hund?“ Und Lieder mit Pausen, in denen euer Kind ergänzen darf.
• **Kaufen?** Sprechendes Spielzeug ist nicht nötig. In einer Studie (Sosa, 2016) sprachen Eltern mit elektronischem Spielzeug weniger mit ihren Kindern als mit Büchern oder klassischem Spielzeug (einzelne Studie).

## Woche 46 · Und Bildschirme?

Die WHO empfiehlt für Kinder unter einem Jahr keine Bildschirmzeit. Der Grund ist weniger, dass Bildschirme „giftig“ wären, sondern dass sie Zeit verdrängen, in der Babys lernen: Bewegung, Spiel, Gespräche.

🔬 Babys lernen aus Videos deutlich schlechter als von echten Menschen, die Forschung spricht vom „Video-Defizit“. Außerdem zeigen Studien, dass Eltern weniger mit ihren Kindern sprechen, wenn im Hintergrund ein Fernseher läuft.

Videotelefonate mit Oma und Opa sind etwas anderes, denn da reagiert ein echter Mensch auf das Kind. Die amerikanische Kinderärztevereinigung AAP hält sie auch im ersten Lebensjahr für unproblematisch.

💡 Kein schlechtes Gewissen, aber wenn möglich: Fernseher aus, wenn das Baby im Raum spielt.

📚 **Was sonst gerade läuft**

• **Spiel:** Einfaches Spielzeug bringt mehr Gespräch. In einer Studie (Sosa, 2016) sprachen Eltern beim Spielen mit elektronischem Spielzeug weniger mit ihren Kindern als bei Büchern oder klassischem Spielzeug.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Für die Kochzeit statt Bildschirm: eine Küchenschublade mit Töpfen, Deckeln und Holzlöffeln, die euer Kind ausräumen darf.
• **Faktencheck Lern-Videos:** In einer Studie (DeLoache und Kollegen, 2010) lernten 12 bis 18 Monate alte Kinder aus einer beliebten Lern-DVD nicht mehr Wörter als ohne. Am meisten lernten sie, wenn Eltern die Wörter im Alltag benutzten. Eltern, die die DVD mochten, überschätzten den Lerneffekt (einzelne Studie).

## Woche 47 · Ein-, aus-, einräumen

Euer Baby wird zum Sortierer: Dinge in Kisten legen, wieder herausholen, von vorn. Laut CDC legen die meisten Kinder mit einem Jahr Gegenstände in einen Behälter. Dahinter stecken wichtige Konzepte wie „drinnen“ und „draußen“ und die Erfahrung, dass Dinge wieder auftauchen.

💡 Das beste Spielzeug steht oft in der Küche: eine Schüssel, ein paar Holzlöffel, Plastikdosen mit Deckeln.

📚 **Was sonst gerade läuft**

• **Schlaf:** Der Nachtschlaf verlängert sich im ersten Jahr nur wenig, in den Zürcher Studien von etwa 11 auf knapp 12 Stunden. Vor allem der Tagschlaf nimmt ab.
• **Trinken & Essen:** Ab etwa einem Jahr ist Kuhmilch als Getränk möglich, aber in Maßen, weil zu viel Milch die Aufnahme von Eisen aus dem Essen hemmt.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Ein-und-aus-Spiele: Dose mit Schlitz im Deckel und große Holzscheiben oder Bierdeckel zum Einwerfen.
• **Gegenstände:** Eine „freigegebene“ Schublade oder Kiste, die euer Kind jederzeit ausräumen darf.

## Woche 48 · Freies Stehen, erste Schritte?

Manche Babys stehen jetzt schon kurz frei, manche machen erste Schritte, viele brauchen noch Monate. Die WHO-Studie fand für das freie Laufen ein Normalfenster von 8,2 bis 17,6 Monaten, und zwar bei gesunden Kindern.

🔬 Früh laufen heißt nicht klüger. Eine Schweizer Langzeitstudie (Jenni und Kollegen, 2013) fand keinen Zusammenhang zwischen dem Alter beim ersten freien Laufen und der späteren Intelligenz oder Geschicklichkeit im Schulalter.

💡 An beiden Händen „Laufen üben“ ist nicht nötig. Kinder, die sich in ihrem Tempo hochziehen und loslassen, finden ihr Gleichgewicht selbst.

📚 **Was sonst gerade läuft**

• **Wachstum:** In der WHO-Studie hing die Körpergröße kaum mit dem Alter bei Meilensteinen zusammen. Größere Kinder waren nur um wenige Tage früher dran.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Spielzeug oben auf ein niedriges Möbelstück legen, das lockt zum Hochziehen und Stehen. An der Hand „laufen“ nur, wenn euer Kind es selbst will.
• **Kaufen?** Weiterhin keine Schuhe fürs Laufenlernen drinnen. Schuhe erst, wenn euer Kind draußen läuft.

## Woche 49 · Große Gefühle, wenig Werkzeuge

Frust wird jetzt häufiger. Euer Kind will mehr, als es kann: den Turm bauen, ans Regal, die Fernbedienung haben. Gefühle zu regulieren lernen Kinder über Jahre, und zwar zuerst gemeinsam mit euch. Ihr beruhigt, benennt und tröstet, und das Kind übernimmt nach und nach.

🔬 Die Sorge, Babys durch prompte Zuwendung zu „verwöhnen“, ist nach heutigem Forschungsstand unbegründet. Verlässliche Reaktion auf Bedürfnisse gilt als Grundlage einer sicheren Bindung.

💡 Benennt Gefühle: „Du bist wütend, weil der Turm umgefallen ist.“ Wörtlich versteht euer Kind das noch nicht, aber es lernt, dass Gefühle Namen haben und aushaltbar sind.

📚 **Was sonst gerade läuft**

• **Trinken & Essen:** Gegen Ende des ersten Jahres werden viele Kinder skeptischer gegenüber neuen Lebensmitteln. Wiederholt anbieten ohne Druck ist die beste Strategie.

🧸 **Was ihr jetzt tun könnt**

• **Darauf eingehen:** Bei Frust: kurz dabei sein, Gefühl benennen, helfen, statt die Aufgabe sofort komplett abzunehmen.
• **Spielidee:** Gefühlsgesichter im Spiegel oder Buch nachmachen: fröhlich, traurig, überrascht.

## Woche 50 · Hin und her

Spiele mit Abwechslung werden jetzt möglich: einen Ball hin- und herrollen, einen Gegenstand geben und zurücknehmen („Danke!“, „Bitte!“). Euer Baby versteht, dass ein Spiel Regeln und Rollen hat.

🔬 Solche Wechselspiele trainieren dasselbe wie ein Gespräch: aufeinander achten, warten, reagieren. Wie viel solches Hin und Her Kinder erleben, hängt in Studien mit ihrer Sprachentwicklung zusammen.

💡 Rollt einen Ball zu eurem Baby und wartet ab, ob er zurückkommt. Und wenn nicht: Mit dem Ball wegkrabbeln ist auch eine Antwort.

📚 **Was sonst gerade läuft**

• **Motorik:** Die Hände werden geschickter: Seiten im Pappbuch umblättern, bald auch zwei Klötze stapeln.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Ball hin- und herrollen, Dinge geben und nehmen, Turmbauen und Umwerfen im Wechsel.
• **Gegenstände:** Ein großer, weicher Ball und ein paar leichte Klötze.

## Woche 51 · Ein Jahr Gehirnentwicklung

🔬 Das Gehirn eures Babys hat im ersten Lebensjahr sein Volumen ungefähr verdoppelt. So stark wächst es danach nie wieder (Knickmeyer und Kollegen, 2008). Dabei entstehen vor allem sehr viele neue Verbindungen zwischen Nervenzellen, und die, die viel genutzt werden, werden gestärkt.

Wenn ihr zurückblickt: Aus einem Neugeborenen mit Reflexen ist ein Kind geworden, das euch erkennt, mit euch „spricht“, Ziele verfolgt, sich fortbewegt und Späße macht.

💡 Ein guter Zeitpunkt, alte Fotos anzuschauen und euch klarzumachen, was ihr in diesem Jahr alles geschafft habt.

🧸 **Was ihr jetzt tun könnt**

• **Spielidee:** Ein kleines Fotobuch vom ersten Jahr zum gemeinsamen Anschauen: „Wer ist das?“
• **Darauf eingehen:** Nehmt euch auch Zeit für euch. Ein Jahr mit Baby ist eine enorme Leistung.

## Woche 52 · Ein Jahr!

Herzlichen Glückwunsch, ein ganzes Jahr! 🎂 Was die meisten Kinder (etwa 75 %) mit einem Jahr können, laut CDC:

• spielt Spiele wie „Backe, backe Kuchen“ und winkt Tschüss
• sagt „Mama“, „Papa“ oder einen anderen besonderen Namen zur richtigen Person
• versteht „Nein“ und hält kurz inne
• sucht Dinge, die man vor seinen Augen versteckt, und legt Dinge in einen Behälter
• zieht sich zum Stehen hoch und läuft an Möbeln entlang
• trinkt aus einem offenen Becher, den ihr haltet, und greift mit Daumen und Zeigefinger

Denkt daran: Freies Laufen, viele Wörter oder das Zeigen dürfen noch deutlich später kommen.

Das war die letzte Wochennachricht. Danke, dass ich euch durch das erste Jahr begleiten durfte, und alles Gute für alles, was kommt!

🧸 **Was ihr jetzt tun könnt**

• **Kaufen?** Zum Geburtstag lieber wenige Geschenke und die übrigen später nach und nach hervorholen (Erfahrungswissen, kaum untersucht). Bücher und gemeinsame Zeit mit Oma und Opa sind oft die besten Geschenke.
• **Darauf eingehen:** Feiert kurz und in kleiner Runde. Zu viel Trubel überfordert viele Einjährige.

## Termine Woche 0 · bis Woche 1

• **U2** (3. bis 10. Lebenstag), oft noch in der Klinik. Dabei gibt es die zweite Vitamin-K-Gabe. Neugeborenen-Blutscreening und Hörscreening werden meist in den ersten Lebenstagen gemacht. Fragt nach, falls etwas fehlt.

## Termine Woche 0 · bis Woche 52

• **Vitamin D:** Die tägliche Vitamin-D-Gabe (meist als Tablette, oft kombiniert mit Fluorid) beginnt in der ersten Lebenswoche und läuft bis zum zweiten erlebten Frühsommer. Welches Präparat passt, klärt ihr mit Kinderarztpraxis oder Hebamme.

## Termine Woche 0 · bis Woche 8

• Falls noch nicht geschehen: Kinderarztpraxis suchen. Viele nehmen nur begrenzt neue Patienten auf.

## Termine Woche 1 · bis Woche 12

• **Papierkram mit Fristen:** Elterngeld wird rückwirkend nur für die letzten drei Lebensmonate vor dem Antragsmonat gezahlt, Kindergeld für sechs Monate. Also nicht zu lange warten. Meist braucht ihr dafür die Geburtsurkunde vom Standesamt.
• Euer Baby muss bei der Krankenkasse angemeldet werden (Familienversicherung).

## Termine Woche 2 · bis Woche 4

• **U3 vereinbaren:** Die U3 findet in der 4. bis 5. Lebenswoche statt. Dazu gehören ein Ultraschall der Hüfte, die dritte Vitamin-K-Gabe und ein Gespräch über die anstehenden Impfungen.

## Termine Woche 5 · bis Woche 11

• **Rotavirus-Impfung:** Die Schluckimpfung ist ab dem Alter von 6 Wochen möglich (je nach Impfstoff 2 oder 3 Dosen). Startet möglichst früh, weil die Impfserie bis zu einem bestimmten Alter abgeschlossen sein muss. Am besten macht ihr jetzt einen Termin.

## Termine Woche 8 · bis Woche 16

• **Impfungen mit 2 Monaten** (STIKO): Sechsfach-Impfung (Tetanus, Diphtherie, Keuchhusten, Hib, Kinderlähmung, Hepatitis B), Pneumokokken und Meningokokken B, dazu gegebenenfalls die nächste Rotavirus-Dosis.
• **U4** (3. bis 4. Lebensmonat). Sie lässt sich oft mit einem Impftermin verbinden.

## Termine Woche 12 · bis Woche 16 · nur Frühgeborene

• Weil euer Baby zu früh geboren wurde: Für Frühgeborene empfiehlt die STIKO mit 3 Monaten eine zusätzliche Dosis der Sechsfach- und der Pneumokokken-Impfung.

## Termine Woche 17 · bis Woche 21

• **Impfungen mit 4 Monaten:** jeweils die zweite Dosis der Sechsfach-Impfung, der Pneumokokken- und der Meningokokken-B-Impfung.

## Termine Woche 21 · bis Woche 30

• **U5 vereinbaren** (6. bis 7. Lebensmonat). Themen sind unter anderem Bewegung, Sehen, Ernährung und Zahnpflege.
• **Zahnärztliche Früherkennung:** Die Krankenkassen zahlen Untersuchungen beim Zahnarzt ab dem 6. Lebensmonat.

## Termine Woche 26 · bis Woche 52

• **Erster Zahn?** Bei manchen Babys jetzt, bei anderen erst in Monaten. Sobald er da ist: mit dem Zähneputzen beginnen und die Fluorid-Frage klären. Entweder weiter Tabletten mit Vitamin D **und** Fluorid, dann putzen ohne fluoridhaltige Zahnpasta. Oder Vitamin D ohne Fluorid, dann putzen mit einer reiskorngroßen Menge Kinderzahnpasta mit 1000 ppm Fluorid. Nicht beides kombinieren. So empfehlen es Kinder- und Zahnärzte seit 2021 gemeinsam.

## Termine Woche 38 · bis Woche 52

• **U6 vereinbaren** (10. bis 12. Lebensmonat).

## Termine Woche 47 · bis Woche 52

• **Impfungen mit 11 Monaten:** die dritte Dosis Sechsfach- und Pneumokokken-Impfung sowie die erste Dosis gegen Masern, Mumps, Röteln und Windpocken. Die Impfungen dürfen auf mehrere Termine verteilt werden. Kommt euer Kind früher in die Kita, ist die Masern-Impfung schon ab 9 Monaten möglich. Für die Kita ist ein Masernschutz gesetzlich vorgeschrieben.

## Termine Woche 52 · bis Woche 52

• **Meningokokken B:** dritte Dosis mit 12 Monaten. Mit 15 Monaten folgt die zweite Dosis gegen Masern, Mumps, Röteln und Windpocken.
• **Vitamin D** geht weiter bis zum zweiten erlebten Frühsommer.
• **Zähneputzen:** Ab 12 Monaten wird für alle Kinder zweimal täglich eine reiskorngroße Menge Zahnpasta mit 1000 ppm Fluorid empfohlen. Fluoridtabletten gibt es dann nicht mehr.
• Die nächste Vorsorge, die **U7**, ist mit 21 bis 24 Monaten.

## Saison rsv · Monate 9, 10 · bis Woche 30 · geboren Monate 4, 5, 6, 7, 8, 9

**Die RSV-Saison steht bevor.** Euer Baby wurde zwischen April und September geboren, jetzt steht also seine erste RSV-Saison an. Für diese Babys empfiehlt die STIKO, im Herbst einmalig einen Antikörper (Nirsevimab) zu geben, möglichst bevor die Saison richtig losgeht. RSV ist bei jungen Säuglingen einer der häufigsten Gründe für Krankenhausaufenthalte wegen Atemwegsinfekten. Sprecht die Kinderarztpraxis an, falls das noch nicht Thema war. Sie klärt auch, ob es bei euch nötig ist.

## Saison sommer · Monate 5, 6, 7, 8 · bis Woche 52

**Sommer mit Baby:** Babys im ersten Lebensjahr sollten nicht in die direkte Sonne. Besser sind Schatten, leichte, bedeckende Kleidung und ein Sonnenhut. Bei Hitze öfter stillen oder das Fläschchen anbieten, mit Beikost auch Wasser. Deckt den Kinderwagen nie mit einem Tuch ab, darunter staut sich die Hitze. Und lasst euer Baby niemals allein im Auto.

## Saison rsv-geburt · Monate 10, 11, 12, 1, 2, 3 · bis Woche 26 · geboren Monate 10, 11, 12, 1, 2, 3

**RSV-Schutz:** Euer Baby wurde in der RSV-Saison geboren (meist Oktober bis März). Für diese Babys empfiehlt die STIKO einen Antikörper (Nirsevimab) möglichst bald nach der Geburt, idealerweise vor der Entlassung aus der Klinik oder bei der U2. Falls das noch nicht passiert ist, sprecht die Kinderarztpraxis zeitnah darauf an.
