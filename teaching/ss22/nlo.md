---
layout: page
title: Nonlinear Optimization (SS 22)
description: >
  Here you find information about the course on Nonlinear Optimization in the summer term 2022.
hide_description: false
image: 
  path: /../../assets/img/rosenbrock.png
sitemap: true
---

<!-- invert_sidebar: true -->

2022-07-18
{:.note title="Last modified at"}

0. I need this empty list to make the TOC work
{:toc}

## General Information

Organizers
: - [Prof. Dr. Ekaterina A. Kostina][ekaterina]
  - [Ihno Schrot][ihno]
  
  Please contact [Ihno Schrot][ihno] if you have questions regarding this course.
  {:.note title="Contact"}
  
Tutors
: - [Laura Femmer][laura]
  - [Jörn Buchwald][joern]

First Lecture
: Thursday, April 21, 11:15, in the lecture hall (HS) in INF 205

Lecture Dates
: - Mondays, 11:00 - 13:00
  - Thursdays, 11:00 - 13:00

Lecture Room
: Lecture hall (HS) in INF 205 
  
  We meet in person.
  {:.note}

Tutorial Groups
: | Day | Time | Room | Tutor |
  |-----|------|------|-------|
  | Monday | 16:15 - 17:45 | SR 1 | [Jörn][joern] |
  | Thursday | 09:15 - 10:45 | SR 1 | [Laura][laura] |
  | Thursday | 16:15 - 17:45 | SR 4 | [Laura][laura] |
  
Collaborative Working Sessions
: The collaborative working sessions take place **in SR 1 on Thursday at 09:15am**. If Thursday is a public holiday, the collaborative working session takes place in SR 1 on Mondays at 16:15. More details on the format can be found [below][ws].



<!-- Platform for anonymous questions and feedback
: We understand that sometimes you would like to ask a question or provide feedback anonymously. You can do that on [Particify][ars]. Just enter the code *3535 6496* or go directly to [our room][arsroom] and then post your question or feedback in the Q\&A section. We will regularly check the Q\&A section and answer your questions there. -->

Level 
: Bachelor and Master

Language
: English

Requirements
: You should have attended at least the following courses:
    - Analysis 1, 2
    - Linear Algebra 1
  
  Additionally, having attended the following courses is beneficial but not necessary:
    - Basics of Optimization
    - Introduction to Numerics
    
  We will have programming exercises that have to be solved in Python, so it is beneficial if you have some experience with Python already, but we keep the exercises beginner-friendly, so that it is no problem if you have not used Python before.

  You can of course still join the course if you are missing one of these requirements, but we recommend that you acquire the missing knowledge in parallel then.
  {:.note}
  
Registration
: To participate in the course, please register for the course on [MÜSLI][muesli].

## Exercises

Sheets
: | Sheet | Deadline | Notebook Template | Solutions | Comments |
  |-------|----------|-------------------|-----------|----------|
  | [Tutorial sheet][sheettut] | None | | None | Tutorial notebooks\: [python\_for\_nlo][nbtut1] [python_tut_cebulla][nbtut2] |
  | [Sheet 1][sheet1]  | May 13th, 08:00am | [Template 01][temp1], [Auxiliary Functions 01][aux1]  | [Solutions 1][sol1], [Prog. Solution 1][progsol1] | Typo in Exe.1.8 (b) fixed on May 2nd. |
  | [Sheet 2][sheet2]  | May 27th, 08:00am | The programming exercise has been moved to Sheet 3.  | [Solutions 2][sol2] | As we did not yet cover the MFCQ and the Abadie CQ in the lecture, we will move the exercises 2.4 (c), 2.6 (c) and 2.7 to Exercise Sheet 3.  |
  | [Sheet 3][sheet3] | June 10th, 08:00am | [Template 03][temp3], [Auxiliary Functions 03][aux3] | [Solutions 3][sol3], [Prog. Solution 3][progsol3] | You find the definition of Newtons method on p. 90 in the lecture notes. This short definition is sufficient to solve the exercises on this sheet. |
  | [Sheet 4][sheet4] | June 24th, 08:00am | [Template 04][temp4], [Auxiliary Functions 04][aux4] | [Solutions 4][sol4], [Prog. Solution 4][progsol4] | |
  | [Sheet 5][sheet5] | July 15th, 08:00am  | [Template 05][temp5], [Auxiliary Functions 05][aux5]| [Solutions 5][sol4], [Prog. Solution 5][progsol4] | The deadline has been extended to July 15. |
  | [SQP Exercises][sqp] | None  | | [SQP Solutions][sqpsol] | This sheet shall not be handed in. |
  

