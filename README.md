# 💬 Riya

**Riya** is a self-hosted AI assistant for Instagram DMs. She chats like a regular Indian girl — short Hinglish, a little warmth, no long essays — and she lives on a private VPS, not on a third-party bot platform.

Built by [Farhad](https://github.com/div-fdop) (**@div-fdop**).

## 🌸 What Riya is

Riya is a practice-account companion that talks to the owner's account (and, carefully, to other people). Replies are written by Grok CLI. Memory stays on the server. She is honest about being an AI when it matters, and she never sends a post or a message from the owner's real account unless the owner says yes.

## 🕊️ How she chats

- Short Hinglish texts, the way a real person would type on Instagram.
- Server-side memory, with daily learning from recent conversations.
- If someone other than the owner messages her, she says early on that she is an AI agent, then keeps chatting in the same light style. She never pretends to be human.

## 🛠️ What she can do

- **Chat** — auto-replies in character, generated on the host via Grok CLI.
- **Remember** — facts and style notes stay on the VPS and can be refreshed daily.
- **Check the server** — read-only status commands, and only when the owner asks.
- **Post** — the owner can ask Riya to publish to the owner's account, with optional image and video edits. Nothing goes out until the owner confirms.
- **Draft replies** — Riya can write a reply in the owner's own texting style. It is sent only after a `haan` (or an `edit:`), and every message carries a clear AI tag so people know an assistant wrote it.

## 🔒 Privacy first

Riya runs on a self-hosted VPS. Chat history, memory, and login sessions stay on that machine. They are not checked into git and are not sent to a public app. The owner stays in the loop for anything that would appear under the real account.

## ⚙️ Tech stack

- **Python** — the program and skills
- **Playwright** — Instagram in a headless browser
- **Grok CLI** — reply generation
- **Pillow** — image edits
- **MoviePy** — video / reel edits

## 📦 Source code is private

The full program is kept in a private repository. This public page is only a description of the project, not the source.

## 👋 Author

**Farhad** — [github.com/div-fdop](https://github.com/div-fdop)
