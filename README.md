# Claude Meter

A privacy-first Chrome/Brave Manifest V3 extension that estimates
Claude conversation token and context usage locally.

## Features

- Estimated token usage
- Context-window utilization
- Live message detection
- On-page usage overlay
- Browser popup
- Conversation history
- Local-only processing
- No backend
- No analytics
- No external API calls

## Tech Stack

- TypeScript
- React
- Vite
- Manifest V3
- Vitest
- Chrome Storage API
- Shadow DOM
- MutationObserver

## Privacy

Claude Meter processes conversation data locally.
No conversation data is sent to an external server.

> Token counts are estimates and are not official Anthropic usage data.
