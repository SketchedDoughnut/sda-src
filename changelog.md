**This changelog was started at 5/15/24 at 23:50 UTC**

# 5/15/24
**v.1.0.0**

Moved some files around, optimized code, and fixed some bugs. The rhythm game is still disabled until further notice. 
- commit label: [71c47ef](https://github.com/SketchedDoughnut/SDA-src/commit/71c47efb48474a1b1592015df1800b3d99122c8c)

**v1.0.1, v1.0.2, v1.0.3**

Implementing the FOMX system, a small patch-agent that grabs data from its own repository.
- commit label: [55784fd](https://github.com/SketchedDoughnut/SDA-src/commit/55784fdc090d7677c69eb0d199cb0b241efba0e5)

# 5/16/24
**v1.0.4**

Added copying for files not in the everything directory (such as LICENSE, this changelog, README, etc) to both full-redo.exe as well as fiesta-modern.exe (this has been updated on the SDA repository too).
- commit label: [feb7522](https://github.com/SketchedDoughnut/SDA-src/commit/feb752286b83275c9ac4f12fffad8137e2714c05)

# 5/17/24
**v1.0.4-bugfix, v1.0.4-bf1**

I did a lot of updates, such as fixing FOMX and other stuff. I am leaning decently heavily on the FOMX systems to patch updates after install, however the rhythm game is not working.
- commit label: [b1cc712](https://github.com/SketchedDoughnut/SDA-src/commit/b1cc71224b90f79a5c4c4186ea8873eef4ccfec3)

# 5/18/24
**v1.0.5, v1.0.5-bf0**

I released some updates for Conways Game Of Life, such as letting people import / export maps. I also included a default map, the glider gun. More of these will be released later.
- commit label: [b8bf33c](https://github.com/SketchedDoughnut/SDA-src/commit/b8bf33c3f03c738cb92c1aa848fddab0a29c54af)

# 5/18/24
**v1.0.6**

Updates attempted, breakdowns occured, rollbacks commited.
- commit label: [8e0b39a](https://github.com/SketchedDoughnut/SDA-src/commit/8e0b39a880cc2de35f659d0a58e0ec88ed1f94db)

# 5/19/24
**v1.0.6-feature.0, v1.0.6-feature.0-patch.0**

Re-enabling the cmd_reader on FOMX, as it seems to now be working.
- commit label: [30561ac](https://github.com/SketchedDoughnut/SDA-src/commit/30561acf7ebce1d78b38b85ad2830859810846f5)

# 6/28/24 (1:16am)
**v1.0.7, v1.0.7-bugfix.0**

For v1.0.7, read information [here!](https://github.com/SketchedDoughnut/SDA-src/releases/tag/v1.0.7) <br>
For v1.0.7=bugfix.0, read below. <br>
This update fixes an issue where the folder "universe/" was not being created by full-redo, as well as fiesta-modern. Some other systems were fixed, as well. 
- commit label: [71988f6](https://github.com/SketchedDoughnut/SDA-src/commit/71988f6ed731eb0e0d3b34bc3efbfa3492159732)

# 6/29/24 (1:48am)
**v1.0.7-feature.0**

This update includes some new features in fiesta-modern, such as an easier user interface for installing Python, as well as a new propagator tool for FOMX. This allows it to spread updates from the template files for the elevator and the crash handler to all the other files that are duplicates. This makes updates way more easier for me!
- commit label: [19fd827](https://github.com/SketchedDoughnut/SDA-src/commit/19fd8270e6c9e6688176e94a1bd282932b5f8170)

# 6/29/24 (4:29pm)
**v1.0.8, v1.0.8-ohno**

This update includes a lot! The installer, as well as all of the game systems can now have spaces in their file paths. As well as that, the installer requests admin access upon launch, and so does fiesta.exe. This allows them to function properly inside of program files, which makes installation somewhat easier for users!
- commit label: [7be5cc1](https://github.com/SketchedDoughnut/SDA-src/commit/7be5cc1fdac25d05118ef3933f0bbd911b035fe1)

The "ohno" addition update fixes file_list.json, and recompiles full-redo.exe. It is titled "ohno" because, well, oh no.
- commit label: [447c39e](https://github.com/SketchedDoughnut/SDA-src/commit/447c39eea07007d2d7665470f34c4102139f1149)
