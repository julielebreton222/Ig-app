# Pixel Español

An 8-bit app for learning Spanish a few minutes a day, set in a deadpan small-town world: a farm, a high school, a school dance. Works offline, installs to the home screen.

- **Title screen**: at the school dance, under a disco ball and a spotlight, Beto does his dance and says "¡Bienvenido!" when you press start.
- **The cast**: Beto, Abuela Chela (runs the farm), Lalo (the new kid) and Marisol (Radio Papa, the school radio). Each speaker gets a pixel face.
- **Potatoes**: every day you practice earns a potato; the streak (racha) counts them.

## How the lessons work

Eight lessons, one a day. Half are friendly conversations (*charla*); half are arguments (*pleito*) where Beto is deadpan and absolutely wrong, and you push back. Each lesson follows principles that are known to work:

1. **Frases**: 6–7 whole phrases you'll actually use (chunks, not single words). Hear them, then say them; the microphone checks your pronunciation.
2. **Escena**: a short scene that uses them, so you understand them in context (comprehensible input).
3. **¡En vivo!**: a real-time conversation. You play a role, the other character speaks, and a clock runs while you answer out loud or tap the reply (active recall under real-conversation pressure). You always hear the right answer afterwards. *Solo audio* hides the text for pure listening.
4. **Repaso**: spaced repetition. The lesson's phrases come back tomorrow, and missed answers come back today. Each time you know one, it waits longer (1, 3, 7, 14, 30, 60 days).

## Mis lecciones: make your own

On the Hoy tab, **+ Nueva lección**: type phrases he heard or wants to learn, one per line as `Spanish = English` (English optional), and pick a style (friendly or argument). The app turns them into a lesson with the same four steps: Beto reacts to each phrase in a scene, then quizzes you live.

## Guion: your movie script

The Guion tab reads a script a few minutes a day, Spanish and English side by side. It ships with original demo scenes. To use your own, save a spreadsheet as CSV with one line of dialogue per row and import it in Ajustes:

```
Speaker,English,Spanish
BETO,Good morning.,Buenos días.
# The bus stop
LALO,Hi.,Hola.
```

- A row starting with `#` is a scene title (days break at scene titles when they can).
- Speaker is optional: `English,Spanish` works too. Tabs or semicolons also work.
- The imported script is saved **only in that phone's browser**. It is never uploaded or stored in this repository.
- Star (★) a line to add it to Repaso.

## Putting it on a phone

Host it once (repo Settings → Pages → deploy from this branch), open the link on the phone, then "Add to Home Screen". After the first visit it works without internet (speech recognition may need a connection, depending on the phone).

- Spanish voice on iPhone: Settings → Accessibility → Spoken Content → Voices → Spanish.
- The microphone works in Chrome and Safari; allow access the first time. Without it, tap the answers instead.

Data stays on the device (browser storage). Use *Exportar* in Ajustes to keep a backup.
