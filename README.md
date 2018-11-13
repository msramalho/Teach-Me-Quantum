<h1 align="center">Teach Me Quantum</h1>

<!-- This course and all its materials can be found at https://github.com/msramalho/Teach-Me-Quantum  where they are constantly updated, subject to open source contributions and community -->

A university-level course on **Quantum Computing** and **Quantum Information Science** that incorporates [IBM Q Experience](https://quantumexperience.ng.bluemix.net/qx/experience) and [Qiskit](https://www.qiskit.org/). This course is adequate for general audiences without prior knowledge on Quantum Mechanics and Quantum Computing (please read to [prior knowledge](#prior-knowledge) before starting) and has an estimated duration of **10 weeks at 3h/week** (usually 1h theory + 2h practice, except for week 0 (1h+0h), week 1 (1h+1h) and week 9 (2h+0h)) estimated total time: **25h to 30h**.

This course is Open-source and fit for both individual learning as well as to be used by teachers, professors and lecturers in their own classes.

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
 * 📁 [Week 5 - Quantum Algorithms](Week%205%20-%20Quantum%20Algorithms) (Deutsch)
     * 📖 [Slides](Week%205%20-%20Quantum%20Algorithms/slides.pdf)
     * 📁 [Exercises](Week%205%20-%20Quantum%20Algorithms/exercises)
 * 📁 Week 6 - Quantum Algorithms (Simon)
 * 📁 Week 7 - Quantum Algorithms (Quantum Fourier Transform - Shor) [Cryptography]
 * 📁 Week 8 - Quantum Algorithms (Amplitude Amplification - Groover)
 * 📁 Week 9 - State of the Quantum Art, Adiabatic Quantum Computation, History and Final considerations

## Prior Knowledge
Students of this course are expected to be familiar with (this can be done while going through the course):
 * [Python](https://www.python.org/) language
 * [Jupyter](http://jupyter.org/) Notebook environment
 * Linear algebra basics, such as: inner and outer products, eigenvalues, norms, transpose, adjoints (complex conjugates), tensor product, ...

## Learning Goals
After completing this course, students should be able to:
 * Understand ...
 * Leverage QISKit for Quantum research and development
 * ...

## Working with PDF slides
Each `.pdf` file for slides may have two versions `NAME.pdf` and `NAME_animated.pdf`. The first ignores animations (by replacing the document class in any `.tex` file for `\documentclass[handout]{beamer}`) and the second contains animations.

Animated slides will only work with an external program, I advise [dannyedel/dspdfviewer](https://github.com/dannyedel/dspdfviewer/releases) which also has dual screen and timer functionality.

## Compiling LaTeX files
To achieve this use any LaTeX compiler of your choice, if you have [pdflatex](https://www.tug.org/applications/pdftex/) you can simply do `pdflatex week_XX.tex`.

## Aditional notes
Each week's slides has a particular theme, that is to help students distinguish between them and strengthen the learning process by fostering association.
