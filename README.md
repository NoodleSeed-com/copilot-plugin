# Noodle Seed GitHub Copilot plugin

This generated plugin guides GitHub Copilot through the Noodle Seed TypeScript-first workflow: author
one `server.ts`, validate and test locally, then deploy to a governed hosted MCP endpoint. Copilot
writes and edits the application source; Noodle Seed supplies guidance, validation, deployment, and
Cloud operations.

## Install and update

`copilot plugin install NoodleSeed-com/copilot-plugin`

Use the GitHub Copilot plugin update flow to receive a later released version.

## First verification

In a coding workspace, ask Copilot to create a Noodle Seed MCP app. It should use the
`noodle-readiness` MCP when available, or privately run the packaged launcher and report only the
corresponding public `noodle ...` outcome.

## Compatibility and profile

- Plugin version: `0.33.80`
- Agent Kit: `0.65.0`
- CLI: `@noodleseed/one@0.115.0`
- MCP capability: `1`

The local launcher uses a Copilot-specific Noodle profile. GitHub Copilot manages OAuth for the
remote developer MCP; credentials remain outside this generated repository.

## Supported systems

Use macOS or Linux. Native Windows is unsupported for the local launcher; use WSL2 Ubuntu Bash
(`wsl --install -d Ubuntu`) before installing the plugin.

## Support

- [Noodle Seed documentation](https://docs.noodleseed.dev)
- [Support](https://noodleseed.com/support)
- [Privacy](https://noodleseed.com/privacy)
- [Terms](https://noodleseed.com/terms)
