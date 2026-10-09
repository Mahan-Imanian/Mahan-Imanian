<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Mahan Imanian. Founder at GreenTouch. Browser tools that work the moment they open and keep your data on your machine." src="assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/mahan-imanian">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://mahan-imanian.github.io/ML-Algorithm-Visualizer/">Algoscope, live</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/Mahan-Imanian?tab=repositories">All repositories</a>
</p>

<br>

I'm Mahan, founder of GreenTouch. I studied computer science and spend a lot of my time on AI, but most of what I ship runs in the browser: a lab for watching algorithms think, a new tab page worth keeping, a queue that reads the web back to me.

They share one rule. A tool should be useful the second it opens, and your data should stay on your machine unless you send it somewhere.

<br>

## Selected work

### Algoscope

**An algorithm lab that records every operation and plays it back beside the data structure, the pseudocode line and the reason for each step.**

Eighteen algorithms across pathfinding, sorting, searching, spanning trees and machine learning. Scrub any run forwards or backwards with the queue, heap or call stack always on screen. Put two algorithms on the same input and it gives you the verdict, like *"Both find a path of cost 46. A\* expands 55% fewer cells."* Every experiment is a shareable link, and there's a presentation mode for lectures.

<a href="https://mahan-imanian.github.io/ML-Algorithm-Visualizer/"><img alt="Algoscope comparing A* and Dijkstra on one weighted grid, with Dijkstra's min-heap and the synced pseudocode beside it" src="https://raw.githubusercontent.com/Mahan-Imanian/ML-Algorithm-Visualizer/main/docs/screenshots/hero-compare.jpg" width="100%"></a>

<sub>React · TypeScript · Vite · MIT</sub> &nbsp;—&nbsp; **[Open the lab →](https://mahan-imanian.github.io/ML-Algorithm-Visualizer/)** &nbsp;·&nbsp; [Source](https://github.com/Mahan-Imanian/ML-Algorithm-Visualizer)

<br>

### LiveDash

**The front page of your browser.**

A Chrome new tab with one search line that reaches the web, your open tabs, history, bookmarks, tasks and notes. Type two letters and the top hit is the tab you already have open. Numbered shortcut keys, a Today column that understands *"pay rent every month on the 1st"*, weather, focus mode, and a command palette behind <kbd>></kbd>. Nothing leaves your browser unless you ask it to.

<a href="https://github.com/Mahan-Imanian/LiveDash"><img alt="LiveDash in dark mode: a serif search line, numbered shortcut keys, and three columns for picking up, today and notes" src="https://raw.githubusercontent.com/Mahan-Imanian/LiveDash/main/docs/screenshots/front-dark.png" width="100%"></a>

<sub>React · TypeScript · WXT · Chrome MV3 · MIT</sub> &nbsp;—&nbsp; **[View the repository →](https://github.com/Mahan-Imanian/LiveDash)**

<br>

### QueueTTS

**A private listen-later queue for the web.**

Save an article or a selection with <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>S</kbd>. QueueTTS cuts the page down to the article, reads your queue aloud in order with the voices Chrome already has, and picks up from the sentence where you stopped, even after a restart. It makes no network requests of its own.

<a href="https://github.com/Mahan-Imanian/QueueTTS"><img alt="The QueueTTS popup over a news article: one article playing with the current word underlined and two more waiting in the queue" src="https://raw.githubusercontent.com/Mahan-Imanian/QueueTTS/main/assets/readme/hero.png" width="100%"></a>

<sub>JavaScript · chrome.tts · Chrome 116+ · MV3</sub> &nbsp;—&nbsp; **[View the repository →](https://github.com/Mahan-Imanian/QueueTTS)**

<br>

## How I build

- **Useful on open.** No empty first screen and no sign-up wall. Algoscope opens on a recorded run; LiveDash fills its shortcut slots from your history instead of leaving gaps.
- **Local by default.** State lives in the browser. When something does leave it, the interface says so. QueueTTS labels online voices because they send text to Google.
- **Logic you can test without the UI.** Algoscope's algorithms live in a framework-free TypeScript core with its own tests. The React app is only a view onto the recorded trace.

## Tools

`TypeScript` `JavaScript` `React` `Vite` `Tailwind CSS` `Node.js` `Chrome Extensions (MV3)` `WXT` `PHP` `MySQL` `GitHub Actions`

<br>

<p align="center"><sub>Open to collaboration on browser tooling and CS / AI work. The fastest way to reach me is <a href="https://www.linkedin.com/in/mahan-imanian">LinkedIn</a>.</sub></p>
