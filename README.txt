ROZVOZ A SVOZY – PWA PRO IPHONE

OBSAH
- index.html: aplikace
- manifest.webmanifest: údaje pro instalaci na plochu
- sw.js: offline cache a aktualizace
- icons/: ikony aplikace

DŮLEŽITÉ
Tento balíček je připravený k nahrání do stejného GitHub Pages repozitáře, který nyní obsluhuje původní aplikaci.
Před nahráním si v původní aplikaci stáhni zálohu dat (tlačítko „Stáhnout zálohu“), pokud už v ní máš záznamy.
Nahrání nových souborů na stejnou adresu webu obvykle zachová místní data, protože se nemění původ domény; přesto si nejprve udělej zálohu.
Aplikace si po prvním načtení online uloží základní soubory a potom se otevře i bez internetu. Google Mapy a načítání OCR/QR knihoven z internetu vyžadují internet; ostatní uložené funkce jsou dostupné offline.
Aktualizace aplikace se načtou při online návštěvě. Uložená data se při aktualizaci nemažou.

POSTUP NA IPHONU PO PUBLIKOVÁNÍ
1. Otevři původní adresu aplikace v Safari.
2. Klepni na tlačítko Sdílet.
3. Vyber „Přidat na plochu“.
4. Potvrď „Přidat“. Spouštěj aplikaci novou ikonou na ploše.

Pro úplnou instalaci je nutné nahrát VŠECHNY soubory a složku icons do kořenové složky stejného GitHub Pages repozitáře. Samotné stažení HTML souboru nestačí k instalaci PWA.
