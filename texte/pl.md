# Teksty dla bota „Baby-Wochenbot” (polski)

Ten plik jest polskim tłumaczeniem pliku `de.md`. Obowiązują te same zasady:
- Każda sekcja zaczyna się nagłówkiem z dwoma krzyżykami (`## `). **Nagłówki pozostają po niemiecku** (`## Woche 5 · …`, `## Termine Woche 8`, `## Oberfläche`, `## Willkommen`, `## Saison …`). Tłumaczy się tylko tytuł po kropce.
- W sekcji `## Oberfläche` nie wolno zmieniać kluczy po lewej stronie dwukropka, tylko tekst po prawej. `\n` oznacza nowy wiersz, symbole zastępcze takie jak `{n}` czy `{url}` muszą zostać.
- `**pogrubienie**` jest wyświetlane w Telegramie pogrubioną czcionką.
- Wszystko powyżej pierwszego nagłówka (ten akapit) bot pomija.

Uwaga do tłumaczenia: niemieckie pojęcia z systemu ochrony zdrowia (badania U, STIKO, Elterngeld, 116 117 …) zostają zachowane i krótko wyjaśnione, ponieważ rodziny w Niemczech spotykają się właśnie z nimi u lekarza i w formularzach. Tekst zwraca się do rodziców w liczbie mnogiej („wy”). Tłumaczenie powinna sprawdzić osoba, dla której polski jest językiem ojczystym i która ma wykształcenie medyczne lub położnicze.

Źródła są wymienione w pliku `de.md`.

## Willkommen

Cześć! Jestem waszym botem Baby-Wochenbot. Od teraz będę się odzywać raz w tygodniu, w ten dzień tygodnia, w którym urodziło się wasze dziecko. Dowiecie się, co zazwyczaj dzieje się teraz w rozwoju dziecka, jak dobrze jest to potwierdzone naukowo, dostaniecie mały pomysł na codzienność oraz przypomnienia o zbliżających się badaniach profilaktycznych (U-Untersuchungen) i szczepieniach.

**Na początek trzy sprawy:**

**1. Każde dziecko rozwija się we własnym tempie.** Gdy piszę, że coś dzieje się „teraz”, mam na myśli: mniej więcej w tym czasie, u wielu dzieci. Zakres normy jest często ogromny. Samodzielne chodzenie pojawia się na przykład między nieco ponad 8 a prawie 18 miesiącem życia (badanie WHO). Listy kamieni milowych, które cytuję (amerykański urząd zdrowia CDC, 2022), opisują, co potrafi około 75% dzieci w danym wieku. Co czwarte dziecko jeszcze tego nie umie i to jest normalne.

**2. Kiedy nie czekać:** gdy dziecko traci umiejętności, które już pewnie opanowało, albo gdy macie utrzymujące się złe przeczucie. Jeśli chodzi o zdrowie fizyczne: gorączka od 38 °C w pierwszych trzech miesiącach życia, dziecko prawie nie pije, jest wyraźnie wiotkie lub trudno je obudzić, oddycha z wysiłkiem → tego samego dnia do pediatry. W nocy i w weekendy pomaga dyżur lekarski pod numerem 116 117, w nagłych przypadkach dzwońcie pod 112.

**3. Jestem tylko botem** i nie mogę odpowiadać. Nie zastępuję położnej ani gabinetu pediatrycznego.

**Co do dowodów naukowych:** zawsze dopisuję, na ile coś jest pewne: „dobrze udokumentowane” (kilka dobrych badań lub przeglądów), „pojedyncze badanie”, „wyniki badań niejednoznaczne” (badania sobie przeczą) albo „wiedza z doświadczenia, słabo zbadana” (prawdopodobne, ale nie sprawdzone naukowo).

## Oberfläche

sprache_name: 🇵🇱 Polski
bot_beschreibung: Raz w tygodniu krótka wiadomość o rozwoju waszego dziecka w pierwszym roku życia: co się teraz dzieje, jak dobrze jest to potwierdzone, pomysły na codzienność i zbliżające się badania w Niemczech. Bezpłatnie i bez reklam. Kliknijcie poniżej „Start”.
bot_kurzbeschreibung: Cotygodniowe informacje o rozwoju dziecka w pierwszym roku życia.
frage_sprache: 🌍 Wybierzcie język.
datenschutz: Miło, że jesteście! Krótko o ochronie danych, zanim zaczniemy: zapisuję tylko wasz identyfikator czatu, wybrany język, datę urodzenia dziecka oraz, jeśli ją podacie, wyliczoną datę porodu. Bot nie potrzebuje niczego więcej. Poleceniem /delete możecie w każdej chwili wszystko całkowicie usunąć.\n\nWszystkie szczegóły (po niemiecku): {url}
knopf_einverstanden: ✅ Zgadzam się
frage_geburtsdatum: Kiedy urodziło się wasze dziecko? Napiszcie datę w ten sposób: 14.08.2026
datum_ungueltig: Niestety nie mogę odczytać tej daty. Napiszcie ją w ten sposób: 14.08.2026
datum_zukunft: Ta data jest w przyszłości. Bot zaczyna działać od narodzin. Wróćcie, gdy dziecko będzie już na świecie!
datum_zu_alt: Wasze dziecko ma już ponad rok. Bot towarzyszy tylko pierwszemu rokowi życia. Gratulacje z okazji tego kamienia milowego!
frage_frueh: Czy wasze dziecko urodziło się ponad trzy tygodnie przed wyliczonym terminem porodu?
knopf_ja: Tak
knopf_nein: Nie
frage_et: Jaki był wyliczony termin porodu? Napiszcie datę w ten sposób: 14.08.2026
et_ungueltig: Wyliczony termin musi przypadać po dacie urodzenia, najpóźniej 20 tygodni później. Sprawdźcie datę jeszcze raz.
fertig: Wszystko gotowe! Od teraz {wochentag} rano przyjdzie wiadomość. Pod /help zobaczycie, co jeszcze potrafię.
geaendert: Dane zostały zaktualizowane. Oto wiadomość na bieżący tydzień.
wochentage: w każdą niedzielę, w każdy poniedziałek, w każdy wtorek, w każdą środę, w każdy czwartek, w każdy piątek, w każdą sobotę
kopf_woche0: 👶 **Wasze dziecko jest w pierwszym tygodniu życia**
kopf_woche1: 👶 **Wasze dziecko ma już 1 tydzień**
kopf_wochen: 👶 **Wasze dziecko ma już {n} tyg.**
korrigiert: Wiek skorygowany: {k} tyg. Na nim opierają się informacje o rozwoju.
vor_et: Liczba dni do wyliczonego terminu porodu: {tage}. Informacje o rozwoju zaczną się od wyliczonego terminu, do tego czasu będą tylko terminy i wskazówki zdrowotne.
termine_titel: 📅 **Terminy i zdrowie**
hilfe: Tak możecie mną sterować:\n/week – jeszcze raz wiadomość na bieżący tydzień\n/change – zmiana daty urodzenia\n/language – zmiana języka\n/pause – wstrzymanie wiadomości\n/resume – wznowienie wiadomości\n/delete – usunięcie wszystkich danych\n\nJestem botem i niestety nie mogę odpowiadać na pytania. Jeśli martwicie się o dziecko, pomogą położna i gabinet pediatryczny, w nocy i w weekendy dyżur lekarski pod numerem 116 117, w nagłych przypadkach 112.
befehl_week: Wiadomość na bieżący tydzień
befehl_change: Zmień datę urodzenia
befehl_language: Zmień język
befehl_pause: Wstrzymaj wiadomości
befehl_resume: Wznów wiadomości
befehl_delete: Usuń wszystkie dane
befehl_help: Pomoc
schon_angemeldet: Jesteście już zapisani. Poleceniem /week otrzymacie jeszcze raz bieżącą wiadomość, a poleceniem /change zmienicie datę urodzenia.
nicht_angemeldet: Nie jesteście jeszcze zapisani. Zacznijcie od /start.
pausiert: Wiadomości zostały wstrzymane. Poleceniem /resume wznowicie je.
fortgesetzt: Wracamy! Następna wiadomość przyjdzie jak zwykle, {wochentag}.
loeschen_frage: Naprawdę usunąć wszystkie dane? Potem nie będziecie już otrzymywać wiadomości.
knopf_loeschen: 🗑️ Tak, usuń wszystko
knopf_abbrechen: Anuluj
geloescht: Wszystkie dane zostały usunięte. Wszystkiego dobrego! Poleceniem /start możecie w każdej chwili zacząć od nowa.
abgebrochen: Wszystko zostaje bez zmian.
sprache_gewechselt: Językiem jest teraz polski.
unbekannt: Jestem botem i niestety nie mogę odpowiadać na wiadomości. Pod /help zobaczycie, co potrafię.
abschluss: Towarzyszenie przez pierwszy rok życia dobiegło końca. Dziękuję, że byliście ze mną!

## Woche 0 · Przybycie na świat

Pierwszy tydzień życia to przede wszystkim przestawianie się: oddychanie, krążenie, trawienie i regulacja temperatury po raz pierwszy działają zupełnie bez łożyska. To normalne, że noworodki w pierwszych dniach nieco tracą na wadze. Zwykle wracają do masy urodzeniowej po 10–14 dniach, a położna ma to na oku.

Zmysły są na różnym etapie. Słuch działa już dobrze, a badania pokazują, że noworodki rozpoznają głos mamy, który znają z brzucha. Wzrok jest za to jeszcze bardzo nieostry. Najlepiej widzą z odległości około 20–30 centymetrów, czyli mniej więcej z takiej, z jakiej patrzą na waszą twarz podczas karmienia piersią lub butelką.

Wiele z tego, co wasze dziecko teraz robi, to wrodzone odruchy: szukanie i ssanie, mocne chwytanie waszego palca, wzdrygnięcie się z rozrzuconymi rękami przy nagłym dźwięku (odruch Moro). Te odruchy znikają w ciągu najbliższych miesięcy i ustępują miejsca celowym ruchom.

⚠️ **Bezpieczny sen** (dobrze udokumentowane, dotyczy całego pierwszego roku): zawsze na plecach, w sypialni rodziców, w śpiworku zamiast pod kołdrą, na twardym materacu bez poduszek, ochraniaczy i przytulanek, w pomieszczeniu wolnym od dymu tytoniowego i nie za ciepłym (około 16–18 °C). Zaleca się też, aby nie zasypiać razem z dzieckiem na kanapie ani w fotelu, ponieważ dziecko może tam wsunąć się w szczelinę między obiciem a ciałem albo znaleźć się w pozycji, w której trudno mu oddychać. To jedno z najlepiej udokumentowanych zagrożeń (dobrze udokumentowane). Przytulanie dziecka, gdy nie śpicie, albo odpoczynek na kanapie z dzieckiem w nosidle lub na brzuchu nie stanowi natomiast problemu. Jeśli zauważycie, że zamykają wam się oczy, połóżcie dziecko do jego łóżeczka albo idźcie razem do łóżka. To bezpieczniejszy wybór.

🔬 **Własne łóżeczko czy wspólne łóżko?** Tu specjaliści nie są zgodni i chcemy to otwarcie powiedzieć. Oficjalne niemieckie instytucje (BIÖG, DGKJ) zalecają przede wszystkim własne łóżeczko lub łóżeczko dostawne w sypialni rodziców. Wielu badaczy karmienia piersią i snu ocenia to bardziej szczegółowo: wspólne spanie znacznie ułatwia nocne karmienie piersią, a karmienie piersią zmniejsza ryzyko nagłej śmierci łóżeczkowej (SIDS) mniej więcej o połowę. W analizach badań brytyjskich (Blair i współpracownicy) wspólne łóżko było niebezpieczne głównie wtedy, gdy dochodziły inne czynniki ryzyka. Bez nich nie stwierdzono mierzalnie wyższego ryzyka. Inni badacze (np. Tappin, Mitchell i współpracownicy) widzą jednak niewielkie ryzyko resztkowe, zwłaszcza u niemowląt poniżej trzech miesięcy (wyniki badań niejednoznaczne).

⚠️ Wszystkie strony są zgodne co do tego, kiedy wspólne spanie jest **wyraźnie bardziej niebezpieczne** (dobrze udokumentowane): gdy ktoś w łóżku pali albo w ciąży palono, po alkoholu, narkotykach lub lekach wywołujących senność, przy skrajnym wyczerpaniu, gdy dziecko urodziło się przedwcześnie lub z bardzo niską masą urodzeniową albo gdy nie jest karmione piersią.

**Jeśli śpicie razem:** twardy materac bez szczeliny przy ścianie, dziecko na plecach obok karmiącej mamy, a nie między rodzicami, we własnym śpiworku, bez kołdry dla dorosłych i poduszek w pobliżu, bez rodzeństwa i zwierząt w łóżku. Łóżeczko dostawne łączy bliskość z własnym miejscem do spania. Zdecydujcie świadomie, co do was pasuje, i porozmawiajcie o tym z położną.

💡 Teraz niczego więcej nie potrzeba: bliskości, kontaktu skóra do skóry, waszej twarzy i waszego głosu. „Programy stymulacji” są w tym wieku zbędne.

📚 **Co jeszcze się dzieje**

• **Picie i jedzenie:** W pierwszych tygodniach niemowlęta jedzą zwykle 8–12 razy na dobę, często nieregularnie. Wczesne oznaki głodu to szukanie ustami, cmokanie i wkładanie rączki do buzi. Płacz jest raczej późnym sygnałem.
• **Pieluszki i nocnik:** Pierwszy stolec (smółka) jest czarnozielony i lepki. W pierwszych dniach staje się zielonkawy, a potem, przy mleku mamy, musztardowożółty.
• **Wzrost:** Zdrowe donoszone noworodki ważą zwykle od 2,5 do 4 kilogramów i mają około 50 centymetrów długości. Wymiary urodzeniowe mówią głównie o warunkach w brzuchu, mniej o późniejszym wzroście.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Reagujcie na sygnały dziecka, czyli głód, zmęczenie i potrzebę bliskości. Według obecnego stanu badań szybkie pocieszanie nie rozpieszcza.
• **Pomysł na zabawę:** Kontakt skóra do skóry, wasza twarz w odległości 20–30 cm, cicha rozmowa albo nucenie. Żaden dodatkowy „program” nie jest potrzebny.
• **Czy coś kupować?** Do stymulacji rozwoju nic. Ważne są bezpieczne miejsce do spania, śpiworek w odpowiednim rozmiarze i fotelik samochodowy dla niemowląt.

## Woche 1 · Rytm? Jeszcze nie.

Noworodki dużo śpią, mniej więcej 14–17 godzin na dobę, ale krótkimi odcinkami, rozłożonymi na dzień i noc. Wewnętrzny zegar z rytmem dnia i nocy rozwija się dopiero w ciągu najbliższych tygodni i miesięcy. To, że wasze dziecko w nocy budzi się równie często jak w dzień, nie jest więc błędem, tylko biologią.

W tych dniach często pojawia się **żółtaczka noworodków**. Zaczyna się zwykle od drugiego lub trzeciego dnia i z reguły jest niegroźna. Warto jednak skonsultować ją z lekarzem, jeśli dziecko jest bardzo żółte, jeśli zażółcenie narasta po pierwszym tygodniu albo jeśli dziecko jest wyraźnie senne i słabo je.

