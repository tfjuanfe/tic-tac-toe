# Tic Tac Toe

A single-file browser tic-tac-toe game — no installs, no build step. Just open `tic-tac-toe.html`.

## Features

- **Three modes:** 2 players (same screen), vs Easy (random AI), and vs Unbeatable (minimax AI).
- **Login system:** create an account and your win/draw/loss scores are saved per user.
- **Persistent scores** and auto-resumed sessions, stored in the browser.
- **Responsive layout** that scales to your screen.

## How to play

Open `tic-tac-toe.html` in any modern browser, create an account, and play.

## Note on the login system

Accounts are stored client-side in the browser's `localStorage` — this is for
convenience and per-player score tracking, **not real security**. Don't reuse a
real password. Proper accounts would require a backend server.
