# Tuin-app op je telefoon zetten

Het bestand `tuin.html` is één zelfstandig bestand dat werkt op elke telefoon. Hier drie manieren om het op je startscherm te krijgen, van makkelijkst naar meest flexibel.

## Optie 1: GitHub Pages (aanbevolen, gratis, permanent)

Dit is de beste optie — gratis, betrouwbaar, en je hebt een vaste URL.

**Stappen:**
1. Ga naar https://github.com en maak een gratis account (als je die nog niet hebt)
2. Klik rechtsboven op **+** → **New repository**
3. Geef de repo een naam, bijvoorbeeld `tuin`
4. Vink aan: **Add a README file** (verplicht om de repo te initialiseren)
5. Klik **Create repository**
6. In de repo: klik **Add file** → **Upload files**
7. Sleep `tuin.html` naar het upload-vak
8. Klik **Commit changes**
9. Ga naar **Settings** (tab bovenaan) → **Pages** (menu links)
10. Onder "Source": selecteer **main** en map **/ (root)** → **Save**
11. Wacht 1-2 minuten, ververs de Pages-pagina
12. Je krijgt een URL zoals `https://jouwnaam.github.io/tuin/tuin.html`

**Die URL open je op je telefoon.** Dan:
- **iPhone (Safari):** tik op het share-icoon (vierkantje met pijl omhoog) → **"Zet op beginscherm"** → naam kiezen → **Voeg toe**
- **Android (Chrome):** tik op de drie puntjes rechtsboven → **"App installeren"** of **"Toevoegen aan startscherm"**

Je hebt nu een app-icoon "Tuin" dat werkt zoals een echte app.

## Optie 2: Netlify Drop (nog makkelijker, geen account nodig)

Als je geen GitHub-account wilt:

1. Ga naar https://app.netlify.com/drop op je computer
2. Sleep `tuin.html` in het vak
3. Netlify geeft je direct een URL
4. Open die URL op je telefoon en voeg toe aan startscherm zoals hierboven

Nadeel: de URL is lang en willekeurig (`https://abc-def-123.netlify.app`). Je kunt gratis een account maken om een eigen naam te kiezen.

## Optie 3: Direct op je telefoon (werkt zonder internet)

Als je helemaal geen server wilt:

1. Stuur jezelf het bestand `tuin.html` via e-mail, AirDrop, of WhatsApp-chat naar jezelf
2. Download het op je telefoon, bewaar in de **Bestanden**-app (iPhone) of **Downloads** (Android)
3. Open het bestand vanuit Bestanden/Downloads — de browser opent het

Nadeel: je moet het elke keer vanuit Bestanden openen, geen mooi app-icoon. Maar het werkt wel 100% offline.

**Voor iPhone:** je kunt een snelkoppeling maken via de Shortcuts-app die het bestand opent, en die snelkoppeling op je beginscherm zetten.

## Wat er wel en niet werkt

**Werkt:**
- Alle taken per maand afvinken — vinkjes worden bewaard op je telefoon
- Alle plantinfo bekijken
- Bestellijst per maand
- Zone filteren
- Weer-scenario's en tips

**Werkt niet (in deze versie):**
- Live weer ophalen (dat deed de oorspronkelijke app ook niet)
- Foto's uploaden
- Sync tussen apparaten (vinkjes op telefoon zijn niet zichtbaar op tablet en andersom)

## Updates

Als je wijzigingen wilt in de app (nieuwe planten, nieuwe tips, je appelrassen na determinatie toevoegen), vraag je me gewoon opnieuw — ik genereer een nieuwe `tuin.html`. Dan upload je die opnieuw naar GitHub/Netlify (overschrijft de oude), en je app is bijgewerkt. Vinkjes blijven bewaard.

## Wachtwoord-beveiliging?

De URL is niet indexeerbaar maar ook niet geheim. Als iemand toevallig je URL heeft, kunnen ze het zien. Voor een puur persoonlijke tuin-app is dat geen probleem, maar wil je echt privé: dan wordt het complexer (authenticatie, server-side code). Zeg maar als je dat wilt.
