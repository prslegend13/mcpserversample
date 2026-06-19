# Installation Steps

## MCP Server Configuration

Add the following configuration to your `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "addition": {
      "command": "C:\\Users\\prabh\\.local\\bin\\uvx.EXE",
      "args": [
        "--from",
        "git+https://github.com/prslegend13/mcpserversample.git",
        "mcp-server"
      ],
      "env": {
        "UV_LINK_MODE": "copy"
      }
    },
    "mcp-server-deepdive-deployment": {
      "command": "C:\\Users\\prabh\\OneDrive\\Documents\\Claude\\mcp-server-deepdive-deployment\\.venv\\Scripts\\python.EXE",
      "args": [
        "-m",
        "mcpserver"
      ]
    }
  },
  "preferences": {
    "remoteToolsDeviceName": "desktop-u6t43rq",
    "coworkHipaaRestricted": false,
    "coworkWebSearchEnabled": true,
    "coworkScheduledTasksEnabled": true,
    "ccdScheduledTasksEnabled": true,
    "coworkModelAutoFallbackByAccount": {
      "c27c264d-f8c0-4426-91ef-b1a672856b47": true
    },
    "epitaxyPrefs": {
      "starred-local-code-sessions": [],
      "starred-cowork-spaces": [],
      "starred-session-groups": [],
      "dframe-local-slice": {
        "pinnedOrder": [],
        "customGroupAssignments": {},
        "customGroupOrder": {}
      }
    },
    "bypassPermissionsGateByAccount": {
      "c27c264d-f8c0-4426-91ef-b1a672856b47": false
    },
    "sidebarMode": "chat"
  },
  "coworkUserFilesPath": "C:\\Users\\prabh\\OneDrive\\Documents\\Claude"
}
```
