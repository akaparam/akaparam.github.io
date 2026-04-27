# GoodmanROK

GoodmanROK is a Go CLI/TUI for drafting email subjects and bodies with Grok. It is built for quick replies when you do not want to leave the terminal or break focus.

![GoodmanROK TUI](https://github.com/akaparam/goodmanrok/blob/main/docs/assets/tui.png)

![GoodmanROK CLI](https://github.com/akaparam/goodmanrok/blob/main/docs/assets/cli.png)

## Features

- Full-screen terminal UI by default.
- Scriptable `generate` command for shell workflows.
- Tone choices: `professional`, `casual`, `funny`.
- Language choices: `auto`, `english`, `hinglish`, `punjabi-en`.
- Model choices: `grok-4.20-reasoning`, `grok-4.20-non-reasoning`, `grok-4-1-fast-reasoning`, `grok-4-1-fast-non-reasoning`, `grok-4-fast-reasoning`, `grok-4-fast-non-reasoning`.
- Default model: `grok-4-1-fast-reasoning` (to save costs).
- After generation in TUI mode, the app exits and prints output as follows:
  - `Subject: <subject>`
  - blank line
  - `<body>`
- Uses xAI Responses API with `store: false` by default.

**GitHub URL**: https://github.com/akaparam/goodmanrok