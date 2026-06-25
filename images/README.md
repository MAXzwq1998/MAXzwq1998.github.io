# Homepage diagram assets

These PNGs are referenced at fixed URLs. Keep the same filenames when replacing.

## Target dimensions (HiDPI)

Current committed file is **1024px wide**, which can look soft when displayed large on HiDPI screens.

**Recommended export**

| File | Minimum width (px) | Notes |
|------|--------------------|--------|
| `integrated-selection-diagram.png` | **2048** (ideal **2048–2400**) | Preserve aspect (~16:9.5); PNG for crisp text |

Export from the original vector/source at **2×** the max CSS width (e.g. `max-w-[512px]` display → **≥1024px** is 1:1 at DPR2; **2048px** is ideal for headroom).

Avoid browser-only upscaling of 1024px sources; re-export from design files for sharp labels.
