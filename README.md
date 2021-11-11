# Welcome to Physics 215 Repository (v.202122-1)
*by: Johnrob Y. Bantang, Ph.D.*


This is a repository of the codes, notes, and slides used in a course on High-Performance Computing using Julia as the language (Physics 215: Computational Methods of Physics) at the [National Institute of Physics](http://nip.upd.edu.ph), [College of Science](http://science.upd.edu.ph), [University of the Philippines in Diliman](http://upd.edu.ph).

This course is taught in the 2nd semester of the academic year 2021-2022.

Most codes are based on those in the books used as textbook and references. 
Copyright mode is MIT since it covers the copyright mode of those references.

Please drop me a [note](mailto:jybantang@up.edu.ph) for any possible copyright problem since I'm making this public for my class.

# Syllabus and Course Guide Outline

Check it [here](SYLLABUS.md).

# Topics
The sequence of topics will generally follow the MAIN book reference following each chapter. Discussions will be live synchronous activity every Thursdays to discuss the chapter and computational physics topics. I expect everyone to use the Tuesday schedule in finishing the allocated homework sessions posted in the Google Classroom. This list may change as determined by the instructor. Each number will generally be allocated for the week number of the semester.

## Session 0
[**Installation and exploration of the Julia language**](00-Intro/README.md)

**OBJECTIVE**: Successfully Explore Julia

## Session 1
[**HPC and the Julia Framework**](01-HPC/README.md)

**OBJECTIVE**: Confirm Julia framework and Base speed

## Session 2
[**Computing performance**](02-Performance/README.md)

**OBJECTIVE**: Submit a performance analysis of a self-implemented physics textbook function using Julia benchmarking tools.

## Session 3
[**Type and type-related performance**](03-Types/README.md)

**OBJECTIVE**: Demonstrate the dynamic programming features of Julia (type dynamism)

## Session 4
[**Type and type-related performance**](04-Fast-Calls/README.md)

**OBJECTIVE**: Compare benchmark times of different implementation of functions that can be expressed as a recursion relation.

## Mini-projects
[**mProject : Mini-project ideas**](09-mProject/README.md)

**OBJECTIVE:** Identify critical principles of simulation and modeling in at a project involving physical system modeling or simulation.

# Submission modes
Two possible modes of submission is possible.
In both cases, submission must be done through the Google Classroom.
All `[filename]` must have the following pattern: `Session[n]-[Surname-GivenName]-[Exercise/File-short-title]` with the appropriate extension name.
1. **Option 1 -- Jupyter nb file**: Submit a Jupyter notebook file with the following name format `[filename].ipynb`.
   Other related files must be submitted accordingly changing the portion `[Exercise/File-short-title]`.
2. **Option 2 -- GitHub link**: Comment under "Private Comments" the link of the `.ipynb` file in your GitHub repository.
   The repository or at least the file must be public or at least accessible to the Instructor.
   Upload a PDF version of the Jupyter notebook of the same filename base ---after having run all necessary commands--- together with the same functions files stated in Option 1. **If PDF export does not work** you may opt to submit an HTML-formatted output instead.
   
Conversion of the notebook to different formats can be achieved in the web-interface via the menu `File / Download as / [Choose "HTML/PDF via ..."]`.
