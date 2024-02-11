---
title: BWInf - Career Information Day Scheduling
summary: Submission of the second round of the German National Competition in Computer Science in 2007/2008.

tags:
  - Minor
  - Optimization
date: '2008-03-23T00:00:00Z'
# Optional external URL for project (replaces project detail page).
# external_link: ''

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/LeonSering/bwinf_career_information_day_scheduling
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
This project was one part of my submission for the second round of the 26th German National Competition in
Compute Science (Bundeswettbewerb Informatik) held in 2007 and 2008. It was my first mixed integer program
and I had a lot of fun, spending all my holidays on this exercise.

### Task

The goal is to schedule a career information day at a school:

- 16 talks by parents about their work

- 4 time slots

- students provide a preference list of six talks they would like to attend

- each talk has a minimum and maximum number of participants

The task is to write a simple-to-use software that schedules the talks to the 4 time slots and optimizes the
satisfaction of students and parents with the GNU Linear Programming Kit (GLPK).

The full tasks can be found [here](Aufgabenstellung.pdf) (in German).

### My submission

I decided to use C++ with Qt4 as GUI and lifted the requirements of exactly 16 talks and 4 time slots to obtain a tool that would also
be useful for other scheduling tasks. Also, the weight of preference of the students is fully flexible, meaning that all wishes could
be equally good, or the first preference is much more preferred. The full documentation, which was part of the assignment, can be
found [here](Dokumentation_Informationstag.pdf) (in German).

<center>{{< figure src="information_day_gui.png" caption="The GUI allowed for an easy management of talks, participants with their priority list and all necessary parameters." numbered="true">}}</center>


Fortunately, my submission was successful, and I could attend the third and final round (which was an in-person
assessment), where I was selected as "award winner".
