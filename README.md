<div align="center">

<img width="100%" alt="Mahan Imanian" src="https://capsule-render.vercel.app/api?type=waving&height=250&section=header&text=Mahan%20Imanian&fontSize=64&fontAlign=50&fontAlignY=34&desc=Chrome%20MV3%20Extensions%20%E2%80%A2%20Browser%20Automation%20%E2%80%A2%20Local-First%20Tools&descSize=18&descAlign=50&descAlignY=55&animation=fadeIn&fontColor=ffffff&color=0:0d1117,45:1e3a8a,75:3730a3,100:581c87" />

<img width="145" alt="Mahan Imanian profile image" src="https://github.com/Mahan-Imanian.png?size=300" />

<br><br>

<img alt="Profile headline" src="https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=22&duration=3000&pause=900&center=true&vCenter=true&width=950&height=72&color=58A6FF&lines=Chrome%20MV3%20extensions%20for%20browser-based%20workflows;Text%20capture%2C%20speech%20queues%2C%20new-tab%20dashboards%2C%20and%20side-panel%20interfaces;Local-first%20tools%20with%20practical%20UX%20and%20reliable%20client-side%20storage;QueueTTS%20%E2%80%A2%20LiveDash" />

<br><br>

<a href="https://github.com/Mahan-Imanian/QueueTTS">
  <img alt="QueueTTS" src="https://img.shields.io/badge/QueueTTS-Text%20Capture%20and%20Speech%20Queue-c2410c?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" />
</a>
<a href="https://github.com/Mahan-Imanian/LiveDash">
  <img alt="LiveDash" src="https://img.shields.io/badge/LiveDash-New%20Tab%20Dashboard-15803d?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" />
</a>
<a href="https://www.linkedin.com/in/mahan-imanian">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-mahan--imanian-1d4ed8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" />
</a>

<br><br>

<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=facc15" />
<img alt="HTML5" src="https://img.shields.io/badge/HTML5-0d1117?style=flat-square&logo=html5&logoColor=f97316" />
<img alt="CSS" src="https://img.shields.io/badge/CSS-0d1117?style=flat-square&logo=css3&logoColor=1572B6" />
<img alt="Chrome MV3" src="https://img.shields.io/badge/Chrome%20MV3-0d1117?style=flat-square&logo=googlechrome&logoColor=22c55e" />
<img alt="IndexedDB" src="https://img.shields.io/badge/IndexedDB-0d1117?style=flat-square&logo=sqlite&logoColor=38bdf8" />
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=22c55e" />
<img alt="GitHub" src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=ffffff" />

</div>

---

## What I build

I build Chrome Manifest V3 extensions that run without accounts or a backend.

The current projects use `chrome.storage.local`, toolbar popups, side panels, options pages, background service workers, keyboard shortcuts, and extension-local scripts. The goal is simple: capture or organize browser data locally, then make it reachable in one or two actions.

---

<div align="center">

<img width="100%" alt="Selected Projects" src="https://capsule-render.vercel.app/api?type=venom&height=130&section=header&text=Selected%20Projects&fontSize=42&fontAlign=50&fontAlignY=56&animation=fadeIn&fontColor=ffffff&color=0:0d1117,50:2563eb,100:7c3aed" />

</div>

<table>
  <tr>
    <td width="50%" valign="top">
      <h2>
        <a href="https://github.com/Mahan-Imanian/QueueTTS">QueueTTS</a>
      </h2>
      <p>
        Chrome MV3 extension for saving selected text or readable page text into a local playback queue.
      </p>
      <p>
        It uses <code>chrome.storage.local</code> for queue/settings data, Chrome's <code>tts</code> API for playback, context-menu actions for capture, and a side panel for queue management.
      </p>
      <p>
        <b>Source version:</b> 2.4.0<br>
        <b>Chrome target:</b> Manifest V3, Chrome 116+<br>
        <b>Distribution:</b> source repo, load unpacked
      </p>
      <p>
        <a href="https://github.com/Mahan-Imanian/QueueTTS">
          <img alt="Open QueueTTS" src="https://img.shields.io/badge/Open-Repository-f97316?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" />
        </a>
      </p>
      <p>
        <img alt="QueueTTS stars" src="https://img.shields.io/github/stars/Mahan-Imanian/QueueTTS?style=flat-square&label=stars&logo=github&logoColor=white&color=f97316&labelColor=0d1117" />
        <img alt="QueueTTS issues" src="https://img.shields.io/github/issues/Mahan-Imanian/QueueTTS?style=flat-square&label=issues&logo=github&logoColor=white&color=7c3aed&labelColor=0d1117" />
        <img alt="QueueTTS last commit" src="https://img.shields.io/github/last-commit/Mahan-Imanian/QueueTTS?style=flat-square&label=last%20commit&logo=github&logoColor=white&color=0ea5e9&labelColor=0d1117" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h2>
        <a href="https://github.com/Mahan-Imanian/LiveDash">LiveDash</a>
      </h2>
      <p>
        Chrome MV3 extension that replaces the new tab page with a local dashboard.
      </p>
      <p>
        It uses <code>newtab.html</code> for the dashboard, <code>chrome.storage.local</code> for dashboard state, the bookmarks permission for bookmark widgets, plus popup, side-panel, options, and background-worker surfaces.
      </p>
      <p>
        <b>Source version:</b> 14.0.1<br>
        <b>Chrome target:</b> Manifest V3<br>
        <b>Distribution:</b> source repo, build/package scripts included
      </p>
      <p>
        <a href="https://github.com/Mahan-Imanian/LiveDash">
          <img alt="Open LiveDash" src="https://img.shields.io/badge/Open-Repository-22c55e?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" />
        </a>
      </p>
      <p>
        <img alt="LiveDash stars" src="https://img.shields.io/github/stars/Mahan-Imanian/LiveDash?style=flat-square&label=stars&logo=github&logoColor=white&color=22c55e&labelColor=0d1117" />
        <img alt="LiveDash issues" src="https://img.shields.io/github/issues/Mahan-Imanian/LiveDash?style=flat-square&label=issues&logo=github&logoColor=white&color=7c3aed&labelColor=0d1117" />
        <img alt="LiveDash last commit" src="https://img.shields.io/github/last-commit/Mahan-Imanian/LiveDash?style=flat-square&label=last%20commit&logo=github&logoColor=white&color=0ea5e9&labelColor=0d1117" />
      </p>
    </td>
  </tr>
