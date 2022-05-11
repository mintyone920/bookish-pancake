Majority of thing of bevy are in `bevy::prelude`
Main part of bevy is `App` structure.
Initialize an App with `new()`.
Run it with `run()`.

For default app, you need `.add_plugins(DefaultPlugins)`

That will create blank window.
With resources modify the blank window.
`.insert_resource(x)`
x:
`ClearColor()` changes clear color
`WindowDescriptor {}` changes window parameters

 Loading a tileset with a system:
you need a mutable Commands parameter for function for it to be a system, to create the system use [[Loading tileset]]

Then you can spawn a player (sprite) [[Spawning a sprite]]
The same for a camera [[Spawning a camera]]
