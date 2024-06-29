# Upperf
## Upperf is an (*very very very* work in progress) Minecraft optimization mod targeting versions compatible from 1.0.0 to 1.12.2.

![The Upperf logo in a 256 by 256 resoulution.](https://github.com/Idkbuster40/Upperf/blob/master/upperf_logo_256.png) 

### Info: Upperf is an (*very very very* work in progress) Minecraft optimization mod targeting versions compatible from 1.0.0 to 1.12.2. (the current focus is Minecraft 1.8.8) The mod uses JNI (Java Native Interface), which is a feature in Java and uses it with C (_primarily_) to use more better optimization features usually found in most other games and game engines and using experimental or new features which can be used to optimize the game along with faster loading times in game overall. See the rest of the README.md file for a full list of planned features and more info. (until I return to it or actively begin to work on it, give me 3-5 buissness days, maybe longer. I need time to learn more advanced about this stuff.)

The name basically stands for "increased performance" in a weird way. I initially wanted to work on this mod 3 years ago but kept it off till now.

Do note that the Minecraft source code OR MCP's source code is provided here. You will have to find it yourself. A build tutorial will be added soon to compile your own binaries.

Any forks must respect the license that is used in this project. And any shipped binaries must also have the license in it, even if it is a custom Modification of minecraft like a closed source PVP modpack/client or something similar, it must have the license. Forge does not strictly fall into this category. Open source clients/modpacks do not need to follow this at all but I recommend adding the license just in case.

There are currently no plans for a forge mod version of Upperf.

### Checklist of features:
  - [ ] Generic optimisation increases (All the usual stuff that most mods/modpacks/clients do in MC for optimizing the game). 
  - [ ] Custom LoDs.
  - [ ] Async texture streaming.
  - [ ] Offloading memory to a C program which has dynamic memory allocation. (Challenging to do, but where's the fun if you don't try ;] But I need to plan this soon.)
  - [ ] _Atomic based fences for loading assets, shaders and so on in C and Java sources.
  - [ ] Caching texture, shader, world and model data.
  - [ ] Better shadows and lighting. (Can be enabled optionally.)
  - [ ] Faster load times? I need to figure this one out.
  - [ ] Asset streaming from gamefiles and cache.
  - [ ] Custom approach to greedy meshing.
  - [ ] Multithreaded C handoff for more CPU intensive tasks.
  - [ ] Async chunk loading.
  - [ ] ...Add more in the future here, I guess?


### Rules for committing/contributing:
If you are planning on committing or contributing to this repository please follow these rules: 

  0. The allowed languages are: Java, Kotlin (experimental), C, C++ (not recommended), ASM(x86,arm .etc. If you are feeling like you can take a challenge use this). As these are the languages that will work with JNI.
  
  1. No one can commit directly on the main/master branch. Or edit the README file without notifying me first.
       
  2. Use the `develop_<version_number>` branch for new changes to the software which has been approved after a PR between contributors.
     
  3. If you want to make a new change, you will create a new branch, for that specific feature/change. It should follow a naming scheme
  like: `VersionOfMC_TestingBuild_ExperimentalOrStable_YourName`, to give an example: `1122_alpha_experimental_ABC123`. Do note other contributors can see/change what you are doing. Keep this in mind. You are free to make a fork of this and work on it yourself and merge it back to your branch here if you feel others will tamper with what you have done.

  4. Use a TODO.md with a checklist of what you have implemented in your "personal" branch. A much more general checklist of features is in this README file.
     
  5. If it works after _through_ testing, the contributors will do a PR to the `develop_<version_number>` branch. We all can read it, and then merge it to the branch.
  
  6. For discussing stuff to do with the project, like errors or new ideas, use the Github Issues feature.
 
  7. PLEASE at least try to be a little sensible about commit names, like instead of "Fix weird rendering bug" please try to write "Fix rendering bug with anisotropic filtering". It does not strictly need to be like that, but you (hopefully) get the gist.
  
  8. When contributors have finished a major update, we will all agree to merge to the main branch.
     
  9. If you end up having a personal vendetta with someone, please take it outside of this github repository and refrain using the issues feature as a debate battlefield. Argue your personal differences outside of this repository. Refrain from being rude to one another and using offensive language in this repository. (I am iterating this once again, please understand what to do. Settle your differences outside of this repo. ...But this is the internet and people don't care. Well... Just listen to me please.)
  
  10. If you feel the rules are too strict, please try to abide by them, these rules are not constant and will change soon. And if you feel these rules are too confusing, try to break it down and understand it with your brain. (I don't mean to be too rude here, but understand this carefully.)

Please try to follow these rules and understand what you are doing.

### Roadmap for planning:
_TODO_

### FAQs:
_TODO_

### ADD_MORE_HERE:

### DISCLAIMER:
NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT
