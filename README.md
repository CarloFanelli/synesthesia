# synesthesia

> **Work in progress** — being built across 4 flight legs (spring 2026).
>
> Audio-reactive 3D particle visualizer controlled by hand gestures.
> Stack target: MediaPipe (vision) + Gibber (audio) + Three.js (3D) + GLSL shaders.

Build guide: [planeProjects/WORKBOOK.md](https://github.com/CarloFanelli/planeProjects) (umbrella repo).

Depends on the `handmouse` module from [CarloFanelli/handMouse](https://github.com/CarloFanelli/handMouse).

## Local setup (for offline dev)

You need to provide the Gibber bundle locally — it is **not** included in the repo (not redistributed). Either symlink to your local clone or copy the playground assets:

```bash
# Option A — symlink to a local gibber-cc/gibber clone
git clone https://github.com/gibber-cc/gibber.git ../gibber-vendor
ln -s ../../gibber-vendor/playground public/gibber

# Option B — npm install + run (Gibber CDN, online only)
# (TBD: setup.sh that downloads the bundle to public/gibber/)
```
