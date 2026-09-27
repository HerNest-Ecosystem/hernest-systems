# hernest-systems
AI tools that turn emotional and behavioral signals into measurable data
# HerNest Systems

**AI tools that read emotional and behavioral signals as data — so organizations can catch problems before they become collapses.**

Most organizations track what's easy to count: attendance, completion rates, output. They miss what's actually driving those numbers — trust breaking down, quiet burnout, a program that looks healthy right up until it isn't. HerNest closes that blind spot.

## What's in this repo

- **[`vaerus-local/`](./vaerus-local)** — a free, offline text-signal detector. Reads a description of a situation and returns the emotions, domains, and psychological drivers at play. No API key required, runs entirely on your machine.
- **[`agent-runner/`](./agent-runner)** — a lightweight SDK for building your own diagnostic agents on top of Claude, using the same pattern our tools are built on.
- **[`docs/`](./docs)** — architecture notes, the research this is built on, and how the pieces fit together.

## Try it in under a minute

```bash
git clone https://github.com/hernest-systems/hernest.git
cd hernest/vaerus-local
npm install
npm run demo
```

Paste in a sentence like *"the team says they're aligned but nothing ever moves forward"* and see what it reads back.

## Why we're building this

HerNest started in 2025 as a research question: could human organizations survive and adapt the way an ant colony does — with no central boss, guided instead by signals moving through the whole network? Eight years of field work through our nonprofit, QWFN, turned that question into a working set of tools, tested on real programs with real women across Africa before any of it became software for anyone else.

## What's not in this repo (yet)

Our full diagnostic suite — the tools that read team health, entry risk, network vulnerability, collapse forecasting, and more — runs as a hosted API. [Get in touch](mailto:systems@hernest.com.ng) if you want early access or want to talk about what we're building toward.

## License

The code in this repo is open under [MIT](./LICENSE). HerNest's hosted diagnostic API and underlying models are proprietary and not included here.

## Learn more

- [hernestsystems.org](https://hernestsystems.org)
- [HerNest Africa](https://www.hernest.africa) — where these tools are tested in the field
