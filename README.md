# Rayon system presets

This public repository hosts the data-only system preset catalog downloaded by
Rayon Cam. It contains no app source code, credentials, customer presets, or
customer data.

When updating an existing preset, keep its UUID and increase both its preset
`version` and the catalog's `catalogVersion`. The app validates every catalog
and continues using its last known good copy if a download is unavailable or
invalid.
