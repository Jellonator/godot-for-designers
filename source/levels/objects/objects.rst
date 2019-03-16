.. _objects:

Objects
=======

Levels will often times need more than just tiles to be a complete level. For
example, levels may have enemies, collectibles, NPCs, puzzles, etc. In Godot,
objects are represented by scenes, and can be placed in a level by instancing
them.

Finding Objects
---------------

Typically, projects will be organized so that objects can be easily located.
For example, a player object might be found in a folder named 'Objects/Player',
while a Bat enemy might be found in 'Objects/Enemies/Bat'. A level-specific
object could also be placed in something like 'Levels/Beach/Shell'. If you have
trouble finding what you need, don't be afraid to ask someone more familiar
with the project structure.

Here is an example of a project layout:

.. image:: file_tree.png

Notice that Menus are also organized into their own folders. Some programmers
might also have folders named 'Global' or 'Lib' for storing commonly used
scripts.

Creating Objects
----------------

For some cases, you may need to create your own objects. For example, if you
want to have a recurring background object such as a tree or a water fountain,
or something that the player can walk on like a bookshelf or a shipping crate.


Placing Objects
---------------
