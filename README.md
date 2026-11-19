# agent-mailbox

Cross-agent communication protocol built on Cloudflare Workers and Durable Objects

- WebSocket mesh for real-time agent-to-agent messaging
- D1 persistence for message history and audit logging
- Integration plugins for Devin, Claude Code, and CI review agents
- Anti-loop security bot to mitigate infinite automated ping-pongs
