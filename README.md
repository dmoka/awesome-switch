# Awesome Switch [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[Switch](https://www.switchagents.ai/) is a self-hosted server and desktop app that adds AI coding agents to Slack, Microsoft Teams, Discord, Telegram and Mattermost channels. People and agents work in the same thread, and the agents share the room's history as context. It supports Claude Code, Codex, Cursor, OpenCode and Antigravity, with 10 more providers in preview.

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Deploy](#deploy)
- [Agent Providers](#agent-providers)
- [Connectors](#connectors)
- [Tutorials](#tutorials)
- [Videos](#videos)
- [Articles](#articles)

## Official Resources

- [GitHub Repository](https://github.com/sandbox-quantum/switch) - Source code of the Switch server and Switch Console.
- [Documentation](https://docs.switchagents.ai/) - Guides for setup, deployment, agent providers and connectors.
- [Docs MCP Server](https://docs.switchagents.ai/mcp) - MCP server that lets coding agents search the Switch docs.
- [Latest Release](https://github.com/sandbox-quantum/switch/releases/latest) - Switch Console downloads for macOS, Windows and Linux.
- [Changelog](https://docs.switchagents.ai/switch-rooms/resources/changelog) - Release notes for the server and Switch Console.
- [Blog](https://www.switchagents.ai/resources/blog) - Posts from the Switch team.
- [YouTube Channel](https://www.youtube.com/channel/UCYWa6FvBJxQN8XwY7M5AV7A) - Demos and walkthroughs from the Switch team.
- [Discord](https://discord.gg/W2t3CJQNkz) - Community server for questions and feedback.

## Getting Started

- [Quickstart](https://docs.switchagents.ai/switch-rooms/getting-started/quickstart) - Set up Switch on your computer and give the first task to the switch-buddy assistant.
- [Get Started Guide](https://docs.switchagents.ai/switch-rooms/getting-started/index) - Three paths: join your team's rooms, bring your own agent, or set up Switch.
- [Use Cases](https://docs.switchagents.ai/switch-rooms/use-cases/index) - Eight team scenarios, such as incident response and time-zone handoff.
- [Build a Payments Room](https://docs.switchagents.ai/switch-rooms/building/payments-room) - Worked example that turns one channel into a Switch room.
- [Agent Templates](https://github.com/sandbox-quantum/switch/tree/main/examples/agent-templates) - YAML templates for ready-made agents, such as a support desk and a triage pair.

## Deploy

- [Choose How to Run Switch](https://docs.switchagents.ai/switch-rooms/deploy/index) - Compares a server on your computer, a server on a remote host, and a server your team deploys.
- [Host Switch for Your Team](https://docs.switchagents.ai/switch-rooms/deploy/self-host) - Self-host with Docker Compose on one Linux machine or with Helm on Kubernetes, including the required secrets.
- [Helm Chart](https://github.com/sandbox-quantum/switch/pkgs/container/charts%2Fswitch) - Kubernetes chart published to `oci://ghcr.io/sandbox-quantum/charts/switch` with each server release.
- [Compose File](https://github.com/sandbox-quantum/switch/pkgs/container/standalone-compose) - Docker Compose stack published to `ghcr.io/sandbox-quantum/standalone-compose` with the same version as the Helm chart.
- [Onboard a Remote Host](https://docs.switchagents.ai/switch-rooms/deploy/host-remotely) - Run a server or an agent on a Linux or macOS machine that Switch Console reaches over SSH.
- [Connect a Messaging App](https://docs.switchagents.ai/switch-rooms/deploy/messaging-apps/index) - Compares Slack, Microsoft Teams, Mattermost, Discord and Telegram by admin rights, public address and how agents appear.

## Agent Providers

- [Set Up Agent Providers](https://docs.switchagents.ai/switch-rooms/getting-started/set-up-agent-providers) - Install and sign in to Claude Code, OpenCode, Codex, Cursor or Antigravity so Switch can start it under your account.
- [Add a Custom Agent](https://docs.switchagents.ai/switch-rooms/getting-started/add-a-second-agent) - Register an agent with a name, a machine, a working directory and a provider, or bring one you run in a terminal.
- [Agent Settings](https://docs.switchagents.ai/switch-rooms/getting-started/agent-settings) - Auto mode, bypass permissions, who can instruct the agent, service access, model and tools.
- [What Keeps Your Agent Running](https://docs.switchagents.ai/switch-rooms/getting-started/what-keeps-your-agent-running) - Shows whether Switch Console, a remote host or a managed machine holds the agent's connection.
- [The Agent Protocol](https://docs.switchagents.ai/switch-rooms/internals/agent-protocol) - WebSocket and HTTP contract for building your own agent client.
- [Life of a Message](https://docs.switchagents.ai/switch-rooms/internals/life-of-a-message) - One message traced from a Slack channel to an agent and back, hop by hop.

## Connectors

- [Connectors Overview](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/index) - Table of all nine connectors with what agents can do, what you can limit, and how long agent access lasts.
- [GitHub](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/github) - Clone, branch, push and open pull requests as a GitHub App, read only or read and push, in the repositories you choose.
- [GitLab](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/gitlab) - Work in gitlab.com projects as you. Needs a server with a public HTTPS address.
- [Atlassian](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/atlassian) - Read and update Jira issues and Confluence pages as you, with one connection for both.
- [Linear](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/linear) - Read and update Linear issues and projects as you.
- [Datadog](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/datadog) - Query metrics, logs, traces, monitors and incidents, with a read-only option.
- [Sentry](https://docs.switchagents.ai/switch-rooms/getting-started/connectors/sentry) - Look up issues, events, stack traces and releases on sentry.io, for one hour per connection.

## Tutorials

## Videos

## Articles

## Contributing

Read the [contribution guidelines](contributing.md) first.

## Footnotes

The maintainer of this list works with the Switch team through DevTools Academy.
