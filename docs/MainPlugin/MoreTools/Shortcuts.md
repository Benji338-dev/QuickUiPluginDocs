## ⌨️ Shortcuts

The **Shortcuts and more** window lets you turn on or off the helpers that QuickUi+ displays on your canvas.

![Shortcuts](../../../images/more-tools-overview.png)

Open it with the **S** button of the side toolbar.

| Toggle | Description |
|---|---|
| **Rotate button** | Shows the [Rotate](Rotate.md) handle on the selected element. |
| **Center** | Shows the [Center](Center.md) handle on the selected element. |
| **QuickAction** | Shows the QuickAction panel next to the selected element. |
| **Vectors** | Shows the **Add Vector** button of the [Vector Creator](../Vector.md). |

All the helpers are **enabled by default**, and your choices are saved.

### QuickAction

QuickAction is a small panel with 4 quick actions that depend on the type of the selected element. Click the buttons to toggle them.

| Selected element | Actions |
|---|---|
| **Text** (`TextLabel`, `TextButton`, `TextBox`) | Background, TextScaled, Fill to parent, Text align |
| **Image** (`ImageLabel`, `ImageButton`) | Background, Fit / Crop, Fill to parent, Keep ratio |
| **Frame** / **ScrollingFrame** | Background, Fill to parent, Clip content, Fit to content |

What they do:

- **Background**: shows or hides the background.
- **Fill to parent**: the element takes the whole size of its parent.
- **TextScaled**: toggles `TextScaled`.
- **Text align**: switches the text between left, center and right.
- **Fit / Crop**: switches the image `ScaleType`.
- **Keep ratio**: adds or removes a `UIAspectRatioConstraint` with the current ratio.
- **Clip content**: toggles `ClipsDescendants`.
- **Fit to content**: toggles `AutomaticSize`.
