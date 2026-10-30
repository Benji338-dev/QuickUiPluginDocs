## 🔄 Convert

Changes the class of a UI element without losing its properties or its children. For example, turn a `Frame` into an `ImageLabel`.

![Convert](../../../images/more-tools-overview.png)

### How to use

1. Select one or more UI elements.
2. Open **Convert** in the side toolbar (the ↗ button).
3. Click the class you want.

### Available classes

`Frame`, `ImageLabel`, `ImageButton`, `TextLabel`, `TextButton`, `TextBox`, `ScrollingFrame`, `ViewportFrame`.

### What is kept

- The common properties: Name, Size, Position, AnchorPoint, Rotation, background color and transparency, border, ClipsDescendants, Visible, ZIndex, LayoutOrder, SizeConstraint, Active, Selectable, AutomaticSize.
- The **text** properties when you convert between text classes (Text, font, size, color...).
- The **image** properties when you convert between image classes (Image, color, ScaleType...).
- **All the children** (UICorner, UIStroke, other elements...) are moved to the new element.

The new element replaces the old one and stays selected. You can undo it with `Ctrl + Z`.

> Properties that do not exist in the new class are simply not copied. Only `GuiObject` elements can be converted.
