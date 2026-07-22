# Interval Timer / Abrahangs

A simple interval timer. You can set the work and rest intervals, and the number of rounds using query parameters:

```
?work=30&rest=20&rounds=5
```

The default values match the Abrahangs protocol:

- Work interval: 10 seconds
- Rest interval: 50 seconds
- Rounds: 10

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
