<p align="center"><a href="https://tollnode.com"><img src="https://tollnode.com/icon.svg" width="88" height="88" alt="TollNode road-sign logo"></a></p>

<h1 align="center">TollNode</h1>

<p align="center"><b>Give your AI agent new abilities with no setup.</b><br>One API and one MCP server for top AI models and live data. Pay per call, charged only when it works.</p>

## What your agent can do

| | |
|---|---|
| **Images** | Nano Banana, GPT Image, FLUX, Seedream, Recraft, Ideogram, editing and upscaling |
| **Video** | Veo, Kling, Seedance, Runway, Hailuo, Wan |
| **Voice and music** | ElevenLabs voices, Lyria music, full songs with vocals |
| **Live data** | Google search, YouTube transcripts, TikTok, Instagram, Reddit, Maps reviews, Amazon prices, jobs, hotels, homes |
| **Documents** | PDF, Word and slides to Markdown |

New models arrive all the time: [what's new](https://tollnode.com/changes) ([RSS](https://tollnode.com/changes/feed.xml)).

## Connect in one line

**Claude Code, over MCP**

```bash
claude mcp add --transport http tollnode https://tollnode.com/mcp
```

Every tool lists its price. Call the free `list_models` tool to browse them all.

**Any agent, with a wallet (x402, USDC on Base, no account)**

```bash
npx agentcash add https://tollnode.com
```

**Your own app, with an API key**

Open an account at [tollnode.com/account](https://tollnode.com/account), add funds from $1, create a key, then send `Authorization: Bearer <key>` to any node, or to the MCP server.

## Why TollNode

- **No setup per tool.** One connection instead of a dozen sign-ups and keys.
- **Fair pricing.** A fixed price per call, from $0.002. The same number on the page, in the 402 and in the OpenAPI file.
- **Charged only when it works.** We check the payment, run the job, and collect only on a usable result. Failed calls cost nothing.

## For agents and indexers

[llms.txt](https://tollnode.com/llms.txt) · [OpenAPI](https://tollnode.com/openapi.json) · [x402 manifest](https://tollnode.com/.well-known/x402) · [MCP manifest](https://tollnode.com/.well-known/mcp.json)

[tollnode.com](https://tollnode.com) · hello@tollnode.com
