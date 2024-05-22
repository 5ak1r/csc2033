**Reflective Report**
=====================

Roles and Responsibilities during the SE Phases
-----------------------------------------------

Everybody in my group had a different set of qualities coming into this project. Our initial introductions consisted of discussing these skills and assigning each other roles that aligned with their agreed Belbin Team Roles. As I already knew some of my team members before we started, it was easy for them to describe which ones I fit the most. I naturally suited the Cerebral roles, specifically the Plant and Specialist ones. I consider myself able to solve difficult problems, though may dwell on technicalities for example.


**Requirements**

We used the Waterfall methodology for our project. After reading the mandatory requirements for all projects, it was here that we discussed what parts of the development we each wanted to work on. Quite a few of my team members preferred working on front-end, whereas I was the only one who openly enjoyed back-end. As a result, it was very simple to delegate tasks to me as I agreed to do most of the parts they did not want to. However, since there was a large amount of back-end to do, I made sure I was only assigned a fair share of tasks and not too much. The remainder of the back-end tasks were shared out equally so that no one was forced to do too much of something they enjoyed less. As for the database, there was someone on the team who was keen to work on that part themselves.

**Design**

When it comes to the design of the application, I avoided the parts that involved UI/UX such as GUI design as I do not enjoy it, and there were multiple other group members who wanted to work on that aspect. I contributed ideas for the design that I felt were mandatory, such as which buttons are more important and should thus be larger than others, but nothing much more than that. As for my participation in the technical document, I worked on the assumptions section and also picked up some tasks that my team members were struggling with, for example I did a few diagrams for section 9 and provided explanations for my team members' GUI design choices. I also helped with filling out the Contribution Matrix for the document.

Most of the time during this phase, however, I spent doing a lot of research on Unity and Android Studio. I had learned that it was possible to export Unity projects into Android Studio projects and was testing if it were possible to create an Android app and then execute the game when a button is pressed, so that the game was only part of the application as a whole. After some struggles, I did manage to achieve this and so we went ahead with the minigame implementation ideas we previously discussed. It was also at this point that we decided to split our group into two smaller groups, with half of us working on the main application and the other half working on the game.

**Implementation**

This was my favourite part of the project so far. I had a lot of fun with programming for the game, as I was asked to work on that half of the project. My main responsibilities involved working on the core mechanics and writing most of the scripts. I also worked on implementing my teammates' sprite designs and animating their sprite sheets to create fun and unique enemies that the main character has to evade. I have been using Unity and C# for most of this phase. This played into my strengths as I enjoy scripting and writing code in general. My favourite part was procedurally generating platforms that appear at reachable heights relative to the previously spawned platforms.

I had the most confidence with GitHub out of everyone else in my group, so I was also in charge of making the repositories and also explaining how branching and pull requests worked. If anyone had queries or uncertainties with git and how to perform an action they required, they would come to me and I would help them with it.


**Testing**

Besides the previously mentioned testing with Unity and Android Studio compatibility, we have not actually reached this phase of the cycle. However, when we do reach this phase, we will make a testing plan similar to the ones seen on Canvas (a table of things to test, along with expected outcomes and actual observations). Furthermore, we will write unit tests for the main app and potentially for the game, though I will need to do a bit more research into how unit tests work with unity projects. There will also be a playtest session where I will invite my friends to try the game out and see if they can find anything wrong with it or let us know if there are improvements they would like to see, almost like a closed alpha test.

Although not directly testing, I added a simple pipeline to the main application's GitHub repository. This was my first time writing a YAML file and so I kept it very basic. The only requirement for the action to pass was that the project would successfully build. This was important as it allowed those working on the app to check if their work did not interfere with the existing project, which saved us a lot of time when pushing to the main branch - it would always run first try.