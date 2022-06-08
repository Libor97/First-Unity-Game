# First-Unity-Game
Unfinished first try on Unity 2d gamedev

Toto je local multiplayer hra v unity, 
můj první experiment v Unity a hra, kterou jsem načal a rozhodnul se nedokončit. 
S Unity jsem se poprvé začal učit v 2020 a podle souborů 
tipuji že jsem tento projekt dělal květen až srpen 2020.
Celý projekt byl můj a celý kod byl psaný pouze mnou a to v C#.
Bohužel jsem tento a všechny moje ostatní projekty v roce 2021 smazal, tento jsem našel
nedávno zálohovaný na google drive, ale už se nedostanu k C# skriptům a zdrojovému kodu.  

Návod k zprovoznění:

Stáhnout Soubory1.rar a Soubory2.rar. Vytvořit libovolnou složku, například "Hra" a oba dva archívy extrahovat do té složky. Pak spustit přes "Můj nový projekt.exe". Poté hru vypnout přes Ctr+Alt+Delete -> správce úloh nebo Alt + F4.

Hráč 1

Pohyb: WASD
Teleport: Space   ( Teleportne hráče o kousek ve směru pohybu, může tak přeskočit projektily a utéct nebezpečí )
Blokace: E        ( Hráč použije úder štítem, tento útok dává zároveň poškození nepřátelům a zároveň chrání hráče po dobu užití, blokuje poškození )  
Útok: Q           ( základní útok, 2 bodnutí mečem )
Hození zbraně: R  ( hod své zbraně ) 

Hráč 2

Pohyb: Šipky
Teleport: Shift                                         
Blokace: O
Útok: I
Hození zbraně: P

Cíl hry:
Na mapě jsou hroby monster, z nichž se spawnují zombie nepřátelé, cílem hráčů je zabíjet monstra a k prevenci spawnování dalších zničit i jejich hroby.
Hráči můžou kooperovat a pomáhat si proti AI nebo můžou hrát proti sobě o to, kdo dá lepší score. 
Score se počítá za zabití druhého hráče, za zabití monster i monster hrobů. 
Při zabíjení monster z nich spadne power-up který může hráč sebrat a posílit schopnosti své postavy.
Hra nemá naprogramovaný main menu,tutorial,nastavení, zvuk ani konec. Ani nelze klasicky vypnout, je prostě nedokončená. 

Co si pamatuju z vývoje hry:
Nejvíce času mi zabírali animace a grafika, samotný kod byl sice tisíce-desetitisíce řádků dlouhý, ale problém mi zas tak nedělal.
Vytvořil jsem 3 AI soupeře s různými patterny útoků a chováním. Vím že mi path-finding, AI detekce a obecně programování AI dělalo problémy. 
Dále mi dělalo problémy časování animací s kodem, registrace hitboxů a správně načasované útoky.

Proč jsem hru nedokončil:
Byl to první projekt v Unity, neměl budoucnost, hra začala být nezáživná a chybělo toho dodělat mnoho. Audio/Cíl hry/Tutorial/Nastavení atd..
Místo toho jsem se vrhnul na 2D RPG auto battler hru, kterou jsem vyvíjel 8 měsíců skoro non-stop. Bohužel jsem se rozhodnul vymazat a mám z ní pouze screenshoty a videa. 