⚠️ Przyjrzyjcie się **karcie kolorów stolca** w żółtej książeczce badań dziecka (gelbes Kinderuntersuchungsheft). Bardzo jasny, gliniasty lub szarobiały stolec może wskazywać na rzadką, ale pilną chorobę dróg żółciowych. Wtedy szybko do pediatry.

💡 W dzień światło dzienne i codzienne odgłosy, w nocy przyciemnione światło i mało atrakcji: to pomaga wewnętrznemu zegarowi się ustawić.

📚 **Co jeszcze się dzieje**

• **Relacje:** Więź nie powstaje w krótkim okienku zaraz po porodzie. Przypuszczenie, że istnieje decydująca „faza wdrukowania”, się nie potwierdziło. Jeśli początek był trudny, na przykład po cesarskim cięciu lub pobycie w szpitalu, więź i tak rośnie przez tygodnie i miesiące codziennego życia.
• **Pieluszki i nocnik:** Mniej więcej od piątego dnia pięć, sześć lub więcej porządnie mokrych pieluszek dziennie to dobry znak, że dziecko pije wystarczająco. Mocz powinien być jasny.
• **Motoryka:** Wiercące się, płynne ruchy całego ciała u noworodków nazywa się „ruchami globalnymi” (General Movements). Ich jakość jest tak wymowna, że specjaliści wykorzystują je do wczesnego wykrywania zaburzeń ruchowych.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Uczcie się „języka” dziecka: ziewanie, odwracanie wzroku, wiercenie się lub prężenie często oznaczają „na razie wystarczy” (wiedza z doświadczenia, słabo zbadana).
• **Czy coś kupować?** Chusta lub nosidło to wygodny sposób na bliskość z wolnymi rękami. Zwróćcie uwagę, aby twarz dziecka była odsłonięta, broda nie opierała się o klatkę piersiową, a dziecko było ułożone pionowo i blisko waszego ciała.

## Woche 2 · Wieczorny maraton przy piersi

Wiele niemowląt ma teraz okresy, zwykle wieczorem, w których zdaje się chcieć jeść godzinami, krótko śpi i znowu je („karmienie klasterowe”). To częste zjawisko i nie oznacza, że mleka jest za mało. To, czy dziecko dostaje wystarczająco dużo, lepiej pokazują mokre pieluszki, przyrost masy ciała i zadowolenie między karmieniami. Położna potrafi to dobrze ocenić.

🔬 **Skoki wzrostowe?** Często słyszy się o stałych tygodniach skoków wzrostowych. Badania pomiarowe rzeczywiście pokazują, że niemowlęta rosną raczej skokowo niż równomiernie. Nie da się jednak przewidzieć na podstawie stałych tygodni, kiedy nastąpi skok.

**A wy?** Obniżony nastrój z częstym płaczem w pierwszych dniach po porodzie („baby blues”) zdarza się bardzo często i zwykle mija po kilku dniach. Jeśli przygnębienie trwa dłużej niż około dwa tygodnie lub jest bardzo silne, może to być depresja poporodowa. Dotyczy ona około 10–15% matek, mogą na nią zachorować także ojcowie, i dobrze się ją leczy. W takiej sytuacji porozmawiajcie z położną, lekarzem rodzinnym lub ginekologiem. Informacje (po niemiecku) znajdziecie na stronie schatten-und-licht.de

💡 Przyjmowanie pomocy to nie luksus: niech ktoś przyniesie wam jedzenie, ograniczcie wizyty, śpijcie, kiedy tylko się da.

📚 **Co jeszcze się dzieje**

• **Mowa:** Noworodki płaczą z melodią języka swojego otoczenia. W jednym badaniu (Mampe i współpracownicy, 2009) niemieckie noworodki miały raczej opadającą, a francuskie raczej wznoszącą się melodię płaczu. Nauka języka zaczyna się więc już w brzuchu.
• **Wzrost:** Gdy dziecko odzyska masę urodzeniową, w pierwszych miesiącach przybiera często 150–250 gramów tygodniowo. Pojedyncze tygodnie mogą wyraźnie odbiegać w górę lub w dół.
• **Pieluszki i nocnik:** Stolec przy mleku mamy jest żółty, miękki do płynnego i na początku pojawia się często niemal po każdym karmieniu. Przy mleku modyfikowanym jest zwykle twardszy i bardziej brązowy.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Śpiewajcie! Nieważne jakie piosenki i nieważne, czy czysto. Niemowlęta wolą znajomy głos od idealnej muzyki.
• **Jak reagować:** Na długie wieczory karmienia: urządźcie sobie wygodne miejsce, trzymajcie wodę i przekąskę dla siebie pod ręką, włączcie serial albo audiobooka. Wasze samopoczucie też się liczy.

## Woche 3 · Twarze są najciekawsze

Już noworodki wolą patrzeć na wzory przypominające twarz: dwie kropki u góry i jedną pod nimi. Teraz ich spojrzenie staje się dłuższe i bardziej skupione. Wiele niemowląt wpatruje się w waszą twarz i krótko podąża za nią wzrokiem, gdy się powoli poruszacie.

🔬 **Przykład, dlaczego ważne jest umieszczanie wiedzy w kontekście:** W 1977 roku badacze donieśli, że noworodki naśladują pokazywanie języka. Przez dziesięciolecia było to w podręcznikach. Duże badanie z 2016 roku z udziałem ponad 100 niemowląt nie potwierdziło jednak tego efektu. To, czy noworodki naprawdę naśladują, jest dziś otwartym pytaniem.

💡 Spróbujcie mimo to: twarz w odległości 20–30 cm, język na wierzch, buzia otwarta, uśmiech, a potem czekajcie. Czy dziecko was naśladuje, czy nie, i tak jesteście dla niego fascynujący.

📚 **Co jeszcze się dzieje**

• **Płacz:** Wielu rodziców ma nadzieję, że po dźwięku rozpozna, czy dziecko jest głodne, czy boli je brzuszek. Badania pokazują, że udaje się to tylko w ograniczonym stopniu. Bardziej pomocny jest kontekst: kiedy dziecko ostatnio jadło, spało, miało zmienianą pieluszkę?
• **Picie i jedzenie:** Dziecko karmione piersią lub mlekiem modyfikowanym nie potrzebuje wody ani herbatki, nawet w upały. Mleko w pełni pokrywa zapotrzebowanie na płyny.
• **Relacje:** Drugi rodzic też szybko staje się bliską osobą. Kontakt skóra do skóry, noszenie, kąpiel i przewijanie to dobre okazje, niezależnie od tego, kto karmi.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Powoli przesuwajcie twarz lub kontrastową chustkę z jednej strony na drugą, aby dziecko mogło podążać wzrokiem. Wystarczą jedna, dwie minuty.
• **Czy coś kupować?** Czarno-białe karty kontrastowe nie szkodzą, ale nie mają udowodnionego wpływu na rozwój (wiedza z doświadczenia, słabo zbadana). Wasza twarz jest ciekawsza.
• **Jak reagować:** Gdy dziecko odwraca wzrok, to nie brak zainteresowania, tylko przerwa. Poczekajcie, aż samo znowu poszuka kontaktu wzrokowego.

## Woche 4 · Czas na brzuszku

Spanie na plecach, zabawa na brzuszku: to podstawowa zasada. Leżąc na brzuszku, niemowlęta ćwiczą unoszenie główki i wzmacniają kark, barki i plecy. Czas na brzuszku zapobiega też spłaszczeniu tyłu główki, które może powstać przy dużej ilości czasu na plecach.

Dla niemowląt, które jeszcze same się nie przemieszczają, WHO zaleca łącznie co najmniej 30 minut na brzuszku w ciągu dnia, w czasie czuwania i pod nadzorem. Może to być wiele krótkich porcji.

Wiele niemowląt na początku protestuje. To normalne, a na początek wystarczy minuta czy dwie.

💡 Najprostszy start: połóżcie się w pozycji półleżącej, a dziecko brzuszkiem na waszej klatce piersiowej. Wasza twarz to najlepsza motywacja do unoszenia główki.

📚 **Co jeszcze się dzieje**

• **Sen:** Zuryskie badania podłużne (Iglowstein, Largo i współpracownicy, 2003) pokazują, jak różne jest zapotrzebowanie na sen. Nawet wśród środkowej połowy dzieci w wieku sześciu miesięcy różnica wynosiła dwie i pół godziny. Wasze dziecko może więc potrzebować wyraźnie więcej lub mniej snu niż inne.
• **Zabawa:** W tym wieku zabawa oznacza przede wszystkim patrzenie, słuchanie, odkrywanie twarzy. Niemowlęta pokazują, kiedy mają dość, na przykład odwracając wzrok, ziewając lub marudząc. Wtedy pomaga przerwa.
• **Wzrost:** Główka rośnie teraz szczególnie szybko, w pierwszych miesiącach o około dwa centymetry miesięcznie. Dlatego obwód głowy jest mierzony przy każdym badaniu U.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Czas na brzuszku to nie tylko podłoga: na waszej klatce piersiowej, w poprzek na waszych udach albo w chwycie „na samolot” podczas noszenia.
• **Przedmioty:** Zwinięty ręcznik pod klatką piersiową ułatwia niektórym niemowlętom unoszenie główki, oczywiście tylko pod nadzorem (wiedza z doświadczenia, słabo zbadana).
• **Czy coś kupować?** Mata edukacyjna z pałąkiem jest miła, ale niekonieczna. Wystarczy koc na podłodze.

## Woche 5 · Dużo płaczu: co jest normalne?

W tych tygodniach niemowlęta średnio najwięcej płaczą i marudzą. Duża analiza 28 badań z udziałem około 8700 niemowląt (Wolke i współpracownicy, 2017) wykazała, że w pierwszych sześciu tygodniach jest to średnio około dwóch godzin dziennie, przy ogromnej rozpiętości od pół godziny do ponad pięciu godzin. Po około ośmiu, dziewięciu tygodniach płacz wyraźnie się zmniejsza, a w wieku trzech miesięcy średnio mniej więcej o połowę.

🔬 **A „skoki rozwojowe”?** Książka „The Wonder Weeks” (niem. „Oje, ich wachse!”) umieszcza tutaj pierwszy skok rozwojowy. Niespokojne okresy naprawdę się zdarzają. To, że u wszystkich niemowląt przypadają na stałe tygodnie, zbadano jednak tylko na małych grupach i nie jest to wiarygodnie potwierdzone. Wspomniana duża analiza nie wykazała na przykład jednolitego szczytu płaczu w dokładnie tym samym tygodniu.

⚠️ **Nigdy nie potrząsajcie dzieckiem.** Nawet krótkie potrząśnięcie może spowodować zagrażające życiu uszkodzenia mózgu. Jeśli czujecie, że jesteście u kresu sił: połóżcie dziecko bezpiecznie do łóżeczka, wyjdźcie na chwilę, odetchnijcie, zadzwońcie do kogoś. Wsparcie oferują poradnie dla niemowląt z nadmiernym płaczem (Schreiambulanz; gabinet pediatryczny wie, gdzie są) oraz bezpłatny telefon dla rodziców Elterntelefon pod numerem 0800 111 0 550 (po niemiecku).

💡 Często mniej znaczy więcej: noszenie, przyciemnione światło, równomierny szum lub nucenie, zamiast ciągłego próbowania czegoś nowego.

📚 **Co jeszcze się dzieje**

• **Picie i jedzenie:** Wiele niemowląt po karmieniu ulewa trochę mleka. To niegroźne, dopóki dziecko dobrze przybiera na wadze. Skonsultujcie z lekarzem chlustające wymioty po karmieniach, zielonkawe lub krwiste wymiociny albo brak przyrostu masy ciała.
• **Relacje:** Dużo płaczu w pierwszych tygodniach nie oznacza, że robicie coś źle. To, ile dziecko płacze, zależy przede wszystkim od samego dziecka.
• **Motoryka:** Gdy dziecko leżące na plecach odwraca główkę w bok, często prostuje rączkę po tej stronie, a drugą zgina („pozycja szermierza”). Ten odruch zwykle znika w ciągu najbliższych miesięcy.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Sprawdzona kolejność przy płaczu: najpierw potrzeby podstawowe (głód, pieluszka, za ciepło lub za zimno), potem ograniczenie bodźców, noszenie, równomierne kołysanie, nucenie (wiedza z doświadczenia, słabo zbadana). Nie każdy płacz da się zatrzymać, a samo bycie przy dziecku też jest pocieszeniem.
• **Sprawdzamy fakty – kolka:** Krople na wzdęcia (symetykon) według badań nie działają lepiej niż placebo. U niemowląt karmionych piersią z kolką są przesłanki, że określony probiotyk (L. reuteri DSM 17938) zmniejsza płacz, u karmionych butelką nie (wyniki badań niejednoznaczne). Omówcie to z gabinetem pediatrycznym. Na skuteczność osteopatii, chiropraktyki i masażu niemowląt przy kolce brakuje dobrych dowodów.
• **Sprawdzamy fakty – noszenie:** W jednym badaniu (Hunziker i Barr, 1986) niemowlęta, które były dodatkowo dużo noszone, płakały wyraźnie mniej. Dwa późniejsze badania nie wykazały tego efektu (wyniki badań niejednoznaczne). Noszenie jednak nie szkodzi.
• **Czy coś kupować?** Jeśli używacie urządzenia z szumem, ustawcie je cicho i nie tuż przy główce. Otulanie (pucken) jest kontrowersyjne: jeśli już, to tylko na plecach, z luźno poruszającymi się biodrami i już nie wtedy, gdy dziecko mogłoby się przekręcić (wiedza z doświadczenia, słabo zbadana).

## Woche 6 · Pierwszy prawdziwy uśmiech

Zwykle gdzieś w tych tygodniach to się dzieje: dziecko patrzy na was i się uśmiecha. Nie we śnie, nie przypadkiem, ale w odpowiedzi na waszą twarz lub głos. Ten „uśmiech społeczny” pokazuje większość niemowląt do około drugiego miesiąca życia.

Do tego dochodzą pierwsze dźwięki, które nie są płaczem: małe gruchanie i gardłowe odgłosy. Niemowlęta zaczynają reagować, gdy się do nich mówi.

🔬 Dla nauki uśmiech jest punktem zwrotnym: od teraz relacja jest widocznie wzajemna.

💡 Uśmiechajcie się w odpowiedzi, mówcie, a potem zróbcie pauzę. Dziecko potrzebuje czasu, żeby „odpowiedzieć”.

📚 **Co jeszcze się dzieje**