General format
: - **One** exercise sheet every **two** weeks
  - The first exercise sheet will be published April 29.
  - 5 (graded) exercise sheets with 40 points of theoretical exercises and one programming exercise per sheet. See below for more information on the grading.
  - Release: Fridays (biweekly) on [MaMpf][mampf] and in the table above.
  - Submission deadline: Fridays (biweekly) until 08:00am on [MaMpf][mampf]
  - Submission procedure see below.
  - Work in teams allowed **and encouraged** with up to 3 persons per team
  - Information on the correction and the feedback see below.
<!--   - The tutor can ask/allow you to revise your programming exercise once per sheet. -->
  - Solutions can be written in English and German.
  - Plagiarism leads to 0 points for all involved teams (that also applies to plagiarism of the solutions from the winter term 20/21)!
  - Sample solutions will be uploaded in [MaMpf][mampf] and linked in the table above.
  
Programming exercises format
: - Programming language: Python
  - You get templates that you have to complete.
  - The templates are a single Jupyter notebook for each sheet (sometimes accompanied by a Python file with auxiliary functions)
  - A Python tutorial will be available soon.

Submission procedure
: - Both the theoretical and the programming exercises are submitted digitally.
  - The solutions to the theoretical questions have to be submitted as **one PDF** file. Solutions created in LaTeX are allowed as long as the names of the team members are also added using LateX. If you scan handwritten solutions, please make sure that the solutions remain readable and have a moderate file size! Digitally handwritten solutions are accepted, too.
  - The programming exercises have to be submitted as **one Jupyter notebook**.
  - The Jupyter notebooks have to include the created outputs, like plots and logging outputs.
  - The PDF and the Jupyter notebook have then to be added to a **ZIP-archive**.
  - The notebooks, PDFs, and archives have an obligatory naming scheme. Please name your files \<sheet numer (2 digits!)\>\_\<Last name1\>(\_\<Last name2\>\_\<Last name3\>).ipynb/pdf/zip, i.e. for example **01_Femmer_Kostina_Schrot.ipynb**. (Do not use the angle brackets and adjust the number of names according to your team size).
  - Write down your name(s) at the beginning of your theoretical solutions and at the beginning of your Jupyter notebooks. It is not sufficient to have your names only in the file name.
  - Upload your solutions until Friday (biweekly), 08:00am on [MaMpf][mampf].
  - A guide how to submit solutions on [MaMpf][mampf] can be found [here][subguide].

Grading, correction and feedback
: Fortunately, we have found a second tutor such that the grading, correction and feedback works as usual. I.e., all submissions will be corrected and graded and you will receive a commented version of your submission in [MaMpf][mampf].


## Lecture Format

The lectures take place in person and in a "classical" format, i.e. Prof. Kostina will present the lecture content in the lectures.

Handwritten lecture notes will be uploaded on [MaMpf][mampf]. Moreover, lecture notes from the course in the winter term 2020/2021 are available, see [other materials][material].

## Tutorial Format

We will alternate between two different formats: A [*collaborative working session*][ws] and the [*presentation of solutions*][sol].

We want to make sure that the tutorials are as effective as possible for you, so we can possibly still adjust the formats to your needs. Therefore, feedback is always welcome.
{:.note}

### Collaborative working sessions

