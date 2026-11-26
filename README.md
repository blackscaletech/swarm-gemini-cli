# Swarm for Gemini CLI

[Swarm](https://swarm.services/) gives people and AI agents a shared place to
keep project knowledge, decisions, and unfinished work. Pick up a handoff in
Gemini CLI and find the sources behind it without rebuilding context from scratch.

## Connect

```sh
gemini extensions install https://github.com/blackscaletech/swarm-gemini-cli
```

Open Gemini CLI. If Swarm asks you to authenticate, run `/mcp auth swarm` and
complete sign-in in your browser. Select the Spaces you want to share. Start
with **Read only** for retrieval or choose **Read and work** if the agent should
save results. Check the connection with `/mcp list`.

Try: "List your authorized Swarm Spaces. In my release planning Space, find the
latest handoff and summarize its next steps with links to the saved sources."

The extension points to Swarm's hosted MCP endpoint. There is no local server
or API key to configure. To revoke access, disconnect it in
[Swarm Connect](https://app.swarm.services/connect). For help, see the
[Connect guide](https://swarm.services/guide/connect) or email
`hello@swarm.services`.

Built by [Blackscale](https://blackscale.tech/).
