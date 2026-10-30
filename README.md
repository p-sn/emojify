# ✨🦊👻 Emojify 👻🦊✨

An agent skill for adding emojis to text. In case there weren't enough.

## Installation

```bash
npx skills@latest add p-sn/emojify
```

Follow the prompts to choose your agent. Add `-g` to install globally instead of in the current project.

## Use

```text
Emojify this at high: Today we read a book. Then we go to the park.
```

Choose an intensity:

- **low:** discreet accents; every word stays.
- **medium:** visible accompaniment. The default.
- **high:** emojis invade the text and replace words.
- **ultra:** only emojis. Precision becomes a fond memory.

## Example

Source: Today we read a book. Then we go to the park.

| Level | Result |
| --- | --- |
| low | Today we read a book. Then we go to the park. 🌳 |
| medium | Today we read a book 📖. Then we go to the park 🌳. |
| high | 📖✨ Today we read a 📖 🤓📚. Then 🚶➡️ we go to the 🌳🌷☀️. |
| ultra | 📅📖 🕒🚶➡️🌳 |

Examples illustrate intensity, not fixed outputs. Results vary by model. This is for fun, not faithful translation—especially at `ultra`.

## License

[MIT](LICENSE) © 2026 psole.
