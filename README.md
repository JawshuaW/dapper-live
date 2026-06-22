# Dapper Scripts Live Demos

Public-safe static showroom for the existing `dapper-live` GitHub Pages repository.

## Included demos

- `dapper_books_demo.html` — Dapper Books writer and reader demonstration.
- `dapper_medical_demo.html` — Dapper Medical examination, injury map, simulated procedures, dispatch, illness, ledger, practice, dossiers, and role-gated civilian preview.
- `index.html` — unified showroom that launches both demonstrations inside a full-screen modal.
- `assets/medical-plate-demo.webp` — reduced-resolution, watermarked public preview asset. The original medical image is not included.

## Update the existing GitHub repository

1. Extract the ZIP on your computer.
2. Open the extracted `dapper-live` folder.
3. In `https://github.com/JawshuaW/dapper-live`, upload everything inside that folder to the repository root.
4. Allow GitHub to replace the existing `index.html`, `README.md`, `SECURITY.md`, `AUDIT.json`, and `dapper_books_demo.html` files.
5. Add the new `dapper_medical_demo.html`, `.nojekyll`, and `assets` folder.
6. Commit the changes to `main`.
7. Keep GitHub Pages configured for `main` and `/(root)` under **Settings → Pages**.

The existing public URL should update automatically after GitHub Pages redeploys.

## Important security rule

This repository must remain a clean-room browser simulation. Never add the real RedM resource, Lua files, SQL, configuration containing private values, framework integration, internal event names, licensing code, webhooks, credentials, or paid source files.
