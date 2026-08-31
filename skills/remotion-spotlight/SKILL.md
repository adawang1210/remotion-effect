---
name: remotion-spotlight
description: Focus attention on a meaningful UI target in a Remotion product demo using a moving rounded spotlight cutout and dimmed surrounding interface.
---

# Remotion spotlight

Use a rounded bright cutout to direct attention through a dense interface.

- Frame only meaningful UI: status cards, controls, or the result of an action. Never settle on blank page space.
- Dim the exterior with one overlay or oversized box-shadow; preserve the highlighted content at normal brightness.
- Interpolate the cutout position and size between targets, clamping it to the visible recording bounds.
- When the recording is zoomed, transform the spotlight with the same scale and origin so it remains aligned.
- Keep the rounding close to the target component’s own corner radius. A dim level around 50–60% is usually sufficient.

First inspect the [reference animation](../../previews/spotlight.gif), then follow [the reproduction prompt](references/reproduction-prompt.md). Treat the reference's motion beats—not its dashboard copy or colours—as the requirement.
