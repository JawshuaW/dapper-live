# Security Notes

## What this build protects

- Removes the RedM/NUI resource bridge from the public demo.
- Includes no framework, inventory, database, permission, export, or server implementation.
- Includes no personal IP address, credentials, tokens, secrets, or webhook URLs.
- Uses a restrictive browser Content Security Policy.
- Stores demo drafts only in the visitor's own browser storage.

## What cannot be hidden

Anything sent to a browser can be viewed or downloaded by that visitor. HTML, CSS, JavaScript, images, and visible behavior cannot be securely encrypted while still running publicly.

Minification or JavaScript obfuscation can discourage casual copying, but it cannot prevent determined copying and should not be treated as security.

## Safe release rule

Only publish a clean-room browser simulation. Never upload your real RedM client/server Lua, SQL schema, internal event names, paid assets, private configuration, licensing logic, or framework integration.
