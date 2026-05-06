# Nuclear Option — Patch in Italiano (Localization Patch)

Mod di traduzione in italiano per Nuclear Option. Funziona come plugin di BepInEx e traduce l'interfaccia, l'enciclopedia, i suggerimenti e le descrizioni — in totale **2.841 voci**.

- Traduzione contribuita da **Doktor [MUSH]** (community contributor).

## Requisiti

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Accesso Anticipato 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Installazione

1. Installa **BepInEx 5.x** nella cartella del gioco.
   ```
   Esempio: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Avvia il gioco **una volta** e poi chiudilo. (Questo crea la struttura delle cartelle BepInEx.)

3. Copia tutti i file di questa repository in:
   ```
   [Cartella del gioco]\BepInEx\plugins\LocalizationPatch\
   ```
   > Se la cartella `LocalizationPatch` non esiste, creala manualmente.

4. Modifica `BepInEx\config\com.noms.localizationpatch.cfg`:
   ```
   [General]
   Language = it
   ```

5. Avvia il gioco — la traduzione italiana verrà applicata automaticamente.

### Installer automatico (alternativa)

https://github.com/9138noms/NuclearOption-LocalizationInstaller/releases/latest

## File inclusi

| File | Scopo |
|------|-------|
| `LocalizationPatch.dll` | Plugin di traduzione |
| `LocalizationPatchDropdown.dll` | Addon per i menu a tendina |
| `it.json` | Dati di traduzione italiana (2.841 voci) |
| `Exo2-Regular.ttf` | Font con supporto Latin Extended (à, è, ì, ò, ù, ecc.) |

## Tasti di scelta rapida nel gioco

| Tasto | Funzione |
|-------|----------|
| `F10` | Mostra/nascondi overlay di debug |
| `Ctrl+F10` | Ricarica i dati di traduzione (hot reload) |

## Note

- Nomi delle fazioni (PALA, BDF, BOSCALI, PRIMEVA, FFL, LMA) e codenames di velivoli / armamenti (Compass, Alkyon AB-4, FGA-57 Anvil, IRM-S2, ecc.) rimangono in inglese.
- Acronimi NATO standard (AAM, AGM, ARH, APFSDS, IRM, SAM, ecc.) rimangono in inglese, come da prassi nelle comunità aeronautiche italiane.
- In caso di problemi puoi specificare manualmente la lingua nel file `BepInEx\config\com.noms.localizationpatch.cfg`, impostando `Language = it`.

## Crediti

- Traduzione: **Doktor [MUSH]** (community contributor)
- Plugin / framework: https://github.com/9138noms/NuclearOption-TranslationToolkit

## Licenza font

Exo 2 — [SIL Open Font License 1.1](https://fonts.google.com/specimen/Exo+2)

## Progetti correlati

🇰🇷 [Korean](https://github.com/9138noms/NuclearOption-KoreanPatch) ·
🇷🇺 [Russian](https://github.com/9138noms/NuclearOption-RussianPatch) ·
🇺🇦 [Ukrainian](https://github.com/9138noms/NuclearOption-UkrainianPatch) ·
🇧🇾 [Belarusian](https://github.com/9138noms/NuclearOption-BelarusianPatch) ·
🇩🇪 [German](https://github.com/9138noms/NuclearOption-GermanPatch) ·
🇪🇸 [Spanish](https://github.com/9138noms/NuclearOption-SpanishPatch) ·
🇫🇷 [French](https://github.com/9138noms/NuclearOption-FrenchPatch) ·
🇧🇷 [Portuguese](https://github.com/9138noms/NuclearOption-PortuguesePatch) ·
🇳🇴 [Norwegian](https://github.com/9138noms/NuclearOption-NorwegianPatch) ·
🇹🇼 [Traditional Chinese](https://github.com/9138noms/NuclearOption-TraditionalChinesePatch)

Toolkit di traduzione (per creare la tua patch linguistica):
https://github.com/9138noms/NuclearOption-TranslationToolkit
