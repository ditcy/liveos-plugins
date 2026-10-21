# Live OS plugins

Version 0.1.0. Install instructions: https://liveos.world/install/

- OpenAI: download liveos-openai.zip from Releases and upload as a custom plugin
  in supported ChatGPT/Codex clients. Connect the Live OS MCP server when prompted.
- Claude: add this public repository as a plugin marketplace, then install liveos.
  Custom ZIP installation is also available where supported.
- Claude Code: /plugin marketplace add ditcy/liveos-plugins then
  /plugin install liveos@liveos. Run /mcp to authorize if prompted.

Both packages use https://liveos.world/mcp and OAuth sign-in. No local bridge,
API token copied into chat or local executable is required. An existing Live OS
account is required. Revoke a connection in the account token panel.

The repository contains distributable plugin metadata, generic skills and assets
only. Personal records and server implementation are not included. Directory
approval is separate from these publicly downloadable packages; no approval is
implied. Client availability depends on the platform, plan and administrator.

Privacy: https://liveos.world/privacy/
Support: https://github.com/ditcy/liveos-plugins/issues
