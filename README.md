# Confluence Knowledge Assistant
_Powered by Google ADK & Atlassian MCP_

This agent lets you chat naturally with Confluence-based product documentation or other information stored in Confluence. It reads a Markdown index file (a simple list of page titles, IDs, and links) once and stores it in the tool context state, then uses it to look up the most relevant Confluence pages and, in this example, generate accurate answers limited strictly to the Marmind Knowledge Base.


## Installation

Prerequisites
To run the Confluence Knowledge Assistant with an MCP connection, you need:

Python 3.13 with a virtual environment (venv).
JupyterLab (installed inside the venv).
Node.js - includes npx, which is used to launch the MCP client (mcp-remote) on the fly without a global install.
Access to the Atlassian MCP endpoint: https://mcp.atlassian.com/v1/sse
