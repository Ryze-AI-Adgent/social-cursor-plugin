# Social by Ryze AI — Cursor Plugin

Run social media from Cursor: publish, schedule and analyze posts on Instagram, Facebook, TikTok, YouTube, LinkedIn and Threads.

## Install

**In Cursor:**

[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20Social%20by%20Ryze%20AI-000000?logo=cursor&logoColor=white)](cursor://anysphere.cursor-deeplink/mcp/install?name=social-by-ryze-ai&config=eyJ1cmwiOiAiaHR0cHM6Ly9zb2NpYWwuZ2V0LXJ5emUuYWkvbWNwIn0=)

Or by hand: **Cursor › Settings › MCP › Add new MCP server**, type `http`, URL:

```
https://social.get-ryze.ai/mcp
```

Or drop this into `.cursor/mcp.json` in your project (same content as [mcp.json](mcp.json)):

```json
{ "mcpServers": { "social-by-ryze-ai": { "url": "https://social.get-ryze.ai/mcp" } } }
```

Cursor opens a browser tab: sign in to Ryze and allow access. No API keys. Also works in Claude Code: `claude mcp add social --transport http https://social.get-ryze.ai/mcp`.

## What you can do

- **Instagram**: feed posts, carousels, Reels and Stories, first comment, collaborators, user tags; post analytics.
- **Facebook Pages**: posts, Reels, Stories and link carousels; post analytics.
- **TikTok**: videos and photo carousels with privacy, comment, duet and stitch settings; creator limits; post analytics.
- **YouTube**: videos and Shorts with title, description, tags, thumbnail, visibility and playlist; video analytics.
- **LinkedIn**: posts as a person or a company page, images, video, document carousels and polls; post analytics.
- **Threads**: posts, carousels and multi-post threads; post analytics.
- **All networks**: publish now or schedule in any time zone, list drafts, scheduled, published and failed posts, delete posts, upload media from a link, and read account details and followers.

A network's tools appear after you connect it in Ryze.

## Safety

Read tools are read-only. Tools that publish are marked as writes, and delete tools are marked destructive. Every action runs under the permissions of the accounts you connected.

## Requirements

A Ryze AI account. Connecting accounts works before you start a plan. The tools need an active Ryze plan, which starts with a 7-day trial; the assistant gives you the link the first time a tool needs it.

## Links

- [Website](https://www.get-ryze.ai?utm_source=github&utm_content=social-cursor-plugin)
- [Privacy policy](https://www.get-ryze.ai/privacy?utm_source=github&utm_content=social-cursor-plugin)
- Support: hello@get-ryze.ai

Social by Ryze AI is an independent product. It is not affiliated with or endorsed by Meta, TikTok, Google, YouTube or LinkedIn.
