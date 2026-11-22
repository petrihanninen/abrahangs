# Interval Timer / Abrahangs

A simple interval timer. You can set the work and rest intervals, and the number of rounds using query parameters:

```
?work=30&rest=20&rounds=5
```

The default values match the Abrahangs protocol:

- Work interval: 10 seconds
- Rest interval: 50 seconds
- Rounds: 10

The timer defaults to one-handed mode, alternating hands every work set. Toggle to two-handed mode with the button in the corner (or `?hands=2`), which skips every other work set so each set uses both hands.

## Site

Hosted on GitHub Pages:

https://abrahangs.petrihanninen.com

## Local development

There is no build step. Open `index.html` directly in a browser, or serve it locally:

```
python3 -m http.server
```

## License

MIT
