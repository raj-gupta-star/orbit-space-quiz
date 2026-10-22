# Project instructions

## Project overview

Orbit is a self-contained space exploration quiz for the browser. Its complete runtime is `index.html`: markup, styles, quiz data, and JavaScript all live in that file.

## Keep the project lightweight

- Keep the quiz usable by opening `index.html` directly from disk. Do not add a server, package manager, build step, or runtime dependency.
- Keep changes focused on the quiz and preserve its responsive, narrow-column layout and sans-serif typography.
- Respect `prefers-color-scheme` and `prefers-reduced-motion`; make interactive controls keyboard-accessible and provide clear focus and live feedback.
- Keep the quiz at ten questions unless the requested change explicitly changes that requirement. Keep the displayed question count, progress, scoring, and results consistent with the quiz data.
- Use semantic HTML and avoid inserting question or answer text as HTML; treat quiz content as text.

## Validation

- For behavior changes, open `index.html` directly in a browser and verify the affected quiz flow, including scoring, feedback, progress, and results where relevant.
- Check both light and dark themes, and ensure reduced-motion preferences are respected when changing presentation or animation.
- There is no test runner or dependency installation step. Do not add tooling unless the project requirements change.

## Documentation

- Keep `README.md` accurate about direct browser use and the project’s dependency-free setup.
- Update these instructions when the project’s architecture or development workflow changes.
