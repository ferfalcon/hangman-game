# Hangman game

This is a solution to the [Hangman game challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/hangman-game-rsQiSVLGWn).

![Design preview for the Hangman game coding challenge](./preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- Learn how to play Hangman from the main menu.
- Start a game and choose a category.
- Play Hangman with a random word selected from that category.
- See their current health decrease based on incorrect letter guesses.
- Win the game if they complete the whole word.
- Lose the game if they make eight wrong guesses.
- Pause the game and choose to continue, pick a new category, or quit.
- View the optimal layout for the interface depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.
- Navigate the entire game only using their keyboard.

### Expected behaviour

- You can make the default screen the main menu or the in-game board. Note that we're using the in-game design for the design screenshot, so if you choose the main menu, it won't match up in the design comparison slider. This isn't a big deal, but it is something worth considering. We recommend using the in-game page as the default for solution submission so that the screenshot matches and then switching your code to make the main menu the default screen for new players.
- Pick a random word from the chosen category to start a game. You'll need to work out the spacing for words and when to break to a new line, as some names/titles are (intentionally) long.
- If the player guesses a letter correctly, fill in all relevant spaces and disable the letter on the keyboard.
- If the player guesses incorrectly, disable the letter on the keyboard and reduce the health meter. The health meter should empty after eight wrong guesses. The player loses at this point, and the menu appears.
- Selecting "play again" on the menu starts a new game with the same category. Selecting "new category" navigates to the "pick a category" screen. Quitting navigates back to the main menu.
- Players should never be shown the same name/title multiple times if they play more than one game in a visit. The JSON data has a "selected" boolean to help you filter already played options.
- Clicking the hamburger menu during a game should show the "paused" menu.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

### Links

- Solution URL: [Add solution URL here](https://github.com/ferfalcon/hangman-game)
- Live Site URL: [Add live site URL here](https://ferfalcon.github.io/hangman-game/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

## Author

- LinkedIn - [Fernando Falcon](https://www.linkedin.com/in/fernandofalcon/)
- Website - [ferfalcon.com](http://ferfalcon.com/)
- Frontend Mentor - [@ferfalcon](https://www.frontendmentor.io/profile/ferfalcon/)