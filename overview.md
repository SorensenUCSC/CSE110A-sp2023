---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Overview"
layout: single
classes: wide
---

## Class Description

Welcome to CSE 110A: Fundamentals of Compiler Design! In this class we will explore one of the most import tools in computer science: the compiler. In particular, we will explore how compiler techniques transform high level languages into low-level languages, i.e. closer to the instructions that processors can actually execute. We will study how compilers can automatically make code more efficient and safe to execute. When you leave this class you should be comfortable with: specifying programming language grammars, how to efficiently parse these languages, and how to convert complex high-level code into equivalent (and hopefully more performant) low-level code. 

Given the influx in domain-specific languages, and the explosion of architectural diversity occuring in computing today, these are valuable skills.

## Teaching Staff

We have a great teaching staff this quarter! All of them have lots of experience in compilers. Please get to know them and take advantage of the office hours and mentoring sessions they provide

- *Grad TAs*: Devon McKee, Rithik Sharma
- *Undergrad Mentors/Graders*: Sanya Srivastava, Arrian Chi, Gurpreet Dhillon

## Necessary Background

The prerequisites for this class are CSE 12 (systems) and CSE 101 (data-structures and algorithms). You will need some foundation in all of those topics to succeed in this class. You will need to know data-structures as we will use lots of trees and traversals in parsing. You will need some systems background as we will be discussing how to transform a high-level programming language into a low-level language (like assembly). CSE 103 will also be helpful as we will be using regular expressions and context-free grammars.

Because this is an upper division class, I do expect a general CS foundation. For the homeworks, I will assume that you are:

- comfortable using a linux command-line
- programming in a high-level language (e.g. Python)
- programming in a low-level language (e.g. C)

## Class Modules

This class will be split into 5 modules, each of which are roughly two weeks:

* **Module 1: Lexing** 

* **Module 2: Parsing** 

* **Module 3: Intermediate Representations** 

* **Module 4: Optimizations**  
 
* **Module 5: Backends** 

## Class Format

Each class is 65 minutes. I plan to stay after class for roughly 15 minutes to answer questions. Please be respectful of time and make sure that everyone who stays afterwards is able to see me. We will meet out in the hallway so we do not disturb the next class.

_Non-protected materials_ will be hosted on this website. This includes the schedule, lecture slides, and references, etc.

_Protected materials_ will be hosted on a Canvas website that you will need your university credentials to access. These materials include homeworks, lecture recordings, tests, grades, etc.

We plan to host a class forum, likely in Piazza. If you organize other forums outside of the class Piazza, please adhere to academic integrity.

## Attendance

Live discussions are a valuable part of the learning experience. I expect you to make an effort to synchronously attend this class (which will hopefully be in person all quarter).

Depending on the availability of recording equiptment, I will upload recordings of the class to canvas, but this is not a substitute for attendance. These recordings are not guaranteed (e.g. if the equiptment fails). And you will likely miss out on class discussions and may not be able to see the white board.

## Quiz

There will be a quiz for each lecture. These quizes will be assigned immediately after class and you will have until the next class starts to do them. . These are meant to test your understanding, and will not be graded for correctness, but instead, graded for engagement. Any multiple choice question will be awarded full points: any open response question will be graded on if there was some sign of engagement (e.g., a few thoughtful sentences written). These quizes will account for 10% of your class grade. 

You can miss up to 3 quizes without penalty.

## Accessibility

UC Santa Cruz is committed to creating an academic environment that supports its diverse student body. If you are a student with a disability who requires accommodations to achieve equal access in this course, please submit your Accommodation Authorization Letter from the Disability Resource Center (DRC) to me by email, preferably within the first two weeks of the quarter. I would also like us to discuss ways we can ensure your full participation in the course. I encourage all students who may benefit from learning more about DRC services to contact DRC by phone at 831-459-2089 or by email at drc@ucsc.edu.

## Office Hours:

### Instructor Office Hours:

I will provide 2 office hours per week: Thursday 3 - 5 PM

My office hours can be remote or in-person. My physical office is E2-233. I will provide a zoom link closer to the time. I manage the office hours through a Google doc sign-up sheet. I will reset the list around noon on Thursday and notify with a canvas announcement. Any name on the list before then will be erased.

Please sign up for only 1 slot at a time. If there is no other student waiting at the end of your slot, you are welcome to stay. If you want to discuss an issue that you think others might also be interested in, please add the issue to the spreadsheet. If you see your issue listed, please add your name and we add more people to the discussion. 

