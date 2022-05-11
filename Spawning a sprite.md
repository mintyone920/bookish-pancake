To use the loaded tileset you need a resource with the handle to loaded sprites `Res<AsciiSheet>`,
Then you need to specify the texture atlas sprite,
and spawn using a bundle `SpriteSheetBundle` where you specify the sprite, handle, transform.
By spawning a bundle you can add resources for that bundle, like name