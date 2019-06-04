# Dickinson H/FOSS Capstone

## Introduction:

This repository contains materials that support the integration of Free and Open Source Software (FOSS) experiences and more specifically student participation in a Humanitarian FOSS (HFOSS) community into a year-long capstone experience in computer science. These materials support an _in the wild_ approach where students self-select an H/FOSS (FOSS or HFOSSS) project and participate directly in its community. A discussion of this approach and a comparison of it to other possible H/FOSS capstone approaches can be found in:

*	Braught, G., MacCormick, J., Bowring, J., Burke, Q., Cutler, B., Goldschmidt, D., Krishnamoorthy, M., Turner, W., Huss-Lederman, S., Mackellar, B. and Tucker, A. (2018). [A Multi-Institutional Perspective on H/FOSS Projects in the Computing Curriculum](https://doi.org/10.1145/3145476). ACM Transactions on Computing Education. 18(2), Article 7 (July 2018), 31 pages.

This repository will focus solely on the materials for the _in the wild_ approach developed in the [Department of Computer Science](https://www.dickinson.edu/homepage/57/computer_science) at [Dickinson College](https://www.dickinson.edu/). We began using this approach in fall 2016 and these materials have been added to and refined in each of the two years since, and they will continue to evolve over time. However, this repository will remain a static point of reference in their development. Please feel free to reach out if you are interested in the most recent materials.

## Course Context:

The Senior Seminar in computer science at Dickinson is a year-long capstone experience consisting of a full course in both the fall and spring semesters and is required of all computer science majors during their final year. Students in the seminar engage in either an H/FOSS project or in an honors research project.  The materials in this repository focus solely on the materials that support the H/FOSS project option. The course meets for 75 minutes twice per week for 14 weeks plus a three-hour final exam period each semester.

The goal of participation in an H/FOSS project is to provide a transition from the study of computer science at the undergraduate level to experiences more aligned with professional practices. Students gain experience working on a large on-going project, learning new project specific tools and processes, reading and modifying code created by others and interacting with a professional level developer community. In addition, the senior seminar includes relevant technical skill development and professional preparation though exposure to a variety of topics in software engineering, and readings and discussions of contemporary social/legal/ethical issues in computing.

Prior to taking this capstone all majors will have completed the core courses including a two-course introductory sequence in Java, a data structures course in Java and a computer organization and architecture course.  Students will also have completed or be taking concurrently courses including: analysis of algorithms, theory of computation, programming language structures and operating systems or computer networks.

At the time these materials were developed and refined our curriculum contained little formal introduction to H/FOSS, system administration, version control or Unix tools prior to the capstone. Thus, the materials below provide much of that background material as well as guiding the students into participation in their chosen H/FOSS communities. Based on our experiences this senior capstone we have significantly redesigned our curriculum (beginning fall 2019) so that the technical skill development necessary for H/FOSS participation as well as consideration for social/legal/ethical issues occurs earlier and is distributed across a number of courses. Our website contains the full details of the [computer science curriculum at Dickinson](https://www.dickinson.edu/homepage/402/computer_science_curriculum).

## Materials:

The [full website for the Senior Seminar (COMP 491/492)](https://htmlpreview.github.com/?https://github.com/braughtg/DickinsonHFOSS-SFC-Materials/cs491f18/cs491f18.html) is included in the [cs491f18](./cs491f18) folder in this repository. The items below link to the course elements that focus specifically on the H/FOSS aspects of the course. Materials that were used in discussions of software engineering and (non-HFOSS) social/legal/ethical issues are not included here but do appear on the full site linked above. The materials below are organized by topic and can be assembled into a full H/FOSS capstone course.

#### Technical Skills Development
This set of activities, tutorials and homework exercises introduce students to many general tools and skills that are necessary for participation in FOSS projects.  They are completed as a combination of homework and in-class hands-on activities.

* [Blog/Slack/Wiki/GitHub](./cs491f18/blogslackwiki.html)
* [Ubuntu Install](./cs491f18/ubuntuinstall.html)
* [Unix Tools Challenges](./cs491f18/unixtools.html)
* [Software Installation](./cs491f18/swinstall.html)
* [GitHub Workflow](./cs491f18/github.html)
* [Bash Scripting](./cs491f18/bashscript.html)
* [Building an Open Source Project](./cs491f18/build.html)
* [Getting Around in a FOSS Project](./cs491f18/gettingaround.html)
* [Patching a FOSS Project](./cs491f18/patch.html)

#### H/FOSS Discussion Topics & Readings
Students are assigned readings on a variety of topics related to FOSS and H/FOSS. A class discussion following the completion of the readings explores and reinforces the most interesting and important points.  Following each discussion students write a reflective blog post exploring an aspect of the topic of interest to them.

* [H/FOSS History & Philosophy](./cs491f18/cs491f18.html#0906)
* [H/FOSS Project Community](./cs491f18/cs491f18.html#0913)
* [H/FOSS Project Tools/Structures/Communication](./cs491f18/cs491f18.html#0917)
* [FOSS Licensing](./cs491f18/cs491f18.html#1101)
* [H/FOSS Motivations](./cs491f18/cs491f18.html#1206)
* [FOSS Success Stories and Criticisms](./cs491f18/cs491f18.html#1210)

#### H/FOSS Project Activities
The following set of activities form the core of the students' selection and participation in an H/FOSS project community.

* __Project Selection__ - These activities progressively build toward the formation of project teams and the selection of H/FOSS project communities.  Each activity lasts a week to a week and half.
  * __Activities__:
    * [H/FOSS Project Exploration](./cs491f18/projexpl.html) - Students each identify and explore four H/FOSS projects that are of interest to them.
    * [H/FOSS Project Reviews](./cs491f18/projrev.html) - Students dig deeper into the community and technical details of two of the H/FOSS projects that they explored.
    * [H/FOSS Project Ranking & Selection](./cs491f18/projranking.html) - Teams of 2-4 are formed around general areas of interest and commonly reviewed projects. Teams evaluate and rank H/FOSS projects that the members have reviewed and select the one on which the team will work for the year.
* __Project Setup & Familiarization__ - Teams complete these activities to install and begin to familiarize themselves with their H/FOSS projects.  Teams of more than 3 sub-divide into sub-teams of 2-3 and each sub-team works independently. However, the sub-teams share information and provide assistance and guidance to each other. Each project is different. Some are easy to install and build, others are much more difficult. Thus, these activities do not have due dates. Rather they have completion criterion. When a team or sub-team can demonstrate that they have satisfied the completion criterion they move onto the next activity.
  * __Activities__
    * [User Installation](./cs491f18/projinstalluser.html)
    * [Developer Installation](./cs491f18/projinstalldev.html)
* __Project Contributions__ - Once familiar with the project and a working developer install has been completed, these activities guide the students through increasingly deep participation in their H/FOSS project communities.  Like the prior activities, these each have completion criterion rather than due dates as the effort involved in each will vary significantly from project to project. Most teams or sub-teams complete the Bug Gardening activity by the end of the first semester and the Bug Fixing activity by the end of the second semester.  Many teams or sub-teams make a variety of other contributions to their projects by the end of the year.
  * __Activities__
    * [Bug Gardening](./cs491f18/projbuggardening.html)
    * [Bug Fixing](./cs491f18/projbugfix)
    * [Project Contribution](./cs491f18/projontrib.html)

#### Course Deliverables & Assessment
Assessment of student work is done through a number of deliverables and assessments.

* [Preparation / Attendance / Engagement (PAE)](./cs491f18/syllabus.html#pae) - Students receive a mark for each of these elements for each class meeting.
* [Tutorials / Homework Exercises](./cs491f18/syllabus.html#hw) - During the first semester, each of the technical skill development activities and project selection activities are graded.
* [Reflective Blog Postings](./cs491f18/syllabus.html#blog) - Students write reflective blog posts following readings and class discussions.  These are assessed and feedback is provided at several points during each semester.
* [Project Selection](./cs491f18/projpres.html) - Teams give a presentation on their selected H/FOSS project.
* [Code Review](./cs491f18/coderev.html) - Individual students present a snippet of code from their H/FOSS project.
* [Poster Presentation](./cs491f18/poster.html) - Teams produce and present a poster describing their year's work at a public poster sessions near the end of the second semester.


* [H/FOSS Project Checkpoints](./cs491f18/syllabus.html#ProjCheckpoint) - Following the selection of the H/FOSS projects, teams progress through the H/FOSS Project Activities at different rates. Thus, assessment is done by evaluating the work done by each individual and each team at specified checkpoints rather than based on completion of the activities. Typically there are two checkpoints each semester, one mid-semester and one during the final exam period. At each checkpoint work is assessed along six dimensions:
  * _Daily Reporting_ - Teams or sub-teams maintain [Slack Live-Logs](./cs491f18/syllabus.html#SlackLiveLog) as they work detailing what they try, what works, what doesn't work and what resources they have used.  This provides a useful record for the students and a fine grained documentation of their efforts.
  * _Individual Weekly Reporting_ - Each student writes an (approximately) weekly [Five-Fifteen Report](./cs491f18/syllabus.html#fivefifteen) reflecting on their individual work over the past week and setting goals for the next week.
  * _Team Weekly Reporting_ - Each team writes an (approximately) weekly [Five-Fifteen Report](./cs491f18/syllabus.html#fivefifteen) reflecting on the team's work over the past week and setting goals for the next week.
  * _Team Checkpoint Presentation_ - At each checkpoint, each team gives a presentation summarizing their work to date.
    * [Mid-Semester Checkpoints](./cs491f18/syllabus.html#ProjCheckpoint)
    * [End of Fall Semester](./cs491f18/sem1finalpres.html)
    * [End of Year](./cs491f18/finalpres.html)
  * _Individual Effectiveness_ - This is the instructor's assessment of the individual's effectiveness in the project work.  It is based on interactions in class, out of class, a review of the individual and team 5-15 reports and the team and sub-team Slack live-logs.
  * _Team Effectiveness_ - This is the instructor's assessment of the effectiveness of the team in the project work.  It is based on interactions in class, out of class, a review of the team 5-15 reports and the team and sub-team Slack live-logs.

## Experiences and Observations

Overall this course has been successful in each of the last three years and has been improving with experience each year.  Below are several observations about the course that may prove helpful for anyone adopting or adapting our materials and approach.

* __Managing Expectations:__ Students are drawn to the idea of H/FOSS and making a difference though contribution to these projects.  However, in general these projects are much larger and more complex than what they are used to. They need to learn the tools, processes and technologies, become known and comfortable in the community and find approachable issues on which they can work. This takes time. In our experience, students often become frustrated with the "small" contributions that they are making (documentation refinement, bug gardening, bug fixes, etc). Students often do not fully recognize the value of these contributions to the larger community or fully appreciate the number of people impacted by their efforts. Conversations about the impact have been effective in helping students to recognize the value of their contributions.  In addition, discussions of the learning goals (as opposed to contribution goals) of the course are helpful in emphasizing the future value of the experiences beyond technical code contributions for them as individuals. In particular, students gain significant practice with soft skills. They often report "learning how to ask questions" and "learning how to find resources" as some of the most valuable experiences.
* __Community Engagement:__  In our experience students are initially reluctant to engage and communicate with the project community in other than superficial ways.  When faced with a technical challenge or in attempting to understand an issue they are hesitant to reach out for fear of "not knowing enough." They struggle in silence using google and project documentation to try to figure out issues with which the community may be able to give quick guidance. Such struggle is important for them to have confidence that they are not "asking a stupid question." Helping students figure out how to identify when the issue is not their limited knowledge and it is time to reach out is an important part of the faculty role in this course. Monitoring Slack Live-Logs and 5-15 reports can help identify when teams have reached the point where they will benefit from engaging the community. Helping students compose their first e-mail or forum post and reviewing drafts of it before they send it off to the community has been helpful in encouraging them to reach out.  Typically once they clear this initial hurdle they quickly engage much more deeply.  Some teams will begin this process if difficulties are encountered during the User or Developer Install, but other only begin during the Bug Gardening activity, which requires it. However, most teams will not engage deeply with the community until they spend some time working on a Bug Fix. Occasionally there are teams that continue to resist engagement with the community through the full year. Invariably, we find that the teams that engage report greater satisfaction with their experiences and generate more contributions than those that do not.
* __When to Intervene:__ While for our _in the wild_ approach we hope that students are able to engage with and obtain the technical support that they need through the project community, that is not always practical. When student queries do not receive responses, or repeated responses prove unhelpful, it is often necessary for faculty to try to wade into the technical details.  We have found this happens most often, and is most effective, during the Developer Install activity. Most projects have documentation for the install, but it is often out of date and/or incomplete.  This results in students having difficulties completing the install and until this activity is complete students cannot progress to the other activities.  When teams struggle it can be very helpful for the faculty to do an install and then provide additional pointed guidance to the teams. When multiple sub-teams are working on the same project, one sub-team will often also be able to help the others.  In some cases, once one sub-team has a working developer install they can share it or at least the information necessary to complete the install with the other sub-team(s).  In extreme cases, the instructor can provide a working developer installation.
* __Getting Scooped:__  Some projects assign issues to individuals who are working on them, while others do not. Even in projects where assignments are made, the frequency with which people abandon assigned issues means that other contributors will sometimes swoop in anyway. Getting scooped on an issue they are working on is one of the more frustrating things that happens to students. Often what happens is students will begin working on an issue they find in the issue tracker and will initiate a conversation on the issue to ensure that they fully understand it. Then, after a few messages back and forth, one of the main project contributors makes a pull request for a fix. Students then worry that they have wasted their time. Pointing out that they have had an important learning experience in understanding and beginning to fix the bug and that the grading scheme used in the course values that effort through their Live-Logs and 5-15 reports, generally helps to mitigate the effect of this experience.  In practice, their efforts when this happens are no less valuable within the course than if they had actually fixed the bug. Knowing that the bug has been fixed and that their drawing attention to it and refining the understanding of it contributed to that fix also provides some satisfaction.
* __Virtual Machines:__ We highly encourage students to use a virtual machine when installing and working on their chosen project.  Having a common platform makes it much easier for the instructor and sub-teams to share information. When students use their individual machines, each machine is different and thus things that work for the instructor or one sub-team will often not work for another. Virtual machines also provide snapshots and the ability to share machine images.  The ability to roll back to a snapshot is invaluable when working through installation processes. Sharing images can allow sub-teams to synchronize their machine states and to get back up and running much more quickly in the event of accidental system corruption. In our experience students are resistant to using virtual machines and thus require strong encouragement to do so. This resistance can be compounded when students' individual machines do not have the power necessary to run a virtual machine efficiently. With web-based applications, running the server in the virtual machine but the web browser on the host machine can help mitigate performance issues somewhat. The availability of lab machines with more memory and faster processors can provide an alternative with better performance. However even with such availability we have found that students strongly prefer to try to work on their own machines.  Often it isn't until they struggle with crashes, configuration issues, multiple reinstalls and poor performance that they come to fully appreciate the benefits that the virtual machine offers.

## Improvements

Based on our experiences with these course materials over the past three years there are a number of improvements that we plan to make.

* __Project Review & Selection:__ Overall the project review and selection process has worked very well. There are a few possible improvements that we believe will lead to more fully informed choices and better overall outcomes. We plan to require that any project being considered for selection include some type of automated testing suite. This is standard practice in most modern projects and without it too much perspective and experience with the project is required to predict ripple effects and to validate changes. We plan to update the Project Review activity to force the consideration of quality and organization over quantity with regard to documentation. Some teams have gone into selected projects only to find out that the mass of documentation they believed they had was poorly written, disorganized, redundant, outdated and/or inconsistent. Similarly, we plan to adapt this activity to more carefully consider the diversity of participation on communication channels. Some teams had reported highly active communication channels, but later had difficulty getting responses because the vast majority of the communication was a few core contributors discussing issues amongst themselves.
* __Developer Installation:__ Currently the Developer Installation activity requires that students make a "cosmetic change" to the application in order to show that they can rebuild it from source. Too often teams have made changes to configuration files, non-compiled code (e.g. html/css), or code that is not manipulated (copied/compiled/etc...) by the project's build process. When they do this, they see a "cosmetic change" but they have not ensured that they can properly build the project to incorporate changes to code that is manipulated in some way by the build process. This leads to challenges later. When attempting a bug fix, an important step is to ensure that they are working on the correct bit of code by making and observing a behavioral change (e.g. the old add a print statement). If they make a change, and do not see the associated behavior change the problem could be that they are in the incorrect place, or it could be that they have not rebuilt the project properly. Thus, we plan to modify the Developer Installation to require a "behavioral change" rather than a "cosmetic change."
* __Technical Tutorials:__ We plan to develop an activity that requires students to complete tutorials on the technologies used by their project. This activity will immediately follow the Developer Install. We have encouraged students to complete such tutorials as a part of their work while they are going through the Bug Gardening activity. In practice, this has not been as effective as we would like.  Students thus often begin the Bug Fix activity with an insufficient understanding of the specific languages, frameworks and tools used by their project.  This results in unfocused ad-hoc attempts to piece together an understanding of the code on which they are working. We are hopeful that adding, up front, a few weeks of foundational technical tutorials on the languages, frameworks and tools used in their project will enable them to fill in details more efficiently later.
* __Code Reviews:__ Currently students do a code review about half way through the second semester. The idea had been that they would present a piece of code on which they had worked. In practice, about half of the students had not completed a bug fix by that point in time making it difficult for them to present on the code. Many others had an incomplete and ad-hoc understanding of the language and frameworks being used. Further, students often reported that being required to present code is what forced them to gain a better understanding of the language and frameworks used by the project. Thus, we plan to move the Code Review to the first semester, having it follow the completion of the Technical Tutorials. Because they will not have written or modified any code at that point, the code review will be based on an issue that has been closed by someone else. They will describe and illustrate the issue, discuss the solution and present the code changes from the commit that resolved the issue.
* __Marking Scheme:__ The syllabus and rubrics provided in these materials use a (admittedly idiosyncratic) marking scheme that assigns &#x2714;+, &#x2714;, &#x2714;-, or 0 for all assignments. The intention was that &#x2714;- was for unacceptable work, &#x2714; would be a very wide category for all acceptable work and that &#x2714;+, would be for exceptional work. The hope was that marks could be assigned very frequently and also very quickly. The amount of unacceptable and exceptional work would then be what differentiated students.  In practice, the system has worked fairly well but has insufficient granularity, resulting in &#x2714;+ being used too often. Going forward, &#x2714; will be for acceptable work, &#x2714;+ for very good work and a new category &#x2714;++ will be added to recognize exceptional work.

## Additional Resources

* Course Surveys - A pair of course surveys have been given each year to assess the impact of the approach on a variety of student perceptions.
  * [Pre-Survey](./resources/DC-COMP491-PreSurvey-F16.docx) - Word source for the survey given at the start of the year.
  * [Post-Survey](./resources/DC-COMP491-PostSurvey-F16.docx) - Word source for the survey given both at the end of the first semester and the end of the year.
* [Grading Rubrics](./resources/Rubrics.xlsx) - Excel source for all of the rubrics used in the course.
* [slackalytics](./resources/slackalytics.zip) - A Slack integration used to gather message statistics from Live-Logs through Google Analytics. This integration can be attached to each team or sub-team channel to collect message count and word count data by day and channel and user.  This provides summary information to complement content reviews of the Slack Live-Logs, and makes it easy to visualize how teams are distributing their work over time. The original [slackalytics](https://github.com/NicoMiceli/slackalytics) project is on GitHub.

---
#### Acknowledgements:

Partial support for the development of these materials has been provided by:
* A grant from the [Software Freedom Conservancy](https://sfconservancy.org/) (July 2018-June 2019).
* The National Science Foundation through a [course materials sprint](http://foss2serve.org/index.php/Course_Materials_Sprint_2018) organized by [foss2serve](http://foss2serve.org/index.php/Main_Page)

Thank you to the following individuals and groups who provided personal input and assistance in the creation and refinement of the materials provided here:
* Dickinson College computer science faculty including:
  * John MacCormick
  * Farhan Siddiqui
  * Michael Skalak
  * Tim Wahls
* The Foss2Serve and POSSE communities including:
  * Darci Burdge
  * Heidi Ellis
  * Greg Hislop
  * Stony Jackson
  * Chris Murphy
  * Lori Postner
  * Karl Wurst
* All of the students in COMP 491/492 at Dickinson College from from fall 2016 through spring 2019.

I want to thank the following for providing invaluable resources that gave me  pointers to readings and/or inspired and informed the activities for this course:
* Karl Fogel for his book [Producing Open Source Software:
How to Run a Successful Free Software Project](https://producingoss.com/en/index.html)
* Greg DeKoenigsberg, Chris Tyler, Karsten Wade, Max Spevack, Mel Chua and Jeff Sheltren for their book [Practical Open Source Software Exploration: How to be Productively Lost, the Open Source Way](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/index.html)
* Chris Murphy for his [Open Source Software Development](https://www.seas.upenn.edu/~cdmurphy/foss/fall2016/) course at University of Pennsylvania.
* Heidi Ellis for her [Software Engineering](http://mars.wne.edu/~hellis/CS490/syllabus.html) course at Western New England College.
* Everyone who has contributed to the  [Learning Activities page on foss2serve](http://foss2serve.org/index.php/Category:Learning_Activity). Many of the materials for this course were adopted, adapted or inspired by the excellent activities on that page.

---
#### Licensing:

![Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License")
###### All textual materials provided in this repository are licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)
