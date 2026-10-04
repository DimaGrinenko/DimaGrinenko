<p align="center">
  <img src="assets/profile-banner.gif" width="1200" alt="Dmitry Grinenko · Fullstack development · Web, mobile and browser games" />
</p>

<p align="center">
  <a href="#game-development">Game development</a> &nbsp;·&nbsp;
  <a href="#web--mobile">Web & mobile</a> &nbsp;·&nbsp;
  <a href="#technical-toolkit">Technical toolkit</a> &nbsp;·&nbsp;
  <a href="#experience">Experience</a>
</p>

## About me

I'm **Dmitry Grinenko**, a **Fullstack Developer** based in Minsk, Belarus. I work across **web applications, React Native mobile apps and browser-based slot games**, with TypeScript connecting the frontend, application logic and backend.

My commercial experience at **Baldmonkey LTD** covers client and server development, application maintenance, bug fixes and test data preparation. Alongside this experience, my portfolio includes mobile applications, NestJS APIs and independent game projects. I have also worked on casino-related projects.

In game development, I build the layer that brings the game to life: **reel behaviour, bonus sequences, character animation, responsive controls and round-state handling**. My current slot projects combine React and TypeScript with **PixiJS, Spine and GSAP**, depending on the rendering approach. I pay particular attention to how gameplay, animation and server events fit together.

I also use **Python for slot mathematics and development tooling**: calibrating outcome weights, checking RTP and payout distributions, and automating release preparation and validation. In Alpha Rooster and Pirate Abyss, this complements the TypeScript game frontend and generation pipeline.

Across web and mobile projects, I work with component-based interfaces, REST APIs, authentication, relational data and local persistence. My portfolio includes fitness tracking, field-task workflows and a rewards-platform prototype, with source code and implementation notes available below.

**Open to remote junior and middle-level opportunities**, including full-time, part-time and project work in web development, mobile development and iGaming.

[LinkedIn profile](https://www.linkedin.com/in/%D0%B4%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B9-%D0%B3%D1%80%D0%B8%D0%BD%D0%B5%D0%BD%D0%BA%D0%BE-95ba4b35b/)

## Game development

Three slot projects with distinct visual worlds and shared engineering concerns: responsive presentation, animation timing and a consistent game state. The screenshots show the actual interfaces. Source releases document each project's current capabilities and setup requirements.

**What I work on in slot development**

- **Game flow:** reel states, win presentation, Wild multipliers, free spins and bonus transitions, according to each game's mechanics.
- **Animation systems:** Spine characters and symbols, idle/drop/win states, reactions and coordinated scene transitions.
- **Server integration:** RGS response validation, result presentation, unfinished-round recovery and replay handling.
- **Python mathematics and tooling:** outcome-weight calibration, RTP validation, payout-distribution checks and release packaging in the Alpha Rooster and Pirate Abyss pipelines.
- **Responsive interfaces:** desktop and portrait layouts, touch controls, loading and welcome screens, sound settings and reduced-motion support.
- **Verification:** unit tests for game logic and integration behaviour, TypeScript checks and production builds. The three published source snapshots pass **232 tests** in total.

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/DimaGrinenko/alpha-rooster"><img src="assets/alpha-rooster.jpg" alt="Alpha Rooster game interface in a golden barn" width="100%" /></a>
      <h3><a href="https://github.com/DimaGrinenko/alpha-rooster">Alpha Rooster</a></h3>
      <p>A 5 × 3 cartoon barn slot with 20 paylines, a Spine-animated rooster and four bonus presentations. Includes a local demo library and round recovery.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Vite</code> <code>Spine</code></p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/DimaGrinenko/pirate-abyss"><img src="assets/pirate-abyss.jpg" alt="Pirate Abyss game interface with an underwater pirate world" width="100%" /></a>
      <h3><a href="https://github.com/DimaGrinenko/pirate-abyss">Pirate Abyss</a></h3>
      <p>A 6 × 5 pirate slot with expanding Wilds, free-spin features, an animated captain and Canvas/WebGL presentation. Includes responsive controls and an asset inspection gallery.</p>
      <p><code>React</code> <code>PixiJS</code> <code>Spine</code> <code>GSAP</code></p>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/DimaGrinenko/ashen-pact"><img src="assets/ashen-pact.png" alt="Ashen Pact local demo with two raven characters" width="100%" /></a>
      <h3><a href="https://github.com/DimaGrinenko/ashen-pact">Ashen Pact</a></h3>
      <p>A 5 × 4 dark-fantasy slot with two animated raven keepers, seal-wheel reveals and three ritual bonus tiers. Includes a local demo engine and replay handling.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Vite</code> <code>Spine</code></p>
    </td>
  </tr>
</table>

## Web & mobile

### [IRON MIND AI](https://github.com/DimaGrinenko/irond_mind_ai)
**Fitness application with a mobile client and a NestJS API.**

Workout and set logging, training programs, nutrition tracking and progress statistics. The mobile app includes local SQLite storage; the API includes authentication and trainer/admin roles.

`React Native` `Expo` `TypeScript` `Zustand` `SQLite` `NestJS` `Prisma`

### [Field Tasks](https://github.com/DimaGrinenko/react-native-test-task)
**Task management for mobile workflows.**

Task creation and editing, search, sorting, attachments, history, maps and local notifications. Local persistence and a REST synchronization prototype support offline workflows.

`React Native` `Expo` `TypeScript` `Zustand` `AsyncStorage` `json-server`

### [BoostLink](https://github.com/DimaGrinenko/-BoostLink-App)
**Rewards-platform prototype with a mobile UI and a separate backend API.**

Quest, wallet and marketplace screens currently use mock data. The backend includes authentication, quest review, wallet operations, marketplace workflows and payment integration handlers.

`React Native` `Expo` `NestJS` `PostgreSQL` `Prisma` `Redis` `BullMQ` `Socket.IO`

<details>
<summary><strong>More web and backend projects</strong></summary>

- [Aroma House](https://github.com/DimaGrinenko/shop-catalog): a responsive HTML/CSS coffee catalog and landing page.
- [NestJS projects](https://github.com/DimaGrinenko/nestjs-projects): a book-catalog API using NestJS, TypeORM, PostgreSQL and Swagger.
- [AI Assistant](https://github.com/DimaGrinenko/Ai-assistant-app): a mobile assistant prototype with chat sessions, tasks and a NestJS API.

</details>

## Technical toolkit

- **Languages:** JavaScript, TypeScript, Python, SQL.
- **Frontend:** React, Vue.js, HTML, CSS.
- **Mobile:** React Native, Expo, Zustand, AsyncStorage, SQLite.
- **Backend:** Node.js, NestJS, Express, Prisma.
- **Data:** PostgreSQL, Microsoft SQL Server, Redis.
- **Game presentation:** PixiJS, Spine, GSAP.
- **Game mathematics and tooling:** Python, NumPy, SciPy, outcome distributions and RTP validation.
- **Workflow:** Git, Docker, Linux, CI/CD, Vite.

## Experience

**Fullstack Developer · Baldmonkey LTD**<br />
February 2024 to December 2025

Developed and maintained the client and server sides of a web application, fixed bugs and prepared test data.

**Education:** Information Systems and Technologies, MITSO International University. Expected graduation: 2027.

**Languages:** Belarusian (native), Russian (C2), English (B1).

<p align="center"><sub>Web applications · Mobile products · Animated browser games</sub></p>
