I am [Albert Mas](link to your linkedIn), student of the
[Bachelor’s Degree in
Video Games by UPC at CITM](https://www.citm.upc.edu/ing/estudis/graus-videojocs/). This content is generated for the second year’s
subject Project 2, under supervision of lecturer
[Ricard Pillosu](https://es.linkedin.com/in/ricardpillosu).

## BETA TESTING

### What is Video Game Testing?

[Wikipedia](https://en.wikipedia.org/wiki/Game_testing) says:
“Game testing [...] is a software testing process for quality control of video games.
The primary function of game testing is the discovery and documentation of software defects.
Interactive entertainment software testing is a highly technical field requiring computing expertise, analytic competence,
critical evaluation skills, and endurance.”

The testing of video games is performed by a QA group that can vary in size and methodology throughout the game development.
The first playtestings will usually start whenever the first playable build is created and will continue until the game is fully released.
At the beginning of the QA activity, the testing team will be of a reduced size until Beta version is hit, when it will greatly
grow in size due to the importance of testing during that phase.

While some companies use QA just to track bugs, others use it as a tool to find the strongest and weakest points of the game
that is being created and so, try to focus more on the good aspects and fix the ones that are not working. That way, you may
have to invest a bit more into QA but the final result will probably be a more fun and refined gameplay.

This job is a typical entry point for people who want to join the game development industry and want to have some insight
into the video game creation. That leads to few people staying on this job for several years.

![Pic](https://i2.wp.com/2.media.dorkly.cvcdn.com/51/94/8a50767fc39a7d6cb54d98d1fccaa5fb.jpg)

### Frome Beta to Release

The Beta is a phase on video game production where no more features, code or assets are implemented to the code. From the moment
the Beta version is started, the development team will be completely focused on the elimination of bugs.
A good playtesting team will be mandatory in order to detect as many bugs as possible and create useful reports of each one
to help programmers locate the pertinent bug and deal with it as fast as possible.

When this version is closed, we will create a code release candidate that will be sent to the publisher and console manufacturers.
That version will be tested and if it is approved it will turn into the Gold master.
If it fails to meet the publisher’s or console manufacturer’s requirements, the developers will have to solve the problems that
were found and submit another release candidate. The problems that can prevent a release candidate from being approved are usually
bugs that were not found or solved during the Beta phase or compatibility issues with unusual versions of the targeted platforms.
Sometimes though, especially in indie/small studios, the publisher could ask you to change some features of the game or add some
others before being approved.

When you have your Gold master version, which is considered the finished game, the physical and digital production and
distribution will start. This process will usually take over a month.
Getting a release candidate approved used to be a tougher job because no bugs (or almost) were supposed to be unsolved
before shipping the game. Nowadays, publishers are not as inflexible, due to day one patches, which are useful to solve
remaining bugs without delaying the release any further.

### Roles in QA
- **Lead tester:** He is in charge of the whole QA process. His job is to organise the playtesting teams, make sure that testers create formal and complete reports and that every reported bug is fixed by the developers. His goal is to obtain a bug-free game.

- **Testers:** Their job is to ensure that the game contains as few bugs as possible, it’s easy to use, its mechanics are logic and coherent with the gameplay, and it’s fun to play. For each error or improvement they have to write a specific and accurate report, and if possible how to reproduce it.

- **Technical Testers (SDET):** This team is formed by highly skilled programmers with knowledge on manual testing. They are responsible for building automated test cases and managing complex test problems such as overall game performance and security. That means that they have to combine their game testing and software development knowledge to automate processes for thorough testing and improve the game’s robustness and stability. They are usually only employed on big studios.

### QA Process
- **Identification:** Game problem is spotted.

- **Reporting:** Tester creates a detailed report on the bug and how to trigger it.

- **Analysis:** Programmer/Artist/Designer (depending on the bug origin) checks the report and patches the bug.

- **Verification:** Tester tries to replicate the bug again several times and if it no longer occurs, it is considered fixed.

![Pic](https://www.gameindustrycareerguide.com/wp-content/uploads/2014/01/Dead-Fly-Scene_Grant-Cochrane-300x197.jpg)

### Testing Steps
- **Game knowledge**: Thorough understanding of the game’s concept, mechanics, characters, features, rules, level design…

- **Test strategy:** Create a document with the number of testers, testing cycles, timeline, types of testing that will be used, scope…

- **Test cases design:** Both positive and negative test cases will have to be designed. It is important not to forget to review the content of the game (Is it easy to understand?, Does it create a fun gameplay?, Is it appropriate for the targeted audience?...).

- **Execute test cases:** In order to spot the maximum amount of bugs, it will be optimal to use different software and hardware. It’s advisable to record playtesting sessions.

- **Report errors:**  Each error found has to be logged, categorized, prioritized and tracked.

## Types of playtesting
- **Functionality testing:** Consists on playing the game and look for general problems within the game itself or its UI. Testers are not required to have a high technical profile.

- **Compliance testing:** Consists on checking that the game fulfils all the Technical requirements from every targeted platform. If the game aims for a certain content rating from audience regulatory bodies such as PEGI (european) or ESRB (american).

- **Compatibility testing:** Consists on testing the game on different types of hardware and software to make sure it works on every computing environment. Specially important in PC titles.

- **Localization testing:** Consists on reviewing the translation of the game scripts and text, to foreign languages. It also covers the review of text translation related problems such as text not fitting in the screen. Testers are usually native to the country where that game version is being launched.

- **Soak testing:** Consists on leaving the game running for long periods of time without any human interaction in order to identify any possible memory leak or rounding error that appears over time. The game might be left in various modes of operation, such as idling, paused, or at the title screen. This test doesn’t require any testers after the initial setup and automated tools may be used in order to simulate repetitive actions, such as mouse clicks.

- **Beta testing:** It’s done during the Beta phase. It consists on opening a version of the game to the public. That way you can get thousands of players that will test your game for free and probably find a lot of bugs that your testers missed. It can be an open beta, where anyone can join, or closed beta, restricted to some selected players.

- **Regression testing:** Whenever a bug is fixed by a developer, a tester will have to test it again to check if it no longer happens. Afterwards, the tester will have to check related features to see if fixing that bug has broken anything else.

- **Load testing:** Consists on pushing some part of the game to the limit in order to know how far can it go before it starts causing problems. The test can be the maximum number of active players on an MMO, the number of active sprites on the screen, or the number of threads running in the program.

- **Multiplayer testing:** Consists on ensuring that all the desired multiplayer options (Internet, LAN, Modem) working correctly.

### Types of bugs
- **A:** Critical bugs that prevent the game from being playable. (e.g. Crash, A door to the next objective that doesn’t open, a main quest NPC disappears…)

![Pic](https://content.invisioncic.com/r273030/monthly_2017_10/erro.png.7dd08c6b72912fdc00285c3516a5c679.png)

- **B:** General bugs. Essential problems that require attention; however, the game may still be playable. Multiple B bugs are equally severe to an A bug. (e.g. dead bodies fall through the floor or start moving randomly, a useless NPC disappears…)

![Pic](https://dilanlahiru.files.wordpress.com/2014/01/untitled2.png)

- **C:** Smaller problems that may annoy the player but don’t completely ruin the experience. (e.g. a texture isn’t loading, sound bug, a character’s facial expression remains still while talking...)

![Pic](https://morrisatlarge.files.wordpress.com/2015/01/game-tester.jpg?w=233&h=131)

![Pic](https://1.bp.blogspot.com/-156gvbaFg8E/Vq5hTTywMVI/AAAAAAAAGKg/pl0AIVhshIk/s1600/AC-Unity-bugs.jpg)

![Pic](https://connorryan1994.files.wordpress.com/2014/01/e2.jpg)

![Pic](https://mygaming.co.za/news/wp-content/uploads/2016/10/Skyrim-Headless-Glitch.jpg)
