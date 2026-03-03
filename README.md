# Community Apps Starter Repository

This repository is generated from the submit spec in the Community Apps worker.

## Quick Start

1. Replace placeholder values in `ca_profile.xml` and `templates/example-app.xml`.
2. Add one XML file per app under `templates/` (and plugin wrappers under `plugins/` if needed).
3. Commit your changes and push to GitHub.
4. Run Validate + Scan in the submit flow: `/submit`.

## Files

- `ca_profile.xml`: repository overview shown in Community Apps.
- `templates/example-app.xml`: Docker app template example.
- `plugins/example-plugin.xml`: Plugin wrapper example.

## Notes

- Keep `ca_profile.xml` at the repository root.
- Each app template must include either `<Repository>` (Docker) or `<PluginURL>` (plugin).
- Add an OSI-approved license for your repository content.
