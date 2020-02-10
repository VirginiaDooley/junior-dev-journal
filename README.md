# Junior Dev Journal :notebook: 

_The purpose of this journal is to document my first weeks as a developer on a digital team after 
completing coding bootcamp. I hope that this journal will help me chart my professional growth and help others that are currently on or considering a similar path understand what lies ahead._

* Week 1-2

Over the past two weeks, I've been getting set up in my new role as a junior developer 
including gaining access to online systems and meeting colleagues in various departments 
to better understand the business mode. I observed a user feedback session which 
helped me to understand the users' needs. I've been reviewing the code base for the main product 
that is in development - a tool to help users make payments and book home repairs. I've also 
tried to document work flow to help refine the onboarding process for future devs on my team. 

* Week 3

    * Day 1
        * Daily standup call: We review progress, identify blockers, and make plans for the next sprint
        * Identify remaining onboarding items
        * Review Trello for outstanding issues and work with other devs to fix a bug: 
            * The codebase is massive and still largely unfamiliar to me, so we use the console to identify 
            the objects and arrays and related data that we are working with. 
            *With a big hint from a senior dev, we solved the issue and then refactor to minimise the code. 
        * Research and practice version control with git rebasing
        * Resources: 
            * [Working with Git](https://medium.com/@grazibonizi/the-best-branching-model-to-work-with-git-4008a8098e6a)
            * [Thoughbot Guides](https://github.com/thoughtbot/guides)
            * [Don't mess with master: Working with branches](https://thenewstack.io/dont-mess-with-the-master-working-with-branches-in-git-and-github/)
        * :relaxed: Reflections: Previously, I was a freelancer working on smaller scale projects mostly on my own so looking at this large scale app is honestly very intimidating. If you're anxious about preparing for your first coding job, try to refocus that energy onto what's in front of you at the moment (finishing your projects, practicing for interviews, improving your git version constrol skills). The apps you will be working on in your first job will likely be more vast than anything you previously worked on while studying so be patient with yourself while you get familiar with the code base. If anything, contributing to open source projects can help you prepare for jumping into a new team. Jump into an existing app and try to understand how everything fits together so that you can better understand the context of raise issues. 

   * Day 2
        * Review the data model diagram: We walked through the flow of data with visual aids and identified changes that need to made in the architecture. 
        * Pre-planning for next sprint: From tomorrow, a new 2 week sprint begins. :party: 
        * Reviewed design guide
        * Walked through objects and properties in the User model in prep for the next sprint
        * :relaxed: Reflections: Today, I particpated in several meetings which helped in provide deeper context on the history and future direction of the product. 

    * Day 3
        * Retro (reflecting on the last sprint): Following the conclusion of each sprint, the team 
        identified and discussed: 
            * What worked? 
            * What could have been improved? 
            * What didn't work? 
            * Actions
            * Discussed which items to push to staging
        * New concepts, terms and tools
            * Feature flags (or toggle): _A feature toggle (also feature switch, feature flag, feature flipper, conditional feature, etc.) is a technique in software development that attempts to provide an alternative to maintaining multiple source-code branches (known as feature branches), such that a feature can be tested even before it is completed and ready for release. Feature toggle is used to hide, enable or disable the feature during run time. For example, during the development process, a developer can enable the feature for testing and disable it for other users._
            * Method stub: _A method stub or simply stub[1] in software development is a piece of code used to stand in for some other programming functionality. A stub may simulate the behavior of existing code (such as a procedure on a remote machine, such methods are often called mocks) or be a temporary substitute for yet-to-be-developed code. Stubs are therefore most useful in porting, distributed computing as well as general software development and testing._
            * VCR and cassettes: _Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests._
            * Webmock: _Library for stubbing and setting expectations on HTTP requests in Ruby._
            * Heredoc: _A heredoc is a way to define a multiline string, while maintaining the original indentation & formatting._
            * Her gem: _Her is an ORM (Object Relational Mapper) that maps REST resources to Ruby objects. It is designed to build applications that are powered by a RESTful API instead of a database.-
            * Miro: _collaborative whiteboard platform for distributed teams_
        * Next sprint! 
            * CRUD contact details writable to API
            * Complete accessibility course
            * Designing certain fields for mobile first vs qwerty
            * End goal: first iteration of contact details page working on staging, 
            with feature flag available for a demo. "As a customer, I can add a phone number."
        * Unblocking a testing issue: A security issue has caused a connection issue with tests using VCR; it was decided that we should turn off VCR for this test and stub a new test to unblock the related work. 
        * Resources
            * [Accessibility from Google](https://classroom.udacity.com/courses/ud891)
            * [More on feature toggles](https://en.wikipedia.org/wiki/Feature_toggle)
            * [Stubbing](https://en.wikipedia.org/wiki/Method_stub)
            * [VCR gem](https://github.com/vcr/vcr)
            * [Webmock](https://github.com/bblimke/webmock)
            * [Heredoc](https://www.rubyguides.com/2018/11/ruby-heredoc/)
            * [Her gem](https://github.com/remi/her)
            * [Miro](www.miro.com/)
        * :open_hands: Reflections: A bit of info overload, but taking one day at a time. 

* Week 4-5

    By Week 4, I felt I had an understanding of the large chunks of the code base as well as the tickets that needed to be completed and the workflow to complete them. I started pairing with another junior developer on a more regular basis and we reached out to senior devs as needed. During this time, I used a prototype as a guide for implementing a new models, views and controllers, injecting javascript where needed. I also worked on building out Rspec and capybara tests for the controller and new features we had built. I still find TDD difficult but will continue to try to lead with tests going forward. Once the basic work was complete and functioning, we worked with a senior dev to refactor our code for clarity and performance. In the end, we didn't complete the work required for the sprint, mostly due to having to implement a new front end style. There were several learning curves, but as a result, I expect progress to much faster next sprint.  
    * Resources
        * [Ruby strings cheatsheet](https://www.shortcutfoo.com/app/dojos/ruby-strings/cheatsheet)
        * [Importing JS into a HAML file](https://stackoverflow.com/questions/11455551/how-do-import-a-javascript-file-into-a-haml-view)
        * [Page specific JS](https://brandonhilkert.com/blog/page-specific-javascript-in-rails/)
        * [Rspec cheatsheet](https://devhints.io/rspec)
    * :metal: Reflections: The pace is picking up and I like it! 

* Week 6

    I took on my first ticket solo but still don't feel comfortable with branching and committing the right way so that will take priority this week. Other than that, writing more and more tests...
    * Resources
        * [Stashing with Git](https://stackoverflow.com/questions/19003009/how-to-recover-stashed-uncommitted-changes/19003191)
    * :thinking: Reflections: 

    