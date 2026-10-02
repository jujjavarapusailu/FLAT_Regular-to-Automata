# Regular Grammar ↔ Finite Automata Converter

## Run
1. Extract the ZIP file.
2. Open `index.html` in a modern browser (Chrome, Edge, or Firefox).
3. Choose a conversion tab, edit the input, and click the relevant Convert button.

## Grammar syntax
Use right-linear productions, one per line. Example:
```
S -> aA | b
A -> aA | b
```
Supported RHS forms are a single lowercase terminal optionally followed by one uppercase nonterminal (`aA`), a terminal-only rule (`b`), and epsilon (`ε`). Each terminal is a single character.

## Automaton syntax
Provide comma-separated states/alphabet/final states and transitions in `from,symbol,to` format, one transition per line. This reverse conversion creates a right-linear grammar.

The app is a standalone HTML/CSS/JavaScript application and does not require a server or dependencies.
