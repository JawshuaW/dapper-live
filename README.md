# Dapper Scripts Live Showroom

Public-safe static showroom for the `dapper-live` GitHub Pages repository.

## Included demonstrations

- `dapper_books_demo.html` — interactive Dapper Books writer and reader preview.
- `dapper_medical_demo.html` — examination, injuries, procedures, dispatch, records, practice management, and doctor/civilian access preview.
- `dapper_banking_demo.html` — accounts, transfers, safebox storage, loan requests, and banker console preview.
- `dapper_planting_demo.html` — plant care, supply purchasing, wagon rental, processing stages, and harvest market preview.
- `dapper_printingpress_demo.html` — published titles, multi-page authoring, proof reader, author wallet, and publisher office preview.
- `index.html` — unified five-script showroom with full-screen demo launcher.
- `assets/` — reduced, compressed, and public-demo presentation assets only.

All balances, patients, plants, publications, customers, inventory, transactions, and staff records are fabricated. Demo state exists only in the visitor's browser and resets without touching a RedM server.

## Upload to the existing GitHub repository

1. Extract the ZIP on your computer.
2. Open the extracted `dapper-live` folder.
3. Open the existing `JawshuaW/dapper-live` repository on GitHub.
4. Upload **everything inside** the extracted folder to the repository root.
5. Allow GitHub to replace the existing files when prompted.
6. Commit the upload to `main`.
7. Keep GitHub Pages configured to deploy from `main` and `/(root)` under **Settings → Pages**.

Do not upload the outer folder as another nested `dapper-live/dapper-live` directory. GitHub Pages should see `index.html` directly at the repository root.

## Repository safety rule

This repository must remain a clean-room browser simulation. Never add the real RedM resources, Lua files, SQL, original NUI application logic, private configuration, internal events, framework integration, licensing code, webhooks, credentials, or paid source archives.
