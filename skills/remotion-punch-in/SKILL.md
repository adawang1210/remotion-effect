---
name: remotion-punch-in
description: Add a target-centred punch-in zoom to a Remotion product demo to make a small UI interaction legible, then settle back to the destination state.
---

# Remotion targeted punch-in

Use a short zoom only when it improves legibility or makes an interaction’s consequence clear.

- Set `transform-origin` to the activated target, rather than the screen centre.
- Ease from 1× to roughly 1.35–1.55× over 20–42 frames, then hold long enough to read.
- Return to 1× before the scene ends or crossfade to the resulting destination UI.
- Zoom the source at its decode/layout size when possible to avoid softening a raster recording through repeated CSS scaling.
- If an overlay follows the UI, derive its coordinates from the same scale and origin.

First inspect the [reference animation](../../previews/punch-in.gif), then follow [the reproduction prompt](references/reproduction-prompt.md). Treat the reference's motion beats—not its dashboard copy or colours—as the requirement.
