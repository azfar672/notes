QA Team
==

I am looking for 1 or 2 team members to run the testing section of an application that i'm
developing.   One person will specialize in general QA - test case management,
planning, manual testing.   The other will specialize in automated testing.

Here are several questions that I'd like you to respond to to
help me select my team members.  Please answer in as much detail as possible,
as this will be my main criterion for selecting the members.  Please also state
your preference of "Manual Tester" or "Automated Tester"


Problem:
-------

I've built a site that allows users to log in, upload documents, and select
their language preferences.  You've been assigned this task to test.  Please
tell me how you would proceed in the two cases (if automated testing isn't your
specialty, just state that you prefer Feature testing, and vice versa)


**If you're on the "Feature testing" team:**

List your steps of how you would proceed from start to finish.  Things to
consider in your answer:

* test case planning
* what test cases would you test exactly
* cross browser testing
* regression testing
* explain how you go about obtaining log files in javascript, and in a Rails application
* explain what tools you will use for test case planning and management
* explain what tools you will use for capturing screenshots of bugs
* explain what tools you will use for video recording bugs
* explain your experience with pivotal tracker
* explain how to file a bug on pivotal tracker
* We are currently a startup of 3 people, not a big enterprise like Microsoft.
    Explain what other things you might be able to add to the team, that I
    haven't mentioned here, that will help move the startup along at a much
    more efficient rate


**If you're on the "Automated testing" team:**

List your steps of how you would proceed from start to finish.  Things to
consider in your answer:

* what automation tools would you use
* how would you use them
* how do you connect these tools to the CI server (we're using CircleCI)





Generalities:
=============

General information that you can see regarding the job


Test Plan
---------

Please state how you will implement your test planning.
What tools do you use to store and manage test cases, especially for future
refrence for the team?
How do you communicate the test cases among other team member?





Feature Validation
------------------

When validating a feature, your main goal is to first ensure that it functions
as expected.  Once that has been determined, it is then your goal to try every
possible way you can to break the functionality, that the original developer
may not have imagined.   This will help make the product more robust




Reporting a Bug
---------------

When you are testing a part of the application, you are expected to try novel
ways of breaking it so that we can catch bugs before they get pushed to
production.

Once you suceed in breaking the app in some way, you should create a bug ticket
in Pivotal tracker.  In the ticket, you should supply the following
information:

* screenshot of the problem, with key points highlighted
* video of the problem if its a behavioral bug
* instructions on how to reproduce the problem:
  (make sure you've tested these instructions.  Make sure they are crystal
  clear, and include every step from start to finish.  These instructions will
  be read by someone who **is not you**, and thus they won't have the benefit of
  the knowledge you've acquired.  The most basic steps must be obtained from
  start to finish.
* Include a rails log if there is a 500 error - This will help debug the error
  more quickly
* Please tell me if you don't know what a 500 error is
* Include Javascript logs if there are errors in the Javascript console
* Include browser type and version


Tools:
------

** Screenshots: **

  When providing screenshots, please upload them to a hosted site, and only
  provide the URL. Tools such as droplr are good for taking quick screenshots