• **Pieluszki i nocnik:** U niemowląt karmionych piersią wypróżnienia po około sześciu tygodniach często stają się rzadsze. Wszystko od kilku razy dziennie do raz na siedem do dziesięciu dni jest normalne, o ile stolec jest miękki, a dziecko dobrze się rozwija. U niemowląt karmionych butelką długie przerwy i twardy stolec są raczej powodem, by zapytać lekarza.
• **Sen:** Według badań smoczek przy zasypianiu zmniejsza ryzyko nagłej śmierci łóżeczkowej. U niemowląt karmionych piersią najlepiej proponować go dopiero wtedy, gdy karmienie piersią jest dobrze ustabilizowane, i nie wciskać go na siłę, jeśli dziecko go nie chce.
• **Mowa:** Pierwsze gruchanie to głównie samogłoski, takie jak „aaa” i „ooo”. Spółgłoski dochodzą później.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Dialog uśmiechów: uśmiech, czekanie, uśmiech w odpowiedzi. Niemowlęta uwielbiają małe niespodzianki, takie jak szeroko otwarte oczy albo „Oo!”, ale w małych dawkach.
• **Jak reagować:** Naśladujcie dźwięki i mimikę dziecka. To „odzwierciedlanie” pokazuje mu, że jest widziane.

## Woche 7 · Małe rozmowy

Już teraz powstają wymiany: wy mówicie, dziecko patrzy i grucha, wy odpowiadacie. Specjaliści nazywają to „protokonwersacją”, czyli strukturą rozmowy na długo przed pojawieniem się słów.

🔬 **Eksperyment „kamiennej twarzy”** (Tronick, 1978): gdy mamy podczas zabawy nagle nieruchomo patrzą w pustkę, kilkumiesięczne niemowlęta najpierw próbują je „przywołać” uśmiechem i dźwiękami, a potem stają się niespokojne. Niemowlęta oczekują więc reakcji. Ważne: codzienne przerwy w kontakcie nie szkodzą. Liczy się to, że kontakt raz po raz się odnawia.

💡 Typowy wysoki, melodyjny sposób mówienia do niemowląt to nie bzdura. Badania pokazują, że niemowlęta wolą go słuchać, a on wspiera naukę języka.

📚 **Co jeszcze się dzieje**

• **Zabawa:** Niemowlęta zwracają się ku nowym rzeczom i krócej patrzą na znane. Badacze wykorzystują właśnie to, aby sprawdzić, co niemowlęta potrafią rozróżnić. Dla was oznacza to: różnorodność jest dobra, ale w małych dawkach.
• **Wzrost:** W żółtej książeczce masa ciała, długość i obwód głowy są nanoszone na siatki centylowe. 50. centyl to średnia, wszystko między 3. a 97. uznaje się za zakres normy. Ważniejsze od położenia jest to, żeby dziecko mniej więcej trzymało się swojej krzywej.
• **Picie i jedzenie:** Również przy butelce: karmcie na żądanie i szanujcie oznaki sytości, takie jak odwracanie główki lub wolniejsze ssanie. Mleko początkowe („Pre” lub „1”) można podawać przez cały pierwszy rok, mleko następne według niemieckiej sieci Gesund ins Leben nie jest potrzebne.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Relacja z przewijania: opowiadajcie, co robicie („Teraz świeża pieluszka”), i zostawiajcie pauzy na „odpowiedzi”.
• **Sprawdzamy fakty – Mozart:** Słynny „efekt Mozarta” pochodzi z badania ze studentami, był krótkotrwały i prawie nie dało się go powtórzyć. Nie ma dowodów, że muzyka klasyczna czyni niemowlęta mądrzejszymi (dobrze udokumentowane). Muzyka i tak jest piękna, najlepiej z waszym własnym głosem.

## Woche 8 · Dwa miesiące: małe podsumowanie

Co potrafi większość niemowląt (około 75%) w wieku dwóch miesięcy według list kamieni milowych CDC (2022):

• uspokaja się, gdy się do niego mówi lub bierze na ręce
• patrzy na twarze i uśmiecha się, gdy ktoś się do niego uśmiecha
• wydaje dźwięki inne niż płacz i reaguje na głośne odgłosy
• podąża za wami wzrokiem i przez kilka sekund patrzy na zabawkę
• leżąc na brzuszku, krótko unosi główkę, porusza rączkami i nóżkami, na chwilę otwiera dłonie

**Jak to czytać:** 75% oznacza, że co czwarte niemowlę niektórych z tych rzeczy jeszcze nie potrafi. Jeden brakujący punkt nie jest sygnałem alarmowym, ale dobrym tematem na następne badanie U. Inaczej jest, gdy dziecko traci umiejętności, które już pewnie opanowało. Wtedy prosimy o szybką konsultację lekarską.

📚 **Co jeszcze się dzieje**

• **Relacje:** Niemowlęta od samego początku różnią się temperamentem, na przykład tym, jak są aktywne, wrażliwe na bodźce czy elastyczne. Badacze Thomas i Chess ukuli na to pojęcie „dopasowania”: mniej chodzi o „właściwy” temperament, a bardziej o to, jak dobrze dziecko i otoczenie do siebie pasują.
• **Pieluszki i nocnik:** Odparzona, zaczerwieniona pupa zdarza się często. Pomagają częste przewijanie, powietrze na pupę i maść z cynkiem. Jeśli zaczerwienienie ma ostrą granicę i małe kropeczki na brzegu, może to być grzybica. Wtedy do pediatry.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Dopasujcie bodźce do temperamentu: spokojne niemowlęta często potrzebują nieco więcej zachęty do zabawy, wrażliwe raczej mniej zamieszania (wiedza z doświadczenia, słabo zbadana).
• **Przedmioty:** Lekkie gryzaki lub grzechotki, które nie zrobią dziecku krzywdy, jeśli spadną mu na twarz.
• **Czy coś kupować?** Zabawki muszą mieć oznaczenie CE. Znak GS („geprüfte Sicherheit”, sprawdzone bezpieczeństwo) jest dobrowolny i stanowi dodatkową wskazówkę.

## Woche 9 · Odkrywanie rączek

Wasze dziecko odkrywa, że ma rączki. Wiele niemowląt długo się im teraz przygląda, porusza paluszkami przed oczami i wkłada je do buzi. Wrodzony odruch chwytny słabnie, a dłonie częściej są luźno otwarte. To warunek, by później celowo chwytać.

Buzia jest przy tym ważnym narzędziem. Wargi i język to w tym wieku najczulsze narządy dotyku, jakie ma niemowlę.

💡 Włóżcie dziecku do rączki lekką grzechotkę albo materiałowe kółko. Trzyma je jeszcze raczej przypadkiem, ale uczy się przy tym, co potrafi jego dłoń.

📚 **Co jeszcze się dzieje**

• **Mowa:** Już noworodki rozróżniają języki o różnym rytmie, na przykład angielski i japoński. Melodia mowy to pierwsze, czego niemowlęta uczą się o swoim języku.
• **Sen:** W ciągu dnia zwykle nie ma jeszcze stałego rytmu, tylko kilka drzemek różnej długości. Bardziej regularne pory snu rozwijają się w najbliższych miesiącach.
• **Picie i jedzenie:** Ile dziecko wypija, zmienia się z karmienia na karmienie i z dnia na dzień. Zdrowe niemowlęta dobrze same regulują swoje zapotrzebowanie. Liczy się rozwój na przestrzeni tygodni, a nie pojedyncze karmienie.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Rymowanki paluszkowe i delikatne łączenie rączek: klaskanie przed klatką piersiową, dotykanie po kolei paluszków.
• **Przedmioty:** Lekkie materiałowe kółko, myjka, paski materiału do trzymania. Bez długich wstążek i sznurków.
• **Sprawdzamy fakty – karmienie piersią:** Udowodniono, że karmienie piersią chroni przed niektórymi infekcjami. To, czy zwiększa też inteligencję, jest sporne: duże badanie PROBIT wykazało korzyść w wieku sześciu i pół roku, ale w wieku 16 lat już nie, a porównania rodzeństwa nie wykazują prawie żadnych różnic (wyniki badań niejednoznaczne). Jeśli nie karmicie piersią lub nie możecie, nie musicie martwić się o rozwój dziecka.

## Woche 10 · Świat staje się bardziej kolorowy

Wzrok robi teraz duże postępy. W wieku około trzech miesięcy niemowlęta rozróżniają kolory już w dużej mierze jak dorośli, a mniej więcej w tym czasie zaczyna się też widzenie przestrzenne: mózg uczy się łączyć obrazy z obu oczu w trójwymiarowe wrażenie. Niemowlęta płynniej śledzą teraz wzrokiem poruszające się przedmioty.

🔬 Tak ostro jak dorośli niemowlęta jednak jeszcze długo nie widzą. Ostrość wzroku dojrzewa przez pierwsze lata życia.

💡 Drogie karty kontrastowe nie są potrzebne. Na zewnątrz jest wystarczająco dużo do oglądania: liście na wietrze, światło i cień, twarze.

📚 **Co jeszcze się dzieje**

• **Relacje:** Niemowlęta nie przywiązują się tylko do jednej osoby. W klasycznym badaniu (Schaffer i Emerson, 1964) większość dzieci w wieku półtora roku miała kilka osób przywiązania. Najsilniej przywiązywały się do tych, którzy wrażliwie reagowali na ich sygnały i się z nimi bawili, niekoniecznie do tych, którzy najczęściej karmili i przewijali.
• **Motoryka:** W najbliższych tygodniach wiele niemowląt łączy rączki przed klatką piersiową i się im przygląda. Środek ciała staje się miejscem spotkań rąk i oczu.
• **Pieluszki i nocnik:** Niemowlęta bardzo często siusiają, pęcherz opróżnia się jeszcze automatycznie. Do świadomej kontroli nad nim jeszcze lata.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Śledzenie wzrokiem: powoli przesuwajcie zabawkę tam i z powrotem. Albo zabawy w cienie ręką na ścianie.
• **Jak reagować:** Najlepszy trening wzroku jest na dworze: drzewa, chmury, poruszające się liście.
• **Czy coś kupować?** Karuzela nad łóżeczkiem jest w porządku, jeśli jest dobrze zamocowana i poza zasięgiem rączek. Nie jest konieczna.

## Woche 11 · Robi się spokojniej (zwykle)

Dobra wiadomość dla wielu rodzin: po ośmiu, dziewięciu tygodniach płacz średnio wyraźnie się zmniejsza. Jednocześnie rozwija się rytm dnia i nocy. Mniej więcej od trzeciego miesiąca organizm coraz częściej wytwarza hormon snu melatoninę w rytmie dobowym, a dłuższe okresy snu w nocy zdarzają się częściej.

Jeśli natomiast wasze dziecko nadal bardzo dużo płacze, porozmawiajcie z gabinetem pediatrycznym. Nie dlatego, że coś musi być „nie tak”, ale dlatego, że istnieje wsparcie, na przykład w poradniach dla niemowląt z nadmiernym płaczem (Schreiambulanz). Natychmiast skonsultujcie z lekarzem płacz połączony z gorączką, słabym piciem lub wymiotami albo płacz, który brzmi zupełnie inaczej niż zwykle.

💡 Gdy robi się spokojniej, świadomie róbcie sobie przerwy. Rodzice też muszą odpocząć po pierwszych tygodniach.

📚 **Co jeszcze się dzieje**

• **Zabawa:** Niemowlęta bawią się własnym ciałem: rączkami, stópkami, głosem. To prawdziwa zabawa, bo powtarzają ruchy dlatego, że sprawiają im przyjemność.
• **Wzrost:** Wiele niemowląt w wieku około czterech do sześciu miesięcy podwaja masę urodzeniową, a w wieku roku mniej więcej ją potraja. Długość ciała w pierwszym roku zwiększa się mniej więcej o połowę. To orientacyjne wartości z dużym rozrzutem.
• **Picie i jedzenie:** Nocne karmienia są w tym wieku normalne. To, kiedy dziecko przetrwa noc bez karmienia, jest u każdego bardzo różne.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zabawy z ciałem: delikatny „rowerek” nóżkami, dmuchanie na stópki, przykładanie rączek do buzi.
• **Jak reagować:** Gdy robi się spokojniej, może zacząć się stały wieczorny rytuał, nawet jeśli jeszcze nie zawsze się udaje (wiedza z doświadczenia, słabo zbadana).

## Woche 12 · Główka do góry!

Kontrola główki się poprawia. Wiele niemowląt, leżąc na brzuszku, podpiera się teraz na przedramionach i dłużej trzyma główkę w górze. W wieku około czterech miesięcy większość niemowląt stabilnie trzyma główkę, gdy są trzymane pionowo.

Jednocześnie znikają wrodzone odruchy. Odruch Moro (wzdrygnięcie z rozrzuconymi rękami) zanika zwykle między trzecim a szóstym miesiącem. To znak, że kontrolę coraz bardziej przejmuje kora mózgowa.

💡 Podczas czasu na brzuszku połóżcie przed dzieckiem ciekawą zabawkę albo nietłukące się lusterko. Wtedy warto unieść główkę.

📚 **Co jeszcze się dzieje**

• **Płacz:** Niemowlęta, które dużo płaczą, są często też przemęczone. Niektórym rodzinom pomaga regularny rytm dnia i świadome proponowanie drzemek, zanim dziecko będzie całkiem rozdrażnione.
• **Relacje:** Uśmiech staje się bardziej ukierunkowany. Znajome osoby dostają teraz często bardziej promienny uśmiech niż obce.
• **Pieluszki i nocnik:** Stolec wygląda bardzo różnie w zależności od diety. Zielonkawy stolec u zdrowego, zadowolonego dziecka jest zwykle niegroźny. Ważne pozostaje tylko ostrzeżenie przed bardzo jasnym, gliniastym stolcem.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Okazje do chwytania: trzymajcie lekkie materiałowe kółko przed rączkami dziecka tak, żeby trafiało w nie podczas wymachiwania i w końcu je złapało.
• **Sprawdzamy fakty – rękawiczki na rzepy:** W eksperymentach (Needham, 2002; Libertus, 2016) trzymiesięczne niemowlęta dostawały rękawiczki z rzepami, do których przyczepiały się lekkie zabawki. Po dwóch tygodniach po dziesięć minut dziennie częściej badały przedmioty, i było to mierzalne nawet rok później (pojedyncze badanie). W przełożeniu na codzienność: stwarzanie okazji do udanego chwytania prawdopodobnie pomaga.
• **Sprawdzamy fakty – kształt główki:** Spłaszczony tył główki zdarza się często. Pomagają czas na brzuszku, zmiana ułożenia główki i mówienie do dziecka z obu stron. Randomizowane badanie (van Wijk, 2014) nie wykazało u zdrowych niemowląt w wieku pięciu, sześciu miesięcy przewagi terapii kaskiem nad naturalnym przebiegiem, za to wiele skutków ubocznych (pojedyncze badanie). Jeśli dziecko odwraca główkę prawie wyłącznie w jedną stronę, pokażcie to w gabinecie pediatrycznym.

## Woche 13 · Trzy miesiące: gruchanie i chichotanie

Wasze dziecko staje się bardziej rozmowne. Gruchanie w stylu „ooo” i „aaa” oraz pierwsze chichoty, gdy je rozśmieszacie, CDC opisuje u większości niemowląt w wieku około czterech miesięcy. Wiele niemowląt odpowiada teraz dźwiękami, gdy się do nich mówi, i odwraca główkę w stronę waszego głosu.

🔬 Śmiech jest w tym wieku przede wszystkim sygnałem społecznym i pojawia się głównie w kontakcie z innymi. Prawdziwe „poczucie humoru”, czyli śmianie się z rzeczy zaskakujących i niedorzecznych, przychodzi później.