</table>

---

## Product proof

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">Runtime surface</th>
    <th align="left">File / manifest entry</th>
    <th align="left">Purpose</th>
  </tr>
  <tr>
    <td>QueueTTS</td>
    <td>Toolbar popup</td>
    <td><code>pages/popup.html</code></td>
    <td>Capture, playback controls, queue preview, command entry</td>
  </tr>
  <tr>
    <td>QueueTTS</td>
    <td>Side panel</td>
    <td><code>pages/sidepanel.html</code></td>
    <td>Full queue management</td>
  </tr>
  <tr>
    <td>QueueTTS</td>
    <td>Options page</td>
    <td><code>pages/options.html</code></td>
    <td>Voice, playback, pronunciation, storage, privacy, shortcut settings</td>
  </tr>
  <tr>
    <td>QueueTTS</td>
    <td>Background worker</td>
    <td><code>src/background.js</code></td>
    <td>Extension events, context menus, capture flow, TTS coordination</td>
  </tr>
  <tr>
    <td>QueueTTS</td>
    <td>Validator</td>
    <td><code>scripts/check.mjs</code></td>
    <td>Manifest, required files, assets, syntax, remote references, placeholder checks</td>
  </tr>
  <tr>
    <td>LiveDash</td>
    <td>New tab</td>
    <td><code>newtab.html</code></td>
    <td>Main dashboard override</td>
  </tr>
  <tr>
    <td>LiveDash</td>
    <td>Toolbar popup</td>
    <td><code>popup.html</code></td>
    <td>Quick actions</td>
  </tr>
  <tr>
    <td>LiveDash</td>
    <td>Side panel</td>
    <td><code>sidepanel.html</code></td>
    <td>Side-panel workflow</td>
  </tr>
  <tr>
    <td>LiveDash</td>
    <td>Options page</td>
    <td><code>options.html</code></td>
    <td>Dashboard settings</td>
  </tr>
  <tr>
    <td>LiveDash</td>
    <td>Background worker</td>
    <td><code>background.js</code></td>
    <td>Extension event handling</td>
  </tr>
  <tr>
    <td>LiveDash</td>
    <td>Validator</td>
    <td><code>scripts/validate-extension.js</code></td>
    <td>Manifest, required pages, CSP, local assets, runtime file checks</td>
  </tr>
</table>

---

<div align="center">

<img width="100%" alt="Runtime Surfaces" src="https://capsule-render.vercel.app/api?type=venom&height=130&section=header&text=Runtime%20Surfaces&fontSize=42&fontAlign=50&fontAlignY=56&animation=fadeIn&fontColor=ffffff&color=0:7c3aed,50:2563eb,100:0d1117" />

</div>

```mermaid
flowchart TB
  Chrome["Chrome"] --> Manifest["manifest.json"]

  Manifest --> Popup["Toolbar popup"]
  Manifest --> SidePanel["Side panel"]
  Manifest --> Options["Options page"]
  Manifest --> Worker["Background service worker"]
  Manifest --> Storage[("chrome.storage.local")]

  QueueTTS["QueueTTS"] --> QPopup["pages/popup.html"]
  QueueTTS --> QPanel["pages/sidepanel.html"]
  QueueTTS --> QOptions["pages/options.html"]
  QueueTTS --> QWorker["src/background.js"]
  QueueTTS --> QTTS["chrome.tts"]
  QueueTTS --> QMenus["contextMenus"]

  LiveDash["LiveDash"] --> LNewTab["newtab.html"]
  LiveDash --> LPopup["popup.html"]
  LiveDash --> LPanel["sidepanel.html"]
  LiveDash --> LOptions["options.html"]
  LiveDash --> LWorker["background.js"]
  LiveDash --> LBookmarks["chrome.bookmarks"]

  QPopup --> Storage
  QPanel --> Storage
  QOptions --> Storage
  QWorker --> Storage
  LNewTab --> Storage
  LPopup --> Storage
  LPanel --> Storage
  LOptions --> Storage
  LWorker --> Storage

  classDef core fill:#0d1117,stroke:#38bdf8,color:#ffffff,stroke-width:2px;
  classDef project fill:#111827,stroke:#a855f7,color:#ffffff,stroke-width:2px;
  classDef file fill:#111827,stroke:#22c55e,color:#ffffff,stroke-width:2px;
  classDef api fill:#111827,stroke:#f97316,color:#ffffff,stroke-width:2px;

  class Chrome,Manifest core;
  class QueueTTS,LiveDash project;
  class Popup,SidePanel,Options,Worker,QPopup,QPanel,QOptions,QWorker,LNewTab,LPopup,LPanel,LOptions,LWorker file;
  class Storage,QTTS,QMenus,LBookmarks api;
