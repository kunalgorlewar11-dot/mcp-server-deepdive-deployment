```json
{
  "preferences": {
    "coworkWebSearchEnabled": true,
    "coworkScheduledTasksEnabled": false,
    "ccdScheduledTasksEnabled": false
  },
  "mcpServers": {
    "airbnb": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/kunalgorlewar11-dot/mcp-server-deepdive-deployment.git",
        "mcp-server"
      ]
    }
  }
}
```