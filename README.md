<!-- This course and all its materials can be found at https://github.com/msramalho/Teach-Me-Quantum  where they are ket in the most recent version, subject to open source contributions from the community -->

<h1 align="center">Teach Me Quantum</h1>

A university-level course on **Quantum Computing** and **Quantum Information Science** that incorporates [IBM Q Experience](https://quantumexperience.ng.bluemix.net/qx/experience) and [Qiskit](https://www.qiskit.org/). 
This course is adequate for general audiences without prior knowledge on Quantum Mechanics and Quantum Computing (see [prior knowledge](#prior-knowledge)), has an estimated average duration of **10 weeks at 3h/week** (see [duration](#duration)) and is meant to be the entrypoint into the **Quantum World**.

<p align="center"><img  width="300px" src="https://i.imgur.com/39Mv9Ra.gif"></p>

This course is **Open-source** and appropriate for both _autodidacticism_ as well as _classroom teaching_ by educators, professors and lecturers in their own classes. Given the dynamic nature of the topic, any open-source contributions and future improvements are welcome.

<h3 align="center">🏆 This project was the winner of <a href="https://www.ibm.com/blogs/research/2019/01/ibmq-teach-quantum-winners/">IBM Q Teach Me Quantum award</a>!</h3>

## Course Overview

 * 📁 [Week 0 - Hello Quantum World](Week%200%20-%20Hello%20Quantum%20World)
     * 📖 [Slides](Week%200%20-%20Hello%20Quantum%20World/slides.pdf)
 * 📁 [Week 1 - Quantum Tools](Week%201%20-%20Quantum%20Tools)
     * 📖 [Slides](Week%201%20-%20Quantum%20Tools/slides.pdf)
     * 📁 [Exercises](Week%201%20-%20Quantum%20Tools/exercises)
 * 📁 [Week 2 - Quantum Information Science](Week%202%20-%20Quantum%20Information%20Science)
     * 📖 [Slides](Week%202%20-%20Quantum%20Information%20Science/slides.pdf)
     * 📁 [Exercises](Week%202%20-%20Quantum%20Information%20Science/exercises)
 * 📁 [Week 3 - Quantum Gates](Week%203%20-%20Quantum%20Gates)
     * 📖 [Slides](Week%203%20-%20Quantum%20Gates/slides.pdf)
     * 📁 [Exercises](Week%203%20-%20Quantum%20Gates/exercises)
 * 📁 [Week 4 - Quantum Facts](Week%204%20-%20Quantum%20Facts)
     * 📖 [Slides](Week%204%20-%20Quantum%20Facts/slides.pdf)
     * 📁 [Exercises](Week%204%20-%20Quantum%20Facts/exercises)
 * 📁 [Week 5 - Quantum Algorithms](Week%205%20-%20Quantum%20Algorithms) (Deutsch's algorithm)
     * 📖 [Slides](Week%205%20-%20Quantum%20Algorithms/slides.pdf)
     * 📁 [Exercises](Week%205%20-%20Quantum%20Algorithms/exercises)
 * 📁 [Week 6 - Quantum Search](Week%206%20-%20Quantum%20Search) (Grover's algorithm)
     * 📖 [Slides](Week%206%20-%20Quantum%20Search/slides.pdf)
     * 📁 [Exercises](Week%206%20-%20Quantum%20Search/exercises)
 * 📁 [Week 7 - Quantum Factorization](Week%207%20-%20Quantum%20Factorization) (Shor's algorithm)
     * 📖 [Slides](Week%207%20-%20Quantum%20Factorization/slides.pdf)
     * 📁 [Exercises](Week%207%20-%20Quantum%20Factorization/exercises)
 * 📁 [Week 8 - High Level Quantum Programming](Week%208%20-%20High%20Level%20Quantum%20Programming) (qiskit-aqua)
     * 📖 [Slides](Week%208%20-%20High%20Level%20Quantum%20Programming/slides.pdf)
     * 📁 [Exercises](Week%208%20-%20High%20Level%20Quantum%20Programming/exercises)
 * 📁 [Week 9 - State of the Quantum Art](Week%209%20-%20State%20of%20the%20Quantum%20Art)
     * 📖 [Slides](Week%209%20-%20State%20of%20the%20Quantum%20Art/slides.pdf)

## Prior Knowledge
Students of this course are expected to be familiar with (this can be done while going through the course):
 * [Python](https://www.python.org/) language
 * [Jupyter](http://jupyter.org/) Notebook environment
 * Some linear algebra: inner and outer products, eigenvalues, norms, transpose, adjoints (complex conjugates), tensor product, ...

## Learning Goals
After completing this course, students should be able to:
 * Understand the basics of Quantum Mechanics
 * Know how a computing model can be built around Quantum Mechanics
 * Understand the advantages, disadvantages and implications of Quantum Computing
 * Understand Quantum Information Science and how it contrasts with classical information theory
 * Leverage QISKit towards research and development in the _Quantum World_
 * Understand the empirical differences between Quantum Simulators and real Quantum Devices (such as those available in IBMQ)
 * Design, interpret and deploy quantum circuits (simulators and real processors)
 * Know and describe a few of the most common quantum algorithms: Deutsch, Grover, Shor
 * Be able to quickly understand new quantum algorithms based on the same principles: Simon, ...
 * Be able to quickly understand new principles of quantum computing: Adiabatic, ...
 * Understand the impact that the advance of quantum computers can have on the world as we know it
 * Understand High Level applications of near-end quantum algorithms, namely how to use qiskit-aqua for solving real world problems
 * Move on to deeper waters, by exploring according to their heart's desire!

## Duration
 * Estimated average duration of **10 weeks at 3h/week**
 * Duration is flexible depending on level of depth a teacher imposes on each week.
 * Usually 1h theory + 2h practice, except for:
     * week 0 (1h + 0h = 1h)
     * week 1 (1h + 1h = 2h)
     * week 9 (2h + 0h = 2h)
* Estimated total time: **25h to 30h**.


## Customizing Slides
#### Reusing Slides
The materials in this course can be adapted to specific classes, contexts, schools,... to the desire of the educators.

The `author`, `date` and `instute` properties of each presentation is defined in the respective `macros.sty` file (this file is an exact copy for each week). If you want to update global settings for all weeks (like the author, update links colors, update code snippets display, ...) you can use the [`sh replicate_macros.sh`](utils/replicate_macros.sh) (linux) | [`replicate_macros.bat`](utils/replicate_macros.bat) (windows) to replicate the changes from a copy of the file for every week's folder (the source file must be in the [utils](utils/) folder, there is already an updated version of [macros.sty](utils/macros.sty) in there).

The constraint for using this materials is to replace the `\author[]{}` command by the following command: `\author[LASTNAME]{FIRSTNAME LASTNAME,\\ \scriptsize{based on slides by \textbf{Miguel Sozinho Ramalho}}}` with the update author info.

#### Animating Slides
Each `.pdf` file for slides is static, but if you want to include animations you can do so by replacing the `document` class in the first line of the `main.tex` files by `\documentclass[handout]{beamer}`) and following [these instructions](https://tex.stackexchange.com/a/177060/126771).


#### Adding Notes to Slides
This can also be accomplished by appending the following lines before `\begin{document}`:
```tex
\usepackage{pgfpages}
\setbeameroption{show notes}
\setbeameroption{show notes on second screen=right}
```

#### Compiling LaTeX files
To achieve this use any LaTeX compiler of your choice, if you have [pdflatex](https://www.tug.org/applications/pdftex/) you can simply do `pdflatex main.tex` on each week's latex folder.

#### Presenting Slides with Notes and/or Animations
To present the slides with **notes** or with **animations** will only work with an external program, I advise [dannyedel/dspdfviewer](https://github.com/dannyedel/dspdfviewer/releases) which also has dual screen and timer functionality.

---

## Aditional notes
Each week's slides has a particular theme, that is to help students distinguish between them and strengthen the learning process by fostering association. 

## Final remarks
This was an excelent oportunity to both  teach and learn. I have sought to come up with a methodology of how I wanted my quantum education to have been, hopefully this will help others with similar learning tastes. If not, oh well, shift happens...

<p align="center"><img src="http://assets.amuniversal.com/7c4d9f70a05b012f2fe600163e41dd5b"></p>
