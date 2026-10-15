# AgentDesk

A live demo dashboard for an autonomous AI work assistant. It triages email, drafts replies, extracts tasks, proposes calendar changes, and keeps an audit log. Risky actions wait for human approval.

**Live demo:** `https://YOUR-USERNAME.github.io/agentdesk/`

> This is a front-end simulation with sample data. It is not connected to Gmail, Kafka, or any AI model yet.

## Run it locally

No build step. Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Planned real stack

- Java + Spring Boot (Spring AI or LangChain4j for tool calling)
- Gmail API with OAuth2
- Kafka for asynchronous jobs
- Postgres for emails, tasks, approvals, and the audit log
- Scheduled workflows and human approval

## Contributing

1. Fork this repo.
2. Create a branch and edit `index.html`.
3. Open a pull request describing what you changed.

Changes to `main` go live automatically through GitHub Pages.

## License

MIT