⚠️ **Krótkie przypomnienie o bezpiecznym śnie:** Między drugim a czwartym miesiącem ryzyko nagłej śmierci łóżeczkowej jest największe. Dlatego jeszcze raz najważniejsze: na plecach, śpiworek, twarde podłoże bez poduszek i przytulanek, bez dymu tytoniowego, nie za ciepło, dziecko w sypialni rodziców. Czy we własnym łóżeczku, łóżeczku dostawnym czy we wspólnym łóżku, co do tego specjaliści nie są zgodni (wyniki badań niejednoznaczne). Wspólne spanie jest jednak wyraźnie niebezpieczne po paleniu, alkoholu, narkotykach lub lekach wywołujących senność, u wcześniaków oraz na kanapie lub w fotelu (dobrze udokumentowane).

💡 Naśladujcie dźwięki dziecka i czekajcie na odpowiedź. Takie wymiany to prawdziwe przygotowanie do mowy.

📚 **Co jeszcze się dzieje**

• **Motoryka:** Siedzenia nie da się jeszcze ćwiczyć. Ale noszone pionowo, wiele niemowląt już trzyma główkę i z ciekawością się rozgląda.
• **Sen:** Dłuższe okresy snu w nocy zdarzają się coraz częściej, ale prawie żadne niemowlę jeszcze nie „przesypia nocy”. W badaniach oznacza to zresztą zwykle tylko sześć godzin bez przerwy.
• **Wzrost:** Po pierwszych trzech miesiącach niemowlęta przybierają zwykle tygodniowo mniej niż na początku. Wzrost stopniowo zwalnia przez cały pierwszy rok.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zabawy w rozśmieszanie: delikatne dmuchanie, „Zaraz cię złapię!”, nosek w nosek. Przestańcie, zanim dziecko się nadmiernie pobudzi.
• **Czy coś kupować?** Nic. To wy jesteście teraz ulubioną zabawką.

## Woche 14 · Najpierw machanie, potem chwytanie

Niemowlęta zaczynają celowo uderzać w przedmioty, na początku jeszcze niezgrabnie, raczej zamachem całej ręki. W ciągu najbliższych tygodni zamienia się to w prawdziwe chwytanie. To, co złapane, wędruje do buzi. Tak niemowlęta poznają kształt, materiał i smak.

⚠️ Od teraz obowiązuje zasada: wszystko w zasięgu może trafić do buzi. Reguła kciuka: to, co przejdzie przez rolkę po papierze toaletowym, może zostać połknięte. Szczególnie niebezpieczne są **baterie guzikowe**, które w ciągu kilku godzin mogą spowodować ciężkie oparzenia chemiczne, oraz silne **magnesy**. Przy podejrzeniu połknięcia natychmiast szukajcie pomocy lekarskiej, w nagłym przypadku dzwońcie pod 112.

💡 Trzymajcie zabawki tak, żeby dziecko musiało się po nie wyciągnąć, zamiast wkładać mu je od razu do rączki.

📚 **Co jeszcze się dzieje**

• **Zabawa:** Niemowlęta bawią się teraz wszystkim, co mogą złapać: potrząsają, obracają, wkładają do buzi. Różne materiały (drewno, tkanina, silikon) są ciekawsze niż wiele podobnych zabawek.
• **Picie i jedzenie:** Podczas karmienia piersią lub butelką wiele niemowląt łatwo się teraz rozprasza, rozgląda się i pije niespokojnie. To dlatego, że świat staje się ciekawszy. Pomaga spokojne miejsce z niewielką ilością bodźców.
• **Mowa:** Niemowlęta więcej się śmieją i piszczą, i sprawdzają, jak głośno potrafią.

🧸 **Co możecie teraz robić**

• **Przedmioty:** Z kuchni: drewniane łyżki, silikonowa szpatułka, materiałowy woreczek z supełkiem. Żadnych plastikowych torebek, nic tłukącego się i nic, co przejdzie przez rolkę po papierze toaletowym.
• **Pomysł na zabawę:** Gdy dziecko leży na brzuszku, połóżcie zabawkę tuż poza zasięgiem, żeby opłacało się wyciągnąć.
• **Czy coś kupować?** Wystarczy kilka gryzaków z różnych materiałów. Badanie z udziałem małych dzieci (Dauch, 2018) wykazało, że przy niewielu zabawkach bawiły się dłużej i bardziej różnorodnie niż przy wielu (pojedyncze badanie). U niemowląt tego nie badano, ale „mniej i na zmianę” to dobra reguła.

## Woche 15 · Uwaga na przewijaku

Wiele niemowląt po raz pierwszy przekręca się między czwartym a szóstym miesiącem, zwykle najpierw z brzuszka na plecy. Często dzieje się to zupełnie niespodziewanie, także dla samego dziecka.

⚠️ Upadki z przewijaka, kanapy lub łóżka należą do najczęstszych wypadków w tym wieku. Dlatego: zawsze trzymajcie jedną rękę na dziecku albo przewijajcie od razu na podłodze.

Do snu nadal zawsze kładźcie dziecko na plecach. Jeśli samo przekręca się na brzuszek i potrafi wrócić na plecy, może tak zostać.

💡 Dużo czasu na kocu na podłodze daje miejsce do próbowania, więcej niż leżaczek czy fotelik.

📚 **Co jeszcze się dzieje**

• **Relacje:** Niemowlęta wyraźnie rozpoznają teraz, kto należy do rodziny, i witają znajome osoby promiennym uśmiechem i machaniem nóżkami.
• **Sen:** Pomoce przy zasypianiu, takie jak karmienie piersią, noszenie czy kołysanie, są w tym wieku zupełnie normalne. To, jak to rozwiążecie, to sprawa waszej rodziny.
• **Wzrost:** Przy ważeniu w domu waga, pora dnia i zawartość pieluszki bardzo się różnią. Pojedyncze pomiary niewiele mówią. U zdrowych niemowląt zwykle wystarczą badania U.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zachęcanie do przekręcania: trzymajcie zabawkę z boku dziecka tak, żeby podążało za nią wzrokiem i całym ciałem.
• **Jak reagować:** Bawcie się raczej na podłodze niż na kanapie czy łóżku. Wtedy nic się nie stanie, gdy dziecko nagle się przekręci.

## Woche 16 · Własne imię

🔬 W znanym eksperymencie (Mandel i współpracownicy, 1995) niemowlęta w wieku około czterech i pół miesiąca dłużej słuchały, gdy wołano ich własne imię, niż gdy wołano podobnie brzmiące imiona. Rozpoznają więc już ten wzór dźwiękowy, prawdopodobnie dlatego, że tak często go słyszą.

Według CDC większość niemowląt niezawodnie reaguje na własne imię, czyli patrzy, gdy się je woła, dopiero w wieku około dziewięciu miesięcy. Rozpoznawanie i reagowanie to dwa różne kroki.

💡 Opowiadajcie dziecku, co właśnie robicie: przy przewijaniu, gotowaniu, ubieraniu. To, ile rodzice mówią bezpośrednio do dziecka, wiąże się w badaniach z późniejszym rozwojem mowy.

📚 **Co jeszcze się dzieje**

• **Motoryka:** W najbliższych tygodniach wiele niemowląt leżących na plecach sięga po swoje kolana i stópki. Stópki to świetna zabawka.
• **Płacz:** Po trzecim miesiącu niemowlęta rzadziej płaczą bez widocznego powodu. Płacz staje się bardziej ukierunkowany: z frustracji, nudy lub zmęczenia.
• **Pieluszki i nocnik:** Dziecko, które przy wypróżnianiu czerwienieje, pręży się i stęka, nie musi mieć zaparcia. Współpracy mięśni brzucha i dna miednicy trzeba się najpierw nauczyć. Liczy się to, czy stolec jest miękki.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Wplatajcie imię dziecka w piosenki i rymowanki.
• **Sprawdzamy fakty – liczba słów:** Słynna „luka 30 milionów słów” (Hart i Risley, 1995) opiera się na małej próbie i jest sporna. Nowsze badania (np. Romeo, 2018) sugerują, że prawdziwa wymiana jest ważniejsza niż sama liczba słów (wyniki badań niejednoznaczne). Nie chodzi więc o ciągłe mówienie, tylko o wzajemny kontakt.
• **Przedmioty:** Książeczki ze zdjęciami twarzy niemowląt są teraz często szczególnie ciekawe.

## Woche 17 · Cztery miesiące i pytanie o rozszerzanie diety

Długo obowiązywała w Niemczech zasada: rozszerzanie diety najwcześniej od początku 5. miesiąca i najpóźniej od początku 7. miesiąca. Od lutego 2026 roku w Niemczech po raz pierwszy obowiązują wytyczne S3 dotyczące długości karmienia piersią. Zalecają one, aby dzieci urodzone o czasie karmić wyłącznie lub przeważnie piersią do końca szóstego miesiąca życia, zgodnie z zaleceniami WHO. Posiłki uzupełniające dochodzą potem od początku 7. miesiąca, czyli za mniej więcej dziewięć tygodni. Do tego czasu mleko mamy lub mleko modyfikowane w pełni wystarczają.

🔬 **Na ile to pewne?** Wytyczne opierają się na badaniach obserwacyjnych, w których dzieci karmione wyłącznie piersią przez sześć miesięcy miały na przykład rzadziej zapalenia ucha środkowego i infekcje żołądkowo-jelitowe. Same wytyczne oceniają jakość dowodów jako niską do bardzo niskiej. Dwa towarzystwa naukowe, towarzystwo medycyny żywienia (DGEM) oraz związek zawodowy pediatrów (BVKJ), zgłosiły dlatego sprzeciw i nadal uważają 4–6 miesięcy za odpowiednie, między innymi ze względu na alergie i zaopatrzenie w żelazo (wyniki badań niejednoznaczne). Wytyczne wyraźnie podkreślają, że nikt nie może być pod presją: ani do karmienia piersią, ani do odstawienia, ani do wczesnego rozszerzania diety. Jeśli w rodzinie występują alergie albo dziecko jest karmione mlekiem modyfikowanym, najlepiej omówcie termin z gabinetem pediatrycznym.

Po czym później poznacie, że dziecko jest gotowe (oznaki gotowości):

• siedzi prosto z niewielkim podparciem i pewnie trzyma główkę
• wyraźnie interesuje się waszym jedzeniem
• otwiera buzię, gdy zbliża się łyżeczka
• nie wypycha już odruchowo jedzenia językiem

Przy okazji: według CDC większość niemowląt w wieku czterech miesięcy potrafi samo się uśmiechać, żeby zwrócić na siebie uwagę, chichotać, gruchać, odwracać główkę w stronę głosu, stabilnie trzymać główkę, trzymać zabawkę, wkładać rączki do buzi i podpierać się na przedramionach, leżąc na brzuszku.

📚 **Co jeszcze się dzieje**

• **Wzrost:** Dzieci karmione piersią rosną w drugiej połowie pierwszego roku często nieco wolniej niż dzieci karmione mlekiem modyfikowanym. Dlatego siatki wzrostu WHO opierają się na dzieciach karmionych piersią.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Pozwólcie dziecku uczestniczyć w rodzinnych posiłkach na waszych kolanach: patrzeć, wąchać, być częścią rodziny.
• **Czy coś kupować?** Krzesełko do karmienia dopiero wtedy, gdy dziecko siedzi prosto z niewielką pomocą. Do tego czasu najlepszym miejscem są wasze kolana. Do papek wystarczy miękka, płaska łyżeczka dla niemowląt. Samodzielne gotowanie i słoiczki są w porządku.

## Woche 18 · Sen: co właściwie jest normalne?

Dla niemowląt w wieku od czterech do dwunastu miesięcy Amerykańska Akademia Medycyny Snu (AASM) podaje około 12–16 godzin snu na dobę, wliczając drzemki, przy dużych różnicach indywidualnych.

🔬 **„Regres snu w czwartym miesiącu”** to popularne pojęcie. Prawdą jest, że sen w tych miesiącach rzeczywiście się zmienia: cykle snu stają się bardziej podobne do cykli dorosłych, a krótkie wybudzenia między nimi są wyraźniejsze. To jednak, że wszystkie niemowlęta w określonym wieku nagle gorzej śpią, nie jest dobrze udokumentowane.

Budzenie się w nocy jest w tym wieku regułą, a nie wyjątkiem.

💡 Krótki, zawsze taki sam wieczorny rytuał (na przykład pieluszka, śpiworek, piosenka, światło zgaszone) daje orientację.

📚 **Co jeszcze się dzieje**

• **Mowa:** Niemowlęta odwracają się teraz w stronę dźwięków i coraz dokładniej je lokalizują.
• **Picie i jedzenie:** Duże zainteresowanie waszym jedzeniem samo w sobie nie jest oznaką gotowości do rozszerzania diety. Wiele niemowląt śledzi wzrokiem każdy kęs na długo przed tym, zanim będą gotowe.
• **Motoryka:** Leżąc na brzuszku, wiele niemowląt podpiera się teraz na dłoniach i unosi klatkę piersiową. Niektóre „latają”, czyli jednocześnie odrywają od podłogi ręce i nogi.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Wcześnie rozpoznawajcie oznaki zmęczenia, takie jak tarcie oczu, ziewanie czy nieobecny wzrok, i kładźcie dziecko spać, zanim będzie przemęczone (wiedza z doświadczenia, słabo zbadana).
• **Czy coś kupować?** Śpiworek w odpowiednim rozmiarze i grubości do temperatury w pokoju. Lampka nocna czy niania elektroniczna to kwestia gustu, nie są konieczne.

## Woche 19 · Ja coś sprawiam!

Wasze dziecko odkrywa przyczynę i skutek: gdy potrząsam grzechotką, słychać dźwięk. Gdy się śmieję, tata śmieje się w odpowiedzi.

🔬 W klasycznych eksperymentach psycholożki Carolyn Rovee-Collier trzymiesięcznym niemowlętom przywiązywano do nóżki wstążkę połączoną z karuzelą. Szybko uczyły się poruszać karuzelą przez machanie nóżkami i pamiętały to jeszcze kilka dni później. Niemowlęta wcześnie uczą się więc, że same mogą coś sprawić.

💡 Zabawki, które reagują (szeleszczą, dzwonią, poruszają się), są teraz szczególnie ciekawe. Najbardziej reagującą zabawką jesteście jednak wy.

📚 **Co jeszcze się dzieje**

• **Płacz:** Niemowlęta płaczą teraz też wtedy, gdy coś się nie udaje, na przykład gdy zabawka odtoczy się poza zasięg. Frustracja napędza naukę, o ile pomagacie, gdy robi się jej za dużo.
• **Wzrost:** Główka rośnie teraz wolniej, o około jeden centymetr miesięcznie.
• **Pieluszki i nocnik:** Niektóre rodziny obserwują sygnały dziecka przed siusianiem i trzymają je nad nocnikiem („bez pieluchy”). To możliwe, ale według badań zuryskich (Largo i Stützle, 1977) nie przyspiesza późniejszego odpieluchowania. Wczesny trening nocnikowy miał tam tylko krótkotrwały wpływ na wypróżnienia i żadnego na kontrolę pęcherza.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Wszystko, co reaguje na działanie: szeleszczący papier (papier do pieczenia), grzechotka, dobrze zamknięta i zaklejona plastikowa butelka z ryżem. Zawsze pod nadzorem.
• **Jak reagować:** Wyraźnie reagujcie na to, co robi dziecko. Tak uczy się: „Ja coś sprawiam”.
• **Czy coś kupować?** Elektroniczne zabawki z przyciskami, światłem i muzyką nie są potrzebne. Więcej o tym za kilka tygodni.

