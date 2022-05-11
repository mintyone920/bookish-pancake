To load a tileset, you need access to resource `Res<AssetServer>`,
then using a texture atlas you map the tiles `ResMut<Assets<TextureAtlas>>`,
function  `TextureAtlas::from_grid` is used to map,
when the mapping is done add the created atlas to atlas parameter.
To use the sprites we need a `Handle`,
that is achieved with inserting a new resource to the world, that has the handle `commands.insert_recource(struct(handle))`,