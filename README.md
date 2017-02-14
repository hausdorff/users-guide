# A User's Guide to Managing Alex

## Career goals (at Heptio)

[TBD]

## Where I get stuck or sidetracked

Camille Fournier has a great post where she [points out](https://medium.com/@skamille/how-do-individual-contributors-get-stuck-63102ba43516#.ixz2u23ii) that all individual contributors get "stuck" or sidetracked at some point, and being able to recognize when people on your team get stuck is a super power, because you can plan your projects around their relative weaknesses.

Here are some of the things I have observed about where I get sidetracked or stuck:

### Sidetracked

Some examples of stuff I spend a bit too much time on, as I move on my way to accomplishing a goal:

* I sometimes solve problems because they are interesting, even if they're not the most important thing to be working on. I have gotten a lot better at this, but there is still progress to be made. This used to manifest as working on interesting side-projects instead of my main deliverable, but these days I'm more prone to spend more time over-thinking core APIs and abstractions.
* Refactoring. I sometimes catch myself "weeding the garden" (_e.g._, moving header files around, refactoring interfaces, and so on) a bit too much.
* Testing. I believe tests are a good insurance policy to help you reason about the technical risks you're taking, but I'm a bit of a completionist, and sometimes spend a bit too much time on this.

### Stuck

Some examples of stuff that causes intellectual throughput of my brain to drop precipitously:

* Sometimes I'll start to solve a problem, and then forget to periodically re-examine whether there's an easier way to accomplish my goals. This is related to the fact that I see one of my biggest strengths as persistence; so while this is sometimes a good quality, I haven't learned yet how to always tell the difference.
* I learn best when I have something I can interact with. Corollary: I do occasionally get stuck when I have to imagine how something works instead of being able to actually play with it and find out for sure. For example, I used to hack on the Linux kernel in my spare time, and the undocumented locking conditions of different subsystems plus the 5-8 minute compile times caused me a lot of anxiety about ever being able to figure stuff out, which subsequently caused me to take quite a bit more time on this task than I think I could have if I wasn't worrying about this.
* Procrastination is an anxiety disorder, and most people do it whe something is causing them anxiety. I am most anxious when I feel like I'm not trusted to carry out my job, so trust is at the center of how I process all work interactions. If I feel like I'm not trusted to do my job, I am very likely to start procrastinating.

## Things that make me grumpy

* People who are overly competitve with their peers. I realize everyone _is_ competing for recognition and stuff, but I tend hope to concentrate most of my emotional engergy on making my work better, rather than positioning my work so people think of it as the best. I realize that some of this is unavoidable, but it is nice when it's minimized.
* Managers managing at the task level instead of the goal level.
  * I am (of course) completely happy to receive feedback about the goal alignment of actions, but I tend to perform better when I feel mostly accountable for triaging and prioritizing work items, and communicating the status of those things to the team.
  * More specifically of my input is not taken seriously at the task- or goal-level, then I will start to wonder if I'm being used to my full potential.
* Not being consulted about processes that it is my job (or my direct team's job) to enact.
  * I obviously don't expect my advice to be taken all the time (or even most of the time), but when it is mandated that (_e.g._) a code review process is instituted, and it does not seem that the input required to affect the correct outcome was sought, it makes me wonder whether the team is really trusted to carry out this task.

## My happiest times at work in the last year

I am lucky in that I tend to intrinsically like even kind of boring programming, like writing build systems. But the times that I feel best about my job tend to be the ones where I feel like I have contributed to the success of my team in some material way, or when I watch a colleague or mentee become successful.

Here is a small sampling of stuff I found very rewarding.

* Mentoring a talented junior programmer as they started to ramp up on a complex codebase. I find it very rewarding to coach younger engineers.
* Debugging race conditions in the Mesos event loop. There was something that was just very interesting about doing detective work to find out why the state machine was going awry.
* Being told that my intern saved the superfresh index team in Bing 15% query service time.
* Successfully recruiting a very senior collegue after months of effort. I love the feeling of building out a team with talented people.
* Completing the Mesos handoff checklist as I passed responsibilities on to the remaining MSFT team (finally getting VP signoff to staff a team to replace me as I left MSFT, removing the thousands of compiler warnings, finally shipping Windows Container support, pushing the last patches required to deprecate the autotools build system and replace it with the CMake build system). It was just so rewarding to see it ship after all the work I put into it.