## Woche 20 · Uczenie się czytania uczuć

W najbliższych miesiącach niemowlęta coraz lepiej rozróżniają uczucia: przyjazne i gniewne głosy, roześmiane i smutne twarze. Wiele z nich śmieje się teraz naprawdę głośno.

Według CDC większość niemowląt w wieku sześciu miesięcy lubi oglądać się w lustrze. Rozpoznawanie siebie w lustrze przychodzi jednak znacznie później, w testach zwykle od około 18 miesiąca.

💡 Nietłukące się lusterko na podłodze to ciekawy partner do zabawy podczas czasu na brzuszku.

📚 **Co jeszcze się dzieje**

• **Sen:** W wieku sześciu miesięcy dzieci w badaniach zuryskich spały średnio nieco ponad 14 godzin na dobę, przy dużej rozpiętości.
• **Motoryka:** Wiele niemowląt przekręca się teraz także z pleców na brzuszek. Na podwyższonych powierzchniach nadal obowiązuje ostrożność.
• **Picie i jedzenie:** Przy rozszerzaniu diety szczególnie ważne jest żelazo, bo zapasy żelaza z czasu ciąży w drugim półroczu się kończą. Dlatego pierwsza papka zawiera mięso albo, w wersji wegetariańskiej, bogate w żelazo zboża, takie jak owies czy kasza jaglana, razem z owocami lub warzywami zawierającymi witaminę C.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Śpiewajcie, gdy dziecko marudzi. W jednym badaniu (Corbeil i współpracownicy, 2016) niemowlęta w wieku od sześciu do dziewięciu miesięcy przy śpiewie pozostawały spokojne mniej więcej dwa razy dłużej niż przy mowie (pojedyncze badanie).
• **Przedmioty:** Nietłukące się lusterko na wysokości oczu przy podłodze.
• **Jak reagować:** Nazywajcie uczucia: „Oj, to cię przestraszyło”. Dziecko nie rozumie jeszcze słów, ale rozumie ton.

## Woche 21 · Piszczenie, parskanie, gaworzenie

Wasze dziecko eksperymentuje z głosem: piszczy, mruczy, parska wargami. To nie bzdury, tylko trening głosu. Niemowlęta odkrywają, co potrafią krtań, język i wargi. Według CDC większość niemowląt w wieku sześciu miesięcy „rozmawia” z wami dźwiękami na zmianę.

💡 Przyłączcie się! Parskajcie w odpowiedzi, piszczcie, czekajcie na odpowiedź. Głupkowatość jest tu wartościowa wychowawczo.

📚 **Co jeszcze się dzieje**

• **Relacje:** Niemowlęta zaczynają przewidywać punkt kulminacyjny zabaw. Gdy kilka razy tak samo bawicie się w łaskotki, cieszą się już, zanim się zacznie.
• **Zabawa:** Zabawki wędrują z rączki do rączki i do buzi. Niemowlęta obracają i oglądają teraz przedmioty bardziej systematycznie.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Dźwiękowy ping-pong: dziecko piszczy, wy piszczycie w odpowiedzi, pauza. Parskanie na brzuszek.
• **Sprawdzamy fakty – masaż niemowląt:** Wiele niemowląt lubi masaż. Przegląd Cochrane (2013) nie wykazał jednak u zdrowych niemowląt solidnych dowodów na korzyści dla rozwoju, snu czy płaczu, także dlatego, że wiele badań było metodologicznie słabych (wyniki badań niejednoznaczne). Czyli: róbcie go, jeśli obojgu wam jest dobrze.
• **Czy coś kupować?** Zajęcia dla niemowląt, takie jak PEKiP, masaż niemowląt czy pływanie niemowląt, prawie nie zostały zbadane pod kątem wpływu na rozwój. Ich wartość leży prawdopodobnie raczej w kontakcie z innymi rodzicami i wspólnych przeżyciach (wiedza z doświadczenia, słabo zbadana).

## Woche 22 · Ślinienie, ząbki i gorączka

Wiele niemowląt bardzo się teraz ślini. Wynika to głównie z tego, że w tym wieku wzrasta produkcja śliny, i nie jest automatycznie oznaką ząbkowania. Pierwszy ząbek pojawia się zwykle gdzieś między 6 a 12 miesiącem. Niektóre dzieci mają go wcześniej, inne dopiero po pierwszych urodzinach.

🔬 Badania pokazują: ząbkowanie może sprawiać, że dziecko marudzi, i lekko podnosić temperaturę, ale nie powoduje prawdziwej gorączki. Jeśli dziecko jest naprawdę chore, nie zrzucajcie tego na ząbki.

💡 Schłodzony (nie zamrożony) gryzak może pomóc. Pediatrzy odradzają bursztynowe naszyjniki ze względu na ryzyko uduszenia i zadławienia.

📚 **Co jeszcze się dzieje**

• **Sen:** Wielu niemowlętom wystarczają teraz dwie, trzy drzemki.
• **Mowa:** Melodię niemowlęta rozumieją przed słowami. W jednym badaniu (Fernald, 1993) pięciomiesięczne niemowlęta reagowały odpowiednią mimiką na chwalącą i zakazującą melodię mowy, nawet w obcych językach.

🧸 **Co możecie teraz robić**

• **Przedmioty:** „To samo, ale inaczej”: podawajcie po kolei łyżeczkę z drewna, metalu i silikonu. Niemowlęta porównują ciężar, temperaturę i dźwięk.
• **Czy coś kupować?** Wystarczy gryzak, który można schłodzić. Żele na ząbkowanie ze środkami znieczulającymi nie są zalecane dla niemowląt; w razie wątpliwości zapytajcie w aptece lub gabinecie pediatrycznym.

## Woche 23 · Siedzenia trzeba się nauczyć

Wiele niemowląt podpiera się teraz rączkami podczas siedzenia; CDC podaje to dla wieku sześciu miesięcy. Samodzielne siedzenie przychodzi nieco później. Duże badanie WHO z udziałem dzieci z pięciu krajów wykazało dla siedzenia bez podparcia zakres normy od 3,8 do 9,2 miesiąca.

🔬 Ciekawostka: siedzenie miało w tym badaniu najwęższe okno czasowe ze wszystkich badanych kamieni milowych. Przy samodzielnym staniu i chodzeniu między najwcześniejszymi a najpóźniejszymi zdrowymi dziećmi mija prawie dziesięć miesięcy.

💡 Nie musicie „ćwiczyć” siedzenia, sadzając dziecko. Dużo swobodnego ruchu na podłodze trenuje dokładnie te mięśnie, które są do tego potrzebne.

📚 **Co jeszcze się dzieje**

• **Zabawa:** Gdy dziecko siedzi z podparciem, obie rączki są wolne. Teraz możliwe staje się badanie przedmiotów obiema rękami.
• **Picie i jedzenie:** Do jedzenia dziecko powinno siedzieć prosto i dobrze podparte, na przykład na waszych kolanach albo w krzesełku z wkładką zmniejszającą, a nie półleżąc w leżaczku.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Siedzenie między waszymi nogami i podawanie zabawek raz z lewej, raz z prawej. Tak dziecko ćwiczy równowagę, nie przewracając się.
• **Przedmioty:** „Koszyk skarbów”: płaski koszyk z trzema, czterema przedmiotami codziennego użytku z różnych materiałów, na przykład drewnianą łyżką, metalową miską, dużą szyszką, chustką. Pomysł pochodzi z pedagogiki małego dziecka (wiedza z doświadczenia, słabo zbadana). Nic mniejszego niż mniej więcej dziecięca piąstka.
• **Czy coś kupować?** Kółka do siedzenia i siedziska dla niemowląt nie są potrzebne. Fizjoterapeuci zwykle odradzają długie sadzanie niemowląt, zanim same to potrafią (wiedza z doświadczenia, słabo zbadana).

## Woche 24 · Mali geniusze językowi

🔬 Niemowlęta przychodzą na świat jako „obywatele świata”. W pierwszych miesiącach potrafią rozróżniać dźwięki mowy ze wszystkich języków, także takie, których dorośli już nie słyszą. Między około 6 a 12 miesiącem specjalizują się w języku lub językach, które słyszą, i tracą wrażliwość na obce dźwięki (Werker i Tees, 1984). Mózg dostosowuje się do własnego otoczenia.

Jeśli w domu mówicie w kilku językach: wielojęzyczność nie myli niemowląt i nie jest przyczyną zaburzeń rozwoju mowy.

💡 Mówcie do dziecka w języku, w którym czujecie się najlepiej. Prawdziwi ludzie są przy tym niezastąpieni. W badaniach niemowlęta uczyły się obcych dźwięków mowy od osoby w pokoju, ale prawie wcale od tej samej osoby na nagraniu wideo.

📚 **Co jeszcze się dzieje**

• **Płacz:** Jeśli dziecko po trzecim miesiącu nadal bardzo dużo płacze lub bardzo źle śpi, specjaliści mówią o zaburzeniu regulacji. Dobrym miejscem, gdzie można się zwrócić, są poradnie dla niemowląt z nadmiernym płaczem (Schreiambulanz) i Frühe Hilfen (lokalne programy wczesnego wsparcia), które doradzają całej rodzinie.
• **Motoryka:** Wiele niemowląt uwielbia teraz stawać na waszych kolanach i podskakiwać. To zabawa i trening siłowy jednocześnie.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Czas z książeczką: pokazywać, nazywać, czekać. Metaanaliza (Dowdall, 2020) wykazała, że wspólne oglądanie książeczek wspiera rozwój mowy u dzieci w wieku od roku do sześciu lat (dobrze udokumentowane). U niemowląt jest to słabiej zbadane, ale to dobry początek nawyku.
• **Czy coś kupować?** Książeczki kartonowe z wyraźnymi obrazkami lub zdjęciami. Biblioteka często ma kącik dla najmłodszych.

## Woche 25 · Co z oczu, to z serca?

🔬 Klasyka psychologii rozwojowej: Jean Piaget uważał, że niemowlęta dopiero w wieku około ośmiu miesięcy wiedzą, że przedmioty istnieją dalej, gdy ich nie widać („stałość przedmiotu”). Późniejsze eksperymenty Renée Baillargeon sugerowały, że już trzy- do pięciomiesięczne niemowlęta patrzą zdziwione, gdy ukryty przedmiot znika w „niemożliwy” sposób. Ile niemowlęta naprawdę przy tym rozumieją, jest do dziś przedmiotem dyskusji.

Pewne jest: aktywnie szukać schowanych rzeczy, na przykład upuszczonej łyżeczki, większość niemowląt według CDC zaczyna w wieku około dziewięciu miesięcy.

💡 Zabawy w „a kuku” sprawiają teraz ogromną frajdę: chustka przed twarz i… jest!

📚 **Co jeszcze się dzieje**

• **Picie i jedzenie:** Gdy niedługo zacznie się rozszerzanie diety: pierwsze łyżeczki papki często lądują z powrotem na zewnątrz. To nie odmowa, język musi się najpierw nauczyć przesuwać papkę do tyłu. Nowe smaki często potrzebują 8–10 prób, zanim zostaną zaakceptowane.
• **Wzrost:** Wielkość i masa urodzeniowa odzwierciedlają głównie warunki w brzuchu. Dlatego w ciągu pierwszych 12–18 miesięcy wiele dzieci przechodzi na inną krzywą centylową, lepiej odpowiadającą ich predyspozycjom. Małe nadrabiają, duże rosną nieco wolniej.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Warianty „a kuku”: przykryć zabawkę chustką, schować ją do połowy pod kocykiem, schować się samemu za zasłoną.
• **Jak reagować:** Nastawcie się na spokój przy rozszerzaniu diety: proponujcie nowe rzeczy raz po raz, bez presji, nawet jeśli buzia najpierw się krzywi.

## Woche 26 · Pół roku!

Co potrafi większość niemowląt (około 75%) w wieku sześciu miesięcy według CDC:

• rozpoznaje znajome osoby, śmieje się, lubi oglądać się w lustrze
• „rozmawia” dźwiękami na zmianę, parska, piszczy
• wkłada przedmioty do buzi, żeby je poznać, i sięga po zabawki
• zamyka buzię, gdy nie chce już jeść
• przekręca się z brzuszka na plecy i leżąc na brzuszku, podpiera się na wyprostowanych rękach

🔬 **Przesypianie nocy?** Badanie z udziałem prawie 400 niemowląt (Pennestri i współpracownicy, 2018) wykazało: w wieku sześciu miesięcy 38% jeszcze nie spało sześciu godzin bez przerwy, a 57% nie spało ośmiu godzin. Nie miało to związku z ich rozwojem ani z nastrojem matek. Budzenie się w nocy jest w tym wieku normalne.

**Rozszerzanie diety:** Według nowych wytycznych S3 (2026) teraz, na początku 7. miesiąca, jest zalecany czas na start. Jeśli za radą gabinetu pediatrycznego zaczęliście wcześniej, to też jest w porządku. Jeśli w najbliższych tygodniach dziecko w ogóle nie będzie się interesować jedzeniem, wspomnijcie o tym pediatrze.

📚 **Co jeszcze się dzieje**

• **Pieluszki i nocnik:** Przy posiłkach uzupełniających stolec się zmienia: staje się twardszy, bardziej brązowy i mocniej pachnie. Niestrawione kawałki, na przykład marchewki, są normalne.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Półroczne porządki: schowajcie połowę zabawek i wymieniajcie je co tydzień, dwa. Rzeczy pozostają wtedy nowe, ale u niemowląt nie jest to udowodnione (wiedza z doświadczenia, słabo zbadana).
• **Czy coś kupować?** Mały otwarty kubeczek i śliniaki. Na start rozszerzania diety nic więcej nie trzeba.

## Woche 27 · Nauka jedzenia

Rozszerzanie diety to coś więcej niż odżywianie. Wasze dziecko poznaje smaki, konsystencje, uczy się gryźć i połykać. Klasyczna kolejność według niemieckiej sieci Gesund ins Leben: najpierw w porze obiadu papka z warzyw, ziemniaków i mięsa, około miesiąc później wieczorem papka mleczno-zbożowa, a kolejny miesiąc później po południu papka zbożowo-owocowa. Miękkie kawałki do jedzenia rączkami („baby-led weaning”, BLW) to alternatywa lub uzupełnienie.

Nie musicie unikać alergennych produktów, takich jak dobrze ugotowane jajko czy ryba. Ich pomijanie nie chroni przed alergiami.

⚠️ **Zakazane w pierwszym roku:** miód (ryzyko botulizmu niemowlęcego) oraz dodatek soli i cukru. Mleko krowie do picia dopiero od około roku, w papce jest w porządku. **Ryzyko zadławienia** stwarzają całe orzechy, całe winogrona czy pomidorki koktajlowe (kroić na ćwiartki!) oraz twarde surowe kawałki marchewki lub jabłka.

