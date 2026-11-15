# TrueHelm: Realistic Shipping Lanes (`v1.9.4`) — Official Game Download

Official Windows 10/11 PC & OpenXR VR distribution repository for **TrueHelm: Realistic Shipping Lanes** (`v1.9.4`).

---

## Direct Download (`v1.9.4` — Windows 10 / 11 64-bit PC & OpenXR VR)

| Option | Direct Download Link | Details |
| :--- | :--- | :--- |
| **Windows 10 / 11 — Desktop Launcher (Recommended)** | [**Download `TrueHelmLauncher.exe` (`0.2 MB` — No `.zip` Extraction Required!)**](https://github.com/jbender083-prog/TrueHelm-Game-Download/releases/latest/download/TrueHelmLauncher.exe) | Zero-dependency single-file installer, 1-click auto-updater & PC / OpenXR VR launcher |
| **Windows 10 / 11 — Portable Archive (`.zip`)** | [**Download `TrueHelm_Windows_Playable.zip`**](https://github.com/jbender083-prog/TrueHelm-Game-Download/releases/latest/download/TrueHelm_Windows_Playable.zip) | Standalone cooked Unreal Engine 5.8 DirectX 12 build (extract & run `RealisticShippingLanes.exe`) |

---

## What's New in `v1.9.4`

- **Lossless 60+ FPS Multi-Boat Ultra Water & Wake Optimization (`80+ FPS` Side-by-Side)**: Multi-core `UOceanFastDynamicMeshComponent` RHI vertex stream uploads, zero procedural ray-tracing BLAS rebuilds, pre-allocated `18,000` 3D foam pool, and tightened multi-ship Kelvin wake culling with 100% Ultra visual fidelity preserved.
- **Captain Profile Username & Company Name Editing Fix**: Fixed per-frame auto-refill when deleting characters in `Edit Captain Profile`, added 1-click `[ CLEAR ]` buttons on both `1. USERNAME` and `2. COMPANY NAME`, smooth `Backspace` hold-repeat, `Ctrl+A/C/X/V/Backspace` shortcuts, and viewport focus lock.
- **9-Bug Gameplay, Multiplayer & Co-Op Sweep**: Eliminated Firebase/UDP rubber-banding, fixed shared-hull Co-Op passenger physics & wake deduplication, accurate Commission `%` vs. Even `1/N` splits, remote container sync across all 8 container/reefer/ConRo vessels, host kick persistence, and full long-haul/express voyage save/load restoration.
