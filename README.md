# How OpenClaw Scaled to almost 1M Lines Of Vibe Code In 3 Months Without Becoming Unmaintainable

Interactive visualization of how the [OpenClaw](https://github.com/openclaw/openclaw) codebase went from one file to 91 modules across 15,000+ commits.

[Live demo](https://openclaw-architecture-analysis-gshtgghug-vladbroks-projects.vercel.app/) | [Watch the video walkthrough](https://youtu.be/iPunXq5MMv4)

![demo](demo.gif)

## Usage

```
git clone https://github.com/VladBrok/openclaw-architecture-analysis.git
cd openclaw-architecture-analysis
npx serve .
```

Then open http://localhost:3000 in your browser.


## What's inside

A timeline slider with 17 snapshots of the architecture, one every ~1000 commits. Modules are circles sized by lines of code, grouped into layers (Channels, Extensions, Core, AI, Infrastructure, Platform). Hover any circle to see what the module does and how it connects to the rest. Toggle dependency arrows to see the full import graph.

All data was extracted from git history. Visualization built with D3.js.
