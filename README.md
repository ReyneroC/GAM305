Cashis: Begin Here


## Module Two Team Project Plan

### Project Concept and Brainstorming
**Contributor: Colin Farrington (cfarr93)**

Our team has discussed developing a dark carnival-themed game. The concept could include an abandoned carnival, a haunted funhouse, interactive attractions, and environmental puzzles. These ideas would allow us to create an immersive atmosphere while incorporating gameplay mechanics appropriate to our assigned scenario.

The final scenario and four additional elements are awaiting team confirmation.

### Proposed Development Timeline

**Module Two — Planning**
- Confirm the scenario and four additional elements.
- Finalize team responsibilities and the game concept.
- Complete the initial level blockout.
- Establish communication and task tracking.

**Alpha Stage — Core Development**
- Create the basic playable environment.
- Implement player controls and initial gameplay mechanics.
- Add placeholder assets and basic interactions.
- Test essential functionality and document issues.

**Beta Stage — Feature Completion**
- Implement all required gameplay elements.
- Integrate environmental art and UI components.
- Conduct playtesting and fix major bugs.
- Verify gameplay against the design requirements.

**Final Release — Testing and Polish**
- Resolve remaining critical issues.
- Complete final testing.
- Prepare the final game build and release branch.
- Document lessons learned for the postmortem.

Exact milestone dates will be added after reviewing the course schedule.

### Proposed Communication and Task Management
Discord will serve as our primary communication platform. Thursday check-ins have been proposed to review progress and identify any challenges.

I recommend using GitHub Issues to assign responsibilities, track progress, and document bugs. Team members can use feature branches for individual development tasks.

### Colin Farrington — Individual Contribution
Prepared the initial project planning recommendations, proposed development timeline, Alpha and Beta goals, and task management approach for team review.

### Charlie Witzel- Individual contribution
Suggested the theme of the game (Dark Carnival) and took on the role of artist.

### Angel Morales - Individual Contribution
Recommended defining our core gameplay mechanics before development, including player movement, inventory, object interactions, enemy behavior, and win or lose conditions. I also suggested organizing tasks through GitHub Projects using Todo, In Progress, In Review, and Done so we can track responsibilities and progress.

## Module Three Project Log - Team Development: QA and Testing Plan

**Contributor:** Colin Farrington (cfarr93)
**Project:** Dark Carnival (proposed)

### Communication and Collaboration
Our proposed primary communication method is Discord, with weekly Thursday check-ins to review testing progress, discuss bugs, and coordinate fixes. GitHub Issues will be used to document test failures and assign responsibility for resolving them. Team members should update the shared test plan whenever gameplay requirements change.

### Testing Schedule
| Stage | Testing Activities | Completion Criteria |
| --- | --- | --- |
| Play Test — Preproduction | Test prototype movement, placeholder objects, basic level navigation, and initial interactions. | Core mechanics function and major design problems are documented. |
| Demo — Before Marketing Demonstration | Test the full intended demo path, UI, interactions, visual presentation, and stability. | Demo-critical features pass and no known blocker prevents completion. |
| Code Release — Before Release Submission | Execute the full test plan against the release candidate, verify fixed bugs, and perform regression testing. | All required features pass and no unresolved critical bugs remain. |

Testing will also take place after each significant gameplay change. Specific dates will be aligned with course deadlines and team milestones.

### Pass/Fail Testing Checklist
| Test Item | Expected Result | Status |
| --- | --- | --- |
| Player movement | Character moves according to design specifications. | Not tested |
| Camera controls | Camera responds correctly without unintended behavior. | Not tested |
| Level navigation | Player can navigate required areas without becoming stuck. | Not tested |
| Object collision | Objects block or allow movement as intended. | Not tested |
| Interactive objects | Objects activate when the correct interaction occurs. | Not tested |
| Gameplay objectives | Objectives trigger and complete as designed. | Not tested |
| UI and menus | Buttons and displays function correctly. | Not tested |
| Level progression | Required transitions and completion conditions work. | Not tested |
| Game stability | No crashes or blocking errors occur during the test. | Not tested |

Each test will be marked Pass or Fail after execution. Failed tests will be linked to a bug report. The checklist will be adjusted to match the team's selected scenario and four additional elements.

