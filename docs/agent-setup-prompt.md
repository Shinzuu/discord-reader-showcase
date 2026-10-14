Set up discord-reader, a private Discord bot that runs as a local MCP server for Claude Code, on this computer. Do as much as you can yourself and ask me only for the things you cannot do.

<context>
discord-reader lets Claude Code read and search Discord channels and, after my approval, post, reply, react and more. It runs as my own Discord bot with my own bot token; nothing is shared or hosted. It reads only allowlisted channels and writes only to a separate write list. I received the discord-reader folder from its author; it is not downloaded from anywhere. The folder's README describes setup step by step; read it first and follow it. Where it and this prompt disagree, the README wins.

What discord-reader needs:
- Claude Code.
- Node.js 24 or later.
- A Discord bot I create in Discord's developer portal (private, with the Message Content intent on).
- Manage Server rights on the Discord server I want it in.
</context>

<steps>
1. Ask me where the discord-reader folder is. Confirm it contains the server, the skill and the example config.
2. Check Node.js. Install dependencies and run the project's checks. Stop if tests fail.
3. Walk me through creating the bot in the developer portal, one setting at a time, as the README lists. I do the clicks.
4. Have me store the token: create the private config folder and give me the README's one-line command that reads the token without echo, so I paste it myself. Never ask me to paste the token into this chat, and never read, print or copy it.
5. Give me the invite link with the read-only permissions from the README, with my application ID filled in. I open it and pick the server.
6. Write the allowlist with me: ask which server and which channels it may read, and which (if any) it may write to. Show me the file before saving it with private permissions. Leave events and DMs off unless I ask.
7. Register the server with Claude Code at user scope and install the skill, as the README describes. Show me each command before you run it.
8. Test after I reconnect: list my servers, then pull the last 24 hours from one read channel I choose and give me a three-line summary.
9. Report what you installed, the allowlist in plain words, and the test result.
</steps>

<rules>
- Do not post, react, pin or change anything in Discord during setup.
- Never put a token in any file except the token file the README names.
- If a step fails twice, stop and tell me what you saw instead of trying other routes.
</rules>
