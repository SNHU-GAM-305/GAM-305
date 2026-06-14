# Module 2 Team Project Plan
**Team:** Jared, Alex, Blaise, Michael, Noah

## Chosen Scenario
* **Base Scenario:** Unannounced First-Person Simulation (Miniaturized inside the body)
* **Four Additional Elements:** Jared White: Pick-Ups, Michael Walker: Teleporter, Alex Hartschenko: Virus-tracking capability, Noah Ketzenberger: Capillary Traversal System

## Brainstorming & Content Design
We are building a fast-paced, "Doom-like Boomer Shooter" adapted to the human body environment. 
* **Theme:** Miniaturized inside the human body.
* **Level Design:** 5 rooms of varying sizes representing different organs/systems.
* **Enemies:** 3 distinct virus types with varied AI and movement patterns (Total 20 kills required).

## Schedule & Timeline
* **Week 3 (5/18 - 5/24):** Player Setup, Enemy Parent Class/Placeholder Enemy, Projectile Parent Class, Health System with placeholder UI, Initial Level Layout. 
* **Week 4 - ALPHA RELEASE (5/25 - 5/31):** Kill Tracker with placeholder UI, Pickup Parent Class, Game End State (Game over/Level complete), Enemy Sprites complete, Gun Sprite complete, Playtest and QA.
* **Week 5 - BETA RELEASE (6/1 - 6/7):** QA and bug fixes, Apply textures to material, Enemy Animations, Gun Animations.
* **Week 6 - 1.0 RELEASE (6/8 - 6/14):** Complete outstanding tasks, Final Bug fixes.

## Communication Plan
* **Method:** Weekly voice meetings and continuous text collaboration via a dedicated Discord server.
* **Frequency:** Primary team meeting on Sundays to review the upcoming sprint, plus at least one mid-week check-in to assess progress.

# Module Three Project Log - Team Development: QA and Testing Plan.

**Method:** All tests will be done on a pass/fail system and will be reported within the bugs channel of the group discord with the corresponding role tagged in the bug report so they can investigate.
When the bug has been resolved they will respond to the initial bug report with confirmation of completion. All branches for bug fixes will be headed with BUGFIX/system/bugtype to make it clear in the commit tree what has been fixed.

*   **Test Plan Updates:** If we change any game mechanics or update the design document, the team will meet on Discord to update this test plan right away so we don’t waste time testing old features. 
*   **Long-Term Bug Tracking:** To keep track of bugs over time and make sure nothing gets forgotten, we will log every bug from Discord into a shared Google Sheet that shows the bug's status (Open, In Progress, or Fixed), who is working on it, and when it was resolved.

**Bug Severity Levels:**

- **Critical:** Game crashes or major systems fail.
- **Major:** Gameplay systems function incorrectly but the game still runs.
- **Minor:** Small gameplay issues that do not hravily affect gameplay.
- **Cosmetic:** Visual or audio issues that do not affect gameplay.

**Week 4 - Play Test**

Environment
* Level: We will test the level collision by walking into all walls while standing and crouched. We will also observe enemies as they collide with walls.
* Teleporter: We will test by walking over the teleporter while standing, crouched, shooting, and while taking damage to make sure no issues are created between systems.
  
Player
* Collision: We will test by walking into all walls and enemys while standing and while crouched to make sure no physics issues occur when colliding with other objects.
* Health Systems: We will test taking damage and grabbing a pickup in short succession to make sure no errors occur in the health and armor systems.
* Gun: We will test the firing system by depleting our ammo and grabbing ammo pickups to make sure ammo is replenished and the gun is able to fire
       We will test the firing system against enemies to test that damage is being calculated accurately and hits are registering on the enemy.
  
