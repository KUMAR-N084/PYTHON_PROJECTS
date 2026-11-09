# Python Mini Projects

A collection of beginner-friendly Python projects built to practise programming fundamentals and GUI development.

## Projects

| File | Description | Main concepts |
|---|---|---|
| `CALCULATOR.py` | Desktop calculator with basic arithmetic operations | Tkinter, event handling, conditionals |
| `PWD_GENERATE.py` | Random password generator with selectable character sets and clipboard support | `secrets`, strings, Tkinter |
| `ROCK_PAPER_SCISSORS.py` | Command-line Rock Paper Scissors game with score tracking | Loops, conditionals, random selection |
| `TO-DO_LIST.py` | Desktop task manager with due dates, editing, completion, and JSON persistence | Tkinter, JSON, file handling |

## Requirements

- Python 3.9 or later
- Tkinter (usually included with standard Windows Python installations)
- Optional: `pyperclip` for clipboard integration in the password generator; the app has a Tkinter clipboard fallback

Install the optional clipboard package:

```bash
python -m pip install pyperclip
```

## Run a project

Open a terminal in this folder and run the selected script:

```bash
python CALCULATOR.py
python PWD_GENERATE.py
python ROCK_PAPER_SCISSORS.py
python TO-DO_LIST.py
```

Each script runs independently. The calculator and password generator open desktop windows; Rock Paper Scissors runs in the terminal; the to-do app stores tasks in a local `tasks.json` file.

## Notes

- Do not use generated passwords as a replacement for a dedicated password manager's secure generation and storage workflow without reviewing the generated settings.
- The to-do app's `tasks.json` file is local application data and should not be committed if it contains personal tasks.
- These are learning projects intended to demonstrate Python basics and simple GUI workflows.
