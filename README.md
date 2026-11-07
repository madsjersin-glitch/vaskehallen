# Vaskehallen

Et vaskehal-spil til mobilen. Bilen kører ind dækket af grene, blade og mudder:

1. **Saks** – klip grenene af ved de stiplede mærker
2. **Luft** – blæs bladene væk
3. **Vand** – spul mudderet af
4. **Skum** – vask skummet af

Vælg mellem personbil, politibil, ambulance, brandbil, bus og monstertruck, med almindelige hjul eller monsterhjul.

## Installér på telefonen

Åbn siden på telefonen og vælg **Del → Føj til hjemmeskærm** (iPhone) eller **⋮ → Installer app** (Android).
Spillet åbner i fuld skærm og virker også uden internet, når det har været åbnet én gang.

## Hosting

Ren statisk side uden build-trin. På Vercel: importér repoet, vælg framework **Other**, og lad build-kommando og output-mappe være tomme.

Når `index.html` eller ikonerne ændres, så hæv `VERSION` i `sw.js`, så telefonerne henter den nye version.
