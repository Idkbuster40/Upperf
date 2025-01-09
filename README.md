# Upperf 
## Upperf is a (*very very very* work in progress) Minecraft optimization mod targeting versions compatible from 1.0.0 to 1.12.2.

![The Upperf logo in a 256 by 256 resoulution.](https://github.com/Idkbuster40/Upperf/blob/master/upperf_logo_256.png) 

### Info: Upperf (pronounced "Up-perf") is a *very very very* work in progress Minecraft optimization mod targeting versions compatible from 1.0.0 to 1.12.2. (the current focus is Minecraft 1.8.8) The mod uses JNI (Java Native Interface), which is a feature in Java and uses it with C (_primarily_) to use more better optimization features usually found in most other games and game engines and using experimental or new features which can be used to optimize the game along with faster loading times in game overall. See the rest of the README.md file for a full list of planned features and more info. (Until I return to it or actively begin to work on it, give me 3-5 business years, maybe longer. I need time to learn about this stuff, which is pretty advanced. Ok the years part was sarcasm, but you hopefully get the point as I am working on this now thanks to boredom.)

The name basically stands for "increased performance" in a weird way. I initially wanted to work on this mod 3 years ago but kept it off till now.

Do note that the Minecraft source code OR MCP's source code is provided here. You will have to find it yourself. A build tutorial will be added soon to compile your own binaries.

Any forks must respect the license that is used in this project. And any shipped binaries must also have the license in it, even if it is a custom Modification of Minecraft like a closed source PVP modpack/client or something similar, it must have the license. Forge does not strictly fall into this category. Open-source clients/modpacks do not need to follow this at all but I recommend adding the license just in case.

There are currently no plans for a forge mod version of Upperf.

### Checklist of features:
  - [ ] Better math.
  - [ ] Generic optimisation increases (All the usual stuff that most mods/modpacks/clients do in MC for optimizing the game). 
  - [ ] Custom LoDs. (Tricky.)
  - [ ] Async texture streaming. (More so difficult.)
  - [ ] Offloading memory to a C program which has dynamic memory allocation. (Challenging to do, but where's the fun if you don't try;] But I need to plan this soon.)
  - [ ] Memory fences for loading assets, shaders and so on in C and Java sources.
  - [ ] Caching texture, shader, world and model data. 
  - [ ] Better shadows and lighting? (Can be enabled optionally.)
  - [ ] Faster load times? I need to figure this one out.
  - [ ] Asset streaming from game files and cache. (Frostbite-esque implementation, there's a presentation by EA somewhere on the internet.)
  - [ ] Custom approach to greedy meshing.
  - [ ] Multithreaded C handoff for more CPU intensive tasks.
  - [ ] GPU-based chunk loading? (Might have to use OpenCL here.)
  - [ ] ...Add more in the future here, I guess?

### Roadmap for planning:
_TODO_

### FAQs:
_TODO_

### ADD_MORE_HERE:

### DISCLAIMER:
NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT
