Copyright Douglas S. Leonard 2024.  All rights reserved
Licenses are shown in each link.  If in doubt, all rights, reserved/ask, especially for **for the non-public repos, where license text is a draft only.**  Generally, I don't like gpl, particularly gpl3.

## Fun Highlights:

---
### PyLaunch  <br><sub>A uv-based python project and git repo generator to streamline source-based deployment, dependency, and development </sub>
- **[dsleonard-pylaunch](https://github.com/DSLeonard-coding/dsleonard-pylaunch/#dsleonard-pylaunch)**

### SISIFI 
Super simple C#-like solution to polymorphic fluent classes in C++ (a super hard problem) using a shadowing method
   usually avoided as a pitfall to do things usually believed impossible: 
- **[SISIFI](https://github.com/DSLeonard-coding/SISIFI)**
​

### DLG4::VolumeBuilders
- **[DLG4::VolumeBuilders: A documented, streamlined, fluent geometry API for Geant4](https://douglas_s_leonard.gitlab.io/physics_utilities/VolumeBuilders/)**
- **[DLG4::Units: Type-safe units for Geant4](https://github.com/DSLeonard-coding/DLG4Units)**

## Notebooks and wikis:

---
- [Properties and C# vs python, Jupyter notebook](Csharp_vs_python_jupyter.html)  

This next one is mostly obsolete since MS shut down their polyglot development:
- [Setting up an SoS multi-language Jupyter Notebook](SoS-install.html)
- [Multi-language list benchmark tests](benchmarks.html)
- [My wiki about how to unerstand git](https://gitlab.com/douglas.s.leonard/gitwiki)


## Public Physics utilities/libraries:

---
- **[DLG4::VolumeBuilders: A documented, streamlined, fluent geometry API for Geant4](https://dsleonard-coding.github.io/VolumeBuilders/)**
- [alldat: Data read/write/conversion and utility clas for Ortec and root formats](https://github.com/DSLeonard-coding/alldat)
- [UAO2_PLTLY: Representative use of PLTLY.NET for interactive plots ]( https://gitlab.com/douglas.s.leonard/UAO2_PLTLY)

## Misc utilities:

---

### **git**
- [git-alltrees subtree behavior with root-tree compliment and seamless merge history (no-squash/duplicates)](https://gitlab.com/douglas.s.leonard/alltrees/-/wikis/home)

### **python:** 
- [dsleonard-pylaunch scaffolding launcher for ](https://github.com/DSLeonard-coding/dsleonard-pylaunch)
- [dsleonard-git-tools, for github/gitlab pylaunch interaction, but useful elsewhere](https://github.com/DSLeonard-coding/dsleonard-git-tools)
- [qx: Console command/log-level convenience utility for phython](https://github.com/DSLeonard-coding/qx) This one is pretty handy for CLI scripting.
- [strictdataclasses: Prevents many un-intentional or ad-hoc modification of dataclasses](https://github.com/DSLeonard-coding/strictclasses) Now with extensive test/demonstration/CI/CD


### **C-sharp/C#** (my favorite language):
- [UAO2_PLTLY: Representative use of PLTLY.NET for interactive plots ]( https://gitlab.com/douglas.s.leonard/UAO2_PLTLY)

Largely obsolete since Lezyne quit making gps units, but the code is a useful example of repairing fit files:
- [[Fitfix:  Fixes garmin fit files with corrupt times](https://gitlab.com/douglas.s.leonard/FitFix)  alpha code, but it works. My first C# project.

### C++
This first one solves polymorphic fluent classes in C++ in a very simplistic C#-like way believed impossible using a method
   usually avoided as a pitfall. 
- [SISIFI](https://github.com/DSLeonard-coding/SISIFI)
​
- [ CMake module for easy Geant4, and ROOT setup, and env variable grabbing](https://github.com/DSLeonard-coding/DSLeonard-cmake)
- [ Heterogeneous tuple order/sort by column priority list](https://gitlab.com/douglas_s_leonard/programming_utilities/cpp/tuple_comp)  Good for sorting column-wise heterogeneous output. Harder than it sounds.

### Other
- [DOCTocActions:  A simple auto Table of Contents generator script for markdown on github repos](https://github.com/marketplace/actions/doctoc-action) Just the sctript is mine, not the genertor.


## Internal physics tools (access may be required, public versions comming soon!):
- [DecayChain: WIP, A decay network buider/analyzer parsing endsf data files](https://gitlab.com/douglas_s_leonard/physics_utilities/DecayChain)  This may go public.
- [HpgeSim:  CupSIM/GLG4SIM/ect based HPGe Geant sim with a focus on flexible sample/source batch deployment and portability](https://gitlab.com/douglas.s.leonard/HpgeSim)
- [HpgeSim-distrib:  Same as above but without proprietary models, may not be as updated](https://gitlab.com/douglas.s.leonard/HpgeSim)
- [HpgeAnalys:  Data processing pipeline/event-/histogram-builder for CUP HPGe data and sims](https://gitlab.com/douglas.s.leonard/HpgeSim)  Shares event selection and usage interface for Sim/Data.
- [gdcodes/gdfit: Branching/Intensity-constrained multi-activity peak fitting targetting HPGe](https://gitlab.com/douglas.s.leonard/gdcodes) This code has a lot of history.  It shows, but it works. Used originally for NAA analysis in EXO, although that was an adaptation too. Uses alldat for data reading.  Now includes a python API for automation.
- [Decay coincidence toy MC generator in C#](https://gitlab.com/douglas.s.leonard/decay_mc_cs) Intended for alpha coincidence analysis for DES measurements.
- [Decay coincidence toy MC generator, original python version](https://gitlab.com/douglas.s.leonard/decay_MC)

## Comming soon:

---

- A cookie cutter for easy creation and straight-to-git(lab/hub) deployment of new pip-installable python projects, so you can just code.
- A vscode extension to report and export an organized view of extensions and packs per profile.
- DecayChain may go public.

## How this page was made:

---

This is a gitlab/github (depending where you are)-pages page.  The underlying repo is here: [Link](https://github.com/DSLeonard-coding/DSLeonard-coding.github.io).
I just use scripts to generate static html in public/  and the only thing needed to publish on gitlab is the .gitlab-ci.yml and enabling pages in the project.
