# Ideový plán

## Název hry: **Cloud Kingdom**

## Marketingový úvodník
Ztratil se magický krystal, který drží Království v oblacích pohromadě! Chopte se role Nubeho, odvážného hrdiny s neobyčejně silnýma nohama, a vydejte se na záchrannou misi. Skákejte přes zrádné propasti, odrážejte se od hlav nepřátel, sbírejte ztracené mince a proskákejte se šesti pestrými světy až do doupěte mechanického Golema, který krystal ukradl. Dokážete zachránit své domovské nebe dřív, než spadne na zem?

## Popis hry
- **Principy:** Hra je klasická 2D side-scrolling platformer
- **Funkčnost a možnosti:** 
  - Hráč se může pohybovat do stran, skákat a provádět double jump.
  - Eliminace nepřátel probíhá klasickým skokem na jejich hlavu.
  - V levelech jsou rozesety sběratelské předměty jako mince pro skóre, srdíčka pro doplnění zdraví.
- **Cíle hráče:** 
  - Projít zleva doprava 5 běžných úrovní plných překážek a nepřátel, přičemž na konci každé z nich čeká magický portál do dalšího světa.
  - V 6. úrovni (Boss Fight) musí hráč využít všechny naučené mechaniky, aby třikrát zasáhl bosse na zranitelném místě a získal zpět magický krystal.

## Popis audiovizuálu
- **Grafika:** 16-bitový barevný pixel art. Prostředí bude jasné a kontrastní (zelené louky, modré nebe, temnější jeskyně a mechanické doupě bosse). Animace budou plynulé, s využitím principů "squash and stretch" pro zdůraznění váhy a odrazu při skoku.
- **Zvuk a hudba:** Chiptune soundtrack inspirovaný érou SNES/Sega Genesis. Rychlá, veselá hudba pro první úrovně, která postupně ztemní v jeskyních a vyvrcholí epickým retro motivem při souboji s bossem. Zvukové efekty budou obsahovat uspokojivé cinknutí při sběru mincí a bop při odrazu od nepřítele.

## Chystané použité technologie
- **Herní engine:** Godot Engine 4.x (Tvorba logiky, fyziky, UI a sestavení hry).
- **Programovací jazyk:** GDScript.
- **Tvorba grafiky:** Aseprite.
- **Tvorba zvuků/hudby:** Bfxr nebo sfxr pro generování retro zvukových efektů, BeepBox/Bosca Ceoil pro chiptune hudbu.
- **Verzování:** Git a GitHub.

## Hypotézy (k ověření po releasu)
1. **Hypotéza 1 (Hratelnost a obtížnost):** Průměrný hráč pochopí mechaniku dvojskoku intuitivně a dokončí první level za méně než 2 minuty bez toho, aby více než třikrát zemřel. *(Měření: Analýza gameplay videí nebo herní analytiky od testerů).*
2. **Hypotéza 2 (Boss fight design):** Finální boss bude pro hráče představovat adekvátní výzvu – průměrný hráč bude potřebovat minimálně 3 pokusy na jeho poražení, což zajistí pocit zadostiučinění bez extrémní frustrace.