### Updating the Test Plan
When the game design document or gameplay functionality changes, the team will review affected requirements and update the relevant test cases. New mechanics will receive additional tests, while changed mechanics will have their expected results revised. Changes should be recorded in GitHub commits so the team can identify when and why the test plan was updated.

### Bug Reporting
Bugs will be reported using GitHub Issues with the following information:
- Bug title and description
- Game version or development branch
- Steps to reproduce
- Expected result
- Actual result
- Severity level (Critical, High, Medium, or Low)
- Screenshots or video evidence when available
- Assigned team member and current status

### Bug Tracking and Verification
Each bug will be tracked through the following workflow:

Open → Assigned → In Progress → Ready for Retest → Closed

Developers will reference the relevant GitHub Issue when submitting a fix. The tester will reproduce the original test and perform regression testing to verify that the fix works without breaking other features. If the bug remains, the issue will be reopened.

### Individual Contribution — Colin Farrington
Prepared the proposed QA and testing schedule, pass/fail checklist, test-plan update process, bug-reporting procedure, and bug-tracking workflow for team review.
### Individual Contribution - Ashley Bougher 
Helped establish the specific gameplay elements that would need testing 

### Cashis Reynero - Individual Contribution
Established the repository, as well as created a project board for team members to view their specific job related tasks. 

### Ashley Bougher - Individual Contribution
Helped when it came to role decisions, even though I only helped narrow things down by giving my strengths and weaknesses

### Angel Morales - Individual Contribution
I opened the team project in Unreal Engine 5.8.4 and performed preliminary checks of movement, jumping, and camera controls. For our testing plan, I recommended focusing on gameplay interactions, enemy behavior, and room progression, with failed tests documented and retested after corrections. These initial checks do not replace formal Alpha testing.

### Charlie Witzel- Individual Contribution
Honestly confused about what else I should be doing so I've been focused on the art and figuring out modeling. I've created a tent, crystal ball, table, curtains so far, and tried to figure out materials.
## MODULE FOUR PROJECT LOG- TEAM REFLECTION 
Throughout the development of our Alpha release, I think one of the parts of our testing process that may have gone well was us being able to identify areas of the game that needed improvement as we continued developing it. Having a clear idea that we wanted a dark carnival theme so our environment would have to match; obviously, this helped us recognize when certain features were not working as intended. Testing these different elements of a game, including the environment, menus, and the gameplay mechanics, allowed us to catch any issues before moving forward with our development.
Some errors were identified through testing and observing how different elements of the game behaved during gameplay. When something didn’t work as we expected, we could always go back into Unreal Engine and troubleshoot any of the problems. Some issues required adjusting blueprints, changing our designs, or changing how things interacted with one another. I think identifying these issues early helped us prevent any bigger problems later.
If I could change anything about our QA and Testing process, it would be better communication throughout development. I would also encourage our team to do more frequent testing throughout our development rather than waiting for larger portions to be completed. I also wish we were a lot more organized with bug tracking so our team can document problems, prioritize them, and keep track of which issues have been resolved. This would help improve our communication and make sure everyone understands what still needs attention. 
One of the most important tools for our project was Unreal Engine 5.8. It provided the ability to build the environment within our game, create movable characters, and develop the overall atmosphere of the dark carnival. Our blueprints were also helpful because they allowed us to have functionality without having to rely on programming. These tools gave us flexibility when we developed our alpha release, especially with different features, and they allowed us to bring all of our ideas from the game design document into the result.
One area I found really challenging was when I was trying to get my main menu to fully function; Unreal Engine has many settings and systems and sometimes finding the right buttons to use and it took more time than anticipated. I also think having more consistent documentation and testing would make development easier. While the tools themselves were useful, learning how to use them effectively was sometimes a challenge.  
Our initial analysis of the game design document helped us decide the direction which we wished to take the game and gave the team a better understanding of what we wished to accomplish. By identifying our game's theme, the type of game we wanted, the rooms, the types of puzzles, and some of the mechanics, Unreal Engine was a good choice because it offered the tools we needed to create an immersive environment and interactive gameplay for the players. Overall, having a clear understanding of our video game before we started working on it helped guide any decisions and kept our team focused on creating a game that matches a vision we agree on. 

Individual Contribution: I opened up my Unreal Engine 5.8.4 and designed the Main menu  for our Alpha Phase 
