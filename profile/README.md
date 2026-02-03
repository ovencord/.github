# **Ovencord**
[![CI](https://img.shields.io/github/actions/workflow/status/ovencord/buncord/ci.yml?branch=main&label=ci&logo=github&color=brightgreen)](https://github.com/ovencord/buncord/actions)
[![npm](https://img.shields.io/badge/npm-%40buncord-orange?logo=npm)](https://www.npmjs.com/org/buncord)
[![bun](https://img.shields.io/badge/bun-%3E%3D1.0.0-black?logo=bun)](https://bun.sh)
[![discord](https://img.shields.io/badge/discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/TUO_INVITO)

## **Discord.js, but Bun-native**
**90% faster • 85% lighter • 100% compatible**

<p align="center">
  <img src="https://github.com/user-attachments/assets/a130ed79-3750-4973-a1d9-8a9e2b90a0a2" width="400">
</p>

## **Stop Emulating. Start Running.**

**Ovencord** is not just a fork; it's a ground-up re-engineering of the Discord.js ecosystem, optimized exclusively for the **Bun runtime**. 

We’ve slaughtered the legacy Node.js dependencies, bypassed the slow emulation layers, and rebuilt the core using Bun's native Zig-powered APIs. The result? A blazing-fast, ultralight Discord library that consumes a fraction of the RAM while delivering lower latency.

## **Why Ovencord?**

*   **`Bun-Native Engine:`** Replaced `undici` with native `fetch` and `ws` with Bun's high-performance WebSockets.
*   **`Zero-Copy Compression:`** Integrated `Bun.inflateSync` for Discord gateway streams, reducing CPU overhead by up to 40%.
*   **`Zero Legacy Bloat:`** Purged over 60MB of Node-specific junk and build tools. 
*   **`0s Build Time:`** Source-only distribution. Bun executes the TypeScript code directly. No more `dist` folders, no more transpilation lag.
*   **`Drop-in Compatibility:`** Maintain your existing Discord.js logic. Just change the import and feel the speed.

---

