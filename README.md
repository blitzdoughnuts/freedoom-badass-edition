# BadAGMss

One of the most **BAD\*SS** Freedoom mods on Earth. Forked from Freedoom: Badass Edition. Made for ZDoom-based source ports.

Changes from upstream FDBE:
- No build system; you just run the mod directory as if it were a .wad
- All non-free material removed, so the mod is now properly FOSS
- Rewritten Decorate code, mainly to reduce wasteful code
- DB Shotgun sprites are included in the mod, so the weapon can be used in Phase 1
- The Polaric Energy Cannon is now a Polaric Energy Blaster that fires several projectiles at once, quite fast too.
- The SKAG 1337 is now the SFAG 911. It's the nuclear weapon, mind you.
- New BADASS30

## FAQ

### Why make this fork?
I like Freedoom, and I like mods made for it. What I don't like is when they incorporate proprietary content, going against free culture. This fork is made to both optimize and liberate the mod, so it is both cleaner and libre

### You removed the build system! How can we play?
Simple, download the source repository and load it like a mod. Drag and drop it onto GZDoom, or use the ``-file`` parameter on the folder. The Deutex and Python buuld systen FBE uses is not only bloated (due to Python), but straight-up unnecessary because GZDoom and ZDoom-like ports can load folders as mods. Hell, *PK3 files are basically just ZIP files.* It's not rocket science.

## License

BadAGMss is released generally under the MIT License.

The project makes use of the following assets with different licensing:
    - Freedoom project (BSD 3-Clause)
    - Freedoom: Bad\*ss Edition (MIT license, proprietary assets not taken)

The rewritten Decorate code in ``decorate.txt`` is licensed under CC0.
