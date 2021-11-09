# Open Source game development

## Intro
### What’s this about?
The current state of game development is in shambles. The big corpo game studios are all clearly in the game for just pure gains. That’s how the corporations work by design. They need to make money to feed the corporate machine. No matter the intention of the actual team making a game the overlords will always push quotas onto them to fill with the sole intent of making as much as possible for as little cost as possible. That trickles down the whole system into the actual design of game systems. This is visible the most in multiplayer games especially if they are competitive. To a point one can argue that even indie game devs do the same thing when money gets involved. Just a quick scroll through Kickstarter proves the point and its long history of projects funded that never saw the light of the day. Some of that is inexperience and over-promise. The reasons for those failures have been discussed elsewhere; that's not the point here.

Game development didn’t start like this. At the beginning people made games just for fun out of passion. Money and success came as a side effect of that effort. That passion is long gone now. Many people get into the game dev world just because there is money to make. While there is nothing wrong with wanting to have a financially stable life and career, for the people playing games it’s all about having fun. The end user is in many cases looking for entertainment and or escape from the real world. A nice evening when you get to turn off your brain and relax having fun alone or with friends.

These two sides go directly against each other. And it gets especially bad when the game is intentionally built to exploit the player and waste either their time or money. When in fact that’s the exact thing the player might be trying to avoid/escape from in the real world. A boss has been on their neck for the past weeks pressuring timelines and what have you. Just to come home and have a game you are trying to play to relax do the exact same thing to you (unless you pay extra and we magically make your pain go away … MTX).

