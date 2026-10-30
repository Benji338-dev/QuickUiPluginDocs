## 🧱 Texture Frame

how to use Texture tools : 

1. open the texture frame of the plugin.
2. You will see this window :.


 ![TextureFrame](textureframe.png)

3. select an ImageLabel/ImageButton.
4. Click on the texture you want to add.

### Options

Before clicking a texture, you can choose how it is displayed:

| Option | Description |
|---|---|
| **Scale Type** | **Stretch**, **Crop**, **Fit** or **Tile**. The default is **Tile**. |
| **Tile Size** (X / Y) | The size of one tile, in pixels (default `100` x `100`). Only used with the **Tile** scale type. |
| **Image Transparency** / **Image Color** | Coming soon. |

When you click a texture, it is applied to **all selected** `ImageLabel` and `ImageButton` (the `Image` and `ScaleType` properties, and `TileSize` for Tile). You can undo it with `Ctrl + Z`.
