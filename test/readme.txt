WorldGuard Custom Flags V. 1.7

Description
===============
WorldGuard Custom Flags allows modders to create, set and get custom flags on WorldGuard regions. It is currently under development and maybe a little buggy. As a user you just need to download this if a plugin requires it, it does not do anything on its own.

If your plugin uses this plugin please comment on this or send me a PM

It automatically uses the same database as WorldGuard (if specified), but you need to create the tables (2) manually using an included sql-file.

WorldGuard Custom Flags is also available on github

The following flag types are supported:
BooleanFlag 
CommandStringFlag 
DoubleFlag 
EntityTypeFlag 
EnumFlag 
IntegerFlag 
LocationFlag (better use CustomLocationFlag, it does not produce error messages if WorldGuard uses a database as this does) 
SetFlag (better use CustomSetFlag) 
StateFlag 
StringFlag 
VectorFlag (better use CustomVectorFlag)

Setup
===============
To install WorldGuard Custom Flags simply drop the jar file and (optional) the WGCustomFlags folder into your plugins folder.
If you do not copy the WGCustomFlags folder it will be created automatically.

License
===============
This product is published under the conditions of the GNU general public license version 3. For more information read LICENSE.txt.

