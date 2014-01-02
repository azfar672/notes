Expectations
------------

You do what you say you're going to do

You ask questions when you don't know something



How to Start a Task
-------------------

When you are assigned a task to perform:

* Look up the existing story in Pivotal, and click "Start" to start it.  If there is no story,
  then create one, assign it to the proper Epic, and start it

* Create a new git branch referencing the feature that you're implementing. 
  
* **DO NOT COMMIT CODE TO MASTER**  - No code should ever be commited or merged
  into master.  There is a code review process, and build/deploy automation.
  Do **NOT** merge code into master



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
  checklist, if any of the following apply:
    - which database migrations to run
    - which build scripts to run
    - which env variables or config settings need to be set
    - which cronjobs need to be set

* **TEST YOUR FEATURE**

    **DO NOT MARK WORK AS COMPLETED IF YOU HAVEN'T TESTED IT!!!**     I am not
    QA, and don't have time to walk through every feature multiple times,
    seeing if it works.  You need to **test your feature YOURSELF** before
    communicating that the work is done.

* **Create a Github "Pull Request"**, to merge your branch into master.
  Once you've created the pull request, I will review your code, line by line,
  and leave comments on things to change or improve.  You should then make all
  fixes and push them to the same branch, which will update the pull request.

  If you don't know what a github pull request is, then [google "github pull
  request"](http://lmgtfy.com/?q=github+pull+request)


What Qualifies as Completed
---------------------------

In order for work to be considered as completed and approve, the following
things must be true:

* You have created unit tests for your models and its methods
* You have created controller tests for your controllers
* You have created integration tests in capybara for end to end testing of your feature
* You have run all of the tests, and they are passing
* You have pulled the latest code from master, and merged the master branch
  into your branch
* You have fixed any git conflicts between your branch and master
* You have pushed your branch to github, and it passes CI
* You have issued a Pull Request on Github
* Github looks like this: http://d.pr/i/dy2G
* You have deployed your code to the QA server
* You have tested all of the features yourself on the QA server.
* The features work on the QA server according to spec


**THEN AND ONLY THEN, DO YOU REPORT THE WORK AS COMPLETED**


We don't have time to test all of the code ourselves that is being pushed.  Its your job to ensure that a feature works as expected before marking it as
complete.  That means *YOU NEED TO TEST IT* yourself, on the server.  Don't mark work as complete if you haven't tested it.




What to do Next?
----------------

* Send me your Github username, and email address.  I will use this to add you
  on Github, Pivotal, and Heroku

* Join CircleCI:  https://circleci.com/?join=dont-test-alone

  You will be able to observe the CI builds of the project once you are added
  to the Github Repo