Enemy
* Pathing: we will observe enemy pathing and make sure the enemies are not getting stuck in the environment.
* Damage: we will test that enemies are able to apply damage upon collision with the player by colliding with them while standing and crouching.
* Dectection: we will walk into the enemies detection radius and make sure the enemy begins following the player while standing and while crouching.
* Shooting: we will test that the enemy can properly track the player and fire projectiles towards the player if they are ranged.

UI
* Health and Armor: We will take damage and grab pickups in quick succession to make sure the Health and Armor update properly in the player UI.
* Ammo: we will deplete the weapons ammo and pickup more ammo while firirng to make sure ammo count is properly displayed.

**Week 5 - Demo**

This week is heavily based around getting all assets in the game. Therefore testing will revolve more around general game feel and any animation bugs.

Animation
* we will observe the enemy animations and make sure they look smooth and that they always face the player.

Environment
* We will move around the environment to make sure it is evenly lit and easily readable.
* We wll check for any texture issues in on objects like floors, walls, ceilings, and teleporters

**Week 6 - Code Release**

This week is all about testing so we will be rerunnig every test from week 4 to make sure nothing has changed in the final build.


## Task Assignment & Reporting Method
* **Workflow:** [e.g., We will use GitHub Projects / Trello] to maintain a Kanban board. Tasks will be created as issues, assigned to the respective team members, and moved from To-Do to Done.
* **Roles:** 
  * Team Lead: Jared White
  * UI/UX Designer: Alex H.
  * Environmental Artist: Blaise Pascal
  * Lead Programmer: Michael W.
  * Level Designer / Programmer: Noah Ketzenberger


## Module 4 Project Log - Team Reflection

* What parts of the testing process did the team perceive to go well?
  * Initial systems testing has made it very easy to integrate each system with minimal issues.
  * Utilizing Print strings to debug during development led to more complete systems.
* How were bugs identified and corrected?
   * Bugs were tracked using a discord channel and updated as fixed. 
   * As bugs were identified they were reported and resolved using proper feature branching.


* In terms of the QA and testing process, what would you do differently to improve the process?
  * Utilize discord channels to report more bugs as they are found.
  * Make sure pull requests are completed in timely fashion to avoid merge conflicts in local branches.


* What tools (chosen in Module Two) did you find successful in the development of your Alpha project? Why?
  * Using Discord and Trello to track progress has made it easier to develop a functioning alpha build within 2 weeks
  * Having clearly laid out tasks with checklists allowed for better task management throughout the process.
* Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
  * All tools currently being used have been useful to completing the tasks assigned.


* How did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques?
  * Having a set theme made it much easier to break down tasks early on into small pieces with less decision paralysis. 
  * Because the task breakdown was so easy, translating it to a checklist made it very clear and concise what needed to be done

## Module 5 Project Log - Team Reflection

* What parts of the plan did the team perceive to go well in relation to the last stage evaluation?
  * We coordinated our pushs more effectively to avoid merge conflicts.
  * Better overall communication.

  
* What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?
  * We could have recongized a bit earlier the need for uniform environmental pieces to make texture mapping easier.

* How were the previous evaluations integrated into this latest stage?
  * We intergrated discord more effectively into our workflow.
  * Our pushes have been more streamlined with less merge conflicts.

* What would you do differently to improve the collaboration or development process?
  * Clearer communication on who was assigned to do pull requests.
  * On trello identify what files each person will be working to better plan pushs and reduce redundant work.
  * Daily tasks to complete to better communicate the progress on project.

* Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
  * We under utilized the Discord channel and should have used it more for communication early on but all tools and techniques used served a purpose.

## Module 6 Project Log - Team Reflection

* What parts of the plan did the team perceive to go well in relation to the last stage evaluation?
  * Communication went well and we planned out the week's tasks in a great way to mitigate conflicts when we scheduled adding the environment art material update to after the modular map update.
* What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?
  * 
* How were the previous evaluations integrated into this latest stage?
  * We focused on our strengths of communication and continued this week strong.
* What would you do differently to improve the collaboration or development process?
  * 
* Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
