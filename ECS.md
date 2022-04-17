E -> entity
C -> component
S -> system

Components are like structures that define set of data which entity can use. For example: camera_entity uses camera_component and transform component.

Entities are objects with defined data.

Systems use components that modify entity data.

In bevy plugins define sets of systems.
Systems use resources as parameters.