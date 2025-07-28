# Resources on Model Context Protocol, Agent2Agent and related protocols for interfacing LLM agents

## Model Context Protocol

### Specification and Architecture

anthropic MCP architecture page: https://modelcontextprotocol.io/specification/2025-03-26/architecture

main github repo: https://github.com/modelcontextprotocol

[MCP Toolbox for Databases: Simplify AI Agent Access to Enterprise Data, Hamsa Buvaraghan, Derek Egan, April 2025](https://cloud.google.com/blog/products/ai-machine-learning/mcp-toolbox-for-databases-now-supports-model-context-protocol)

[An introduction to MCP Toolbox for Databases on googleapis.github.io](https://googleapis.github.io/genai-toolbox/getting-started/introduction/)

github repo for MCP Toolbox for Databases: https://github.com/googleapis/genai-toolbox

### Examples implementing MCP

Streamable MCP implementation by InvariantLabs AI: https://github.com/dimitarpg13/mcp-streamable-http

Claude-Deep-Research: MCP server by Mathew Cherukara:  https://github.com/dimitarpg13/Claude-Deep-Research

### Demo and Tutorial Code

**Tutorial**: https://modelcontextprotocol.io/tutorials/building-mcp-with-llms

**Examples**: https://modelcontextprotocol.io/examples

  **[Servers](https://modelcontextprotocol.io/examples)**:
   
  Filesystem MCP Server: https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem

  Fetch MCP Server: https://github.com/modelcontextprotocol/servers/tree/main/src/fetch

  Knowledge Graph Memory Server: https://github.com/modelcontextprotocol/servers/tree/main/src/memory

  Sequential Thinking MCP Server: https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking

  **Clients**:

  Notes on building clients: https://github.com/modelcontextprotocol/docs/blob/main/tutorials/building-a-client-node.mdx

  Full list of supported clients here: https://modelcontextprotocol.io/clients

  **Client list for supperted frameworks**: https://modelcontextprotocol.io/llms-full.txt

**FastMCP Examples**: https://github.com/jlowin/fastmcp/tree/main/examples
   



### Online articles, videos, and blogs

[Building Agents with Model Context Protocol - Full Workshop with Mahesh Murag of Anthropic, AI Engineer Summit February 2025 (youtube video)](https://youtu.be/kQmXtrmQ5Zg?si=TYAn4vJMX8_mwQ5H)

[FastMCP — the best way to build an MCP server with Python, June 11, 2025, ZazenCodes (youtube video)](https://www.youtube.com/watch?v=rnljvmHorQw)

github repo: https://github.com/zazencodes/zazencodes-season-2/tree/main/src/fastmcp-tutorial

[MCP vs API: Simplifying AI Agent Integration with External Data, IBM Technology, May, 2025 (youtube video)](https://www.youtube.com/watch?v=7j1t3UZA1TY)

[MCP vs ACP vs A2A: Comparing Agent Protocols with Laurie Voss from LlamaIndex, MCP Developers Summit, June 2025 (youtube video)](https://www.youtube.com/watch?v=kqB_xML1SfA)

[MCP vs A2A vs RAG Explained Simply! Cloud with Raj, May, 2025 (youtube video)](https://youtu.be/u546On9iEBk?si=11bpXOnXXgFb9OLi)

[Why MCP really is a big deal | Model Context Protocol with Tim Berglund, Confluent Developer, June 2025 (youtube video)](https://youtu.be/FLpS7OfD5-s?si=0QypUC5Rx-OLJ1Ok)

[MCP Authentication: The Confusing parts Explained, Arcade, July 7, 2025 (youtube video)](https://youtu.be/oVHuxXSxr8U?si=OVvg5mxmrmqRtibv)


#### HuggingFace

https://huggingface.co/blog/tsadoq/agent2agent-and-mcp-tutorial

github repo with code: https://github.com/Tsadoq/a2a-mcp-tutorial


#### Medium

[The Model Context Protocol (MCP) — A Complete Tutorial, Dr. Nimrita Koul, March, 2025](https://medium.com/@nimritakoul01/the-model-context-protocol-mcp-a-complete-tutorial-a3abe8a7f4ef)

[The MCP-First Revolution: Why Your Next Application Should Start With a Model Context Protocol Server, Ravi Kiran Vemula, March, 2025](https://medium.com/@vrknetha/the-mcp-first-revolution-why-your-next-application-should-start-with-a-model-context-protocol-9b3d1e973e42)

[True Agentic RAG: How I Taught Claude to Talk to My PDFs using MCP (Model Context Protocol), 
Alexander Komyagin, Jan 2025](https://medium.com/@adkomyagin/true-agentic-rag-how-i-taught-claude-to-talk-to-my-pdfs-using-model-context-protocol-mcp-9b8671b00de1)

[AI Agents Using MCP = Your “Guy in the Chair”, Medium, James Buckhouse, 2025](https://buckhouse.medium.com/ai-agents-using-mcp-your-guy-in-the-chair-f32ac850c60e)

[Creating AI Agents with MCP and Ollama local: A Hands-On Tutorial, Usamah Jassat, May 2025](https://medium.com/@UsamahJ/creating-ai-agents-with-mcp-and-ollama-local-a-hands-on-tutorial-8a8d8f698315)

[The Future of AI Agent Communication with ACP: A practical guide to connecting and coordinating multiple AI agents, Mariya Mansurova, 2025](https://towardsdatascience.com/the-future-of-ai-agent-communication-with-acp/?fbclid=IwY2xjawLpkXlleHRuA2FlbQIxMQABHoCnI9gisZXNm4FPteE0ZpHNKnIxwmAKF6pVFjB4YckLAocwssgXWSj6GiDr_aem_atj4xC3L0uOndgWS763SFg)

#### Other Media Outlets

##### FrameLink Figma Server

[Quickstart with FrameLink Figma Server using MCP, FrameLink, 2025](https://www.framelink.ai/docs/quickstart?utm_source=github&utm_medium=referral&utm_campaign=readme)

FrameLink Figma Server github repo: https://github.com/GLips/Figma-Context-MCP

[Creating a UI with Figma to Cursor MCP Server, Graham Lipsman, youtube video, 2025](https://www.youtube.com/watch?v=6G9yb-LrEqg)

[AI Agents Using MCP = Your “Guy in the Chair”, Medium, James Buckhouse, 2025](https://buckhouse.medium.com/ai-agents-using-mcp-your-guy-in-the-chair-f32ac850c60e)

##### ClaudeMCP

[MCP's New Transport Layer - A Deep Dive into the Streamable HTTP Protocol, 阳明, ClaudeMCP, 2025-07-07](https://www.claudemcp.com/blog/mcp-streamable-http)

## Agent2Agent

https://github.com/a2aproject/A2A

## ACP

https://github.com/i-am-bee/acp

## Language Server Protocol

https://en.wikipedia.org/wiki/Language_Server_Protocol

## RAG Systems and Context Engineering

[A Survey of Context Engineering for Large Language Models, L. Mei et al, 2025](https://github.com/dimitarpg13/mcp_intro/blob/main/articles/A_Survey_of_Context_Engineering_for_Large_Language_Models_Mei_2025.pdf)
