# Dealing

**Your personal board of directors. Under the influence.**

Dealing is an ecosystem of personal AI agents that works as your own unconventional board of directors. Five agents, each inspired by a different altered state of mind (Marijuana, Ayahuasca, Alcohol, LSD, Cocaine), debate your problem. The Chairman weighs their arguments and makes one decision. The agents don't consume anything: their behavior is inspired by stereotypes of altered states, and Dealing doesn't promote substance use or give information about it.

> Five questionable minds. One surprisingly good decision.

## What's in this repo

| File | What it is |
|---|---|
| `index.html` | Landing page. Scroll-driven WebGL journey: a particle head in profile → x-ray brain → reward system → neurons → one synapse → neon burst → the ring lands inside the app (match cut) → manifesto. |
| `demo.html` | Clickable demo. Board table of particle agents, 1:1 chats, full board meetings with clarifying questions, the Chairman's decision with approvable actions, seats and chaos levels, memory and actions tabs. |

Both pages are single, self-contained HTML files. They load Three.js r128 from cdnjs and fonts from Google Fonts.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

To publish it, enable **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root).

## Notes

- The demo's answers are scripted for the video. Nothing is sent anywhere and actions are simulated. The next step is wiring the agents to Mastra.
- Built for the hackathon stack: Mastra (agents), assistant-ui (chat), AgentMail, Exa, Kernel, Neon, Fly.io.

## Credits

- 3D head model: **Lee Perry-Smith** by [Infinite-Realities](https://www.ir-ltd.net/), licensed [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Converted to a point cloud.
- [Three.js](https://threejs.org/) (MIT).
- Fonts: Syne, VT323, Manrope (Google Fonts, OFL).
