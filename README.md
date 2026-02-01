# Will You Be My Valentine?

A fun little side project you can customize and share with your loved one. It presents a Valentine's Day question with an interactive twist — the "No" button shrinks, dodges, and eventually disappears.

## Features

- Animated floating hearts background
- Confetti celebration when they say yes
- A "No" button that fights back (shrinks, moves, and vanishes)
- Fully containerized with Docker + nginx

## Quick Start

```bash
docker build -t valentine .
docker run -d -p 80:80 valentine
```

Then open `http://localhost` in your browser.

## Customization

Edit `html/index.html` to change the name, colors, or messages to make it your own.
