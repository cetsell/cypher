# Cypher

A daily quote cipher. Each local calendar day hides one famous quote and its author with the same substitution cipher. Select a ciphertext letter, then type the letter you think it stands for. Every copy of that letter changes, in the quote and in the source line under it. If the letter you type is already in the puzzle, the two letters exchange. The puzzle stays the same until local midnight, then a new one begins.

## Play

Open `index.html` in a browser. It works from `file://`. Or serve the folder with any static server:

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8765/

The daily puzzle is seeded from your local date, chosen from the quotes embedded in the page. There is no account, no network request, and no build step.
