---
name: setup
description: Connect Live OS and initialize shared account context when installing the plugin or starting work with Live OS.
---

Use the bundled liveos MCP connection. If disconnected, ask the client to connect
through its OAuth flow at https://liveos.world/mcp. The user signs in and grants
access on Live OS; never request their password or token in chat.

Call get_context before working. Read the returned current date, timezone,
preferences, available trackers and active skills. Load relevant server skills;
they are authoritative and updated independently of this package. User-owned
preferences and facts belong in Live OS, never in the plugin directory.

Explain briefly that the same account is available from other connected clients.
Do not create trackers, preferences or sample records just to demonstrate setup.
For an actual task, use the relevant bundled skill and server tool descriptions.

Reference: [Shared bootstrap](references/live-os-bootstrap.md).
