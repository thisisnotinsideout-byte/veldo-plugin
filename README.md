# Veldo

Make your Claude your cofounder. Veldo gives the Claude you already use a memory of your startup: what you're building, what you decided and why, and your best next move. It asks whether you did it, and it catches you when a plan goes against something you already decided.

## What's in this plugin

- **The Veldo connector** (`.mcp.json`): Veldo's remote server at `https://veldo.co/mcp`, over HTTP. It holds your startup memory. Connect it from the plugin's Connectors tab and sign in with Google.
- **The `veldo-cofounder` skill** (`skills/veldo-cofounder/SKILL.md`): plain instructions that tell Claude when to use Veldo and how to act as your cofounder.

The plugin runs no code on your computer: no hooks, scripts or packages.

## What it sends where

- **To Veldo (`https://veldo.co`, hosted on Cloudflare in the United States):** what Claude saves to your startup memory (your one-page picture and short library notes, each with the date and reason it changed), the searches Claude runs on that memory, and a record of which Veldo tools were used and when (never what was in them). Your name, email and Google account ID come from signing in with Google.
- **To Google:** only the sign-in itself. Veldo asks for your name and email, nothing else.
- **Nothing else leaves Claude.** Veldo never reads your chats on its own; only what Claude saves reaches it. Veldo doesn't sell or share your data, show ads, or run AI on it.

See and edit everything Veldo holds at https://veldo.co/me.

## Links

- Docs: https://veldo.co/docs
- Privacy: https://veldo.co/privacy
- Terms: https://veldo.co/terms
- Support: support@veldo.co
