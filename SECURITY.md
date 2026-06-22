# Public Demo Security Notes

## What is protected

This build includes no RedM client or server Lua, SQL schema, framework bridge, inventory implementation, exports, server events, medical calculation engine, permission implementation, credentials, tokens, webhooks, licensing logic, or paid resource source code.

The Dapper Medical demonstration was independently reduced to fabricated browser data and local visual interactions. The public anatomical plate is lower resolution and watermarked; the original asset is not shipped.

## What visitors can inspect

Anything a browser receives can be viewed or downloaded. Visitors can inspect the public HTML, CSS, JavaScript, and preview image. That is unavoidable for any interactive website, because humans apparently insist on receiving the files required to display the files.

Protection comes from publishing only a clean-room simulation. Minification and obfuscation are not reliable security controls.

## Safe update checklist

Before every public upload:

1. Confirm there are no `.lua`, `.sql`, `.env`, source-map, archive, credential, or configuration files.
2. Search for private IP addresses, email addresses, API keys, tokens, webhook URLs, event names, database details, and license secrets.
3. Confirm every interaction uses fabricated local data and no external API or RedM bridge.
4. Keep full-resolution paid assets outside the public repository.