🔬 Odruch wymiotny i krztuszenie się należą do nauki jedzenia. To odruch ochronny i jest głośny. Prawdziwe zadławienie jest za to często ciche. Dlatego jedzcie zawsze przy stole i zostańcie przy dziecku.

💡 Do posiłków z papką proponujcie wodę z kubeczka.

📚 **Co jeszcze się dzieje**

• **Sen:** Z posiłkami uzupełniającymi niemowlęta nie śpią automatycznie lepiej. W dużym brytyjskim badaniu wcześniejsze rozszerzanie diety dało tylko nieco ponad kwadrans więcej snu w nocy.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Szanujcie oznaki sytości: odwracanie główki, zamykanie buzi, odsuwanie łyżeczki. Żadnego „samolotu” i żadnych sztuczek. Towarzystwa naukowe zalecają takie „karmienie responsywne”, bo zdrowe niemowlęta dobrze same regulują ilość jedzenia.
• **Sprawdzamy fakty – BLW:** Duże badanie z Nowej Zelandii (BLISS) wykazało, że dostosowane BLW (miękkie, duże kawałki, jedzenie bogate w żelazo przy każdym posiłku) nie zwiększało ryzyka zadławienia. Nie wykazało jednak też korzyści w zakresie masy ciała (pojedyncze badanie). Papki, jedzenie rączkami lub połączenie obu są w porządku.
• **Czy coś kupować?** Krzesełko do karmienia z podnóżkiem. Stabilne oparcie dla stóp ułatwia wielu dzieciom siedzenie i gryzienie (wiedza z doświadczenia, słabo zbadana).

## Woche 28 · Nadchodzi lęk przed obcymi

Między około szóstym a dziesiątym miesiącem wiele niemowląt zaczyna bać się obcych. Patrzą sceptycznie na nieznajomych, przytulają się do was albo płaczą, gdy ktoś obcy chce je wziąć na ręce. Według CDC większość niemowląt pokazuje to zachowanie w wieku dziewięciu miesięcy.

🔬 Lęk przed obcymi to nie krok wstecz, tylko krok w rozwoju. Wasze dziecko potrafi teraz wyraźnie odróżnić znajome osoby od obcych i zbudowało z wami więź. Jego nasilenie jest bardzo różne. Niektóre niemowlęta prawie w ogóle go nie okazują.

💡 Nie podawajcie dziecka po prostu dalej. Pozwólcie gościom zbliżać się powoli, gdy dziecko czuje się bezpiecznie przy was.

📚 **Co jeszcze się dzieje**

• **Zabawa:** Niemowlęta celowo upuszczają teraz przedmioty i obserwują, gdzie lądują. Kluczem jest powtarzanie: to, co dwadzieścia razy dzieje się tak samo, zostaje zrozumiane.
• **Picie i jedzenie:** Można teraz ćwiczyć picie z otwartego kubeczka, na początku z dużą ilością rozlewania. Otwarty kubeczek jest lepszy dla zębów i rozwoju buzi niż ciągłe ssanie butelki lub kubka niekapka.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Wprowadzajcie nowe osoby powoli: niech opiekunka czy dziadkowie najpierw poznają dziecko w waszej obecności.
• **Pomysł na zabawę:** Pozwólcie upuszczać: wrzucanie rzeczy z krzesełka do miski, podnoszenie, i od nowa.

## Woche 29 · W ruchu

Wiele niemowląt staje się teraz mobilnych, i to na bardzo różne sposoby: pełzanie, kręcenie się w kółko, turlanie, przesuwanie się na pupie. Dla raczkowania na dłoniach i kolanach badanie WHO wykazało zakres normy od 5,2 do 13,5 miesiąca. Niewielka część zdrowych dzieci nigdy nie raczkuje, a później i tak chodzi zupełnie normalnie.

⚠️ **Czas na zabezpieczenie mieszkania.** Najlepiej przejdźcie raz przez mieszkanie na kolanach: bramki na schody, środki czystości i leki wysoko i pod zamknięciem, gniazdka, luźne kable, trujące rośliny. Przy podejrzeniu zatrucia pomoże ośrodek toksykologiczny waszego kraju związkowego (dla północnych Niemiec: Giftnotruf Nord pod numerem 0551 19240, po niemiecku), w nagłym przypadku dzwońcie pod 112.

💡 Kurs pierwszej pomocy dla niemowląt daje ogromne poczucie bezpieczeństwa. Wiele położnych i organizacji pomocowych je oferuje.

📚 **Co jeszcze się dzieje**

• **Sen:** Nowe ruchy są często „ćwiczone” w nocy. Niektóre niemowlęta siadają w półśnie albo raczkują po łóżeczku. Badania rzeczywiście wykazały częstsze budzenie się w nocy w okresie rozpoczynania raczkowania, zwykle przejściowo.
• **Relacje:** Mobilne niemowlęta oddalają się, oglądają się za siebie i wracają. Badania nad przywiązaniem nazywają to „bezpieczną bazą”: ponieważ jesteście obok, odważają się na wyprawy odkrywcze.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Mały tor przeszkód z poduszek i koców na podłodze. Kładźcie zabawki tuż poza zasięgiem.
• **Czy coś kupować?** Teraz opłaca się sprzęt zabezpieczający, ale tylko to, czego naprawdę potrzebujecie: bramki na schody, ewentualnie zabezpieczenia gniazdek i narożników, blokady szafek ze środkami czystości.

## Woche 30 · Chodzik? Lepiej nie.

Gdy niemowlęta stają się bardziej mobilne, kusi, żeby pomóc im chodzikiem z siedziskiem. Pediatrzy to odradzają. W takich urządzeniach zdarza się wiele wypadków, zwłaszcza upadków ze schodów, i nie pomagają one w nauce chodzenia.

To samo dotyczy skoczków i długiego siedzenia w leżaczkach: krótko jest w porządku, ale dla rozwoju ruchowego najcenniejszy jest ruch na podłodze.

💡 Boso albo w antypoślizgowych skarpetkach na podłodze: to najlepszy sprzęt treningowy.

📚 **Co jeszcze się dzieje**

• **Sen:** To, czy korzystacie z łagodnych programów nauki snu, czy nie, jest decyzją waszej rodziny. Australijskie badanie długoterminowe (Price i współpracownicy, 2012) po pięciu latach nie wykazało ani szkód, ani korzyści dla dzieci.
• **Pieluszki i nocnik:** Przy posiłkach uzupełniających częściej zdarzają się zaparcia. Twardy stolec w postaci kulek i ból przy wypróżnianiu to powód, by porozmawiać z gabinetem pediatrycznym. Często pomagają papki bogate w błonnik, na przykład z gruszką, i wystarczająca ilość płynów.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Tunel z dużego kartonu (bez zszywek) albo przeczołgiwanie się pod stołem.
• **Przedmioty:** Kartony, poduszki, materac na podłodze jako góra do wspinaczki.

## Woche 31 · Ba-ba-ba, da-da-da

U wielu niemowląt zaczyna się teraz gaworzenie sylabami: łańcuchy spółgłoski i samogłoski, takie jak „ba-ba-ba” czy „da-da-da”. Specjaliści nazywają to gaworzeniem kanonicznym. Z tych sylab powstaną później pierwsze słowa.

🔬 Ten kamień milowy jest zadziwiająco niezawodny: większość niemowląt zaczyna między 6 a 10 miesiącem. Badania prowadzone przez językoznawcę D. Kimbrougha Ollera wykazały, że początek dopiero po 10 miesiącu może wskazywać na późniejsze trudności językowe lub zaburzenia słuchu. Jeśli dziecko w wieku około dziesięciu miesięcy jeszcze nie gaworzy sylabami, zbadajcie mu słuch, nawet jeśli badanie przesiewowe słuchu po urodzeniu było prawidłowe.

💡 Gaworzcie w odpowiedzi, śpiewajcie, bawcie się w rymowanki paluszkowe, na przykład „Idzie rak nieborak”. Swoją drogą: „mamama” to zwykle jeszcze nie słowo oznaczające mamę. To przyjdzie później.

📚 **Co jeszcze się dzieje**

• **Wzrost:** W drugiej połowie pierwszego roku wiele niemowląt staje się szczuplejszych. Wskaźnik masy ciała (BMI) osiąga szczyt około 9. miesiąca, a potem spada aż do wieku przedszkolnego. „Dziecięca pulchność” znika więc sama.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Sylabowy ping-pong: „Ba-ba?” „Ba-ba!” Do tego zabawy w podskakiwanie na kolanach, takie jak „Jedzie, jedzie pan”, i rymowanki paluszkowe.
• **Sprawdzamy fakty – język migowy dla niemowląt:** W pierwszym randomizowanym badaniu na ten temat (Kirk i współpracownicy, 2013) dzieci, których rodzice używali znaków migowych dla niemowląt, nie mówiły ani wcześniej, ani więcej. Matki reagowały jednak wrażliwiej na sygnały niewerbalne (pojedyncze badanie). Jeśli sprawia wam to przyjemność: śmiało, ale jako przyspieszacz mowy się nie sprawdza.

## Woche 32 · Od grabienia do chwytu pęsetowego

Motoryka mała rozwija się dalej. Małe przedmioty są najpierw przyciągane całą dłonią, jakby „grabione” (według CDC typowe w wieku dziewięciu miesięcy). Stopniowo powstaje chwyt pęsetowy kciukiem i palcem wskazującym, który większość dzieci opanowuje około pierwszego roku.

Typowe jest też przekładanie rzeczy z rączki do rączki i uderzanie dwoma przedmiotami o siebie. Wspaniale głośno!

💡 Miękkie kawałki jedzenia (gotowana na parze marchewka, banan) to trening motoryki małej i posiłek jednocześnie. ⚠️ Szczególnie konsekwentnie sprzątajcie teraz małe przedmioty.

📚 **Co jeszcze się dzieje**

• **Sen:** Większość niemowląt śpi teraz dwa razy w ciągu dnia, przed południem i po południu.
• **Płacz:** Płacz jest coraz częściej skierowany do was. Niemowlęta patrzą na was, płacząc, i często uspokajają się, gdy tylko pojawicie się w zasięgu wzroku.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Wrzucanie rzeczy do pojemników z dużym otworem: piłeczki do wiaderka, klocki do pudełka.
• **Przedmioty:** Miękkie ugotowane groszki lub ziarna kukurydzy na tacce to idealny trening chwytu pęsetowego; jedzenie pod nadzorem.

## Woche 33 · Podciąganie się i trzymanie

Wiele niemowląt podciąga się teraz na meblach, szczebelkach łóżeczka albo na waszych nogach. Dla stania z trzymaniem się badanie WHO wykazało zakres normy od 4,8 do 11,4 miesiąca.

⚠️ Wszystko, na co da się wspiąć, staje się drabinką. Przymocujcie regały i komody do ściany, bo przewracające się meble powodują poważne wypadki. Nie stawiajcie gorących napojów na krawędzi stołu i zrezygnujcie ze zwisających obrusów. Oparzenia gorącymi płynami należą do najczęstszych poważnych urazów u niemowląt i małych dzieci.

💡 Kilka stabilnych, niskich mebli obok siebie to idealny teren do ćwiczeń.

📚 **Co jeszcze się dzieje**

• **Mowa:** Gesty pojawiają się przed słowami: unoszenie rączek, kręcenie głową, machanie na pożegnanie. Dzieci, które wcześnie używają wielu gestów, mają w badaniach później zazwyczaj większy zasób słów.
• **Picie i jedzenie:** Apetyt waha się teraz bardziej. Niektórego dnia niemowlęta jedzą dużo, innego prawie nic. Na przestrzeni kilku dni zwykle się to wyrównuje.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Róbcie muzykę: garnek i drewniana łyżka jako bęben, grzechotki, wspólne śpiewanie i kołysanie się w rytm.
• **Sprawdzamy fakty – zajęcia muzyczne:** W kanadyjskim badaniu (Gerry i współpracownicy, 2012) niemowlęta, które od szóstego miesiąca przez pół roku aktywnie muzykowały z rodzicami, wcześniej pokazywały określone gesty i więcej się uśmiechały niż niemowlęta, które tylko słuchały muzyki (pojedyncze badanie). Liczyło się wspólne uczestnictwo, a nie same zajęcia.

## Woche 34 · Protest przy pożegnaniu

Wiele niemowląt protestuje teraz, gdy wychodzicie z pokoju. Płaczą, raczkują za wami albo trudno je odłożyć. CDC podaje „reaguje, gdy wychodzicie” jako kamień milowy w wieku dziewięciu miesięcy. Ten protest przy rozstaniu często nasila się aż do drugiego roku życia.

🔬 Stoi za tym osiągnięcie poznawcze. Dziecko wie teraz, że istniejecie dalej, gdy was nie ma, ale nie potrafi jeszcze ocenić, kiedy wrócicie.

💡 Żegnajcie się krótko i wyraźnie, zamiast wymykać się ukradkiem. Wtedy wasz powrót staje się przewidywalny, a to buduje zaufanie. Pomaga to też, jeśli niedługo czeka was adaptacja w żłobku.

📚 **Co jeszcze się dzieje**

• **Sen:** Protest przy rozstaniu często pojawia się też przy zasypianiu i w nocy. To przejściowy etap rozwoju, a nie znak, że czegoś zaniedbaliście.
• **Pieluszki i nocnik:** Przewijanie zamienia się w zapasy, bo mobilne niemowlęta chcą uciekać. Pomóc może przewijanie na podłodze, specjalna zabawka tylko do przewijania albo piosenka.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Ćwiczcie rozstanie w zabawie: na chwilę za drzwi, „Już jestem!” Dzięki temu wychodzenie i wracanie stają się przewidywalne (wiedza z doświadczenia, słabo zbadana).
• **Jak reagować:** Krótki, zawsze taki sam rytuał pożegnania, na przykład buziak, machanie i jedno zdanie, ułatwia rozstania.

## Woche 35 · Patrzeć tam, gdzie ty patrzysz

Dużym krokiem najbliższych miesięcy jest „wspólna uwaga”. Dziecko coraz częściej podąża za waszym spojrzeniem lub palcem wskazującym i spogląda z powrotem na was, żeby upewnić się, że widzicie to samo. W badaniach rozwija się to głównie między około 9 a 15 miesiącem.

🔬 Wspólna uwaga uchodzi za ważną podstawę nauki mowy. Niemowlęta szczególnie dobrze uczą się słów, gdy dorosły nazywa to, na co dziecko akurat patrzy.

💡 Podążajcie za spojrzeniem dziecka i nazywajcie, co widzi: „Pies! Pies szczeka.”

📚 **Co jeszcze się dzieje**

