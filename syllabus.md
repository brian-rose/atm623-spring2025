---
title: Syllabus
exports:
  - format: pdf
    template: lapreprint
    output: exports/syllabus.pdf
downloads:
  - file: exports/syllabus.pdf
    title: The syllabus in pdf format
---

# Syllabus for A ATM 623: Climate Modeling (Spring 2025)

## Course information

### Essential details

Class number
: 9129 (Spring 2025)

Meeting times
: Tuesday, Thursday 1:10-2:30 PM in ETEC 482[^disclaimer]

Prerequisites
: _A ATM 500 Atmospheric Dynamics_, _A ATM 504 Introduction to Atmospheric Physics I_ or permission of instructor[^prereq]

Credit hours
: 3

[^prereq]: Note that the usual co-requisite ATM 551 is waived for 2025 due to course availability.

[^disclaimer]: The University at Albany reserves the discretion to change the date, time, location, and modality of instruction.

### Instructor and office hours

Who am I
: [Brian Rose](https://www.atmos.albany.edu/facstaff/brose/)

What's my email?
: <brose@albany.edu>

Where is my office?
: ETEC 425

When are my office hours?
: Mondays after class, 2:30-3:30 PM (or by appointment).

### Course website and online text

Course-specific website is [https://brian-rose.github.io/atm623-spring2025/](https://brian-rose.github.io/atm623-spring2025/).

Much of the course content will be delivered through Prof. Rose's online textbook [_The Climate Laboratory_](https://brian-rose.github.io/ClimateLaboratoryBook/), available at [https://brian-rose.github.io/ClimateLaboratoryBook/](https://brian-rose.github.io/ClimateLaboratoryBook/).

Both the website and the book are likely to be updated throughout the semester. 

### Grading: A-E, 3 credit

- Participation: 15%
- Assignments: 40%
- Final project: 45% (written submission 40%, oral presentation 5%)

Late assignments and projects will only be allowed for reasonable and university-recognized reasons, which include religious observances. Please discuss absences and late work with Prof. Rose _in advance_ whenever possible.

## Course description, objectives, and resources

### Bulletin description

From the [graduate bulletin](https://www.albany.edu/graduatebulletin/a_atm.htm):

_Investigation of fundamental climate processes through hands-on use of numerical and mathematical models. Topics may include: the global energy budget; radiation and the greenhouse effect; radiative-convective equilibrium; climate feedback analysis; orbital geometry, insolation and the seasonal cycle; heat transport and storage in the climate system; rates of transient climate change; sea ice and its coupling to the global climate system; the surface energy balance and the hydrological cycle. Emphasis on building physical understanding through active investigation with hierarchies of model complexity. Assumes some experience with computer coding in a high-level programming language (Python, Matlab, or similar)_

### Potential course outline

Our approach will be hands-on and data-centric wherever possible, putting significant emphasis on reproducible workflows. We will collectively get our hands on a range of models, including both comprehensive GCMs and assorted simpler process models. We will use these models to build our understanding of topics such as

- The global energy budget
- Greenhouse effect and radiative-convective equilibrium
- Radiative forcing and feedback analysis
- Orbital geometry, insolation and the ice ages
- Arctic sea ice and its coupling to the global climate system
- Mechanisms of heat transport in the atmosphere and ocean
- The hydrological cycle in a warming climate
- Links between tropical precipitation and global energy flows
- Ocean heat uptake and storage
- Dynamics of warm equable climates

It's unlikely that we will be able to cover all these subjects. The topic list and outline is subject to change and may be adapted to students’ interests.

### Learning outcomes

In this course, students will achieve the following:

- Develop a nuanced conceptual and quantitative understanding of key processes regulating the planetary energy budget and their causal links to climate change.
- Develop a practical understanding of the hierarchy of climate model complexity and the role of physical modeling in climate science.
- Be able to communicate strengths and limitations of scientific results that make use of climate models in one or more research contexts.
- Be able to formulate, execute, interpret, and explain simple climate model experiments using `climlab`.
- Gain skills in data-intensive analysis and visualization of output from comprehensive climate models using modern, cloud-based tools.
- Apply theoretical and data-analysis methods developed in this course to an original research problem.
- Communicate their research results clearly in oral and written form, with an emphasis on computational reproducibility.

### Resources

Here are links to various helpful resources for this course.

- The [course website](https://brian-rose.github.io/atm623-spring2025/)
- [The Climate Laboratory](https://brian-rose.github.io/ClimateLaboratoryBook/) book
- [Pythia Foundations](https://foundations.projectpythia.org/) is an invaluable resource for tutorials on Python and computing tools for climate science.
- [Pythia Cookbooks](https://cookbooks.projectpythia.org) may have useful resources for some more advanced topics.
- I may assign additional readings from the book @ClimateModellingPrimer:4ed. A copy will be on reserve at the University Library reserve desk.

## Attendance, assignments, and projects

### Attendance and participation policy

This is an active-learning class, and a significant portion of the course grade is given for class participation. You are expected to attend all lectures and participate fully in class discussions and exercises. Any absence should be discussed with Prof. Rose _in advance_ whenever possible. 

### Assignments

Much of the course will consist of hands-on computing exercises using the Python language. I will provide code to get us started on each problem. Students will have access via a web browser to a JupyterHub environment for the course, or may optionally maintain a custom Python environment on their own computer.

The goal of the exercises is to carry out meaningful calculations. _Grading will be based more on scientific understanding than on programming skill._ Assignments will usually be letter-graded on a qualitative A-E scale:

- A: excellent
- B: good
- C: fair
- D: poor
- E: fail 

Assignments will normally be due by the beginning of class on the stated due-date. Extensions will usually be granted for legitimate reasons but _must be discussed in advance with Prof. Rose._ Electronic submission of homework by email is preferred whenever possible.

In this course we put a strong emphasis on **computational reproducibility** as well as clarity of scientific communication. You will typically submit assignments as Jupyter notebooks that fully described your work and your results. The notebook is a document combining formatted text with executable computer code for self-describing calculations, and is a widely-used format for scientific computing. We will use these notebooks frequently throughout the course so all students will become well acquainted with them (if they aren't already). Professor Rose will give guidance on effective use of the notebook format for reproducible scientific narratives.

### Final projects

#### Overview

Each student will complete an independent (or small group) research project exploring an issue in climate science and climate modeling. The project must include some original calculations described and carried out by you. A written report and oral presentation are required. You will submit a project proposal (less than one page) by **Friday March 14**. You are encouraged to discuss your ideas with the instructor beforehand.

#### The reproducible notebook

You will submit your written report electronically as a Jupyter notebook, which you will use to communicate your **scientific and computational narrative**. Your notebook should be organized into a coherent narrative like a standard scientific paper, e.g.:

- A brief abstract
- Introduction that motivates and describes the scientific problem you are studying
- Brief review of the relevant peer-reviewed literature
- Necessary details and references for the data sources and methods you are using
- Clear communication of results through well-labeled figures and tables as appropriate
- Discussion of results including caveats and shortcomings
- Conclusions

The difference between this report and a standard paper is that your notebook will be **reproducible**. You will include all the code necessary to access your data, carry out your calculations, and plot your figures. Grades for the written notebooks will be determined by scientific content, clarity of presentation, and reproducibility. Reports are due **Friday May 9**.

#### Oral presentations

Presentations will be scheduled near the end of the semester (details TBD). Each student or small group will give brief presentations, followed by a class discussion. The purpose of the oral presentations is to share your work with your classmates, practice your presentation skills, and get feedback in advance of your final notebook submission. Grades for the oral presentation will be based primarily on clarity of communication.

#### Group projects

Small groups (maximum three students) may choose to collaborate on their final projects, **subject to Professor Rose's approval**. That approval will be contigent on a clear work plan that identifies specific roles and contributions for each group member. The scope of a group project is expected to be more ambitious than an individual project. Please discuss your group plan informally with Professor Rose prior to submitting your written proposal. 

#### Pythia Cookbook contributions

Optionally, students (or groups) may choose to organize their final project for publication on the public [Pythia Cookbook Gallery](https://cookbooks.projectpythia.org) as a new Cookbook or significant addition to an existing book. This will make the work citeable and available to the broader scientific community. Publication on the Pythia gallery requires use of a [specific GitHub template](https://github.com/ProjectPythia/cookbook-template) and adherence to a [community style guide](https://projectpythia.org/cookbook-guide.html). Professor Rose will be very happy to give guidance on these for interested students.

## Academic integrity

In this class we will strive to be interactive, learning by doing and by discussion. Some collaboration on exercises is therefore encouraged. However you are ultimately expected to submit *your own work* and *your own thoughts*, and to *give proper credit to others* for previous work and ideas.

This is very important when writing computer code! There is nothing wrong with borrowing useful pieces of code from classmates or online sources — that is in fact the central principle of open-source software. However, _you must always cite your sources and acknowledge the original author(s)_. You must also, wherever practical, _understand_ the code you are borrowing and be able to explain what it does.

It is every student's responsibility to become familiar with the standards of academic integrity at UAlbany. Claims of ignorance, of unintentional error, or of academic or personal pressures are not sufficient reasons for violations of academic integrity. Please refer to the UAlbany academic integrity policies here: <https://www.albany.edu/graduate-bulletin/regulations-and-degree-requirements.php>

Note that submission of substantially similar work for required final projects in multiple courses is a violation of this policy and is not acceptable. Discuss your all your project plans with all instructors well in advance if you have any doubts.
