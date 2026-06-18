# 🦑 Agent-Squid
```
    🦑 AGENT
    ██████╗ ██████╗ ██╗   ██╗██╗██████╗
   ██╔════╝██╔═══██╗██║   ██║██║██╔══██╗
   ╚█████╗ ██║   ██║██║   ██║██║██║  ██║
    ╚═══██╗██║▄▄ ██║██║   ██║██║██║  ██║
   ██████╔╝╚██████╔╝╚██████╔╝██║██████╔╝
   ╚═════╝  ╚══▀▀═╝  ╚═════╝ ╚═╝╚═════╝
```

**Use your $20 plan like a $100 plan.**

Named sessions, parallel prompts, and goldfish mode across Claude Code, Codex, and Cursor Agent.

Most developers burn tokens they never meant to spend. Long sessions drift — stale context, forgotten decisions, dead branches still in the window. The model reads all of it. You pay for all of it.

Squid gives you the controls to stop that.

```text
#launch@claude write the release notes
#launch@codex! review the diff for regressions
#bug@cursor reproduce the auth failure
```

- **Named agent lanes** that survive terminal restarts, reboots, and phone switches
- **Goldfish mode** — `!` for a clean prompt, `!3` for only the last three exchanges
- **Parallel work** — Claude and Codex on the same problem, each in its own lane
- **Live progress** — watch tool activity and partial output while the CLI works
- **Phone/tablet access** — your local machine keeps coding while you're on the couch

## Install

```bash
# 1. Install at least one agent CLI
npm install -g @anthropic-ai/claude-code   # Claude Code
npm install -g @openai/codex               # OpenAI Codex
curl https://cursor.com/install -fsS | bash  # Cursor Agent

# 2. Install and start Squid
bin/install.sh
bin/start.sh
```

Open `http://127.0.0.1:8000` in your browser.

## Full Documentation

→ [github.com/agent-squid/squid](https://github.com/agent-squid/squid)
