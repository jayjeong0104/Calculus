# The Calculus Website

Interactive AP Calculus BC practice, graphing tools, and mathematical expression typing in one browser-based learning project.

**[Open the live website](https://jayjeong0104.github.io/Calculus/)**

## What it does

- **Calculus practice:** Choose from ten unit modes covering limits, derivatives, integration, differential equations, parametric and polar functions, and series. Practice includes score, streak, level, and answer feedback.
- **Desmos practice:** Work with an embedded graphing calculator, expression challenges, a keyboard-input tutorial, and configurable timing.
- **Math typing:** Practice mathematical expression input with time- or word-based sessions and speed and accuracy feedback.
- **Study tools:** Browse study videos, AP information links, and a TI-84 calculator interface with button guides.
- **Display options:** Switch between light and dark themes.

This is a student-built practice tool. Its generated exercises and scoring are not an official AP assessment.

## Try it

1. Open the [live website](https://jayjeong0104.github.io/Calculus/).
2. Select **CALCULUS**, choose a unit with the mode-settings control, and select **START**.
3. Use **DESMOS**, **TI84**, **Study**, and **Info** to explore the other tools.

## Run locally

Install Node.js, then run these commands:

```sh
git clone https://github.com/jayjeong0104/Calculus.git
cd Calculus
node local-server.js
```

Open **http://127.0.0.1:8000/**. Run the server from the repository root so it can find the site files.

The local server uses Node.js built-in modules; no package installation or build step is required. Internet access is still needed for external scripts, embedded calculators, and video resources. The server is intended for local development.

## Code guide

| File | Purpose |
| --- | --- |
| [index.html](index.html) | Page structure, navigation, practice controls, and external library loading |
| [game.js](game.js) | Practice modes, answer feedback, typing sessions, graphing integration, and interface state |
| [styles.css](styles.css) | Layout, themes, and visual presentation |
| [ti84calc.html](ti84calc.html) | Embedded TI-84 calculator wrapper |
| [local-server.js](local-server.js) | Local static-file server |
| [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) | Attribution and notices for adapted components |

The application uses JavaScript, HTML, and CSS, with jQuery, MathQuill, and the Desmos API.

## Attribution

The TI-84 wrapper and math-typing interface include adapted third-party work. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for sources and license notices. Calculator services, logos, fonts, and other third-party assets remain subject to their respective terms.
