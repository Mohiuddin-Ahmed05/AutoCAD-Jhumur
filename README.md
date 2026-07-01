# Project 55 - AutoCAD Closed-Traverse Assignment

**Student:** Jhumur Chandni  
**Software:** AutoCAD 2027  
**Save name:** `Chandni_Project55_06-30-2026.dwg`

Draw two closed traverses — **Figure 11-3c** and **Figure 11-4e** — set units, layers,
dimensions, and north arrows; determine segment **AB** and the enclosed **area** of 11-4e.

---

## TL;DR — how to finish

1. Open a `.dwg` from **`3-Determine_Approach/`** in AutoCAD and eyeball it (or view the `_Preview` PNG).
2. Pick the approach to submit (see the two options below).
3. Submit **only that `.dwg`** — not the previews, `.txt`, `.dxf`, or docs.
4. Once submitted, add that `.dwg` to **`4-Final_Submission/`** as the final record.

---

## Folder map (numbered = work order)

| Folder | What's inside | Use it to… |
|---|---|---|
| `1-Assignment_Docs/` | Assignment brief, the two figures, textbook PDF, `outline.txt` (plan), `autocad-guide.txt` (full how-to) | Understand the requirements + the overall plan |
| `2-Outlined_Strategies/` | Both candidate builds, each as: `1-…Outline` (step-by-step), `2-Convert_dxf_to_dwg` (the `.dxf`), `3-Preview_Final_Output` (PNG) | Review how each version was built; grab the `.dxf` to (re)convert |
| `3-Determine_Approach/` | The converted **`.dwg`** for each approach + a preview | Compare the two and decide which to submit |
| `4-Final_Submission/` | *(empty until you submit)* | Once an assignment is submitted, add the submitted `.dwg` here as the final record |

---

## The two versions (they differ ONLY in Figure 11-3c leg lengths)

Figure 11-3c gives azimuths but **no lengths**, so each version sources them differently.
Figure 11-4e is **identical** in both.

| Version | Folder name in `3-Determine_Approach/` | 11-3c lengths | Status |
|---|---|---|---|
| **A** | `Fig_Scales_Length_with_Azimuth_Angles` | Scaled/measured from the figure + given azimuths | **Complete** (recommended) |
| **B** | `Uses-Only_Azimuth_Angles_Lengths_Unconfirmed` | Given azimuths only; hand-measured lengths, **one leg unconfirmed (~444′ est.)** | Needs that leg re-measured |

---

## Key drawing facts (both versions)

- **Units:** Engineering (feet-inches). Type the **foot mark** on lengths (`@245'<129`, not `@245<129`).
- **Angles:** Decimal degrees, **North** base + **Clockwise** (azimuths read directly; `DIST` returns bearings).
- **Layers:** `TRAVERSE`, `NORTH`, `DIM-ANG`, `DIM-LIN`, `TEXT`.
- **Figure 11-4e results:** segment **AB = 215′-6″, bearing N 42° E**; **area = 877,207 sq ft** (~20.14 ac).
- North arrow at every vertex; azimuth arcs + labels; leg-length callouts.

---

## Notes

- **`.dxf` vs `.dwg`:** the `.dxf` files (in `2-Outlined_Strategies/…/2-Convert_dxf_to_dwg`) are the
  source drawings; the `.dwg` files (in `3-Determine_Approach/`) are the AutoCAD-converted versions.
  To re-convert: open a `.dxf` in AutoCAD → **Save As → AutoCAD Drawing (\*.dwg)**.
- **Filenames repeat** (`Chandni_Project55_06-30-2026.*`) across versions — the *folder* tells them apart.
- Previews are labeled by version: `Version_A_Preview.png` / `Version_B_Preview.png` in `2-Outlined_Strategies/`,
  and `Project55_Version_A.png` / `Project55_Version_B.png` in `3-Determine_Approach/`.
