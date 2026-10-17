# IQ Quiz Quest

A single-file, no-backend multiple-choice quiz built from *The Ultimate IQ Test Book*.
Open `index.html` in a browser and play.

- 25 chapters (Test One to Twenty-Five), 392 questions with the book's answers verbatim
- Colorful game-style feedback, jokes, Web Audio sound effects, mute toggle
- Progress, scores and a missed-questions list saved in `localStorage`
- Clickable question numbers, chapter menu, Review-missed mode

## Adding questions
Edit the `ITEMS` array at the top of the `<script>` in `index.html`:

```js
{ chapter: "Test One", question: "…", answer: "…", options: ["…","…","…"], explanation: "…", id: "T1-3" }
```
Only `chapter`, `question` and `answer` are required. Keep `id`s stable so saved progress still matches.

## ⚠️ Copyright
`index.html` contains question and answer text from a copyrighted book. Keep this repository
**private** (or remove the data from `ITEMS` before making it public).
"# IQ_test_ultimate" 
