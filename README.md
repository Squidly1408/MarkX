# markx

A small grade planner for university units. Enter your assessments, their weights and the marks you've got back so far, and markx works out where you stand and what you still need on the remaining pieces to hit your target grade (Pass, Credit, Distinction, High Distinction).

- Marks are entered as a score and what it's out of (e.g. `17 / 20`). Leave the score blank for anything not marked yet.
- Hurdles are supported: the minimum mark needed on a single piece to pass the unit, whatever your total.
- Track several units at once with tabs.
- Weights that don't add up to 100 are scaled to a 100-point course.

## Running it

It's a single static page with no build step or dependencies. Open `index.html` in a browser, or serve the folder with anything, for example:

```sh
npx serve .
# or
python -m http.server
```

## Your data

Everything is stored in your browser's `localStorage`; nothing is sent anywhere. Use **Back up or move your data** at the bottom of the page to copy a backup and paste it into another browser or device.

## Project layout

```
index.html       the whole app: markup, styles and script
images/logo.svg  favicon
```

## License

[MIT](LICENSE)
