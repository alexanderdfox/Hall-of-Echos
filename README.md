# The Hall of Echoes

**A mystical web-based AI chat experience** — where ancient wisdom meets the living web.

![The Hall of Echoes](https://alexanderdfox.github.io/Hall-of-Echos/)

## About

**The Hall of Echoes** is a beautiful, atmospheric frontend for interacting with knowledge. It combines:

- A dark, gothic fantasy aesthetic inspired by ancient libraries and stone halls
- Real-time web search capabilities (via DuckDuckGo Instant Answers)
- Elegant fallback wisdom drawn from learned patterns
- A companion "Scribe's Window" for next-token prediction experiments

**Live Demo**: [https://alexanderdfox.github.io/Hall-of-Echos/](https://alexanderdfox.github.io/Hall-of-Echos/)

## Features

### Hall of Echoes (`index.html`)
- **Thematic UI**: Stone-and-gold fantasy design with parchment-like text
- **Web Search**: Automatically queries the living web when relevant
- **Pattern Weaver**: Rich fallback responses styled as ancient wisdom
- **Responsive chat interface** with smooth animations

### The Scribe's Window (`whispers.html`)
- Elegant parchment-style interface
- Attempts to connect to **Meta Llama 3 8B** via Hugging Face Inference API
- Robust local simulation fallback (never breaks)
- Temperature slider ("Dice Wildness") for controlling creativity
- Conversation memory

## Project Structure

```
Hall-of-Echos/
├── index.html              # Main Hall of Echoes chat interface
├── whispers.html           # Scribe's Window (LLM experimentation)
├── .github/workflows/      # GitHub Pages deployment
└── README.md
```

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/alexanderdfox/Hall-of-Echos.git
   cd Hall-of-Echos
   ```

2. Open either file in your browser:
   - `index.html` — Main Hall experience
   - `whispers.html` — The Scribe's Window

No build step required — it's pure HTML + CSS + JavaScript.

## Technologies

- **HTML5 / CSS3** (with custom fantasy styling)
- **Vanilla JavaScript**
- **DuckDuckGo Instant Answer API** (public, no key needed)
- **Hugging Face Inference API** (optional for Scribe)

## Future Ideas

- Integration with more powerful local or hosted LLMs
- Voice input/output
- Persistent conversation history
- Multiple "Elders" with different personalities
- Image generation integration

## Contributing

Feel free to open issues or submit pull requests! Ideas for new themes, improved search, or additional mystical interfaces are welcome.

---

**Enter the Hall...**  
*It listens. It searches. It predicts.*
