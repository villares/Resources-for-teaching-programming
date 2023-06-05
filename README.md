# Resources for teaching programming for artists, designers and architects

([repository](https://github.com/villares/Resources-for-teaching-programming/))

<h1 id="toc"></h1>

## Python on the Landscape of Programming Tools for Design and Architectural Education

This page was originally made to host data from this paper, that presented an earlier version of the table below:

*VILLARES, A. B. A., & MOREIRA, D. (2017). [**Python on the Landscape of Programming Tools for Design and Architectural Education**](https://villares.github.io/mestrado/VILLARES_MOREIRA_SIGRADI_2017). Presented at the SIGRADI 2017, Concepcíon, Chile.*

### Extended table of Hosts, Platforms & Languages

[**SORTABLE VIEW OF THE TABLE**](http://villares.github.io/csv-to-html-table/host-platforms-and-languages)| [CSV on GitHub](https://github.com/villares/Resources-for-teaching-programming/blob/master/I%20-%20Host%20platforms%20%26%20languages.csv) | [raw CSV](https://raw.githubusercontent.com/villares/Resources-for-teaching-programming/master/I%20-%20Host%20platforms%20%26%20languages.csv) 

> **About the table contents**: (inclusion criteria)
> - Drawing or 3D modeling software that embeds a scripting language on the user interface or allows automation with a very limited number of steps between programming and code execution.
> - Tools aimed at teaching programming in a visual or graphic context.
> - [Ad hoc: tools that have shown potential for teaching in a visual or graphic context.]

After updating a few times the data from the earlier table, work started on compiling the other tables below.

----

## Processing + Python tools table

| Name | Processing features | based on (& Python version) | Python standard library | libraries ecosystem | main features | main limitations |
| --- | --- | --- | --- | --- | --- | --- |
[Processing Python Mode](https://py.processing.org) (the "reference implementation" for comparison) | [Processing 3](https://processing.org) Java | [Jython](https://www.jython.org/) (Python 2) | complete | Java & Processing Java | Available inside Processing IDE, very Processing 3 compatible | no web sharing/deployment, no modern Python 3 libs, not working with Processing 4, [needs a new maintainer](https://discourse.processing.org/t/python-mode-needs-a-new-project-owner/36399) |
[**py5**](http://py5coding.org/)✱ | [Processing 4](https://github.com/processing/processing4) Java graphics via [JPype](https://jpype.readthedocs.io/en/latest/) |  Python 3 | complete | Python & Java* | truly Python 3 compatible for libraries, can be used on Jupyter notebooks, same core capabilities as Processing 4 Java | New snake_case names, experimental, maybe some Processing Java libraries might not work |
[p5py](https://github.com/p5py/p5) | a new inplementation based on OpenGL (incomplete), and will add Skia backend |  Python 3 | complete | Python only | truly Python compatible, no Java/JVM dependency | New snake_case names, experimental, still incomplete, no access to Processing Java libraries  |
[**pyp5js**](https://berinhard.github.io/pyp5js/)✱ (pyodide or transcrypt mode)| [p5.js](https://p5js.org/) | Python 3 via [Pyodide](https://luxapodular.github.io/Py5.js/) or [Transcrypt](https://transcrypt.org/documentation) | complete | Python, JavaScript & p5.js |  web ready sketches & [editor](https://berinhard.github.io/pyp5js/pyodide/), very p5.js compatible & pyodide makes it very Python compatible | Experimental, still incomplete, p5.js features (as opposed to Processing Java/Python modes) |
[Proceso](https://proceso.cc/)  | [p5.js](https://p5js.org/) | Python 3 via Pyodide | complete | Python, JavaScript & p5.js | browser based sketches & very p5.js compatible, Python compatible,, names similar to py5 | p5.js features (as opposed to Processing Java/Python modes) |
[SkulptIDE](http://esperanc.github.io/skulptIde/pages.html) and [trinket.io](https://trinket.io/processing) | [ProcessingJS](http://processingjs.org/) | [Skulpt](http://skulpt.org/) (Python 2, going to 3 now) | partial | unknown, possibly JavaScript |  very nice web IDE, browser based sketches | ProcessingJS is defunct; not extensible
[BrythonIDE](https://esperanc.github.io/brythonide/) and [p5py.com](http://p5py.com/)  | [p5.js](https://p5js.org/) | [Brython](https://brython.info/) (Python 3) | [fairly complete](https://brython.info/static_doc/en/stdlib.html) | JavaScript & p5.js |  browser IDE, browser based sketches & very p5.js compatible | p5.js features (as opposed to Processing Java/Python modes)  |


✱ **these are the ones I'm using most!**

----

## More FLOSS + Python options to explore

### 3D 

- **[FreeCAD](https://freecadweb.org)** — Your own 3D parametric modeler
  - It has great a Python interactive console, bult-in editor (macro panel) and can also be used for 2D.
- [Blender](https://blender.org) — Blender's [Python API](https://docs.blender.org/api/current/index.html)
- OpenSCAD + Python tools:
  - [OpenPySCAD](https://github.com/taxpon/openpyscad)
  - [SolidPython](https://github.com/SolidCode/SolidPython)
  - [PythonOpensCAD](https://www.bvcw.org/)
- [CADQuery](https://github.com/CadQuery/cadquery) & [CQ-Editor](https://github.com/CadQuery/CQ-editor) — A Python parametric CAD scripting framework
- [PyPlasm](https://github.com/plasm-language/pyplasm) — Python version of the PLASM 3D modeling functional language
- [VPython](https://vpython.org/) — A 3D programming environment for Python:
- [sdf](https://github.com/fogleman/sdf) — A Python library to generate 3D meshes based on SDFs (Signed Distance Functions)

### 2D

- **[ShoeBot](https://shoebot.github.io/)** — A great creative coding environment designed for making vector graphics and animations 
  - Related to the DrawBot/NodeBox1/PlotDevice family of tools. See also [drawbot-skia](https://github.com/justvanrossum/drawbot-skia) (a new implemetation of DrawBot) 
- [pyxel](https://pypi.org/project/pyxel/) — A retro game engine for Python.
- [pygame-zero](https://pygame-zero.readthedocs.io/en/stable/) — A zero-boilerplate games programming framework for Python 3, based on Pygame.
- [guizero](https://lawsie.github.io/guizero/drawing//) — A really easy Python GUI library (based on Tkinter).
- [Bezmerizing](https://github.com/aparrish/bezmerizing/blob/master/demo.ipynb) — Allison Parrish's wonderful tiny library.
  - based on [Flat](https://xxyxyz.org/flat) — Generative infrastructure for Python.
- [PageBot](https://github.com/PageBot/PageBot) — Scriptable page layout, vector graphics and typography environment.
- [Pero](https://github.com/xxao/pero) — A unified Python API for multiple drawing backends. 
- [generativepy](https://github.com/martinmcbride/generativepy) — Generative art and graphing library based on PyCairo.
- [vsketch](https://github.com/abey79/vsketch) — A plotter-centric Python generative art toolkit. 

----

## Books and references

- The py5 tutorial series: [intro to py5 and python](https://py5coding.org/tutorials/intro_to_py5_and_python.html)
- Tristan Bunn's [Learn Pyhon Visually](https://nostarch.com/learn-python-visually) and [other wonderful resources](https://tabreturn.github.io/), including [Processing.py in Ten Lessons](https://tabreturn.github.io/code/processing/python/2021/04/16/processing.py_in_ten_lessons-resources.html) and the [thonny-py5mode](https://github.com/tabreturn/thonny-py5mode) plugin EN
- Allen Downey's [Think Python 2e](https://greenteapress.com/wp/think-python-2e/) EN / [Pense em Python 2e](https://penseallen.github.io/PensePython2e/) PT
- Al Sweigart's [Automate the Boring Stuff](https://autmatetheboringstuff.com) and [many other open resources](https://alsweigart.com/) EN
- Jake VanderPlas' [Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) EN
- My own open resources for teaching, in Portuguese [Introdução à programação com Python em um contexto visual](https://abav.lugaralgum.com/material-aulas/) PT

----

**Please consider feedback, colaboration by means of pull requests, and/or a small [donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HCGAKACDMVNV2)!**

----

Copyright (c) 2014-2023 [Alexandre B A Villares](https://abav.lugaralgum.com). This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. [CC-BY-SA-4.0 License](https://creativecommons.org/licenses/by-sa/4.0/)
