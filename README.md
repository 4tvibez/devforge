# FORGE — Systems Lab

FORGE is an original, dependency-free browser systems laboratory built to demonstrate advanced front-end engineering without APIs, paid services, frameworks, or build tooling.

## Engineering features
- Reactive Store + EventBus state architecture.
- Canvas-rendered service topology with pan, zoom, drag and selection.
- Request tracing with animated dependency pulses.
- Runtime health, load, capacity, latency and throughput telemetry.
- Keyboard-first command palette.
- Local persistence through localStorage.
- JSON snapshot export.
- Responsive mobile/desktop UI.
- No API, backend, framework or package dependency.

## Controls
- Space — simulate a request
- Ctrl/Cmd + K — command palette
- R — reset
- + / - — zoom
- Drag nodes — reposition
- Click node — inspect
- Mouse wheel — zoom around cursor

Open index.html directly. It is static and deployable to GitHub Pages or any static host.

Architecture:
Store → EventBus → GraphEngine → Renderer → Telemetry → UI

Built with HTML, CSS, vanilla JavaScript and Canvas.