• **Motoryka:** Badania zuryskie prowadzone przez Remo Largo opisały bardzo różne drogi do chodzenia: poza raczkowaniem także pełzanie, turlanie się czy przesuwanie na pupie. Dzieci, które przesuwają się na pupie, często zaczynają samodzielnie chodzić nieco później, ale poza tym rozwijają się prawidłowo.
• **Zabawa:** Niemowlęta badają teraz, jak rzeczy do siebie pasują: pokrywka na pudełko, łyżeczka do kubka. To łączenie przedmiotów zaczyna się zwykle między około 9 a 18 miesiącem.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Spacer z pokazywaniem: przy oknie albo na dworze pokazujcie rzeczy, nazywajcie je i czekajcie, czy dziecko spojrzy.
• **Przedmioty:** Kubeczki do układania, puszki z pokrywką, garnek z pokrywką.
• **Sprawdzamy fakty – nauka czytania:** Programy, które rzekomo uczą niemowlęta czytać, w kontrolowanym badaniu (Neuman i współpracownicy, 2014) nie wykazały żadnego efektu. Rodzice byli jednak przekonani, że ich dziecko uczy się czytać (pojedyncze badanie).

## Woche 36 · Rozumienie przychodzi przed mówieniem

🔬 Niemowlęta rozumieją znacznie więcej, niż potrafią powiedzieć. W jednym badaniu (Bergelson i Swingley, 2012) już 6–9-miesięczne niemowlęta przy prostych słowach, takich jak „jabłko” czy „nos”, częściej patrzyły na pasujący obrazek. Pierwsze słowa są więc rozumiane na długo przed wypowiedzeniem pierwszego słowa.

Wiele niemowląt reaguje teraz na znajome słowa i czynności. „Gdzie jest tata?”, i główka się odwraca.

💡 Oglądajcie razem książeczki. Nie chodzi o czytanie tekstu, tylko o pokazywanie, nazywanie i czekanie.

📚 **Co jeszcze się dzieje**

• **Picie i jedzenie:** Jedzenia łyżeczką trzeba się nauczyć. Pomagają dwie łyżeczki: jedna dla dziecka, jedna dla was.
• **Wzrost:** Nóżki w kształcie litery O i płaskie stopy są u niemowląt normalne. Łuk stopy tworzy się dopiero w ciągu następnych lat.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Pytajcie przy książeczce: „Gdzie jest piesek?”, a potem czekajcie, aż dziecko spojrzy lub pokaże.
• **Czy coś kupować?** Książeczki kartonowe, materiałowe i sensoryczne. Wymiana z innymi rodzicami albo biblioteka to tanie alternatywy.

## Woche 37 · Szukanie w złym miejscu

🔬 Słynnym zjawiskiem w tym wieku jest „błąd A-nie-B”. Jeśli kilka razy schowacie zabawkę pod chustką A, dziecko ją tam znajduje. Jeśli potem schowacie ją wyraźnie na jego oczach pod chustką B, i tak szuka pod A. To pokazuje, że pamięć robocza i kontrola nad wyuczonymi działaniami jeszcze dojrzewają. Te umiejętności są związane z rozwojem płata czołowego i poprawiają się pod koniec pierwszego roku.

💡 Zabawy w chowanie pod kubeczkami lub chustkami są teraz idealne. Sprawdźcie sami, czy wasze dziecko wpadnie w pułapkę błędu A-nie-B.

📚 **Co jeszcze się dzieje**

• **Relacje:** Przytulanka lub kocyk-przytulak staje się dla wielu dzieci ważny teraz albo w drugim roku życia, jako kawałek czegoś znajomego, gdy was nie ma. W pierwszym roku nie powinien jednak jeszcze leżeć w łóżeczku do spania.
• **Pieluszki i nocnik:** Pieluszka będzie jeszcze długo potrzebna. W badaniach zuryskich w dzień i w nocy pewnie suchych było: w wieku dwóch lat około 20% dzieci, w wieku czterech lat około 90%.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Gra w kubeczki: schowajcie zabawkę pod jednym z dwóch odwróconych kubeczków i pozwólcie dziecku szukać.
• **Przedmioty:** Dwa, trzy kubeczki, chustki, ulubiona zabawka.

## Woche 38 · Spojrzenie na was: czy to niebezpieczne?

Gdy dziecko widzi coś nowego, na przykład głośny odkurzacz albo obcego psa, coraz częściej najpierw patrzy na was. Badania nazywają to „odniesieniem społecznym”.

🔬 W znanym eksperymencie (Sorce i współpracownicy, 1985) roczne niemowlęta raczkowały przez pozorną krawędź na szklanej płycie, gdy mama patrzyła radośnie, ale prawie wcale, gdy patrzyła z lękiem. Niemowlęta traktują więc waszą mimikę jako informację.

💡 Wasz spokój jest zaraźliwy. Gdy komentujecie coś nowego przyjaźnie, dziecko odważa się na więcej.

📚 **Co jeszcze się dzieje**

• **Mowa:** Wiele niemowląt rozumie teraz proste prośby w kontekście, na przykład „Daj mi piłkę”, gdy wyciągacie przy tym rękę.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zabawa w „daj”: wyciągnijcie rękę, „Dziękuję!”, oddajcie, „Proszę!”
• **Jak reagować:** Podchodźcie do nowych rzeczy przyjaźnie i z ciekawością. Wasza mimika pokazuje dziecku, czy jest bezpiecznie.

## Woche 39 · Dziewięć miesięcy: podsumowanie

Co potrafi większość niemowląt (około 75%) w wieku dziewięciu miesięcy według CDC:

• jest nieśmiałe lub lękliwe wobec obcych i reaguje, gdy wychodzicie
• pokazuje różne miny (radość, smutek, złość, zdziwienie)
• patrzy, gdy woła się je po imieniu, i śmieje się przy „a kuku”
• gaworzy sylabami, takimi jak „mamama” i „bababa”, i wyciąga rączki, żeby je podnieść
• szuka rzeczy, które zniknęły z pola widzenia, i uderza dwoma przedmiotami o siebie
• samo siada, siedzi bez podparcia i przekłada rzeczy z rączki do rączki

Jak zawsze: pojedyncze brakujące punkty nie są powodem do niepokoju, ale dobrymi pytaniami na badanie U6. Jeśli dziecko nie reaguje na swoje imię **i** nie gaworzy sylabami, pokażcie je szybko lekarzowi. Należy przy tym między innymi zbadać słuch.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Wymieniajcie zabawki i wyciągajcie stare ulubione. Dziecko często odkrywa je na nowo.
• **Czy coś kupować?** Przydatne na najbliższe miesiące: kubeczki do układania, miękka piłka, książeczki kartonowe. Resztę zapewni dom.

## Woche 40 · Naśladowanie z opóźnieniem

Wasze dziecko staje się naśladowcą: machanie, klaskanie, „Kosi, kosi łapci”. Według CDC większość dzieci w wieku roku bierze udział w takich zabawach.

🔬 Niemowlęta potrafią nawet naśladować czynności z opóźnieniem. W eksperymentach Andrew Meltzoffa dziewięciomiesięczne niemowlęta naśladowały nową czynność z zabawką jeszcze 24 godziny po tym, jak ją zobaczyły. To pokazuje zadziwiającą pamięć.

💡 Pokazujcie wyraźnie proste czynności: pokrywka na puszkę, piłka do pudełka, machanie na pożegnanie.

📚 **Co jeszcze się dzieje**

• **Picie i jedzenie:** Ile dzieci jedzą, jest bardzo różne i wiąże się ze wzrostem i ruchem. Presja („Jeszcze jedna łyżeczka!”) prowadzi w badaniach raczej do tego, że dzieci jedzą mniej chętnie.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Pokazujcie codzienne czynności: czesanie włosów, mieszanie łyżką, karmienie misia.
• **Przedmioty:** Prawdziwe, niegroźne przedmioty codziennego użytku często fascynują bardziej niż ich zabawkowe wersje (wiedza z doświadczenia, słabo zbadana). Żadnych starych telefonów ani pilotów z bateriami w zasięgu dziecka.

## Woche 41 · Pokazywanie palcem

W najbliższych miesiącach pojawi się jeden z najważniejszych gestów: pokazywanie palcem wskazującym. Najpierw zwykle po to, żeby coś dostać („Chcę to!”), nieco później także po to, żeby się czymś podzielić („Patrz, ptaszek!”). CDC podaje pokazywanie palcem, żeby uzyskać pomoc, jako kamień milowy dla 15 miesięcy, a pokazywanie czegoś ciekawego dla 18 miesięcy.

🔬 Pokazywanie, żeby się czymś podzielić, jest szczególnie ciekawe, bo pokazuje: wasze dziecko chce, żebyście widzieli to samo co ono. To jedna z podstaw mowy i rozumienia społecznego.

💡 Reagujcie na każde pokazywanie: spójrzcie, nazwijcie, dziwcie się razem.

📚 **Co jeszcze się dzieje**

• **Sen:** Większość dzieci potrzebuje teraz jeszcze dwóch drzemek. Wiele przechodzi na jedną gdzieś między 12 a 18 miesiącem.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Album ze zdjęciami rodzinnymi: „Gdzie jest babcia?” Pokazywać, nazywać, dziwić się.
• **Jak reagować:** Reagujcie na każde pokazywanie, nawet gdy jesteście zajęci, przynajmniej spojrzeniem i słowem.

## Woche 42 · Wzdłuż mebli

Wiele niemowląt przesuwa się teraz bokiem wzdłuż kanapy i stołu. Dla chodzenia z trzymaniem się badanie WHO wykazało zakres normy od 5,9 do 13,7 miesiąca.

Dziecko nie potrzebuje do tego butów. Boso najlepiej czuje podłoże, a mięśnie stóp się wzmacniają. Buty mają sens dopiero wtedy, gdy dziecko chodzi na dworze.

💡 Zabawki do pchania bez siedziska, na przykład stabilny pchacz z uchwytem (najlepiej z hamulcem), są w porządku. To coś innego niż chodziki, w których dziecko siedzi.

📚 **Co jeszcze się dzieje**

• **Relacje:** Inne niemowlęta stają się ciekawe: niemowlęta patrzą na siebie, uśmiechają się i dotykają. Prawdziwa wspólna zabawa przychodzi jednak znacznie później.
• **Wzrost:** Przy większej ilości ruchu wiele niemowląt wolniej przybiera na wadze. To normalne i nie oznacza, że jedzą za mało.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Rozłóżcie zabawki wzdłuż kanapy, żeby dziecko przesuwało się do nich, trzymając się mebla.
• **Czy coś kupować?** Buty do nauki chodzenia nie są potrzebne. W domu najlepiej boso lub w antypoślizgowych skarpetkach (wiedza z doświadczenia, słabo zbadana). Pchacz z hamulcem jest opcjonalny.

## Woche 43 · Do rodzinnego stołu

Według niemieckiej sieci Gesund ins Leben mniej więcej od 10. miesiąca niemowlęta mogą stopniowo przechodzić na jedzenie rodzinne: miękko ugotowane kawałki, pieczywo, łagodne dania rodzinne, tylko mniej słone i ostre. Wiele niemowląt chce teraz jeść samodzielnie, rączkami i łyżeczką.

🔬 Samodzielne jedzenie to trening motoryczny i sensoryczny. To, że przy tym robi się bałagan, jest częścią nauki.

⚠️ Nadal obowiązuje: żadnego miodu przed pierwszymi urodzinami, okrągłe twarde produkty (winogrona, pomidorki koktajlowe) kroić na ćwiartki, żadnych całych orzechów.

💡 Jedzcie razem. Niemowlęta chętniej próbują nowych rzeczy, gdy widzą, że wy też je jecie.

📚 **Co jeszcze się dzieje**

• **Mowa:** Przy wspólnym jedzeniu jest wiele okazji do rozmowy: nazywać, komentować, pytać „Jeszcze?” i czekać na odpowiedź.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Jedzcie razem przy stole te same produkty, tylko dostosowane (bardziej miękkie, z mniejszą ilością soli).
• **Przedmioty:** Własna łyżeczka, mały otwarty kubeczek, miseczka z przyssawką.

## Woche 44 · Rozumieć „nie” i i tak to robić

Według CDC większość dzieci w wieku roku rozumie „nie” i na chwilę się zatrzymuje. Ale nic ponad to. Umiejętność powstrzymania impulsu rozwija się dopiero w ciągu następnych lat. To, że dziecko po raz dziesiąty raczkuje do gniazdka, nie jest więc przekorą, tylko etapem rozwoju.

Ulubiona zabawa „Zrzucam łyżeczkę z krzesełka” też jest badaniem: co się stanie, gdy puszczę? I czy łyżeczka wróci?

💡 Urządzenie otoczenia działa lepiej niż wiele zakazów. Uprzątnijcie to, co jest niedozwolone, i proponujcie alternatywy.

📚 **Co jeszcze się dzieje**

• **Relacje:** Granice i więź się nie wykluczają. Przyjazne i konsekwentne przekierowywanie daje dzieciom poczucie bezpieczeństwa, nawet jeśli w danej chwili protestują.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Przekierowujcie zamiast wielu „nie”: „To telefon mamy, a tu jest twoja puszka.” Urządźcie „strefy tak”, w których wszystko jest dozwolone.
• **Pomysł na zabawę:** Pozwólcie rzucać tam, gdzie się da: miękkie piłeczki do koszyka.

## Woche 45 · Pierwsze słowa w zasięgu

Pierwsze prawdziwe słowa pojawiają się u wielu dzieci około pierwszych urodzin, przy dużej rozpiętości: u niektórych wcześniej, u wielu wyraźnie później. Według CDC większość dzieci w wieku roku mówi „mama” lub „tata” (albo inne szczególne imię) celowo do właściwej osoby. Także „hau-hau” czy „am” liczą się jako słowa, jeśli zawsze znaczą to samo.

💡 **Rozszerzać zamiast poprawiać:** Jeśli dziecko mówi „Pi!” na piłkę, odpowiedzcie: „Tak, piłka! Czerwona piłka się toczy.” W ten sposób słyszy właściwe słowo, nie będąc poprawianym.

📚 **Co jeszcze się dzieje**

• **Motoryka:** Niektóre niemowlęta wchodzą teraz na czworakach po schodach. Schodzenie jest trudniejsze: tyłem, na brzuszku, nóżkami do przodu. Można to ćwiczyć pod nadzorem.
• **Pieluszki i nocnik:** Niektóre dzieci już pokazują, że zauważają pełną pieluszkę. Odpieluchowanie to jednak przede wszystkim kwestia dojrzewania. W badaniach zuryskich (Largo i współpracownicy) nie dało się go przyspieszyć wczesnym ani intensywnym treningiem.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zabawa w odgłosy zwierząt: „Jak robi piesek?” I piosenki z pauzami, w których dziecko może dopowiedzieć.
• **Czy coś kupować?** Mówiące zabawki nie są potrzebne. W jednym badaniu (Sosa, 2016) rodzice przy zabawkach elektronicznych rozmawiali z dziećmi mniej niż przy książeczkach czy tradycyjnych zabawkach (pojedyncze badanie).

## Woche 46 · A ekrany?

WHO nie zaleca dzieciom poniżej pierwszego roku życia żadnego czasu przed ekranem. Powodem jest nie tyle to, że ekrany są „trujące”, ile to, że zabierają czas, w którym niemowlęta się uczą: ruch, zabawę, rozmowy.

🔬 Niemowlęta uczą się z filmów wyraźnie gorzej niż od prawdziwych ludzi, badania nazywają to „deficytem wideo”. Badania pokazują też, że rodzice mniej rozmawiają z dziećmi, gdy w tle włączony jest telewizor.