The sign-up sheet is meant to provide fairness; as such I will be strict about keeping to the schedule. Please forgive any abruptness.

### TA Office Hours:

Devon is available on Tuesdays from 3:00PM to 5:00PM, virtual.

Devon will use the Zoom waiting room feature, and answer questions first-come-first-serve. Please try to keep your question within 10 minutes. 

[Zoom Link](https://ucsc.zoom.us/j/6705118855?pwd=alQ1SmlFbzFXMlQrYVFET1JiK1pJQT09)


Rithik is available on Fridays from 3:00PM to 5:00PM, TBD.

Rithik’s office hours will be hybrid and he will use a similar sign-up sheet.

### Mentoring Hours:

Arrian is available on Thursdays from 1:00PM - 3:00PM, virtual.

Neal is available on Tuesdays and Thursdays, 6:30PM - 7:30PM, [virtual](https://ucsc.zoom.us/j/99946604176?pwd=NlQ3MWRxbXZsK2kzOVdzTVNTVmdrZz09).

## Asynchronous Communication

For any questions outside of office hours: Please post to the class forum (Piazza). If these are sensitive questions, please make the post private. If it is more general, make it visible to the rest of class. If it isn't clear if it is a sensitive question or not, please start out by making the question to the teaching staff and we can advise on making it public or not. Feel free to answer questions that your classmates post or freely participate in discussions there!

Please do not email us individually. Those emails get buried, or they might not be seen by the right member of the teaching staff. Any re-grading requests must occur through Piazza.

We will strive to reply to homework questions and discussions within 24 hours. Do not plan on, or expect help, outside of regular business hours (after 5 pm or weekends)

## Homework:

We plan to redesign our homework setup to be more scalable and provide automated feedback. To do this, we will use github classroom. Because this is a new setup, there may be some friction getting started. We appreciate your patience and understanding. I will update the class as we make progress.

While we don't have all the details yet, we will provide a docker for you to develop in. We plan to enable a git-based workflow where you push your current solution to a repo and receive feedback from a server. You will be graded on the server feedback rather than the results from your own machine. This is to help provide fair (and scalable) grading across the increasing diversity of devices that everyone has these days. 

Homeworks are due at midnight on their due date, but do not plan on help after 5 pm.

This class has homeworks that build on each other, that is, later homeworks will use earlier homeworks. We will provide reference solutions so that your later homeworks are not impacted by mistakes in earlier homeworks. Because of this, we cannot accept late homeworks and we will be strict about this. Please keep this in mind. It is a good idea to plan to have homeworks done in advance, or upload checkpoints.

## Tests:

There will be two tests in this course: a midterm and a final. The midterm will roughly be worth as much as a single homework assignment (~10%). The final will be worth 30%.

The midterm will be given halfway through the class: Monday May 8th
The final will be given on: Monday, June 12	8:00–11:00 a.m.

## Grade Breakdown

- Attendance/Quiz: 10%
- Homeworks: 50% (10% each)
- Midterm: 10%
- Final Exam: 30%

If you want to discuss a grade, please contact the teaching staff no later than 1 week after the grades are posted.

## Academic Integrity

One of the joys of university life is socializing and working with your classmates. I want you to make friends with each other and discuss the material. 

**That said, I expect all assignments (code, write-ups, and tests) to be your own original work.**

If you work together with a classmate on an assignment, please mention this, e.g. in the comments of your code. If you use a figure you didn't create in a write-up, then it needs a citation. Please review the [universities policy on plagiarism](https://guides.library.ucsc.edu/citesources/plagiarism)

This class has a zero tolerance policy on cheating. Please don't do it. I would much rather get a hundred emails asking for help than have to refer anyone for academic misconduct.

## Privacy

I plan to record in-person lectures, and in case I need to be remote, I will use zoom. Please keep the following in mind:

- Things you do or say will be recorded. I doubt that this will be an issue, but if you want me to remove any part of the recording, please just let me know.
- Many forums (e.g. zoom chats, Piazza posts, etc.) chats are not private. Please be respectful and kind and assume everyone can see what you are typing.

## Acknowledgements

This page is based off of Professor [Lindsey Kuper](https://users.soe.ucsc.edu/~lkuper/)'s CSE232, Fall 2020 website
