----

# Resources for teaching programming
# for artists, designers and architects ([repository](https://github.com/villares/Resources-for-teaching-programming/))

An earlier version of this table was published as: *VILLARES, A. B. A., & MOREIRA, D. (2017). [**Python on the Landscape of Programming Tools for Design and Architectural Education**](https://villares.github.io/mestrado/VILLARES_MOREIRA_SIGRADI_2017). Presented at the SIGRADI 2017, Concepcíon, Chile.*

### Extended table of Hosts, Platforms & Languages
> - Drawing or 3D modeling software that embeds a scripting language on the user interface or allows automation with a very limited number of steps between programming and code execution.
> - Tools aimed at teaching programming in a visual or graphic context.
> - [Ad hoc: tools that have shown potential for teaching in a visual or graphic context.]

| | | | 
| --- | --- | --- |
| [**SORTABLE VIEW OF THE TABLE**](http://villares.github.io/csv-to-html-table/host-platforms-and-languages)| [CSV on GitHub](https://github.com/villares/Resources-for-teaching-programming/blob/master/I%20-%20Host%20platforms%20%26%20languages.csv) | [raw CSV](https://raw.githubusercontent.com/villares/Resources-for-teaching-programming/master/I%20-%20Host%20platforms%20%26%20languages.csv) |

----

### Processing + Python tools table

| Name | Processing features | based on (& Python version) | Python standard library | libraries ecosystem | main features | main limitations |
| --- | --- | --- | --- | --- | --- | --- |
[**Processing Python Mode**](https://py.processing.org)✱ | [Processing Java](https://processing.org) | [Jython](https://www.jython.org/) (Python 2) | complete | Java & Processing Java | available inside Processing IDE, very Processing compatible | no web sharing/deployment, no modern Python libs |
[p5py](https://github.com/p5py/p5) | a new inplementation (incomplete) |  Python 3 | complete | Python only | truly Python compatible | New names (for those used to Processing), experimental, still incomplete, no access to Processing Java libraries  |
[**pyp5js**](https://berinhard.github.com/pyp5js)✱ (pyodide or transcrypt mode)| [p5.js](https://p5js.org/) | Python 3 via [Pyodide](https://luxapodular.github.io/Py5.js/) or [Transcrypt](https://transcrypt.org/documentation) | complete | Python, JavaScript & p5.js |  web ready sketches & [editor](https://berinhard.github.io/pyp5js/pyodide/), very p5.js compatible & pyodide makes it very Python compatible | Experimental, still incomplete, p5.js features (as opposed to Processing Java/Python modes) |
[SkulptIDE](http://esperanc.github.io/skulptIde/pages.html) and [trinket.io](https://trinket.io/processing) | [ProcessingJS](http://processingjs.org/) | [Skulpt](http://skulpt.org/) (Python 2, going to 3 now) | partial | unknown, possibly JavaScript |  very nice web IDE, browser based sketches | ProcessingJS is defunct; not extensible
[BrythonIDE](https://esperanc.github.io/brythonide/) and [p5py.com](http://p5py.com/)  | [p5.js](https://p5js.org/) | [Brython](https://brython.info/) (Python 3) | [fairly complete](https://brython.info/static_doc/en/stdlib.html) | JavaScript & p5.js |  browser IDE, browser based sketches & very p5.js compatible | p5.js features (as opposed to Processing Java/Python modes)  |
[**py5**](http://py5.ixora.io/)✱ | [Processing Java 4](https://github.com/processing/processing4) via [JPype](https://jpype.readthedocs.io/en/latest/) |  Python 3 | complete | Python & Java* | truly Python 3 compatible for libraries, can be used on Jupyter notebooks, same core capabilities as Processing Java | New names (for those used to Processing), experimental, maybe some Processing Java libraries might not work |

✱ **these are the ones I'm using most!**

----

### More FLOSS + Python options to explore

##### 3D 

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

##### 2D

- **[ShoeBot](https://shoebot.github.io/)** — A great creative coding environment designed for making vector graphics and animations 
  - Related to the DrawBot/NodeBox1/PlotDevice family of tools.
- [guizero](https://lawsie.github.io/guizero/drawing//) — A really easy Python GUI library (based on Tkinter)
- [Bezmerizing](https://github.com/aparrish/bezmerizing/blob/master/demo.ipynb) — Allison Parrish's wonderful tiny library
  - based on [Flat](https://xxyxyz.org/flat) — Generative infrastructure for Python
- [PageBot](https://github.com/PageBot/PageBot) — Scriptable page layout, vector graphics and typography environment
- [Pero](https://github.com/xxao/pero) — A unified Python API for multiple drawing backends 
- [generativepy](https://github.com/martinmcbride/generativepy) — Generative art and graphing library based on PyCairo
- [vsketch](https://github.com/abey79/vsketch) — A plotter-centric Python generative art toolkit 

### Books and references

- Allen Downey's [Think Python 2e](https://greenteapress.com/wp/think-python-2e/) EN / [Pense em Python 2e](https://penseallen.github.io/PensePython2e/) PT
- Tristan Bunn's [Learn Pyhon Visually](https://nostarch.com/learn-python-visually) and [other wonderful resources](https://tabreturn.github.io/), including [Processing.py in Ten Lessons](https://tabreturn.github.io/code/processing/python/2021/04/16/processing.py_in_ten_lessons-resources.html) and the [thonny-py5mode](https://github.com/tabreturn/thonny-py5mode) plugin EN
- Al Sweigart's [Automate the Boring Stuff](https://autmatetheboringstuff.com) and [many other open resources](https://alsweigart.com/) EN
- Jake VanderPlas' [Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) EN
- My own open resources for teaching, in Portuguese [Introdução à programação
com Python em um contexto visual](https://abav.lugaralgum.com/material-aulas/) PT

----

**Please consider feedback, colaboration by means of pull requests, and/or a small [donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HCGAKACDMVNV2)!**

----

Copyright (c) 2014-2022 [Alexandre B A Villares](https://abav.lugaralgum.com). This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. [CC-BY-SA-4.0 License](https://creativecommons.org/licenses/by-sa/4.0/)
