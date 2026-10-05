# Pixel Español

An 8-bit app for learning Spanish a few minutes a day from movie dialogue: Spanish and English side by side, read aloud. Works offline.

- **Title screen**: Beto, the pixel kid, does his dance and says "¡Bienvenido!" when you press start.
- **Hoy (today)**: about 2–3 minutes of dialogue per day. Tap ♪ to hear a line in Spanish, ▶ Todo to hear the whole scene, hide the English to quiz yourself, ★ to save a line. Tap **¡Hecho!** when done to keep the streak (racha) going.
- **Guardado (saved)**: the lines you starred.
- **Ajustes (settings)**: import a script, lines per day, slow voice, music, backup and restore.

## Importing a script

The app ships with a few original demo scenes. To use your own script, save a spreadsheet as CSV with one line of dialogue per row:

```
Speaker,English,Spanish
BETO,Good morning.,Buenos días.
# The bus stop
LALO,Hi.,Hola.
```

- A row starting with `#` is a scene title (days break at scene titles when they can).
- Speaker is optional: `English,Spanish` works too. Tabs or semicolons also work.
- The imported script is saved **only in that phone's browser**. It is never uploaded or stored in this repository.

## Putting it on a phone

Host it once (repo Settings → Pages → deploy from this branch), open the link on the phone, then "Add to Home Screen". After the first visit it works without internet.

For the Spanish voice on iPhone, a Spanish voice must be installed: Settings → Accessibility → Spoken Content → Voices → Spanish.

Data stays on the device (browser storage). Use *Exportar* in Ajustes to keep a backup.
