Expectations
------------

You do what you say you're going to do.

You ask questions when you don't know something.



How to Start a Task
-------------------

When you are assigned a task to perform:

* Look up the existing story in Pivotal, and "Start" it.  If there is no story,
  then create one, assign it to the proper Epic, and start it

* Create a new branch referencing the feature that you're implementing. 
  
* *DO NOT COMMIT CODE TO MASTER*  - No code should ever be commited or merged
  into master.  There is a code review process, and build/deploy automation.
  Do NOT merge code into master



How to Submit Work
------------------



When you have finished working on the agreed upon task, you should do the
following things:

* commit all of your code to the git repository
* push all of the code to Github
* deploy your code to the QA servers
* make a checklist of the things that need to be done in order to release your
  code to the production servers
* create a pivotal "chore"  ticket which lists all of the items in the
  checklist
    - which database migrations to run
    - which build scripts to run
    - which env variables or config settings need to be set
    - which cronjobs need to be set

* TEST YOUR FEATURE
    **DO NOT MARK WORK AS COMPLETED IF YOU HAVEN'T TESTED IT!!!**     I am not
    QA, and don't have time to walk through every feature multiple times,
    seeing if it works.  You need to **test your feature YOURSELF** before
    communicating that the work is done.

* Create a Github "Pull Request", to merge your branch into master.
  Once you've created the pull request, I will review your code, line by line,
  and leave comments on things to change or improve.  You should then make all
  fixes and push them to teh same branch, which will update the pull request.

  If you don't know what a github pull request is, then [google "github pull
  request"](http://lmgtfy.com/?q=github+pull+request)


What Qualifies as Completed
---------------------------

In order for work to be considered as completed and approve, the following
things must be true:

* You have run all of the tests, and they are passing
* You have pushed your branch to github, and it passes CI
* You have issued a Pull Request on Github
* Github should look like this: http://d.pr/i/dy2G
* You must deploy your code to the QA server
* The features must work according to spec
* You must have tested all of the features yourself on the QA server.


**THEN AND ONLY THEN, DO YOU REPORT THE WORK AS COMPLETED**


We don't have time to test all of the code ourselves that is being pushed.  Its your job to ensure that a feature works as expected before marking it as
complete.  That means *YOU NEED TO TEST IT* yourself, on the server.  Don't mark work as complete if you haven't tested it.