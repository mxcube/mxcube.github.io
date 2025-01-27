











# Report of 2024 MXCuBE code collaboration survey answers













## Introduction

Questionnaire about development workflows for MXCuBE:
coding, testing, deployment, collaborating, etc.














## General

* 12 responses!
  Thank you!

* Some highlights

* Some takeaways

* Deeper investigation at a developer's meeting?

* Answers are available to everyone

















## Resources

### #4 "How many people work on MXCuBE?"

* Many facilities have (very) small workforce

* 5 facilities have only 1 person


### #5 "How many are software developers?"

* 7 facilites have only 1 "software developer"


### #7 "How many hours can they dedicate to working on MXCuBE?"

* Almost no one works on MXCuBE full time



















## Coding

How do you code for MXCuBE?


















### #9 "How far can you get coding locally using your computer or laptop only?"

* High disparity

* Some manage nearly 100% without beamline

* Some manage near 0%














### #10 "How often do you need to go directly at the beamline to code (not test)?"

* Very frequently

* Beamline access is time constrained
  (only specific days of the week)


















### #11 "How do you learn about the inner workings of MXCuBE?"

* Mostly by reading the code itself

* More documentation is needed, including tutorials















### #12 Comments about "coding"

* The documentation code camp
  and code camps in general are appreciated
















## Collaboration

GitHub, pull requests, and so on


### #13 "How do you keep up to date with upstream changes on GitHub?"

* Attend developers meetings

* Follow notifications, pull requests, etc. on GitHub

* Many facilities have their own fork

  * Fork needs to be kept in sync


















### #14 "How often do you integrate upstream changes?"

* Some facilities seem to manage to keep up
  and update within a month or so

* Some are not managing

* Some decided to stay on a fixed version






















### #16 "Do you have your own forks of MXCuBE repositories?"

* 11 facilities have

* Not always public?


















### #17 "How often do you contribute your improvements back to upstream GitHub?"

* "Not as often as we would like"













### #18 "How confident do you feel using the collaboration tools?"

* Mostly yes

* But not everyone, especially non software developers















### #19 Comments on "Collaboration"

* "It would be nice to find a way to increase inter developer interactions"

















## Test
















### #20 "How do you test new code?"

* No "normal" way, every facility different

* Some have simulators, simulated hardware

* Some do every test at the beamline















### #21 "Do you use simulated devices (Tango, Epics, etc.) to test hardware objects?"

* 4 facilites: "No"

* Epics, Ophyd: yes

* Mock hardware objects














### #22 "What limitations or hurdles do you encounter when testing with mockup hardware?"

* Mockup hardware objects are of course very useful
  but their limitations are reached very quickly















## Deployment
















### #23 "Do you use isolation environments for Python?"

* All of them! :D

* Python virtual environments, Conda environments, Docker














### #24 "How do you install Python dependencies?"

* No consensus: conda, Poetry, pip















### #25 "How do you install JavaScript dependencies?"

* pnpm/npm

* Maybe the question was not clear or even unnecessary
















### #26 "What operating systems do you deploy on?"

* Linux everywhere

  * Debian, Ubuntu
  * CentOS, Rocky Linux, AlmaLinux
















### #27 "Do you have infrastructure restrictions for deployment?"

* "Anaconda can not be used"

* "we can use any open-source software,
  but use of software that requires modification
  tends to be limited to the MIT license"

* "Kubernetes deployments
  and must integrate with centralised single single sign on service"














### #28 "Do you have access to specific infrastructure services?"

* Some facilities have custom internal services available

* No consensus, no normal, all facilities have different setup













## Pain points
















### #30 "What are recurring pain points regarding MXCuBE development workflows?"

* "Looking forward to time when all synchrotrons have caught up with upstream develop -
  or there was a stable, widely used version pone could program and develop to
  (unlikley to happen)."

* "Testing and deployment are two topics that are quite difficult to handle.
  Tests are particularly difficult to perform as the hardware is difficult to simulate
  and test benches are expensive."

















### #31 "What do you think could be improved regarding MXCuBE development workflows?"

* "More documentation, in particular on the Qt part and core-Qt communication."

* "Cleaning up the code base and removing deprecated and confusing code"

* "Task allocation within the collaboration"

* "Additional test cases for abstract hardware objects"

* "Interactive coding sessions between small groups of 2-3 developers
  would boost learning and productivity"
















## Takeaways

* How can we make learning easier?
  * More documentation, tutorials
  * More hands-on collaboration: pair-programming, group sessions, code camps
  * Maybe a workshop training about our development process,
    our automated tools, and toolchains

* How can we make testing easier?

* Quite a wide range of deployment processes

* Could we make it so that custom forks are not necessary?

* High disparity in mastery of MXCuBE dev
  * Is it okay? Should we worry about it?



* MAX IV has TWO (2) open positions in the MX software team!




















## The end