For the devs them self. There are many talented people around the world that can see from the outside how the whole system works. And it deters them from wanting to get involved. Software devs of any kind (doesn’t matter if it's a game or any other software) are a special breed. They like to code just for fun and start projects of their own constantly as a hobby. Yes sometimes the outcome of that is money and success, but as the section about how the game dev world started states, that’s purely a side effect. It started as a passion project and evolved into something bigger down the road. Or in many cases people just use these passion projects to build a portfolio. That’s why the open source community is huge in the overall software world. It has never been about instant financial gain.

### But weren’t there attempts to do open source game dev before?
Yes, quite some time ago there was. Some had success like OpenTTD but most flopped. Nowadays all that open source is in game dev is just building frameworks or engines not the actual game.

It’s important to look at why no one really succeeded in this space. There was no process to follow, no rules for the whole system and if you have many people jumping in the dev process you need some clear goals and design to where you are going. Looking into the more successful endeavour, like in the case of OpenTTD, they had a very clear goal. Just do Transport Tycoon. In that case you are basically copying an already made game and can build on top of that. When everyone can clearly see what they are building they can achieve the goal. You need a clear process to follow.

This comes down to what exactly you are building. If you are copying another game you have your path set pretty much. If you are building everything from scratch that’s where you need a more defined process. Concepts like peer review have already been defined and are widely used in the industry. Besides having your path defined you also need some structure in the community to avoid deviation from that path. People to basically steer the ship in the right way and keep the quality at the desired level.
So what are we doing here?
Well we are going to try to define this process. That’s the whole point of writing this. To avoid failing and help building these passion projects hopefully in large scales.

Everyone is well aware that nothing in the world is free. And open source gets you only this far. At some point you might need money to support your game. But that shouldn’t impact how you are building it at all. And if by any chance you get extra that should always be distributed across the contributors fairly. We’ll try to define all of that.

But first...

## Manifesto
- We aren’t in the business of making money we are in the business of making a good game out of passion.
- No gameplay system should be built with the monetization in mind.
- People will play a game if it’s fun. There is no need to forcefully make your players play more with FOMO mechanics.
- If at any point you need money to support the game (infrastructure, release, technology) none of that impacts the gameplay design.
- When in doubt, brainstorm it out. Open source is always about the community.
- Every aspect of the development should be peer reviewed.
- Be transparent. Makes it easy for new contributors to understand the vision and your goals. Also helps with trust from the general public.
- Failure is an option and doesn’t need to mean it’s a bad thing. There are always lessons learned and experience gained.

## Process
### Before we start

Define a plan of actions. Have a clear process to follow that suits your need. If you already have a community of contributors to start with you should all understand what your plan is and have an agreement on it.

We’ll also need to have some structure defined. Someone “owns” the whole game. It can be the owner of the actual code repository or the idea of the game itself. Not everyone wants/can do it. It’s essentially the position of lead dev and for that you need either experience or someone willing to put in the extra work required. Obviously we are talking about a team of people here, not a single person’s private project.

Down the road as you work together with the team of contributors you get to know each other's strengths and weaknesses. Depending on the amount of work being done if at any point the whole team feels like it’s too much to handle, you should consider spreading out the responsibilities if needed.

In regards to handling code specifically, have a defined way of how you are handling branching and the potential way of using pull requests as a part of your day-to-day life. This should include the release strategy that works best for you.

Always keep in mind that this is a passion project and people work on it for fun mostly for free. Do not stress yourself out for no reason. People are most likely doing it in their free time.

## Day-to-day
### Agile? not really!
Use the tools available. In the software world Agile is widely used and can be successful when done properly. Some people don’t like it but that’s because it can be easily miss managed by people that don’t know what they are doing. Many of its parts are open for interpretation but when used correctly it works.

While we can’t really use an Agile approach. Mostly because we are doing this as a hobby, many things corpo can suck the fun out of it. But there is nothing preventing you to use parts of it to make your life easier and help you achieve your goal. Have a roadmap with milestones and plan for what needs to be done to reach them. Use tools like the github ticket/board system to have the plan documented for everyone to see. And slowly work your way up the list at your own leisure.

If desired you can also have meetings open with the contributors to discuss any potential issues and who’s working on what at any moment. OK well maybe that’s a reach people hate meetings :D … but you can just have a Discord server to discuss things as needed, for example.

### Peer review
Every part of the game should be peer reviewed. In coding this is a standard approach many devs are already aware of. For some other aspects this may be a new concept. But there is no reason not to peer review code, art assets, system designs or even stuff like potential marketing materials. It doesn’t always have to be a complicated process. A simple thumbs up/down process is enough and not everyone has to be involved if they don’t have time to do so that’s fine.

Only approved features get greenlit. It’s pretty simple. Just have rules for who needs to approve what for it to pass and how many people are needed.

### Ideas forum
Allow people to have a way to discuss any ideas they like. Sometimes it’s better to show what you are working on to someone else just to get a second pair of eyes on it. Maybe they’ll be able to see problems you didn’t account for in the first place or have other ideas for potential improvements.
Even if you don’t have much to go by, just spit-balling a brief idea you may not be sure about is a good thing and could spark interesting discussion. Some people like pineapple on pizza… monsters!

Again use the tools available. Discord, Slack, Github are good places to start.

### Proof of concepts
Sometimes ideas come in different formats. Or some people that aren’t that good with words would prefer to rather show you what they mean. That’s the beauty of open source. It already allows for POCs and forks of any kind. Allow for anyone interested to do these types of things. Brings in more people and in many cases POCs can be converted into real features.

In a way your whole project is a proof of concept in a way until it gets released.

### Handling system design
This is where having dedicated people in charge of the overall game idea comes in. You need to have someone overarching the whole idea behind the game you are all building together. So you don’t split the focus. Like some parts of the team are building an FPS game and the other part is building an RPG and Peter comes in next week with a pull request to convert it into a tetris game. No, you need to keep focus if you want to finish it at some point.

So peer reviewing design changes and the approval of anything that gets into the final game is crucial here. But make sure that everyone is able to comment on any of it. Don’t gate-keep access to it for anyone. Because even if you are the person in charge of the game systems you may overlook something that breaks your game or simply don’t see the problems behind it.

That’s when the discussion is important and you all may learn something as a part of the process.

### Money
Well this is a big one. Every time money gets involved things can go tricky for multiple reasons. You don’t have a company or organization to back you up in most cases. And some people might have malicious intentions with what you are building here to profit off you in some way.

Depending on what type of game you are working on you may at some point need to get money from somewhere. If you are lucky enough or are building something simpler you may not need money at all. But for a more complex/ambitious game you might. Sometimes people just pay for stuff with their own money and that’s fine. Consider keeping track of what you paid and what for in that case. On the other hand sometimes you simply don’t have money of your own to spend on the bigger expenses.

You might want a website to distribute or promote your game. Or servers to run parts of the game on, in case of online games. Buy a license for software or frameworks to use. All kinds of things that may not be free for you to use.

The safe way of handling money would be to keep it as transparent as possible. “We made X$ from donations and we have to pay Y$ monthly for a game server” goes a long way. If you have extra money to spare, consider spreading it across the contributors in a fair way. At all times everyone involved should know what are your expenses, where the money is and where it goes.

But to be honest after a certain amount you get into a territory where you just need to consider having an overarching company or organization to handle these types of things. For legal reasons depending on where you live. By that point you aren’t really in the “open source game dev” territory anymore. And your path is yours to take after that. And that’s where this whole document doesn’t apply to you anymore.
