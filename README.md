# 🎲 Mad Libs Station

A fun, interactive command-line Mad Libs game written in Python. Choose from three story templates — a hospital visit, a camping trip, or an enchanted castle — and fill in the blanks to generate a hilarious story!

## Features

- **3 story templates** to choose from (or let the game pick one randomly)
- **Input validation** — enforces correct word types (e.g., words ending in `-ing` or `-ly`, numbers, measures of time)
- **Clean error handling** — gracefully exits on `Ctrl+C` or `EOF`

## Requirements

- Python 3.6+
- No external dependencies

## Getting Started

Clone the repository and run the script:

```bash
git clone https://github.com/your-username/mad-libs-station.git
cd mad-libs-station
python mad_libs.py
```

## How to Play

1. Run the script
2. Choose a template (1, 2, or 3) — or enter anything else to get a random one
3. Fill in the prompted words one at a time
4. Read your generated story!

```
___Mad Libs Station___

Pick a template (1, 2, or 3): 2

Template 2 it is! Fill in the blanks:

Person's Name: Jordan
Noun: spatula
...
```

## Templates

| # | Theme |
|---|-------|
| 1 | 🏥 Hospital Stay |
| 2 | 🏕️ Camping Trip |
| 3 | 🏰 Enchanted Castle |

## Input Types

The game prompts for a variety of word types and validates each one:

| Type | Rule |
|------|------|
| Word | Letters only |
| Number | Digits only |
| Verb (ing) | Must end in `-ing`, letters only |
| Adverb (ly) | Must end in `-ly` |
| Measure of time | e.g. `minute`, `days`, `year` |
| Silly Word / Place | Any input accepted |

## Project Structure

```
mad-libs-station/
└── mad_libs.py   # Main game script
```

## License

This project is open source and available under the [MIT License](LICENSE).
