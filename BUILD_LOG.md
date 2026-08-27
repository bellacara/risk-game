# Risk — Build Log

## 2026-08-27 — Initial release

- Created a one-page, dependency-free browser game named **Risk**.
- Added a shuffled standard 52-card deck split evenly between the player and an automated opponent.
- Implemented simultaneous card flips, higher-card round outcomes, ties, card counts, win detection, and replay.
- Applied the requested win condition: a player wins by reaching zero cards. Therefore, the round winner gives both revealed cards to the loser.
- Added responsive visual design and keyboard-accessible game controls.
- Connected the project to `https://github.com/bellacara/risk-game` and pushed the initial release to the `main` branch.
- GitHub Pages has not yet been confirmed as enabled, so the public game URL is pending activation.
- Manually reviewed the standalone HTML, CSS, and game rules. Automated browser testing and JavaScript syntax validation could not run because this session has neither a browser connection nor a JavaScript runtime.

## Publishing checklist

1. Initialize or connect this folder to a GitHub repository.
2. Push `index.html` and this log to the repository's default branch.
3. In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, and select the default branch and `/ (root)`.
4. Record the resulting public URL in this file, then update it after each deployed change.
