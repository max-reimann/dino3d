# 🦖 T-Rex Run 3D (German/Deutsch)
Spiele das Spiel hier: https://max-reimann.github.io/dino3d/low.html  
Alt. Version mit höchsten Qualitäts-Einstellungen für "High-End"-PCs: https://max-reimann.github.io/dino3d/

# Beschreibung
T-Rex Run 3D ist ein, als Experiment erstelltes, ThreeJS WebGL-Spiel.  
Alle Grafiken wurden mithilfe der Software "Magica Voxel" von Hand erstellt, sodass das allgemeine Spielgefühl und das Erscheinungsbild dem, des ursprünglichen 2D-Spiels, entsprechen.

Diese deutsche Übersetzung enthält auch die Maus-/ und Touchscreen-Unterstützung.

Original-Version des Autors: https://github.com/Priler/dino3d  
Version mit Maus-/ und Touchscreen-Unterstützung: https://github.com/Misheus/dino3d

*Der Code wurde NICHT extra aufbereitet und wird "so, wie er ist" bereitgestellt. Es ist sehr viel überflüssiger Code enthalten und es könnten noch eine Menge Verbesserungen vorgenommen werden.*

# Screenshot
![T-Rex Run 3D](https://i.imgur.com/fESLYlF.png)

# ToDo
https://trello.com/b/Pt4FSqOi/t-rex-run-3d

## Changelog
- Update 1
  - New interface
  - Infinity jumping while holding jump button
  - Jumping buttons now is: Space, Arrow Up, W
  - Bend down buttons now is: Arrow Down, S, Ctrl
  - Restart on game end
  - Fixed bug when a player could switch active tab and collisions ingame was not working
  - Fixed bug with not fully loaded textures before game start
  - Fixed bug when high scores continued to count even after game end
  - Fixed hitbox
  - Fixed ability to jump from bend down position
  - Fixed disappearing ground textures
  - Other minor bug fixes

- Update 2
  - Voxel landscape added
  - Palm trees has been removed, instead there is scorpions, skulls, etc
  - UI is now fully in pixel art style
  - Load screen added
  - New dino reaction on collisions
  - W & S keys was removed
  - Nature Manager & Enemy Manager was fully rewritten for better performance and new feautures
  - "Black screens" bug fixed
  - High jumps bug fixed
  - Scores display fixed
  - Moving objects stuttering fixed (never use .splice() again :3)

## Credits
https://threejs.org/ - WebGL 3D Library  
https://ephtracy.github.io/ - Free lightweight 8-bit voxel art editor  
https://github.com/daishihmr/vox.js/ - MagicaVoxel *.vox file parser and Three.js mesh builder  
https://github.com/goldfire/howler.js/ - Audio library  
https://github.com/creativelifeform/three-nebula - WebGL based particle system engine for three.js  
https://github.com/addyosmani/visibly.js/ - Page Visibility API shim

## Autor
(C) 2020 Abraham Tugalov.
http://howdyho.net

## Mitwirkende
- Aidar Ayupov <https://github.com/preposition17> & Vildan Safin <https://github.com/Enigma228322> for inspiration about 3D models
- Rifat Fazlutdinov <https://github.com/Rifat-Fazlutdinov> for telegram bugreport bot
- Arnur Bekbolov <https://vk.com/kurasaiiiii> for skins ideas
