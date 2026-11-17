# ResumeCraft — Frontend Resume Builder

A responsive, frontend-only single-page application with path-based screens:
- `/` — choose one of three templates
- `/create` — fill in resume details
- `/preview/:id` — preview and print/save as PDF
- `/resumes` — view, preview, download, or delete saved resumes

## Run locally
Because the app uses clean paths and root-relative assets, serve this folder with a local static server.

With Python:
```bash
python -m http.server 5500
```
Then open http://localhost:5500

Or use the VS Code Live Server extension. Resume data is stored in browser localStorage.
PDF download uses the browser print dialog: choose **Save as PDF**.
