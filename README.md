# Awesome MCP Servers

A **curated collection** of the best **Model Context Protocol (MCP) servers**, enabling integration between language models and external tools, platforms, and data sources. MCP servers allow LLMs to access, query, and interact with real-time data, enhancing AI agents workflows and making them context-aware.

> 🚀 *Pull requests welcome!* Have a useful MCP server? Submit a PR!

## 🌐 What is MCP?

The **Model Context Protocol (MCP)** is a standardized way to let AI agents (like Cursor Agent and Composer) interact with external systems — including project management tools, code repositories, file storage, databases, and observability platforms. With MCP, your agent can:

- Search files and databases
- Fetch real-time project data
- Execute queries
- Read error reports, logs, and even automate browser interactions

---

## 📚 Table of Contents

- [MCP Servers](#-mcp-servers)
- [Resources](#-resources)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔗 MCP Servers

### 📊 Project Management & Issue Tracking

| Name     | Description  |
|---|---|
| **Linear** | Integration with Linear's issue tracking system, allowing LLMs to read and interact with issues. |
| **GitHub** | Allows LLMs to interact with GitHub’s issue tracking system, including reading and updating issues. |
| **Sentry** | Provides access to error reports, stack traces, and debugging information from Sentry. |
| **Raygun** | Access crash reporting and performance monitoring data from Raygun. |
| **Todoist** | Task management integration, allowing LLMs to interact with Todoist tasks and projects. |

---

### 🗄️ Databases & Data Platforms

| Name     | Description  |
|---|---|
| **PostgreSQL** | Provides read-only access to PostgreSQL databases for schema inspection and queries. |
| **Neon** | Provides interaction with Neon’s serverless PostgreSQL platform. |
| **Supabase** | MCP server for PostgREST, enabling LLMs to interact with Postgres databases via Supabase. |
| **Snowflake** | Allows querying and interacting with Snowflake databases. |
| **SQLite** | Provides database interaction and lightweight BI capabilities using SQLite. |
| **Tinybird** | Connects to the Tinybird platform for querying and interacting with serverless ClickHouse databases. |
| **Qdrant** | Enables semantic search and memory retrieval via the Qdrant vector search engine. |

---

### 🔧 Cloud & Infrastructure

| Name     | Description  |
|---|---|
| **Vercel** | Integrates with Vercel’s infrastructure to provide endpoints for chatbots, data processing, and content generation. |
| **Cloudflare** | Manage and deploy resources on the Cloudflare developer platform. |
| **Docker** | Enables container, image, volume, and network management directly through MCP. |
| **Kubernetes** | Provides MCP access for pod, deployment, and service management within Kubernetes clusters. |

---

### 💻 Files & Content Management

| Name     | Description  |
|---|---|
| **Google Drive** | Search, read, and browse files stored in Google Drive. |
| **Obsidian Markdown Notes** | Enables LLMs to read and search Markdown notes in Obsidian vaults. |
| **Filesystem** | Provides secure file operations with configurable access controls. |

---

### 🌐 Web Crawling & Browsing

| Name     | Description  |
|---|---|
| **Browserbase** | Automate browser interactions directly from MCP agents. |
| **BrowserTools MCP** | Analyze logs and interact with your browser for rapid debugging. |
| **Apify RAG Web Browser** | A browser-like interface for LLM apps that queries Google Search, scrapes the top results, and returns cleaned content in Markdown. |
| **Firecrawl** | Converts entire websites into structured, LLM-ready data. |
| **Fetch** | Fetch and convert web content into formats optimized for LLM processing. |
| **Puppeteer** | Provides browser automation and web scraping capabilities directly to agents. |
| **Search1API** | Unified API for search, crawling, and sitemaps. |

---

### 💬 Communication & Collaboration

| Name     | Description  |
|---|---|
| **Slack** | Provides direct MCP access to Slack messages, channels, and threads. |
| **Figma** | Provides design data directly from Figma, enabling more accurate design implementations in code. |

---

### 💰 Payments & Finance

| Name     | Description  |
|---|---|
| **Stripe** | Provides MCP-based access to the Stripe API for querying payments, customers, and subscriptions. |

---

### 📊 Observability & Monitoring

| Name     | Description  |
|---|---|
| **Axiom** | Allows LLMs to query and analyze logs, traces, and event data using natural language. |

---

### ⚙️ Other Integrations

| Name     | Description  |
|---|---|
| **[AcqPath](https://github.com/reflectme-source/acqpath-distribution)** | Remote MCP for signed, timestamped source-rights observations used in RAG, indexing, training, search, and AI input workflows. |
| **E2B** | Allows LLMs to securely execute code inside cloud-based sandboxes. |
| **JSON Resume** | Automatically updates your resume as you develop new projects and skills. |

---

## 📖 Resources

- [Model Context Protocol Documentation](https://modelcontextprotocol.io)
- [Cursor's MCP Directory](https://cursor.directory/mcp)
- [Anthropic’s MCP Announcement](https://www.anthropic.com/news/model-context-protocol)
