<p align="center">
  <img src="https://user-images.githubusercontent.com/3369400/133268513-5bfe2f93-4402-42c9-a403-81c9e86934b6.jpeg" width="600"/>
</p>
# Kanishk Ranjan
/kʌn-ɪʃk/ • noun • 
12:33:27
IST
 • [Lofi Music Player]

## About

I am a second-year Computer Science student at Newton School of Technology, Pune, focused on bridging the gap between academic theory and industry-scale software development. My experience centers on contributing directly to major frameworks like Electron.js and building high-performance full-stack applications.

- Open Source Contributor @ElectronJS & Chromium | B.Tech AI/ML Student

## Professional Summary

### Systems Development
Experience navigating and contributing to large-scale codebases like **Chromium** and **Electron.js** to ship technical patches.

### Execution Focus
Driven by a 'finisher's mindset' and a refusal to accept workarounds; committed to debugging deep into the source code to resolve the root cause of issues.

### Technical Agility
Proven ability to pick up and apply new programming languages and frameworks on the fly to resolve complex bugs.

## Experience

### Software Development Intern at **Megahit**
[Jan. 2026 – Present] | Berlin, Germany (Remote)

- Engineered cross-platform features for Electron.js desktop applications, focusing on system-level integration and high-performance design patterns.
- Architected a safeStore mechanism for encrypted credential persistence and integrated a PostgreSQL layer for structured data management.
- Standardized Inter-Process Communication (IPC) using TypeScript Enums, eliminating runtime errors and ensuring type-safety across main/renderer processes.
- Automated development workflows using Webpack, ESLint, and Husky, reducing technical debt and enforcing code quality within an Agile sprint cycle.

*Tech Stack:* Electron.js, TypeScript, PostgreSQL, Webpack

## Open Source Contributions

### Electron.js (Contributor)

