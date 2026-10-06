# KoloFlow

A personal money operating system portfolio prototype featuring safe-to-spend, future balance, money pots, Ajo circles, Kolo AI, and payment confirmations and receipts.

## Run locally

The complete app lives in `dist/`, including the welcome video, glass K artwork and fonts. No build step or package installation is required.

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. Serve over HTTP because the app uses a JavaScript module.

## Edit

- `dist/app.js`: screens, demo data and interactions
- `dist/style.css`: layout, glass surfaces and motion
- `dist/index.html`: application entry point
- `dist/assets/`: artwork, welcome video and bundled fonts

Deploy the `dist/` directory with a static web host.

Live prototype: https://koloflow-money.sylviemailletb107185.chatgpt.site/

This is a portfolio prototype. Payments are simulated, Kolo AI uses scripted sample responses, and demo state is held in sessionStorage. Font licensing is included in `dist/assets/fonts/LICENSE.txt`.
