# Homepage image assets

The homepage is wired to the PNG files below. These are the current production assets used by `index.html`.

| Purpose | Current file | Recommended replacement |
| --- | --- | --- |
| Personal portrait | `profile/jiaqi-yuan-portrait.png` | 960 × 1166 px |
| Ant Group logo | `companies/ant-group-logo.png` | 179 × 78 px |
| AgenticGEO figure | `publications/agenticgeo-overview.png` | 1226 × 516 px |
| DyG-RAG figure | `publications/dyg-rag-overview.png` | 1492 × 783 px |

## Replacing an asset

You can either:

1. Export the final image as PNG using the same filename, then overwrite the placeholder; or
2. Add another PNG with a new filename and update the matching `src` in `index.html`.

Keep images optimized for the web. A useful target is under 500 KB for the portrait and under 350 KB for each paper thumbnail. Do not stretch a logo into a fixed aspect ratio; a transparent-background PNG is preferred.
