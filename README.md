# Prompter

Web-based teleprompter for video script delivery. Auto-scroll, adjustable speed, keyboard shortcuts, line highlighting, built-in script editor.

Open `index.html` in any browser.

## Editing the script
Click **✎ Script** (or press `E`) to open the editor.

- One line of text = one prompter line
- Blank line = section break
- Start a line with `[` or `//` for a stage note, e.g. `[pause 2s]`
- **Save & Use** applies the script and remembers it in the browser (survives reloads)
- **Restore Default** loads the built-in gearbox script back into the editor
- **Delete Script** clears everything; the prompter shows an "Add Script" prompt until you add a new one
- `Ctrl`/`Cmd` + `Enter` saves, `Esc` closes

## Controls
- `Space` — play / pause
- `↑` / `↓` — previous / next line
- `R` — reset to top
- `+` / `-` — adjust scroll speed
- `E` — edit script
- Click any line to jump
