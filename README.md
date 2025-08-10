FlowQuery

The visual way to write SQL

Description

FlowQuery is an open-source, no-code/low-code visual SQL editor for modern data platforms.
Build queries by dragging and connecting nodes, preview results at any step, and see live row counts along the data flow. Designed for data engineers, analysts, and SQL learners.

⸻

✨ Features
	•	Node-based query builder – Drag, drop, connect, and configure
	•	Instant previews – Run queries up to any node
	•	Live row counts between nodes for quick insights
	•	Rich SQL nodes – Filters, joins, aggregations, window functions, pivots, etc.
	•	Result panel with pagination & sample data
	•	Link management – Disconnect upstream/downstream easily
	•	Real-time validation of SQL syntax and config
	•	Keyboard & mouse friendly workflow
	•	Built for extensibility – Future support for DBT, SQLMesh, macros, and AI-powered features

⸻

🖼️ Screenshot

(Add here a screenshot or animated GIF of the editor canvas in action once available.)

⸻

📦 Tech Stack
	•	Frontend: Svelte + TanStack Router + TailwindCSS
	•	Backend: Node.js + Hono
	•	API Protocol: oRPC
	•	Database:
	•	SQLite (libSQL) – configuration, settings, session
	•	KuzuDB – SQL & query metadata
	•	Package Manager: bun
	•	AI Agent Framework: LangChain + LangGraph (JS/TS)

⸻

🚀 Getting Started

Prerequisites
	•	bun >= 1.2.19
	•	Node.js >= 20.x
	•	Databricks SQL Warehouse (for first MVP target platform)

Clone & Install

git clone https://github.com/<your-username>/flowquery.git
cd flowquery
bun install

Run in Dev Mode

bun run dev


⸻

🗺️ Roadmap
	•	Node-based SQL editor MVP
	•	Databricks SQL Warehouse integration
	•	DBT project support (v2)
	•	AI-assisted query generation (v3)
	•	Multi-platform support (Snowflake, Redshift, Fabric, etc.)

⸻

🤝 Contributing

We welcome PRs and discussions! See CONTRIBUTING.md for guidelines.

⸻

📜 License

MIT License — See LICENSE for details.

⸻

📢 Tags

#sql #visualsql #querybuilder #nocode #lowcode #dataengineering #oss #dataplatform