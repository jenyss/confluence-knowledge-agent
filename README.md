# Confluence Knowledge Assistant
_**Powered by Google ADK & Atlassian MCP**_

**This agent lets you chat naturally with Confluence-based product documentation or other information stored in Confluence.** It reads a Markdown index file (a simple list of page titles, IDs, and links) once and stores it in the tool context state, then uses it to look up the most relevant Confluence pages and, in this example, generate accurate answers limited strictly to the [Marmind Knowledge Base](https://knowledgebase.marmind.com/kb/).

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

## How-To

**Prerequisites**
To run the Confluence Knowledge Assistant with an MCP connection, you need:

* Python 3.13 with a virtual environment (venv).
* JupyterLab (installed inside the venv) or you can use the public one at [Jupyter Lab](https://jupyter.org/try-jupyter/lab/).
* Node.js - includes npx, which is used to launch the MCP client (mcp-remote) on the fly without a global install.
* Access to the Atlassian MCP endpoint: https://mcp.atlassian.com/v1/sse