What?
: In these sessions we invite you to come to the seminarroom to work together with your own and other groups on the exercises. Moreover, Laura and myself will be there to help if you have problems or questions. In particular, we can discuss programming related issues here.

  The spirit of these sessions is less the one of a "classical" tutorial, but more the one of an interactive group meeting. Especially, we will not prepare anything unless you have asked us for something specific.
  {:.note}

When?
: In the second week after you submitted your solutions/the new exercise sheet has been published **in SR 1 on Thursday, 09:15am**. Moreover, we have an additional meeting at the beginning and one at the end of the semester. I.e., the dates are:

  | Date | Topic | Comments |
  |---------|-----------|-------|
  | 02.05./05.05. | Setting up the Conda environments and the Python tutorials; possibly we will say a few words about debugging and Git | |
  | 09.05./12.05. | Working on the 1st exercise sheet | |
  | 23.05. | Working on the 2nd exercise sheet | Monday 16:15 instead of Thursday! |
  | 09.06. | Working on the 3rd exercise sheet | |
  | 23.06. | Working on the 4th exercise sheet | |
  | 07.07. | Working on the 5th exercise sheet | |
  | *TBA*  | Exam preparation | |

### Presentation of solutions

What?
: In these tutorials Laura and Jörn will present (some of the) solutions of the previous exercise sheet and answer specific questions to your solutions.

When?
: In the first week after you submitted your solutions/the new exercise sheet has been published. I.e., the dates are:
  
  | Mondays | Thursdays | Topic |
  |---------|-----------|-------|
  | 16.05. | 19.05. | Discussing solutions of the 1st exercise sheet |
  | 30.05. | 02.06. | Discussing solutions of the 2nd exercise sheet |
  | 13.06. | (Public Holiday) | Discussing solutions of the 3rd exercise sheet |
  | 27.06. | 30.06. | Discussing solutions of the 4th exercise sheet |
  | 11.07. | 14.07. | Discussing solutions of the 5th exercise sheet |

## Final Exam

Admission Requirements
: - at least 50% of the points (=95 points) in the theoretical exercises **and** 2 points in the programming exercises.
  
  If you have an old admission, contact [me][ihno] as soon as possible.
  {:.note}
  
Exam Format
: - Date: **August 1st, from 11:00 - 13:00**
  - Room: **Lecture Hall (HS) in INF 205**
  - Written exam of 120min
  - No programming project
  - Theoretical and programming related questions (no coding on paper however)
  - The exam is not an open book exam. In fact, you are not allowed to bring any materials into the exam, i.e. you are not allowed to use cheat sheets or similar.
  - [Exam Information/Preparation Sheet][exprep] In this document you find general information about the exam and materials for the exam preparation including a list of the most relevant exercises and a list of questions.

## Lecture Notes, Literature and Other Materials

Lecture Notes
: The lecture notes will be uploaded on [MaMpf][mampf].

Literature
: - Nocedal, Wright: Numerical Optimization, Springer, 2006.
  - Fletcher: Practical Methods of Optimization, Wiley, 2nd edition 1987.
  - Ulbrich, Ulbrich: Nichtlineare Optimierung, Birkhäuser Verlag, 2012. (German)

Other Materials
: - [MaMpf (WS 20/21)][mampfold] -> Here you find all materials from the last time that we have taught this course
  - [Skript][skript] -> Lecture Notes from the winter term 2011 (German)

[tuts]: #tutorial-format
[ws]: #collaborative-working-session
[sol]: #presentation-of-solutions
[material]: #lecture-notes,-literature-and-other-materials

[sheettut]: https://heibox.uni-heidelberg.de/f/ba748593af694234aa37/?dl=1
[nbtut1]: https://heibox.uni-heidelberg.de/f/ae5a7ea2865d45b98620/?dl=1
[nbtut2]: https://heibox.uni-heidelberg.de/f/bd67a5fbfa3a4021843b/?dl=1

