# MIS312 Assignment 10 — Making Some Games (Loops + Logic)

**Book Alignment:** Chapter 10  
**Primary Goal:** Practice loops/conditionals/input in a small game  
**Environment:** JupyterLab + VS Code (`.ipynb`)  
**Submission:** OneNote Artifact (PDF)

---

## Learning Objectives
- Use loops to control flow
- Use conditions to guide feedback
- Track simple state (attempts)

---

## Student Tasks
Build a number guessing game (1–20) with “too high/low” messages.

Add ONE feature:
- limit attempts OR
- show attempt count OR
- play again

### AI review (required)
Ask how to make the game more user-friendly; implement one change.

---

## VS Code Exercise — Run the Game as a `.py` File (Interactive)

### Task 4 — Move your game into a script
1. In VS Code, create: `C:\Users\<StarID>\MIS312\assignment10\guess_game.py`
2. Copy your working game code into the script.
3. Make sure your script runs only when executed (use `if __name__ == "__main__":`).

Example ending:
```python
def main():
    # your game loop here
    pass

if __name__ == "__main__":
    main()
```

### Task 5 — Run it interactively
Run:
```powershell
python guess_game.py
```
Play one full game session and capture a screenshot of the terminal showing:
- user inputs
- game messages
- end result

### Task 6 — Troubleshooting (required)
Deliberately break one line (example: remove a colon after `if`) and run to trigger a `SyntaxError`.
Then fix it and re-run successfully.

### Add to OneNote Artifact
- Screenshot: full game run in VS Code terminal
- Screenshot: your SyntaxError + the fix
- Code snippet: your `main()` and your loop


## OneNote Artifact Requirements
- Code snippet(s)
- Screenshot of a full game run
- AI prompt + summary
- Reflection: what still confuses you about loops?
