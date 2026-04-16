# calvin.no

Personlig nettside bygget med ren HTML og CSS. Hostet på GitHub Pages.

## Filstruktur

```
index.html                      – Forsiden med artikkel
kontakt.html                    – Kontaktside med kryptert skjema
jimmy-carl-black-interviews.html – Artikkel om JCB-intervjuene
style.css                       – Felles stilark for alle sider
CNAME                           – Domenekobling til calvin.no
fonts/                          – Crimson Text (last ned og legg her)
```

## Sette opp fonter

Last ned Crimson Text fra Google Fonts og legg disse filene i /fonts/-mappen:

- CrimsonText-Regular.woff2
- CrimsonText-Italic.woff2
- CrimsonText-SemiBold.woff2

## Sette opp kontaktskjemaet

1. Logg inn på proton.me
2. Gå til Innstillinger → Kryptering og nøkler
3. Eksporter din offentlige nøkkel
4. Åpne kontakt.html i nettleseren og lim inn nøkkelen

## Bytte artikkel

Åpne index.html i en teksteditor, finn innholdet mellom <article>-taggene,
og erstatt teksten. Be Claude konvertere artikkelen din til HTML-snutter
ved behov.

## Publisere til GitHub Pages

1. Opprett et repo på github.com
2. Last opp alle filene
3. Gå til Settings → Pages → Source: main branch
4. Pek calvin.no mot GitHub Pages via DNS hos domeneregistraren din:
   - Type: CNAME
   - Navn: www
   - Verdi: dittbrukernavn.github.io

## Dropcap

Legg til class="dropcap" på det første avsnittet i en artikkel:
<p class="dropcap">Teksten din...</p>
