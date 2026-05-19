# orthoclass-mcp-server
AGPL-3.0 Model Context Protocol (MCP) server for orthopaedic classification and clinical workflow support. Requires API registration.
# OrthoClass MCP Server (`AGPL-3.0`)

An open-source Model Context Protocol (MCP) server designed to deliver deterministic, surgeon-supervised orthopaedic classification data directly into LLM environments (such as Claude Code, and custom AI agents). 

By connecting your local AI models to **OrthoClass**, developers and healthcare clinicians can ground their LLMs in validated medical structures, fracture classification frameworks, and clinical decision-support data pipelines.

### 🔑 API Registration & Access
While the client-side server logic is open-source under the **AGPL 3.0 license**, connecting to the core cloud infrastructure and live orthopaedic knowledge base requires a valid MAIVAN API key.

* **Get your API Key:** [Register at ortho-x.maivan.ai](https://ortho-x.maivan.ai)
* **Configuration:** Expose your token locally as `ORTHOCLASS_API_KEY=your_key_here`

### 🛡️ Open Source Compliance (AGPL 3.0)
This repository is protected under the GNU Affero General Public License v3.0. If you modify this MCP server code and offer it as a network service to other users, you **must** make your modified source code publicly available under the same AGPL terms.
