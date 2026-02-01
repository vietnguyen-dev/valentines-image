# Will You Be My Valentine?

A fun little side project you can customize and share with your loved one. It presents a Valentine's Day question with an interactive twist — the "No" button shrinks, dodges, and eventually disappears.

## Features

- Animated floating hearts background
- Confetti celebration when they say yes
- A "No" button that fights back (shrinks, moves, and vanishes)
- Fully containerized with Docker + nginx

## Quick Start

### From Docker Hub

```bash
docker run -d --name container-name -p 80:80 -e NAME=your-spouse-name vietnguyen-dev/valentines-image
```

### Build Locally

```bash
git clone https://github.com/vietnguyen-dev/valentines-image.git
cd valentines-image
docker build -t valentine .
docker run -d --name container-name -p 80:80 -e NAME=your-spouse-name valentine
```

Then open `http://localhost` in your browser.

The `NAME` environment variable sets the name displayed on the page. It defaults to `Vera` if not provided.

## Customization

Edit `html/index.html` to change colors or messages to make it your own.
