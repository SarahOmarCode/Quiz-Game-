# Front-End Quiz Game

A multiple-choice quiz that tests HTML, CSS and JavaScript fundamentals. Built with vanilla JavaScript and no frameworks.

**▶ [Play the live demo](https://sarahomarcode.github.io/Quiz-Game-/)**

![Quiz in progress](./frontendquizphoto.png)

## Features

- 13 questions covering HTML structure, CSS properties and core JavaScript DOM APIs
- Instant feedback after each answer; the options lock until you move on
- Tracks your score and shows it at the end
- Restart button to play again

## How it works

The questions live in a single array of `{ question, options, correctAnswer }` objects in `saraDemo.js`. To add or change questions, you only edit that array. The UI is updated through DOM manipulation (`textContent`, toggling `display`, enabling and disabling buttons).

![Quiz results screen](./frontendquizendphoto.png)

## Run locally

No build step. Clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/SarahOmarCode/Quiz-Game-.git
cd Quiz-Game-
open index.html   # or double-click it
```

## Tech

HTML · CSS · JavaScript

---

*An early project from 2023, built while learning front-end development.*
