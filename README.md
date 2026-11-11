# QR Code Generator

A lightweight web app that turns any text or URL into a QR code instantly. It's built with plain HTML, CSS and JavaScript and needs no installation.

**Live demo:** https://kushsharawat.github.io/QR-Generator/

## Features

- Generates a QR code for any text or link
- Input validation: a shake animation warns when the box is empty
- Special characters (`&`, `?`, `#`, spaces) are URL-encoded, so links with query strings encode correctly

## How it works

The text is URL-encoded with `encodeURIComponent` and sent to the free [goQR.me API](https://goqr.me/api/), which returns a QR image that the page displays.

## Tech stack

HTML5 · CSS3 · JavaScript (ES6) · goQR.me REST API

## Run locally

Clone the repo and open `index.html` in any browser:

```bash
git clone https://github.com/KushSharawat/QR-Generator.git
cd QR-Generator
start index.html      # Windows (use "open" on macOS)
```