[sheet1]: https://heibox.uni-heidelberg.de/f/06e19174468a4e1cb8e2/
[temp1]: https://heibox.uni-heidelberg.de/f/d228130612a242749c4c/?dl=1 
[aux1]: https://heibox.uni-heidelberg.de/f/1a918dc82b2a485c966e/?dl=1
[sol1]: https://heibox.uni-heidelberg.de/f/fd770d08a1bf45549600/
[progsol1]: https://heibox.uni-heidelberg.de/f/0a4b99b006d24f41a68b/?dl=1
[sheet2]: https://heibox.uni-heidelberg.de/f/4440d7f540e24907a107/
[temp2]:     https://heibox.uni-heidelberg.de/f/72123d64016445e68841/?dl=1
[aux2]: https://heibox.uni-heidelberg.de/f/47d117e2dc9e4b9fad67/?dl=1
[sol2]: https://heibox.uni-heidelberg.de/f/d278e3bad2094f37ab36/ 
[sheet3]: https://heibox.uni-heidelberg.de/f/d8f1bc27a0f14c64a3b1/
[temp3]: https://heibox.uni-heidelberg.de/f/10370e0eb5b4445c9a05/?dl=1
[aux3]: https://heibox.uni-heidelberg.de/f/0e1cb702b84e4d909648/?dl=1
[sol3]: https://heibox.uni-heidelberg.de/f/d9bf18e543df4cf59949/
[progsol3]: https://heibox.uni-heidelberg.de/f/5645cb4143f946158192/?dl=1
[sheet4]: https://heibox.uni-heidelberg.de/f/3dbc366466b54039ade1/
[temp4]: https://heibox.uni-heidelberg.de/f/a0e1e3b8c2af4fb4b237/?dl=1
[aux4]: https://heibox.uni-heidelberg.de/f/c5cc1cccc9fe4ab0bee6/?dl=1
[sol4]: https://heibox.uni-heidelberg.de/f/fc9e892090ab4057853a/ 
[progsol4]: https://heibox.uni-heidelberg.de/f/76d820fb585e44fe94a0/?dl=1
[sheet5]: https://heibox.uni-heidelberg.de/f/f9753323b1ba469dbf59/
[temp5]: https://heibox.uni-heidelberg.de/f/a5bba0763dd6458bbf6a/?dl=1
[aux5]: https://heibox.uni-heidelberg.de/f/3c89198746a54450b4a3/?dl=1
[sol5]: https://heibox.uni-heidelberg.de/f/7d0bbb0c142742e29cff/
[progsol5]: https://heibox.uni-heidelberg.de/f/46eb537be2be46339008/?dl=1
[sqp]: https://heibox.uni-heidelberg.de/f/3104b2671ff94f04ba86/ 
[sqpsol]: https://heibox.uni-heidelberg.de/f/aaf4e3c33a324cf1b82c/

[exprep]: https://heibox.uni-heidelberg.de/f/4a3a867575a14a10b6a6/

[ekaterina]: mailto:ekaterina(dot)kostina(at)iwr(dot)uni-heidelberg(dot)de
[ihno]: mailto:ihno(dot)schrot(at)uni-heidelberg(dot)de
[laura]: mailto:laura(dot)femmer(at)stud(dot)uni-heidelberg(dot)de
[joern]: mailto:buchwald(at)stud(dot)uni-heidelberg(dot)de
[muesli]: https://muesli.mathi.uni-heidelberg.de/lecture/view/1508
[mampfold]: https://mampf.mathi.uni-heidelberg.de/lectures/48
[mampf]: https://mampf.mathi.uni-heidelberg.de/lectures/124
[skript]: https://mampf.mathi.uni-heidelberg.de/mediaforward/medium/16121/manuscript/2a4d254a6932ae7ef82d9bcc196d27d2.pdf
[subguide]: https://mampf.blog/handing-in-homework-assignments/
[ars]: https://ars.particify.de/
[arsroom]: https://ars.particify.de/p/35356496