* [PR #50188](https://github.com/electron/electron/pull/50188) - Open
- test: add desktopCapturer window icon validation: Introduced a new test suite to verify that window icons retrieved via desktopCapturer are both present and valid.
- Specifically designed to prevent regressions of issue #48063, ensuring that changes in Apple's internal implementation do not break icon retrieval logic.
* [PR #50261](https://github.com/electron/electron/pull/50261) - Merged
- fix: backport macOS Tahoe app icon retrieval: Backported a critical fix from Chromium to resolve an issue where running application icons were not correctly retrieved on macOS Tahoe.
- Addresses internal Apple API changes by incorporating updated Chromium logic, ensuring consistent icon rendering across the latest macOS versions (Fixes #48063).
* [PR #49364](https://github.com/electron/electron/pull/49364) - Merged
- test: fix flaky BrowserWindow test: Fixed flaky test cases in `BrowserWindow` where tests failed when the desktop theme was set to Dark.
- Identified that Chromium applies a #121212 background color in Dark mode, causing failures when loading `about:blank`, and implemented a robust fix to ensure consistent test pass rates.
* [PR #49356](https://github.com/electron/electron/pull/49356) - Open
- feat: Developers tools for BaseWindow: Fixed a critical "JavaScript error in main process" occurring when triggering `toggleDevTools` in `BaseWindow`.
- Updated the logic to target the currently focused `WebContents` using `webContents.getFocusedWebContents()` instead of `getOwnerBrowserWindow()`, handling edge cases where the DevTools window itself was focused.
* [PR #49316](https://github.com/electron/electron/pull/49316) - Merged
- test: fix flaky BrowserView test: Resolved flaky tests in `BrowserView` caused by Chromium's dark mode background color inconsistencies.
- Ensured consistent test execution across different OS theme settings by addressing background rendering behaviors.
* [PR #49315](https://github.com/electron/electron/pull/49315) - Open
- feat: ready-to-show event on webContents: Added `paintWhenInitiallyHidden` option to the `WebContentsView` constructor.
- Enabled renderer "wake up" functionality to correctly fire `ready-to-show` and set initial `visibilityState` to hidden while in the background, addressing issue #43531.
* [PR #49219](https://github.com/electron/electron/pull/49219) - Closed
- fix: resolve appIcon error in desktopCapturer: Solved a high-DPI asset loss issue on macOS where window icons returned by `desktopCapturer` were low resolution (32x32).
- Created a local copy of window icon utility logic to enforce a target size of 128x128, ensuring Electron receives sharp icons without altering upstream Chromium files.

### The Chromium Project (Open Source Developer)

* [CL 7239386](https://chromium-review.googlesource.com/q/7239386) - Merged
- Streamlined the SelectionController logic within the Blink engine to enhance the precision of caret-based text selection.
- Redesigned internal selection checks to ensure that right-clicking an active caret does not trigger unwanted selection expansion, resolving a long-standing UX edge case.
- Managed the end-to-end lifecycle of the patch, including debugging complex rendering engine behaviors and passing Chromium’s rigorous automated test suites (CQ).
* [CL 7276941](https://chromium-review.googlesource.com/q/7276941) - Merged
- Debugged and patched selection controller logic within the Blink rendering engine to fix unexpected selection expansion bugs during right-click events.
- Implemented a cleaner abstraction for platform-dependent selection rules, replacing legacy #if BUILDFLAGS macros with a centralized logic check.
- Collaborated with the Chromium community to review and merge changes impacting text interaction and accessibility in editable web content.

### Visual Studio Code (Contributor)

* [PR #278931](https://github.com/microsoft/vscode/pull/206899) - Merged
- Identified and resolved a race condition in the VS Code startup sequence where early extension activation triggered erratic UI scrolling behavior.
- Refined the Settings tree-view logic to ensure consistent scroll positioning, improving UX within the configuration interface.

## Achievements

* **Years Coding**: 7+ (Started at 13)
* **Rank 1 Streak**: 5x (Consistent Top Performer in College Contest)
* **Open Source PRs**: 9+ (Electron, Chromium, VS Code)
* **Problems Solved**: 740+ (DSA & Competitive Programming)

## Selected Projects

### [Quickka](https://github.com/KanishkRanjan/quickka) | 2026
- Real-time CTF & treasure hunt platform with live scoring
- *Tech:* JavaScript, Express, MongoDB, Socket.io, Docker
- *Outcome:* Deployed for college event

### [BlueKa](https://github.com/KanishkRanjan/BlueKa) | 2025
- Cross-platform habit tracker with identity-based goal system
- *Tech:* React Native, Expo, TailwindCSS
- *Outcome:* Daily active use for 2+ months

### [SplitBuddy](https://github.com/manthansubhash01/SplitBuddy) | 2025
- Group expense and bill splitter with smart settlement logic
- *Tech:* React Native, Expo, Node.js, Express, Socket.io
- *Outcome:* Simplifies group expense management

### [Meowka](https://github.com/KanishkRanjan/meowka) | 2025
- Real-time vehicle tracking system with map visualization
- *Tech:* TypeScript, React, MongoDB
- *Outcome:* Demoed across departments

### [FocusKa](https://github.com/KanishkRanjan/FocusKa) | 2025
- Distraction-blocking desktop app with session analytics
- *Tech:* Electron, Vite
- *Outcome:* Boosted personal productivity

### [WebKa](https://github.com/KanishkRanjan/wapka) | 2025
- Cloud-based collaborative text editor with real-time sync
- *Tech:* TypeScript, Next.js, TailwindCSS, Convex
- *Outcome:* Accessible from any device

### [memoryKa](https://github.com/KanishkRanjan/memoryKa) | 2025
- Multiplayer memory card game with animated UI
- *Tech:* JavaScript, React
- *Outcome:* Built for fun, polished for portfolio

### [QuickSnatch 1.0](https://github.com/KanishkRanjan/QuickSnatch) | 2025
- Scalable treasure hunt platform for college fest
- *Tech:* Python, Flask
- *Outcome:* Handled 300+ concurrent users

### [CP Club Portal](https://github.com/KanishkRanjan/competitive-programming-club) | 2024
- Full-stack portal with automated profile scraping for CP club
- *Tech:* MongoDB, Express, Web Scraping, EJS
- *Outcome:* Adopted by club coordinators

### [CSESLB](https://github.com/KanishkRanjan/cseslb) | 2024
- Automated leaderboard for CSES problem set rankings
- *Tech:* Puppeteer, Express, MongoDB
- *Outcome:* Used by 30+ students daily

### [Eatka](https://github.com/KanishkRanjan/Eatka) | 2023
- WYSIWYG word processor for automated test paper generation
- *Tech:* Java, JavaFX
- *Outcome:* Desktop app with rich text editing

### [Custom HTML Tags](https://github.com/KanishkRanjan/shiny-octo-bassoon) | 2021
- Experiment extending HTML with custom element registration
- *Tech:* HTML, CSS, JavaScript
- *Outcome:* Explored Web Components API

### [TestKa](https://github.com/KanishkRanjan/school) | 2021
- Online examination system with auth & grading engine
- *Tech:* PHP, MySQL, HTML, CSS, JavaScript
- *Outcome:* Full-stack app built at age 15

### [ichigo-v4](https://github.com/KanishkRanjan/ichigo-v4) | 2020
- Remote system management tool via Windows Services
- *Tech:* C#, Windows Services, Express
- *Outcome:* Remote access from anywhere

### [bookish-octo-potato](https://github.com/KanishkRanjan/bookish-octo-potato) | 2020
- E-commerce website with authentication & CRUD operations
- *Tech:* Node.js, Express, HTML, CSS, JavaScript, EJS
- *Outcome:* Full-stack app built at age 15

### Blogka | 2020
- Full-stack blog with authentication & CRUD operations
- *Tech:* Python, Flask, HTML, CSS, JavaScript
- *Outcome:* First auth system built

### ChatKa | 2020
- Real-time chat app with WebSocket communication
- *Tech:* Socket.io, Node.js, Express, EJS
- *Outcome:* Learned real-time architecture

### HomeKa | 2020
- CLI tool to auto-sort homework files by subject
- *Tech:* Python, Bash
- *Outcome:* Automated daily workflow

### Eins | 2018
- Voice-controlled personal assistant with task automation
- *Tech:* Python
- *Outcome:* Sparked the programming journey

### Quizka | *
- Interactive terminal quiz game
- *Tech:* Bash
- *Outcome:* The very first program I wrote

## Education

### Newton School of Technology
* Bachelor of Technology in Computer Science
* Aug. 2024 – May 2028 | Pune, MH

### St. Karen’s High School
* Senior Secondary (Class XII, CBSE)
* Aug. 2022 – May 2024 | Patna, BR

### Open Minds A Birla School
* Matriculation (Class X, CBSE)
* Apr. 2021 – Apr. 2022 | Patna, BR

## Tech Stack

**Languages**: Python, TypeScript, JavaScript, C++, C#, Java, PHP, SQL
**Frontend**: React, Next.js, Tailwind CSS, Shadcn UI, Electron.js
**Backend**: FastAPI, Node.js, PostgreSQL, MongoDB
**Infra**: Docker, Google Cloud, Vercel, Git, GitHub, Linux, Nginx, Webpack, ESLint, Husky
**AI/ML**: Hugging Face, PyTorch, Pandas

## Library (Reading List)

### Technical
* [Design and Analysis of Algorithms](https://www.google.com/search?q=Introduction+to+Algorithms+CLRS) by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, and Clifford Stein
* [Electron: From Beginner to Pro](https://www.google.com/search?q=Electron+From+Beginner+to+Pro+Chris+Griffith) by Chris Griffith and Leif Wells
* [Competitive Programmer's Handbook](https://www.google.com/search?q=Competitive+Programmer%27s+Handbook+Antti+Laaksonen) by Antti Laaksonen

### Casual
- [Atomic Habits](https://www.google.com/search?q=Atomic+Habits+James+Clear) by James Clear
- [Deep Work](https://www.google.com/search?q=Deep+Work+Cal+Newport) by Cal Newport
- [Moonwalking with Einstein](https://www.google.com/search?q=Moonwalking+with+Einstein+Joshua+Foer) by Joshua Foer
- [Hyperfocus](https://www.google.com/search?q=Hyperfocus+Chris+Bailey) by Chris Bailey
- [The 5AM Club](https://www.google.com/search?q=The+5AM+Club+Robin+Sharma) by Robin Sharma
- [Limitless](https://www.google.com/search?q=Limitless+Jim+Kwik) by Jim Kwik

## Contact

- [LinkedIn](https://www.linkedin.com/in/kanishkranjan/)
- [GitHub](https://github.com/KanishkRanjan)
- [Email](mailto:kanishkranjan17@gmail.com)
- [Cal.com Schedule](https://cal.com/kanishk-ranjan-chzi6x)
- [X/Twitter](https://x.com/KanishkRanjan2)
- [Discord](https://discord.com/users/kanishkranjan)

---
