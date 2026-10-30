## 🔍 Zoom and Nudge (Precision tool)

The **Precision tool** (the ▦ button of the side toolbar) contains two tools: **Zoom** and **Nudge**.

![Precision tool](../../../images/more-tools-overview.png)

### Zoom

Scales a whole interface up or down around a point, to resize everything at once.

1. Click **Place**, then click in the viewport where the zoom should be centered.
2. Set the **Zoom** percentage (from `0` to `500`, `100` is the original size).

The sizes, positions and text sizes of the UI elements, but also their strokes, corners, paddings and list / grid spacing, are scaled together. **clear** resets the chosen point.

> The Zoom tool is still being improved and may be temporarily unavailable in some versions of the plugin.

### Nudge

Moves the selected element by a precise number of pixels.

1. Select a UI element.
2. Type the distance in the box (default: `5`).
3. Click an arrow (left, right, up, down).

The element's `Position` offset is changed by that distance, which is more precise than the mouse. It works with several elements at once, and you can undo it with `Ctrl + Z`.
