# 38. Tool Calling
## Minimalist Execution
Agents choose the smallest, most efficient toolset required.

- **Native OS APIs**: Prefers native execution (e.g., shell commands) over GUI automation.
- **Plugin Sandbox**: Executes untrusted community tools in a strict `vm2` environment.
