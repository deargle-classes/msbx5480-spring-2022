---
title: Syllabus
school: CU
year: "2022"
semester: spring
course_name: Information Security Management
coursenum:
 - MSBX-5480-001
 - MSBX-5480-574
slack: https://infosecmanagements22.slack.com
layout: page
---

<div><strong><em>Sections</em></strong></div>

{% for item in page.coursenum %}- {{ item }}
{% endfor %}

<div id='nav-bar'></div>

Instructor
: Dave Eargle  ([contact](<mailto:David.Eargle@colorado.edu>))

Class
: See [my.cu.edu](https://my.cu.edu) for schedule

Office Hours
: See canvas

Slack
: [{{page.slack}}]({{page.slack}})


# Course Description

Learn how to secure systems and the enterprise using cryptography,
authentication, and ethical hacking. You will also identify and communicate
cybersecurity risks facing businesses through risk assessment reports that
support management decisions.


# Learning Outcomes

1.	Explain cybersecurity as a key enterprise risk and how it can be managed.
2.	Apply methods to identify, protect against, detect, respond to, and recover from cybersecurity threats.
3.	Use techniques of ethical hacking to perform penetration testing.
4.	Communicate risk assessment reports that support management decisions.



# Content note

Information security overlaps with politics. In this class, we will at times
examine the tension between security and surveillance. Statements from the
community of information security professionals and experts may be at odds with
statements from government or law enforcement representatives. The freedom to
critique a public policy, public servant, government agent, or government agency
is healthy in a democracy insofar that it encourages critical thinking, which
then in turn impacts public policy through citizen participation in local and national
politics.

During the class, we may critically analyze things that politicians and other
public servants say and do that impact information security or that illustrate
class topics. I will share my own views on topics. I will do my best to make our
discussions a place where we can engage bravely, empathetically and thoughtfully
with potentially difficult content.


# Communication

We will use Canvas and Slack for course communication.

Slack will be used for assignment help and for lighthearted banter.
Please install laptop and phone apps so that you receive notifications. Add an
account at [{{page.slack}}]({{page.slack}}). Use your `@colorado.edu` email
address for instant verification.

If you need assignment help, usually you should ask on a public channel on slack.

You _are required_ to be aware of all announcements made on Canvas. However,
while Slack is an important part of class participation, you are _not_ required
to read everything that happens on slack to complete assignments.


# Technology Requirements

We will use Google Cloud Platform (GCP) to run tools and virtual machines
necessary to complete assignments. New accounts on GCP get a $300 credit. You
should be able to complete this class without going over that cost. However, you
must supply a credit card number to receive the $300 credit. Separately from
this, you will also need to purchase access to lab materials via the
[security-assignments.com storefront](https://security-assignments.com/store).

**You do not need to install anything on your personal computer to complete class assignments. You only require a stable internet connection.**
You will launch a virtual machine instance on GCP from which you can complete class
assignments. You will be able to remotely connect to your instance using Chrome
Remote Desktop, which works just like a browser tab.

Note: This class will require that you learn a bit of Linux and cloud computing. This
class may _feel_ like computer science at times, but it is not. While you will
_run programs_ from a command line, you will not _write programs_.


# Required Readings

Readings will be assigned from various books, blog posts, and business cases, including the following:

* Required: "Security Engineering 2e/3e" by Ross Anderson (2e available online for free [here](http://www.cl.cam.ac.uk/~rja14/book.html))
* Required: "Data Breach at Equifax" Srinivasan et al Harvard Business Case (See Canvas for a link) ($4.25)
* Optional: "Secrets & Lies: Digital Security in a Networked World" by Bruce Schneier (available digitally through the university library)

Many of the book readings are available for free through the university library. See Canvas for links.


# Late Work

All assignments and projects are to be submitted on time or early, so plan
accordingly. If you must miss class, please submit your assignment early. On
rare occasions, an exception may be granted, allowing the student to submit
the work late with a 20% penalty. Under no circumstances will anything be
accepted more than a week late.


# Certification Option

As an option, students seeking certification may replace the final exam by
passing the Security+ certification or another certification approved by the
instructor. You can substitute your score on the certification (plus an
adjustment — 5% for the Security+) for the final. For example, if you received
an 85% on the Security+ exam you would receive a 90% for your final exam score.

To receive credit for the certification, a student must show evidence of having
taken the certification exam by the last day of class. If a student doesn't show
the instructor evidence of passing the certification by this date, then they
will be required to take the final exam.



# Point Distribution

| Category | Weight     |
| :------------- | :------------- |
| Labs       | 30       |
| Penetration Test Project       | 30       |
| Final Exam       | 30       |
| Reading Quizzes       | 4       |
| Security Films       | 1       |
| Participation       | 5       |


| Extra Credit | Value     |
| :------------- | :------------- |
| Third security movie       | Replace 1 reading quiz       |
| Read a security book       | Replace 1 lab       |



# Grading Scale

{: .table .table-condensed }
| Grades         | 100-point Scale     |
| :------------- | :------------- |
| A       | 93       |
| A-       | 90       |
| B+       | 87       |
| B       | 83       |
| B-       | 80       |
| C+      | 77       |
| C      | 73       |
| C-       | 70       |
| D+      | 67       |
| D       | 63       |
| D-       | 60       |
| F       | 59 or less       |


# Assignments


## Labs

Labs are hands-on learning activities associated with material covered in class.
Labs are completed outside of class, and are typically due one week after they
are introduced in class.

<a class='btn btn-success' href='https://security-assignments.com'>Go to the Labs</a>


## Penetration test project

This is a group project. The midterm will be a vulnerability and penetration
assessment report of a server. Teams of students will be given an IP address of
a server to assess for security weaknesses. The final deliverable is a written
report. The report will be due two weeks later.

## Readings Quizzes

Many assigned readings have associated quizzes. Quizzes are
**open book, open Internet** and must be completed within 30 minutes. Quizzes are
administered through Canvas.


## Security Films

Two films are required viewing for this course: "Zeros Days" and "Citizenfour."
To receive credit, watch each film and simply indicate that you watched the
whole film and give your brief reaction to the film on a quiz posted on Canvas.


## Extra Credit

You can **replace your lowest quiz score** by watching a third _security film_ from the [Security Readings and Films list](https://security-assignments.com/books-and-films/). Report it as for the required security films. submitting a few sentences about what you thought about it.

Similarly, you can **replace your lowest lab score** by reading a _security book_ from the [Security Readings and Films list](https://security-assignments.com/books-and-films/). Submit your report on Canvas.



# Classroom Policies

## Participation Policy

Most students will earn 80% of these points. Students who are exceptional and go
above and beyond in enhancing the classroom experience may receive a higher
score.

The following list is not comprehensive, but rather an example of items considered for the class participation score:

* Constructive participation on the **class slack workspace.**
* Completing the **final course evaluation**
* Taking in-class activities seriously
* Treating others with respect
* Showing courtesy for presenters (guest speakers, instructor, students)
* Participating in class discussions
* Arriving on time and not leaving early
* Not using technology inappropriately (i.e., not distracting yourself or others)
* Self-reports and justification about degree of helping others.


## Teamwork

In this class, you will work in teams. As a result, consider reviewing a short report on [team effectiveness]({{site.baseurl}}/classes/general/team_effectiveness.pdf) and establishing a team agreement [(sample agreement)]({{ site.baseurl }}/classes/general/sample_team_agreement.docx).


## Classroom Procedures

It is okay to use your laptop to take notes, but do not use it for non-class
related activities. Not only does this diminish your learning experience, but it
distracts those around you.

For virtual class meetings:

* Cameras enabled. I need the human connection!
* Mics muted by default.
* Preferably [you're not in bed](https://www.thedailybeast.com/florida-judge-asks-attorneys-to-get-out-of-bed-and-put-on-clothes-for-zoom-hearings).
* Wear clothes that would be appropriate to wear on campus.


{% include required-syllabus-statements-spring-2022.md %}
