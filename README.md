# 🐉 REnderAPI

A rendering API for Node.js terminals.

REnderAPI is an open-source rendering library designed to bring graphics, images, animations and interactive interfaces to the terminal.

The name is a little joke: Render + Ender. 🐉

✨ Features

🚧 REnderAPI is currently under development.

* 🖥️ Terminal rendering
* 🎨 ANSI colors and graphics
* 🖼️ Image rendering
* 🎞️ Frame-based animations
* 🎬 Flipbook animation system
* 🧩 Extensible renderer architecture
* ⚡ Designed for Node.js
* 🔌 Support for external rendering libraries

🎯 Goals

REnderAPI aims to provide a simple abstraction over terminal rendering while remaining flexible enough for more advanced applications.

The project is being developed primarily for the Redstone OS (RSOS) ecosystem, but REnderAPI is designed to be useful as an independent library.

🚀 Example
```js
import { Renderer } from "renderapi";
const renderer = new Renderer();
renderer.text("Hello, world!");
```

More examples will be added as the API develops.

🎞️ Flipbook

One of the main goals of REnderAPI is to support frame-based animations directly in the terminal.

```js
const animation = new Flipbook({
    frames: [
        frame1,
        frame2,
        frame3
    ],
    fps: 30
});
await animation.play();
```

The long-term goal is to make it possible to transform graphical content into terminal-renderable frames.

🧱 Architecture

REnderAPI is designed around a modular architecture:

```
REnderAPI
├── Core
├── Terminal Renderer
├── Image Renderer
├── Animation System
└── Flipbook
```

External libraries may be used internally for tasks such as image decoding, video processing and terminal capabilities.

🟥 RSOS

REnderAPI is being developed as part of the Redstone OS ecosystem, a project focused on Minecraft server management, automated clients and related tooling.

However, REnderAPI is not limited to RSOS and can be used independently.

📦 Status

Early development.

The API is unstable and may change considerably before the first stable release.

📜 License

License information will be added before the first stable release.

⸻

REnderAPI — Render beyond the screen. 🐉
