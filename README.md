# Fraction Conquest

**[▶ Play in the browser](https://gluonmaster.github.io/fraction-conquest/)** · [Deutsch](README.de.md) · [Русский](README.ru.md)

A fractions game for grades 5 to 7 (ages 11 to 13). Each correct answer conquers a territory on the map, each wrong one gives ground back, so a practice session turns into a small strategy match. Teachers and parents can choose the topics and the difficulty. The game runs in the browser, in German or Russian, with no installation and no account.

![Fraction task next to the territory map](docs/screenshots/game.png)

## Features

- 11 topics: simplifying, mixed numbers, common denominators, the four operations, conversions between fractions and decimals, and combined expressions.
- 4 difficulty levels.
- Instant feedback, with an explanation after every wrong answer.
- A settings page ([admin.html](admin.html)) for topics, difficulty and timer.
- A test page ([test.html](test.html)) that checks the maths engine in the browser.
- Plain HTML, CSS and JavaScript, without frameworks or a build step.

## Controls

- Click one of the six answers, or press `1` to `6`.
- After a wrong answer, read the explanation and continue to the next task.

## Running it locally

Download or clone the repository and open `index.html` in a browser. Opening the files through a local server is closer to the online version:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/index.html` (or `admin.html`, `test.html`). The game is made for screens of 1024×768 and larger in current Chrome, Firefox and Edge. Settings and progress are stored in the browser's `localStorage`.

## Credits and license

Made by Dr. Konstantin S. Shakun with the help of AI coding agents. The code is available under the [MIT License](LICENSE).
