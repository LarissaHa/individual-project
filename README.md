# Individual Project HWS2018
Analyzing Learning and Working Behaviour of Students with E-Learning Support

With  proceeding  digitization  in  educational  realms,  today’s  learning  more  and
more involves the use of Learning Management Systems (LMS). These systems
(like ILIAS in the actual case) can be customized to individual needs and accessed
and used with an ordinary browser. Within this online e-learning system, lecturers,
tutors, and students are able to communicate and work together in various differ-
ent ways.  All this actions and connections between users, as they are happening
online, are recorded and stored and can be therefore used for data analysis.
The underlying goal of this project and the related report at hand is to connect
the data of LMS usage of students to their exam results, and to answer some of the
following questions en route:
•  How do students work with the e-learning system?
•  Do more active online-users yield an advantage for their studies?
•  Can we predict the failure of students (and how early during the ongoing
semester)?
•  What are the possibilities of these methods, given we had more data?
This project took place in the Spring Semester 2018 under the supervision of Prof.
Dr.  Heiko Paulheim (Chair for Data Science), and in close collaboration with the
Computing Center and Dr.  Daniel Klasen (Chair of Economic and Business Edu-
cation - Learning, Design and Technology), who provided access to the collected
data.

## Content
0 - These notebooks are created to clean and merge the different data sets so I have a base to build my work upon.
1 - students had the possibility to decide if their actions in ILIAS should be tracked anonymously or with pseudonyms. A decision
for pseudonyms would imply that the events in the data set (produced by the actions taken in ILIAS) can be connected to the results of the homework assignments and the final exam.  But because of the low rate of pseudonymously tracked students, we need to make sure that this group of students is not a self-selected, statistically different subset from the population. The pseudonymous students should have the same characteristics as the anonymous students.
2 - Having the data about working behaviors of students at hand, a short additional analysis of the tutorial teams could be interesting for lecturers as well as for the students themselves. Some would expect to find the teams formed by equally good
students, or weaker students to seek the company of better students to make passing the course more easily.
3.1 - Can we predict failing/passing students and how good?
3.2 - How evolves prediction accuracy over the weeks of the semester?
3.3 - Can we predict better, if we only include those students who really tried to write the exam (and were not failing "on purpose")?
3.4 - What about predicting not only 2 but 3 classes, with a "risky" category in the middle around the passing threshold?
3.5 - What happens, if we include ILIAS data (and therefore lose a lot of records)?
