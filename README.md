# Confluence Knowledge Assistant
_**Powered by Google ADK & Atlassian MCP**_

**This agent lets you chat naturally with Confluence-based product documentation or other information stored in Confluence and can be embedded in your product.** It reads a Markdown index file (containing page summaries, titles, IDs, and links) once, stores it in the tool context state, and uses it to look up the most relevant Confluence pages. In this example, it generates accurate answers using the Marmind Knowledge Base space in Confluence, while guiding the user to the mirrored page in the publicly available documentation - [Marmind Knowledge Base](https://knowledgebase.marmind.com/kb/)


[![Watch on YouTube](https://img.shields.io/badge/Watch%20on-YouTube-red?logo=youtube&style=for-the-badge)](https://youtu.be/40ni6oilunQ) 

[![Read on LinkedIn](https://img.shields.io/badge/Article-RAG%20vs%20MCP-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/pulse/another-rag-vs-mcp-article-jenya-stoeva-tpxhf)

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

## How-To

**Prerequisites**
To run the Confluence Knowledge Assistant notebook with an MCP connection, you need:

* Python 3.13
* JupyterLab (installed inside a venv) or you can use the public one at [Jupyter Lab](https://jupyter.org/try-jupyter/lab/).
* Node.js - includes npx, which is used to launch the MCP client (mcp-remote) on the fly without a global install.
* Access to the Atlassian MCP endpoint: https://mcp.atlassian.com/v1/sse and permissions to read the Confluence content.



