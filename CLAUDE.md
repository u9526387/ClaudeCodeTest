# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A collection of standalone browser games, each implemented as a single self-contained HTML file with no external dependencies. All game logic, styling, and rendering are inline.

## Architecture

- **One file per game** — each `.html` file contains everything (HTML, CSS, JavaScript) needed to run
- **No build step, no dependencies** — open any `.html` file directly in a browser to play
- **Canvas-based rendering** — games use `<canvas>` with `requestAnimationFrame` loops and procedural pixel-art via `fillRect()` (no external images)
- **Retro aesthetic** — pixel-scale factor (`PX = 3`), CRT scanline/vignette overlays, monospace fonts, dark color palettes

## Games

- `shooter.html` — Top-down shooter with player movement (WASD/arrows), mouse aiming/shooting, 5 enemy types, 10+ levels with procedural difficulty scaling, minimax AI for enemy shooters
- `tictactoe.html` — Tic Tac Toe with 2-player and vs AI (minimax) modes, score tracking

## Running

Open any `.html` file in a browser. No server required.

## Git & GitHub

- Remote: `origin` → `https://github.com/u9526387/ClaudeCodeTest.git`
- **Commit and push regularly** — as you work, commit progress frequently with clean commit messages and push to GitHub so that no work is ever lost. Do not wait until a task is fully complete to commit; commit at meaningful checkpoints along the way.
