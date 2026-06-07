# My-Projects

Collection of small static web demos. Each demo is self-contained under the `PROJECTS/` folder and typically consists of an `index.html` entry point, optional `style.css`, and optional `script.js`.

Repository structure

- `PROJECTS/` — individual demo project folders (e.g., `PROJECT-2`, `PROJECT-3`, …)

Usage

- Open a project's `index.html` file directly in a browser.
- To serve the repository locally, run:

```bash
cd /workspaces/My-Projects
python3 -m http.server 8000
# then open http://localhost:8000/PROJECTS/PROJECT-2/ in a browser
```

Contributing guidelines

- Add a new folder under `PROJECTS/` with a clear, descriptive name.
- Include an `index.html` file as the entry point and keep related assets inside the same folder.
- Prefer lowercase filenames for cross-platform consistency.

Notes

- File name casing varies across projects (for example `Index.html` vs `index.html`). Use the exact filename when opening files on case-sensitive systems.

License

No license is included. Add a `LICENSE` file to specify reuse and distribution terms.

Repository maintenance

- The repository is intended as a set of static examples and demos. Keep each project self-contained to simplify previewing and sharing.