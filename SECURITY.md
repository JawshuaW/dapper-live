# Public Demo Security Notes

## Protection model

A browser must receive the HTML, CSS, JavaScript, and images it displays. Those public files can always be inspected or downloaded. Minification, disabled right-click menus, and JavaScript obfuscation are not meaningful protection.

The showroom is protected by separation: it publishes independently written browser simulations instead of the real paid RedM resources.

## Not included

This build contains no:

- RedM client or server Lua
- SQL schemas or database queries
- original resource configuration
- framework bridges or inventory integration
- NUI callback names from the paid resources
- server events, exports, or gameplay calculations
- licensing logic, credentials, tokens, webhooks, or private URLs
- original application JavaScript or CSS from Banking, Planting, Medical, or Printing Press
- paid resource ZIP archives or source maps

## Public assets

Selected presentation images were resized, compressed, renamed, and marked for demonstration use. Full original asset folders are not shipped. Any image delivered to a browser remains downloadable, so irreplaceable or private artwork should never be placed in the public repository.

## Safe update checklist

Before every public upload:

1. Confirm the repository contains no `.lua`, `.sql`, `.env`, `.map`, source archive, or private configuration files.
2. Search for framework names, NUI bridge calls, server events, database details, credentials, tokens, webhook URLs, email addresses, and private IP addresses.
3. Confirm every interaction uses fabricated local data and no external API, RedM bridge, or database connection.
4. Keep full-resolution paid assets and all original source files outside this repository.
5. Upload only the completed `dapper-live` public package.
