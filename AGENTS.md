## Cursor Cloud specific instructions

### Project overview
BrainCube is a self-contained, single-file IQ test / cognitive assessment game (`iq-test-game.html`). Everything — HTML, CSS, and JavaScript — lives in one file with zero build steps and zero external dependencies.

### Running the app
Serve the file with any static HTTP server:
```
python3 -m http.server 8080 --directory /workspace
```
Then open `http://localhost:8080/iq-test-game.html` in Chrome.

### Lint / test / build
There are no linters, test frameworks, or build steps configured for this project. Validation is done by opening the HTML file in a browser and manually interacting with the game.

### Notes
- The only external resource is Google Fonts (Inter, Space Grotesk), which is decorative — the page works fine without it using system fallback fonts.
- The file can also be opened directly via `file://` protocol, but using an HTTP server is recommended for a more realistic development experience.
