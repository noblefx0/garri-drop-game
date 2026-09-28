# GARRI DROP

A simple browser game where you tap falling GARRI and avoid bombs.

## Run locally

Open `index.html` in your browser.

Or use VS Code with the Live Server extension.

## Add your real GARRI image

Put your image here:

`assets/garri.png`

The game is already configured to use it.

If your image has a different filename, open `index.html` and change:

```js
GARRI_IMAGE: "assets/garri.png"
```

For example:

```js
GARRI_IMAGE: "assets/my-garri-meme.jpg"
```

## Easy settings

Near the top of the JavaScript you can change:

```js
GAME_TIME: 30,
STARTING_LIVES: 3,
GAME_BACKGROUND: "#0b7a3b"
```

## Put it on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and the `assets` folder.
3. Go to the repository's Settings.
4. Open Pages.
5. Under the deployment/source option, choose the branch containing `index.html` (usually `main`) and the root folder `/`.
6. Save.
7. GitHub will give you a public Pages URL.

Your game will then be playable from that link on phones and computers.