Wideorozmowy z babcią i dziadkiem to co innego, bo na dziecko reaguje prawdziwy człowiek. Amerykańska Akademia Pediatrii (AAP) uważa je za niegroźne także w pierwszym roku życia.

💡 Bez wyrzutów sumienia, ale jeśli się da: wyłączcie telewizor, gdy dziecko bawi się w pokoju.

📚 **Co jeszcze się dzieje**

• **Zabawa:** Proste zabawki sprzyjają rozmowie. W jednym badaniu (Sosa, 2016) rodzice przy zabawkach elektronicznych rozmawiali z dziećmi mniej niż przy książeczkach czy tradycyjnych zabawkach.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zamiast ekranu podczas gotowania: kuchenna szuflada z garnkami, pokrywkami i drewnianymi łyżkami, którą dziecko może opróżniać.
• **Sprawdzamy fakty – filmy edukacyjne:** W jednym badaniu (DeLoache i współpracownicy, 2010) dzieci w wieku 12–18 miesięcy nie nauczyły się z popularnej płyty edukacyjnej więcej słów niż bez niej. Najwięcej uczyły się, gdy rodzice używali tych słów w codziennym życiu. Rodzice, którym płyta się podobała, przeceniali efekt nauki (pojedyncze badanie).

## Woche 47 · Wkładać, wyjmować, wkładać

Wasze dziecko staje się sortowaczem: wkłada rzeczy do pudełek, wyjmuje, i od nowa. Według CDC większość dzieci w wieku roku wkłada przedmioty do pojemnika. Kryją się za tym ważne pojęcia, takie jak „w środku” i „na zewnątrz”, oraz doświadczenie, że rzeczy się pojawiają z powrotem.

💡 Najlepsze zabawki często są w kuchni: miska, kilka drewnianych łyżek, plastikowe pojemniki z pokrywkami.

📚 **Co jeszcze się dzieje**

• **Sen:** Sen nocny wydłuża się w pierwszym roku tylko nieznacznie, w badaniach zuryskich z około 11 do prawie 12 godzin. Zmniejsza się głównie sen w ciągu dnia.
• **Picie i jedzenie:** Mniej więcej od roku mleko krowie może być napojem, ale z umiarem, bo za dużo mleka hamuje wchłanianie żelaza z jedzenia.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Zabawy we wkładanie i wyjmowanie: puszka z otworem w pokrywce i duże drewniane krążki albo podkładki pod kubki do wrzucania.
• **Przedmioty:** „Dozwolona” szuflada lub skrzynka, którą dziecko może w każdej chwili opróżniać.

## Woche 48 · Samodzielne stanie, pierwsze kroki?

Niektóre niemowlęta potrafią już przez chwilę stać samodzielnie, niektóre robią pierwsze kroki, wiele potrzebuje jeszcze miesięcy. Badanie WHO wykazało dla samodzielnego chodzenia zakres normy od 8,2 do 17,6 miesiąca, i to u zdrowych dzieci.

🔬 Wczesne chodzenie nie znaczy mądrzejsze. Szwajcarskie badanie długoterminowe (Jenni i współpracownicy, 2013) nie wykazało związku między wiekiem pierwszych samodzielnych kroków a późniejszą inteligencją czy sprawnością w wieku szkolnym.

💡 „Ćwiczenie chodzenia” za obie rączki nie jest potrzebne. Dzieci, które we własnym tempie podciągają się i puszczają, same znajdują równowagę.

📚 **Co jeszcze się dzieje**

• **Wzrost:** W badaniu WHO wzrost dziecka prawie nie wiązał się z wiekiem osiągania kamieni milowych. Wyższe dzieci były wcześniej tylko o kilka dni.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Połóżcie zabawkę na niskim meblu, to zachęca do podciągania się i stania. „Chodzenie” za rączkę tylko wtedy, gdy dziecko samo tego chce.
• **Czy coś kupować?** Nadal żadnych butów do nauki chodzenia w domu. Buty dopiero wtedy, gdy dziecko chodzi na dworze.

## Woche 49 · Wielkie uczucia, mało narzędzi

Frustracja pojawia się teraz częściej. Wasze dziecko chce więcej, niż potrafi: zbudować wieżę, dosięgnąć półki, mieć pilota. Regulowania uczuć dzieci uczą się przez lata, i to najpierw razem z wami. Wy uspokajacie, nazywacie i pocieszacie, a dziecko stopniowo przejmuje to samo.

🔬 Obawa, że szybkie reagowanie „rozpieszcza” niemowlęta, jest według obecnego stanu badań nieuzasadniona. Niezawodne reagowanie na potrzeby uchodzi za podstawę bezpiecznego przywiązania.

💡 Nazywajcie uczucia: „Złościsz się, bo wieża się przewróciła.” Dosłownie dziecko jeszcze tego nie rozumie, ale uczy się, że uczucia mają nazwy i da się je przetrwać.

📚 **Co jeszcze się dzieje**

• **Picie i jedzenie:** Pod koniec pierwszego roku wiele dzieci staje się bardziej nieufnych wobec nowych produktów. Najlepszą strategią jest ich wielokrotne proponowanie bez presji.

🧸 **Co możecie teraz robić**

• **Jak reagować:** Przy frustracji: bądźcie przy dziecku, nazwijcie uczucie, pomóżcie, zamiast od razu całkowicie przejmować zadanie.
• **Pomysł na zabawę:** Naśladujcie miny uczuć przed lustrem albo w książeczce: radość, smutek, zdziwienie.

## Woche 50 · Tam i z powrotem

Teraz możliwe stają się zabawy z wymianą ról: toczenie piłki tam i z powrotem, podawanie przedmiotu i odbieranie go („Dziękuję!”, „Proszę!”). Dziecko rozumie, że zabawa ma zasady i role.

🔬 Takie zabawy trenują to samo co rozmowa: zwracanie uwagi na siebie nawzajem, czekanie, reagowanie. To, ile takich wymian dzieci doświadczają, wiąże się w badaniach z rozwojem ich mowy.

💡 Potoczcie piłkę do dziecka i poczekajcie, czy wróci. A jeśli nie: odraczkowanie z piłką to też odpowiedź.

📚 **Co jeszcze się dzieje**

• **Motoryka:** Rączki stają się coraz sprawniejsze: przewracanie kartek w książeczce kartonowej, niedługo także ustawianie dwóch klocków jeden na drugim.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Toczcie piłkę tam i z powrotem, dawajcie i bierzcie rzeczy, na zmianę budujcie i przewracajcie wieżę.
• **Przedmioty:** Duża, miękka piłka i kilka lekkich klocków.

## Woche 51 · Rok rozwoju mózgu

🔬 Mózg waszego dziecka w pierwszym roku życia mniej więcej podwoił swoją objętość. Już nigdy potem nie rośnie tak szybko (Knickmeyer i współpracownicy, 2008). Powstaje przy tym przede wszystkim bardzo wiele nowych połączeń między komórkami nerwowymi, a te, które są często używane, się wzmacniają.

Gdy spojrzycie wstecz: z noworodka z odruchami stało się dziecko, które was rozpoznaje, „rozmawia” z wami, dąży do celów, przemieszcza się i żartuje.

💡 Dobry moment, żeby obejrzeć stare zdjęcia i uświadomić sobie, ile w tym roku osiągnęliście.

🧸 **Co możecie teraz robić**

• **Pomysł na zabawę:** Mała fotoksiążka z pierwszego roku do wspólnego oglądania: „Kto to?”
• **Jak reagować:** Znajdźcie też czas dla siebie. Rok z niemowlęciem to ogromne osiągnięcie.

## Woche 52 · Roczek!

Gratulacje, cały rok! 🎂 Co potrafi większość dzieci (około 75%) w wieku roku według CDC:

• bawi się w zabawy takie jak „Kosi, kosi łapci” i macha na pożegnanie
• mówi „mama”, „tata” lub inne szczególne imię do właściwej osoby
• rozumie „nie” i na chwilę się zatrzymuje
• szuka rzeczy, które chowacie na jego oczach, i wkłada przedmioty do pojemnika
• podciąga się do stania i chodzi, trzymając się mebli
• pije z otwartego kubeczka, który trzymacie, i chwyta kciukiem i palcem wskazującym

Pamiętajcie: samodzielne chodzenie, wiele słów czy pokazywanie palcem mogą przyjść jeszcze wyraźnie później.

To była ostatnia cotygodniowa wiadomość. Dziękuję, że mogłem jako bot towarzyszyć wam przez pierwszy rok, i wszystkiego dobrego na wszystko, co przed wami!

🧸 **Co możecie teraz robić**

• **Czy coś kupować?** Na urodziny lepiej mało prezentów, a resztę wyciągać stopniowo później (wiedza z doświadczenia, słabo zbadana). Książki i wspólny czas z babcią i dziadkiem to często najlepsze prezenty.
• **Jak reagować:** Świętujcie krótko i w małym gronie. Zbyt duże zamieszanie przytłacza wiele roczniaków.

## Termine Woche 0

• **U2** (od 3. do 10. dnia życia), często jeszcze w szpitalu. Dziecko dostaje wtedy drugą dawkę witaminy K. Badanie przesiewowe z krwi noworodka i przesiewowe badanie słuchu wykonuje się zwykle w pierwszych dniach życia. Zapytajcie, jeśli czegoś brakuje.
• **Witamina D:** Codzienne podawanie witaminy D (zwykle w tabletce, często razem z fluorem) zaczyna się w pierwszym tygodniu życia i trwa do drugiego przeżytego wczesnego lata. Jaki preparat, ustalcie z gabinetem pediatrycznym lub położną.
• **Ochrona przed RSV:** Jeśli dziecko urodzi się w sezonie RSV (zwykle od października do marca), STIKO (niemiecka Stała Komisja ds. Szczepień) zaleca przeciwciało (nirsewimab) możliwie szybko po porodzie, najlepiej przed wypisem ze szpitala lub podczas U2.
• Jeśli jeszcze tego nie zrobiliście: poszukajcie gabinetu pediatrycznego. Wiele z nich przyjmuje nowych pacjentów tylko w ograniczonym zakresie.

## Termine Woche 1

• **Formalności z terminami:** Elterngeld (zasiłek rodzicielski) jest wypłacany wstecz tylko za ostatnie trzy miesiące życia przed miesiącem złożenia wniosku, Kindergeld (zasiłek na dziecko) za sześć miesięcy. Nie zwlekajcie więc zbyt długo. Zwykle potrzebny jest do tego akt urodzenia z urzędu stanu cywilnego (Standesamt).
• Dziecko trzeba zgłosić do kasy chorych (ubezpieczenie rodzinne, Familienversicherung).

## Termine Woche 2

• **Umówcie U3:** Badanie U3 odbywa się w 4.–5. tygodniu życia. Obejmuje USG bioder, trzecią dawkę witaminy K i rozmowę o zbliżających się szczepieniach.

## Termine Woche 5

• **Szczepienie przeciw rotawirusom:** Ta doustna szczepionka jest możliwa od 6. tygodnia życia (2 lub 3 dawki, zależnie od preparatu). Zacznijcie jak najwcześniej, bo cykl szczepień musi zostać zakończony do określonego wieku. Najlepiej umówcie termin już teraz.

## Termine Woche 8

• **Szczepienia w wieku 2 miesięcy** (STIKO): szczepionka 6 w 1 (tężec, błonica, krztusiec, Hib, polio, WZW typu B), pneumokoki i meningokoki typu B, do tego ewentualnie kolejna dawka przeciw rotawirusom.
• **U4** (3.–4. miesiąc życia). Często można je połączyć z terminem szczepienia.

## Termine Woche 12

• Tylko jeśli dziecko urodziło się przedwcześnie: STIKO zaleca wcześniakom w wieku 3 miesięcy dodatkową dawkę szczepionki 6 w 1 i przeciw pneumokokom.

## Termine Woche 17

• **Szczepienia w wieku 4 miesięcy:** po drugiej dawce szczepionki 6 w 1, przeciw pneumokokom i przeciw meningokokom typu B.

## Termine Woche 21

• **Umówcie U5** (6.–7. miesiąc życia). Tematami są między innymi ruch, wzrok, odżywianie i pielęgnacja zębów.
• **Wczesne badania stomatologiczne:** Kasy chorych pokrywają badania u dentysty od 6. miesiąca życia.

## Termine Woche 26

• **Pierwszy ząbek?** U niektórych dzieci teraz, u innych dopiero za kilka miesięcy. Gdy tylko się pojawi: zacznijcie myć zęby i wyjaśnijcie kwestię fluoru. Albo dalej tabletki z witaminą D **i** fluorem, wtedy mycie bez pasty z fluorem. Albo witamina D bez fluoru, wtedy mycie ilością pasty dla dzieci wielkości ziarenka ryżu z 1000 ppm fluoru. Nie łączcie obu. Tak od 2021 roku wspólnie zalecają pediatrzy i dentyści w Niemczech.

## Termine Woche 38

• **Umówcie U6** (10.–12. miesiąc życia).

## Termine Woche 47

• **Szczepienia w wieku 11 miesięcy:** trzecia dawka szczepionki 6 w 1 i przeciw pneumokokom oraz pierwsza dawka przeciw odrze, śwince, różyczce i ospie wietrznej. Szczepienia można rozłożyć na kilka wizyt. Jeśli dziecko wcześniej pójdzie do żłobka, szczepienie przeciw odrze jest możliwe już od 9 miesięcy. W Niemczech ochrona przed odrą jest w żłobku wymagana prawem.

## Termine Woche 52

• **Meningokoki typu B:** trzecia dawka w wieku 12 miesięcy. W wieku 15 miesięcy następuje druga dawka przeciw odrze, śwince, różyczce i ospie wietrznej.
• **Witamina D** dalej do drugiego przeżytego wczesnego lata.
• **Mycie zębów:** Od 12 miesięcy wszystkim dzieciom zaleca się dwa razy dziennie ilość pasty z 1000 ppm fluoru wielkości ziarenka ryżu. Tabletek z fluorem wtedy się już nie podaje.
• Następne badanie profilaktyczne, **U7**, odbywa się w wieku 21–24 miesięcy.

## Saison rsv · Monate 9, 10 · bis Woche 30

**Zbliża się sezon RSV.** STIKO zaleca, aby niemowlęta urodzone między kwietniem a wrześniem jesienią, przed swoim pierwszym sezonem RSV, jednorazowo otrzymały przeciwciało (nirsewimab). U małych niemowląt RSV jest jedną z najczęstszych przyczyn pobytów w szpitalu z powodu infekcji dróg oddechowych. Zapytajcie w gabinecie pediatrycznym, jeśli ten temat jeszcze się nie pojawił. Tam też wyjaśnią, czy jest to u was potrzebne.

## Saison sommer · Monate 5, 6, 7, 8 · bis Woche 52

**Lato z niemowlęciem:** Niemowlęta w pierwszym roku życia nie powinny przebywać na bezpośrednim słońcu. Lepsze są cień, lekkie, zakrywające ubranie i kapelusik. W upały częściej karmcie piersią lub podawajcie butelkę, a przy posiłkach uzupełniających także wodę. Nigdy nie przykrywajcie wózka chustą, bo pod nią gromadzi się ciepło. I nigdy nie zostawiajcie dziecka samego w samochodzie.
