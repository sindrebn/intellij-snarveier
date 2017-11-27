# Snarveier i IntelliJ IDEA

Under følger et utvalg tastatursnarveier i IntelliJ IDEA for mac OS.

Snarveioppsettet mitt er basert på «Mac OS X 10.5+», men noen snarveier kan være overstyrt. Disse er forsøkt markert med ⚠️  og navnet på handlingen slik at de er lett å finne hvis man selv ønsker å overstyre tilsvarende.

Snarveier overstyres under «Properties» (`⌘ + ,`) → «Keymap».

### Navigering

- `⌘ + <0-9>` åpne panel X

    - `⌘ + 1` prosjektoversikt
    - `⌘ + 4` «Run»
    - `⌘ + 5` «Debug»
    - `⌘ + 8` terminal ⚠️ _Terminal_
    - `⌘ + 9` versjonskontroll

---

- `⌘ + O` åpne klasse

  - `⌘ + O` igjen for å inkludere klasser utenfor prosjektet (avhengigheter, JDK)

  - `<klassenavn>:X` åpne klasse på linje `X`

  - `<klassenavn>#X` åpne klasse på symbol `X` (metode, konstant, felt)

- `⌘ + ⇧ + O` åpne fil

  - `⌘ + ⇧ + O` igjen for å inkludere filer utenfor prosjektet (avhengigheter)

- `⌘ + ⌥ + O` gå til symbol (metode, konstant, felt)

  - `⌘ + ⌥ + O` igjen for å inkludere symboler utenfor prosjektet (avhengigheter, JDK)

- `⌘ + E` vis nylig åpnede filer

- `⇧ + ⇧` søk over alt (klasser, metoder, konstant, felt, nylig åpnede filer)

---

- `⌘ + F12` vis fil- eller klassestruktur

  - `⌘ + F12` igjen for å vise arvede metoder og klasser

- `⌘ + L` gå til linje

- `⌘ + ⇧ + T` gå til tilhørende testklasse

---

- `⌘ + ⌥ + ←` naviger tilbake

- `⌘ + ⌥ + →` naviger fremover

- `⌃ + ↓` gå til neste metode

- `⌃ + ↑` gå til forrige metode

### Kjøring og debugging

- `⌃ + ⇧ + R` kjør program eller test

- `⌃ + ⇧ + D` start debugging av program eller test

- `⌘ + F8` sett eller fjern breakpoint

- `⌘ + ⇧ + F8` se alle breakpoints

- `⌥ + O` debug `Stream`-kjede

- `⌥ + F8` evalurer uttrykk

### Refaktorering

- `⌘ + ⌥ + V` dra ut variabel

- `⌘ + ⌥ + F` dra ut felt

- `⌘ + ⌥ + C` dra ut konstant

- `⌘ + ⌥ + M` dra ut metode

- `⌘ + ⌥ + N` inline variabel/felt/konstant/metode

- `⇧ + F6` endre navn

### Koderedigering

- `⌥ + ↑` øk omfang av markert tekst

- `⌥ + ↓` mink omfang av markert tekst

- `⌃ + G` marker neste forekomst

- `⌃ + ⌘ + G` marker alle forekomster i fil

- `⌃ + ⇧ + G` fjern markering av forekomst

- `⌃ + ⇧ + J` slå sammen linjer

---

- `⌥ + ⇧ + ↑` flytt linje opp

- `⌥ + ⇧ + ↓` flytt linje ned

- `⌘ + ⇧ + ↑` flytt statement opp

- `⌘ + ⇧ + ↓` flytt statement ned

---

- `⌘ + D` dupliser linje eller markert tekst

- `⌘ + back space` slett hele linje

- `⌘ + ⇧ + U` bytt mellom store og små bokstaver

- `⌘ + ⌥ + L` reformatter kode

- `⌃ + ⌥ + O` «fikse» imports (fjerner unødvendige, omorganiserer rekkefølgen)

---

- `⌘ + ⌥ + U` vis arvehierarki (UML-diagram)

- `⌘ + Y` vis implementasjon av metode ⚠️ _Quick Definition_

- `⌘ + B` gå til implementasjon av metode

- `⌘ + P` vis informasjon om metodeparametere

- `⌃ + ⇧ + P` uttrykkets type


---

- `⌥ + ↩` foreslå løsning på problemer (kompileringsfeil, IDE-warnings, …)

- `⌘ + 7` kommenter inn/ut linje ⚠️ _Comment with Line Comment_

### Søk og erstatt

- `⌘ + F` søk i fil

- `⌘ + ⇧ + F` søk i prosjekt

- `⌘ + R` erstatt i fil

- `⌘ + ⇧ + R` erstatt i prosjekt


### Plugins

- `⌃ + ⇧ + m` manipuler tekst ([String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)) ⚠️ _Popup String Manipulation_

- `⌥ + F2` bytt prosjekt ([Frame Switcher](https://plugins.jetbrains.com/plugin/7138-frame-switcher))

- `⌥ + ⇧ + D` skru av og på visning av snarveier ([Presentation Assistant](https://plugins.jetbrains.com/plugin/7345-presentation-assistant))
