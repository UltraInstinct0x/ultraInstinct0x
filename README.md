# Hi, I'm Gokhan — I go by Goku 👋

I build things for myself first: agent infrastructure, local-first AI tooling, and small
utilities that fix a specific annoyance. I live in Izmir and work as a CRM Analyst, and most of my time outside that goes into self-hosted systems and the tools
around them.

I keep a lot private, so this profile does not represent the whole of what I work on.
What it does show is the part I have chosen to make public.

## What I work on

- **Agent infrastructure and observability** — capturing what an agent actually did:
  model I/O, tool calls, and human feedback loops. Mostly C++-free plumbing: proxies,
  collectors, SDKs, plugins, and hooks.
- **Privacy-aware data handling** — redacting PII and secrets before they leave a
  process, with EUR/TR rule packs and reversible token mapping.
- **Local-first and self-hosted software** — my own machines run the stack, so I care
  about things that work offline, survive restarts, and do not need a vendor.
- **Media and voice tooling** — transcription, dubbing, and speech pipelines, including
  Turkish-language work.

## Public repositories worth a look

- **[vlc-auto-dub](https://github.com/UltraInstinct0x/vlc-auto-dub)** — AI-powered video
  dubbing and transcription extension for VLC. Whisper-based transcription, generated
  dubs, SRT/video output.
- **[panel](https://github.com/UltraInstinct0x/panel)** — a feedback layer for agent
  outputs (MIT). The wider `panel-*` set includes an OpenAI/Anthropic-compatible LLM
  proxy, an OpenTelemetry collector for agent spans, Python/Node/Go SDKs, and
  Hermes/OpenCode/Claude Code hooks.
- **[scrubber-proxy](https://github.com/UltraInstinct0x/scrubber-proxy)** — an HTTP
  service that redacts PII and secrets (reversible AES-256-GCM token mapping, rule packs
  for base/eu/tr/medical).
- **[WorkToJiraEffort](https://github.com/UltraInstinct0x/WorkToJiraEffort)** — Rust
  daemon that turns screen activity into Jira and Salesforce time entries (MIT).
- **[schema-evolution-analyzer](https://github.com/UltraInstinct0x/schema-evolution-analyzer)**
  — Python tool for understanding the impact of database schema changes (MIT).

*Forked repositories on this account are other people's work. I am not the author of
anything I only forked.*

## Elsewhere

- Site: [supersaiyan.dev](https://supersaiyan.dev)
- X: [@0xultrainstinct](https://twitter.com/0xultrainstinct)
- LinkedIn: [Gokhan Guney](https://www.linkedin.com/in/gokhang-guney/)
