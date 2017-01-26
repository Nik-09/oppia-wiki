Oppia is excited to be applying for participation in [Google Summer of Code 2017](https://developers.google.com/open-source/gsoc/)! GSoC is a global program which offers post-secondary students an opportunity to discover and work with open source organizations over the course of 3 months and be paid a stipend. Students work one-on-one with a mentor of an open source organization in order to implement either a project idea by the organization or a proposal of their own.

Since GSoC 2017 mentoring organizations are not announced until **February 27, 2017**, it is not yet known whether Oppia will be participating in Google Summer of Code 2017. This page will be updated accordingly once it is known whether Oppia is participating.

The following are Oppia's 2017 GSoC project ideas. **Please note that these are still a work-in-progress.**

* [Self-service playtesting](#self-service-playtesting)
* [Improving the feedback flow](#improving-the-feedback-flow)
* [Applying machine learning to the code interaction](#applying-machine-learning-to-the-code-interaction)
* [Learner dashboard](#learner-dashboard)
* [Prevent learners from getting stuck/frustrated](#prevent-learners-from-getting-stuckfrustrated)
* [Translation console](#translation-console)
* [New interactions](#new-interactions)
* [Code interaction with test suites](#code-interaction-with-test-suites)
* [Sitewide ACL refactor](#site-wide-acl-refactor)
* [Achievement system](#achievement-system)

# Students
GSoC is an excellent opportunity for students to get paid to work on an open source project. If you're interested in applying as a student, you should definitely read the following resources:

- [Google Summer of Code student guide](http://write.flossmanuals.net/gsocstudentguide/what-is-google-summer-of-code/)
- [Google's list of resources](https://developers.google.com/open-source/gsoc/resources/)
- [GSoC FAQ](https://developers.google.com/open-source/gsoc/faq)

## Getting started

If you're specifically interested in applying to work with Oppia for GSoC, we recommend you follow this steps:

1. Sign up to the [oppia-gsoc-announce@](https://groups.google.com/forum/#!forum/oppia-gsoc-announce) mailing list in order to receive important notifications about Oppia's participation in GSoC.

1. If you're not very familiar with what Oppia is all about (or wish to familiarize yourself with concepts like explorations and interactions), take a look at our [user documentation](http://oppia.github.io/#/) will be very helpful for you. We'd also recommend having a go at playing/creating lessons on [Oppia.org](https://www.oppia.org), which hosts an instance of Oppia.

1. Read the [contributors' guide](https://github.com/oppia/oppia/wiki/Contributing-code-to-Oppia#setting-things-up), set up a development instance, and work on a [starter project](https://github.com/oppia/oppia/issues?q=is%3Aopen+is%3Aissue+label%3A%22starter+project%22) to get more familiar with the Oppia codebase and the contribution process. This will also help us get an idea of what it's like to work with you, and how independent you are. (**Note:** if you can't find a suitable starter project, you can also pick an issue labeled "TODO: needs instructions" -- these issues generally require a bit more investigation, but some of them aren't too hard.) You might also find it useful to take at the [overview of Oppia's codebase](https://github.com/oppia/oppia/wiki/Overview-of-the-Oppia-codebase) as a reference, as well as the [coding style guide](https://github.com/oppia/oppia/wiki/Coding-style-guide).

1. Take a look at one of the project ideas below, and select one or more projects that you're most interested in.

1. Write your project proposal! If you have any questions about your project, feel free to ask on [Gitter chat](https://gitter.im/oppia/oppia-chat), or email the [mentors' mailing list](mailto:oppia-gsoc-mentors-17@googlegroups.com). Please be specific when asking questions; this makes it easier for us to help you.

## FAQs

**Q: What technical skills do I need to work on Oppia?**

A: Familiarity with AngularJS (v1), Python, and Google App Engine is useful and recommended for most Oppia work. In addition, UI design skills are useful for frontend, user-facing work. Please see the individual project ideas to determine whether these skills are recommended or required for the project in question.

**Q: How can I increase my chances of getting selected?**

A: Writing a good project proposal, engaging with the community, helping other students, successfully contributing patches, and demonstrating that you can work independently can all help you. Your application will be evaluated holistically, so there's no one thing you must or must not do (other than apply!) to get selected.

**Q: Can you be flexible around other my commitments in the summer?**

A: GSoC is intended to be a full-time commitment, so the main concern is whether you can still get the project done on time. Be upfront about your other commitments and make sure you schedule your time accordingly when creating your proposal. The proposal should be able to reflect your being able to complete the project by the end of the summer.

## GSoC Proposal Template
When proposing a project, please use the following template:

**Project Details**
- Project name
- Why are you interested in working with Oppia?
- What interests you about this project?
- Prior experience (especially with regards to technical skills that are needed for the project)
- Project plan and implementation strategy

**Summer Plans**
- Which timezone(s) will you primarily be in during the summer?
- How much time will you be able to commit to this project?
- What jobs, summer classes, and other obligations might you need to work around? Please be upfront about your any existing commitments you may have.

**Communication**
- What is your preferred method of communication and contact information?
- How often do you plan on communicating with your mentor?

### Notes on the project plan

The project plan is the most important section of the proposal, since it outlines what you'll be doing during the summer. Here's some guidance on what the mentors and organization admins will be looking for in this section:

- **Three clear milestones** explaining the deliverables to be achieved by the end of each coding period. Strong proposals will have clear, concrete and well-defined milestones, whose success can be readily evaluated by an external observer. It's OK to break up a milestone into smaller milestones over smaller timescales, but individual milestones should represent *concrete* deliverables that can be merged into the "develop" branch. Please try to be realistic when setting milestones, and don't over-promise.

- **A technical design and implementation plan**. The project ideas below are annotated with some notes, but please note that these notes are not exclusive and shouldn't serve as a substitute for thinking carefully and critically about the project from first principles. If, in your thinking, you find aspects not mentioned in the notes, feel free to include a discussion of these aspects in your proposal. (For example, certain projects may require a migration of existing production data, and this needs to be accounted for in the project plan.) Strong proposals will demonstrate familiarity with the codebase, a realistic implementation plan, and attention to detail.

- **Mocks or wireframes**, if appropriate. For user-facing projects, we strongly favor proposals that demonstrate an empathy for the user. If you're proposing frontend design mocks, we suggest showing your ideas to your friends and getting their critical feedback, so that you can be confident that others find them intuitive as well. Note that you do not need to make your mocks pixel-perfect, but they should illustrate the primary user journeys clearly enough for us to understand exactly what you're proposing.

## Types of work related to Oppia projects
In order to ensure a well-rounded engineering experience, developers will do some or all of the following depending on their project:
- Meet with their mentors regularly
- Meet with other contributors related to their project area
- Receive code reviews for all code they write for their project
- Write automated tests for their projects
- Create UI mocks (if doing frontend development)
- Write design documents (if implementing large features or introducing new systems)

# Oppia's Project Ideas

**Note to interested students: these project descriptions are not final, and may change in the next few weeks! We're still working on them, and will remove this notice once we've finalized the descriptions.**

This year, the Oppia team is planning to create a cohesive set of lessons on basic mathematics, and run pilots with students in developing countries who lack access to teachers and textbooks, but who do have mobile devices (albeit with limited bandwidth). We want students to enjoy the learning experience, and we also want these lessons to improve continuously based on student feedback. Thus, the team's technical priorities for 2017 include improving the learner experience and building in feedback loops that make it easy for lessons to become better over time.

We believe that the following project ideas will have significant impact on Oppia, and would make excellent Google Summer of Code projects. That said, feel free to suggest your own projects -- we'd be happy to discuss new ideas that you'd like to implement!

## Self-service playtesting

**Aim:** In order to help creators improve their lessons, we depend heavily on student playtests and feedback. However, exploration playtesting currently happens via an [external form](https://github.com/oppia/oppia/wiki/Playtesting-explorations) (which we recommend that you look at, for inspiration), and the overall experience is pretty clunky. The aim of this project is to seamlessly integrate playtesting within the site, so that students who want to give more detailed feedback on an exploration can do so in a structured way.

**Skills/knowledge required**:
- UX design
- Full-stack development
- Finding a concrete solution to an ambiguous problem

**Difficulty**: Medium

**Suggested milestones**:

1. Full, implementation-ready spec with mocks, corner cases and tests finalized. All datastore and backend logic fully implemented.

1. Frontend completed and launched. At least one exploration has been playtested by a user (possibly you, but ideally someone else) using the new system.

1. A further project of your choice based on user feedback. This part of the project will be evaluated based on how much it increases the quantity/quality of playtest feedback.

**Notes**:
- How can we make it easy for students to start the process of playtesting an exploration? One avenue might be the learner dashboard, but there should probably also be an in-exploration way to do this (or a good argument for why not).
- We should make it easy for learners to report that they are stuck or feeling lost on a particular card (and explain why).
- Perhaps we could give students the opportunity to link to a "Let's play" video of their experience on YouTube.

A good proposal should discuss these issues and describe an appropriate UX. It's important to pay attention to details of the playtester’s critical user journey, and be very concrete about what you intend to do.


## Improving the feedback flow

**Aim:** Currently, learners can provide exploration authors with free-form feedback through the site, or via dedicated playtesting of lessons. We want to make it easy for this feedback to get integrated back into the lesson. A possible way to do this is to have a page that surfaces such feedback for all featured explorations, so that any logged-in user can take a piece of free-form feedback and turn it into a suggested edit for that exploration that the original author can subsequently approve/reject. The aim of this project is to build this page.

**Skills/knowledge required**:
- UX design
- UI design
- Full-stack development
- Technical design

**Difficulty**: Hard

**Suggested milestones**:

1. Logged-in users have a way to suggest edits to the RTE content in answer groups and fallbacks.

1. There is a page on the site that lists feedback from learners for explorations that are featured on the site. (It’s fine if it's read-only at this stage, as long as the necessary information is displayed.)

1. Any logged-in user can take a piece of feedback on this page, and act on it by creating a suggested edit to the exploration that addresses the feedback.

**Notes**:
- Currently, logged-in users can only make suggestions to the "content" parts of a state. We need to make it possible for them to make suggestions to the free-form text that the author includes in the "answer group feedback" and "fallback" sections, too, and find a clean way to expose this in the exploration player UI.


## Applying machine learning to the code interaction

**Aim:** We want to give students useful feedback when they get stuck. For this, we need to understand the answers they submit -- e.g., in coding problems, we'd like to understand when the user incorrectly initializes a variable, or makes some other common mistake, so that we can address it. Currently, we are working on building an extensible machine learning framework and a training interface for classifying free-form answers such as text input. The proposed code classifier for this project will be built on top of this framework, and would allow learners to type in code in order to match some sort of output, avoid an error, or match specific code. The project itself involves figuring out a way to cluster similar pieces of code, and then using that to train a classification model that can predict which feedback cluster ("answer group") a new piece of code should belong to. Lesson creators will then be able to create a training set and assign responses to a set of similar code submissions using the training interface. 

**Skills/knowledge required**:
- Machine learning
- Back-end development

**Difficulty**: Hard

**Suggested milestones**:

1. All updates to existing datastore (if any) + backend logic changes implemented. Data collection and updating the training interface: Build/generate a dataset for training the classifier, do any necessary data processing, and fully integrate and test any specific library that needs to be used in the project. Any changes required in the training interface should be done in this phase.
2. **Model building and evaluation.** Build the model using the training data, and complete end-to-end tests for the framework. Evaluate the model on the test data using cross validation and, if possible, do a [spot-check](http://machinelearningmastery.com/why-you-should-be-spot-checking-algorithms-on-your-machine-learning-problems/). Check the performance of the model against a baseline (typically using another classification algorithm).
3. Model deployment: Once the speed and accuracy of the model is acceptable, deploy the model in production.

**Notes**:
- We will be looking carefully at the technical design section of the proposal, in order to evaluate the feasibility of the proposed approach.
- If code evaluation is needed, this needs to happen in the frontend (although the results and the learner's code will be stored in the backend). For security reasons, we can't execute arbitrary Python scripts in the back-end.
- A strong proposal will demonstrate a good understanding of Oppia’s existing classification system, and clearly explain how the proposed classifier will interface with it.
- The proposal should discuss an effective strategy to build/generate datasets for training the classifier.
- The classification algorithm used should be pluggable. The existing classification framework (currently being developed) will provide enough flexibility to change the implementation of the algorithm as and when required.


## Learner dashboard

**Aim:** In order to learn effectively, learners should be able to keep track of what they've learned and what they’re in the middle of. The aim of this project is to create a place on the site where learners can keep track of the lessons they’ve done, the lessons they’ve partially completed, the list of creators they are subscribed to, and any feedback threads they need to read or respond to.

**Skills/knowledge required**:
- UX design
- UI design
- Full-stack development (mostly frontend)

**Difficulty**: Medium

**Suggested milestones**:

1. Basic learner dashboard page completed and launched. This page should contain functionality for "keeping track of completed and partially-completed lessons", as well as for "keeping track of subscriptions".
2. "Keeping track of replies to feedback threads" part of learner dashboard completed and launched.
3. Further project of your choice based on user feedback (e.g., show recommendations for lessons to playtest, or lessons to learn from, or new creators to subscribe to).

**Notes**:
- Proposals should address how a learner gets to their dashboard, as well as any general site changes that might be needed. It’s important to think holistically about the learner user journey and ensure that it's as intuitive as possible, whilst keeping in mind that learners can also be creators.
- Currently, a logged-in user is taken to the creator dashboard by default, which serves as their "logged-in homepage". One could argue that the learner dashboard should play this role for a user who comes to the site mainly to learn. How should we reconcile these factors into a coherent user experience?


## Prevent learners from getting stuck/frustrated

**Aim:** In order to help learners successfully complete lessons, we need to remove things that cause them to drop out or get irretrievably stuck. We also need to ensure that they receive the right hints at the right times (not too early, not too late). Therefore, the aim of this project is to make a couple of changes to the site:
- make fallbacks behave more like hints whose revelation is learner-initiated, since it’s irritating to be given hints when you don’t actually want them;
- make it compulsory for creators to specify, in each state, at least a final hint that gives the answer and helps the learner progress to the next part of the lesson.

**Skills/knowledge required**:
- Strong technical design skills
- Full-stack development

**Difficulty**: Medium

**Suggested milestones**:

1. Finalize full technical plan explaining how the fallbacks-to-hints recharacterization will be carried out. Datastore and backend logic changes implemented; all necessary migrations implemented.
2. UI changes implemented; frontend completed and launched.
3. Further project of your choice based on learner/creator feedback.

**Notes**:
- Proposals should give a very concrete description of how hints will work (e.g., what is the trigger for when they’re displayed), and what the frontend UI/UX for the learner will look like. (We suggest taking a look at how your favourite puzzle games handle this sort of thing; you might find some inspiration there!)
- Strong proposals will discuss multiple possible approaches, make reasoned arguments for and against them, use these to come up with an informed decision, and describe an appropriate UX that achieves the desired effects.


## Translation console

**Aim:** We want good lessons to be easily translatable into other languages, so that they're accessible to students whose first language is not necessarily English. The aim of this project is to make it as easy as possible for contributors to take an existing exploration, and translate it to another language.

**Skills/knowledge required**:
- UX design
- UI design
- Technical design
- Full-stack development.

**Difficulty**: Hard

**Suggested milestones**:

1. Full spec with mocks, corner cases and tests thought out; datastore + backend logic changes implemented; any necessary migrations done.
2. Frontend completed and launched; at least one exploration has been translated by a user (possibly you, but ideally someone else).
3. Further project of your choice based on user feedback.

**Notes**:
- Although the default UX should be as convenient as possible for the author, the newly-created exploration should not be publishable until all translations are completed.
- In the backend, we should keep track of what exploration has been translated from what -- this may be useful later. E.g. we might want to maintain a list of explorations that have been "derived" from a given one.
- The new exploration should be structurally similar to the old one, otherwise we might end up with "translated" explorations that aren't really related to each other.
- Some major design questions:
  - Should we go with a side-by-side view (of original + translation), or inline "annotations" for translators?
  - What if students study in English, but need different (more local) examples, or a different currency unit?
  - Would it actually be better for explorations to contain more than one language? For example, students in Tanzania learn in Swahili in primary school, but in English in secondary school. If we translate all the lessons to Swahili, they are likely to still struggle with the English versions of the lessons. However, if the derived lessons displayed mainly in English with Swahili available on-demand (by tapping words/phrases/cards), this would give the student practice reading and answering questions in English, and referring to the Swahili only when they need to.

A good proposal should discuss these issues, note arguments for and against different approaches, make an informed decision, and describe an appropriate UX. It's important to pay attention to details of the translator's and learner's critical user journeys.


## New interactions

**Aim:** This year, one of Oppia's main aims is to create a really good set of basic mathematics lessons. The aim of this project is to create some of the interactions required for these lessons, as well as to implement a few other commonly-requested interactions.

**Skills/knowledge required**:
- UI design
- Full-stack development (mostly frontend)

**Difficulty**: Medium

**Suggested milestones**:

1. Implement existing designs (by Prasanna) for the fractions and number-with-units interactions. [TODO: add links]
2. Spec out, design and implement a new interaction for drag/drop matching of items in two lists.
3. Spec out, design and implement a new interaction for entering and evaluating answers in the form of ordered lists.

**Notes**:
- Proposals should demonstrate familiarity with Oppia’s interactions framework, and outline the full backend specification, frontend designs, and examples of use for each of the interactions. Note that coming up with a good backend specification is not easy, and some technical judgment will likely be required.
- All interactions need to work on both desktop and mobile devices.

## Code interaction with test suites

**Aim:** Oppia currently has two coding interactions, but they are somewhat limited, and pass on a large chunk of the work to the creator. We would like to improve the existing coding interaction by extending it to include functionality for the creator to specify unit test suites, and using the "signature" of the test results to provide feedback to the student.

As a stretch goal, we would also like to make it easier for the coding interaction to automatically detect and respond to things like syntax errors, so that the exploration creator does not have to manually specify rules to catch every possible error. (This may intersect with the machine learning system that is currently being developed for answer classification.)

**Skills/knowledge required**:
- UI design
- Technical design
- Full-stack development (mostly frontend)

**Difficulty**: Hard

**Suggested milestones**:

1. Full spec for the revised coding interaction. This should include a complete backend specification, frontend design, examples of use and tests.
2. Frontend completed and launched; at least one exploration integrates this interaction.
3. Further project of your choice based on user feedback. This may be the stretch goal mentioned above, or something else.

## Site-wide ACL refactor

**Aim:** The current ACLs in Oppia were written for an older version of the site with slightly different aims, and the needs of the project have changed over time. We have recently come up with a new, simplified structure for site permissions, which is detailed in this [document](https://docs.google.com/document/d/1-JsPVIr1u4LQxpTBFi-VSUpbuIoF8CxgzN9ExCKlyYs/edit#heading=h.qj2574amxs00). The aim of this project is to devise a safe way to implement this, and bring the site up-to-date with the new ACLs.

**Skills/knowledge required**:
- Technical design
- Backend development

**Difficulty**: Medium/Hard

**Suggested milestones**:

1. Finalize the technical document describing new permissions system, including: new domain objects and services being introduced; new storage models needed; new tests that need to be added; a list of all permissions that need to be added; and a plan for migrating the current system to the new one including any testing that needs to be done to ensure nothing breaks. Implement the new storage layer, domain objects, services, and tests.
2. Perform an audit on all existing rights and permissions to ensure there are adequate tests covering each one to prevent regressions. Begin migrating permissions over to the new system, focusing only on new permissions that need to be added (not replacing the current rights manager and tests).
3. Migrate all permissions associated with rights_manager over to the new system, removing the old code once the migration is complete. Ensure all the old rights_manager tests are included in the tests for the new system.

**Notes**:
- It's important for the proposal to be explicit on which permissions are being added and how they will be tested to ensure no behavior regressions happen. A regression in this area of code can result in serious security problems. The student needs to convince the reader their approach will prevent security vulnerabilities from being introduced.
- The student is responsible for designing the system that will replace rights_manager, but we've already decided from a technical perspective that we're changing the way rights works from being pseudo-role-based to being action-based, where permissions grant allowance of certain actions and are inherited by roles.
- The student is responsible for using the [ACL document](https://docs.google.com/document/d/1-JsPVIr1u4LQxpTBFi-VSUpbuIoF8CxgzN9ExCKlyYs/edit#heading=h.qj2574amxs00) above and their own analysis to derive the list of permissions. Only backend permissions are needed here, and we want to implement a system to last into the future (with roles and groups, where groups can inherit from other groups). However, the current application of this system needs to satisfy the ACL document wherein roles 'cascade' their permissions currently -- i.e., 'logged in users' receive all permissions guests are allowed, collection editor users inherit all from the 'logged in users' group, etc.


## Achievement system

**Aim:** We want to encourage learners and creators to contribute to the community in ways that matter, such as by playtesting explorations or resolving student feedback. Oppia has a nice new profile page which could contain achievements like badges, but no current system in place to award such achievements.

**Skills/knowledge required**:
- UX design
- Visual design
- Full-stack development
- Technical design

**Difficulty**: Hard

**Suggested milestones**:

1. Have mocks for each achievement and for changes to the profile page. Update the profile backend controller and frontend page to support badges once the user has them. The controller in this case will be partially incomplete and will be finished in milestone #3.
2. Introduce a new domain layer for badges (domain object, services, and tests). Implement a new system for detecting when a user has earned a new badge and award them that badge. This milestone should also include implementing 1 real badge as a demonstration of the system. The rest of the badges will be implemented in milestone #3.
3. Implement any new storage models or jobs needed among all badges. Implement each badge in the backend using the system created in milestone #2 to award these badges to users. Finish the backend profile controller used to provide badges to the frontend in order to connect the backend badge system with the frontend profile page. Update the badge award system to send a notification to the user when they earn a badge.
4. (stretch) Design and implement the visual indicator that appears when a user earns a new badge.

**Notes**:
- The student's proposal should indicate which key user actions are worth receiving achievements.
- The student's proposal should indicate the types of achievements (badges versus t-shirts), the criteria for unlocking each achievement, and an indication of how achievements are tiered.
- The student should work with the UI/UX team to design icons/badges for each award.
- The student needs to describe, in their proposal:
  - The new domain layer for badges (domain objects and services, and also tests)
  - The storage layer needed for badges
  - The general system for detecting new badges: should this be a job or something computed in real-time? We may want to eventually award badges immediately when the user earns them (see milestone #4 below), though 'immediately' could wait until the real-time layer of a continuous computation is updated.
- The student needs to identify, for each badge:
  - The statistics needed to be recorded for that badge
  - Jobs that need to be written or reused in order to collect those statistics

# Other useful information

## Dates and Deadlines
Noteworthy dates for 2017:
- **Jan 19 - Feb 9**: Mentoring organizations apply
- **Feb 27**: Mentoring organizations are announced
- **Mar 20 - Apr 3**: Student application period
- **May 1**: Accepted students announced
- **May 1 - May 30**: Community bonding period
- **May 30 - Aug 29**: Students enjoy the summer by contributing code to their projects
- **Sep 6**: GSoC officially ends

## List of Mentors

The following individuals will be serving as mentors during GSoC 2017:
- Allan Zhou (@AllanYangZhou)
- Anmol Shukla (@anmolshkl)
- Avijit Gupta (@526avijitgupta)
- Ben Henning (@BenHenning)
- Jared Silver (@jaredsilver)
- Jenna Mandel (@jblair87)
- Joshua Cano (@joshuacano)
- Kevin Lee (@kevinlee12)
- Kristin Anthony (@anthkris)
- Mark Halpin (@markhalpin)
- Rachel Chen (@rachelwchen)
- Sean Lip (@seanlip)
- Xinyu Wu (@wxyxinyu)

## Communication

**Chat**

Oppia doesn't have an official IRC channel, but we do have a real-time chat channel on [Gitter](
https://gitter.im/oppia/oppia-chat#). You can login using your GitHub account (Gitter will ask to be associated with your GitHub account for authentication) and you will then be able to talk in it.

**Email**

If you have questions, please send them to the Oppia GSoC mentors mailing list at oppia-gsoc-mentors-17@googlegroups.com. Please be specific when asking questions; this makes it easier for us to help you.