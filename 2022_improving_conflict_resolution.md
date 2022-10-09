Conflicts are an inescapable part of communities, of working and being together. Much can be done to avoid them, but depending on the size of the group it tends to be inevitable that at some point someone's membership on it should be reconsidered. At best, the conflict is based on misunderstandings. At worst, it is because of a really toxic person who is doing damage to other people and to the project they're part of. There are many cases to suggest the removal of a group member. But who should make that decision? In most softwares it takes just one person to press a button.

## A unique system to remove users from a group

First requested as a way to remove users from a group, the Karrot team wanted to tackle this issue by trying something different than the usual administrator system in which one or very few people could use and abuse their admin powers. What came out was basically a voting system open for a period of time for group members to discuss and decide whether a person should to get removed from the group, stay in it or if the voting and discussion period should be extended. This is one feature that makes Karrot quite unique in relation to other community-organising softwares out there. This should not be taken as just some oddity, but rather as a conscious choice about the values embedded in the code, recognizing that no technology is inherently neutral and disembedded from social and power relations. Just as much as a traditional admin system implies a certain power structure resembling a kind of [implicit feudalism](https://mediarxiv.org/sf432/), in which administrators have power over their community subjects, the way this feature has been designed is about democratizing this particular decision-making power over removing or not group's member. This kind of design is also reflected in Karrot's trust system, which allows people to become editors of a group or to start this voting process against someone based on the number of trust carrots they're given.

![screenshot conflict resolution|690x390](https://community.karrot.world/uploads/default/original/1X/f2a3e867fd0b39d7481ab4777ec9efc1ac4db347.jpeg)

## The bigger picture: governance, conflicts and issues affecting a group

We need to put this feature in a larger context. It's part of a more general ambition of making Karrot into a tool for groups to be able to self-govern and solve issues and conflicts collectively. When the so called conflict resolution feature (described above) was conceived, the idea was to extend its procedure of deciding on someone's membership in the group to different kinds of decisions that the group would like to make. Group governance is a topic that we're constantly exploring and implementing though other features, like the upcoming agreements feature, and while the topic of conflict resolution is part of it, it is a huge topic in and of itself that is actually far from being fully covered by this existing feature. During recent discussions with the groups using it, we realized that we have been hastily calling it "conflict resolution", when actually it is not more than a process to decide whether someone should stay or not in the group. After all, the means to resolve conflicts are way beyond the use of one feature or tool. It usually involves much work using other tools, as simple as e-mail, phone calls and cakes (they calm the spirit) during face-to-face interactions. We've got quite concrete examples from groups using Karrot that have set up their own routines in the event of conflicts and breaking the rules (if you want to get investigative, check out the [notes from Karrot Days](https://community.karrot.world/t/karrot-days-2022-july-16th-17th/922/8)). Using the existing feature to remove people from a group is usually a culmination of a longer process that tries to deal with issues in which the target person had been part of.  In my own foodsaving group I heard many times that starting this voting/discussing period is usually seen as too drastic but necessary in some cases.

Now, we are talking about community organising, in projects that are often based on 100% unpaid work and are purpose- (instead of profit) oriented. There will not be an HR staff whose job is to keep people away from trouble that might affect their work, to keep employees motivated enough so as not to let any issue affect the organization's bottom line. Instead, the whole point is to help groups self-organise and be better equipped by the software to deal with issues that affect the group negatively. Much can be gained from a proper process to solve conflicts and issues, both on an individual and collective level.

A bunch of ideas have been brainstormed at least since the feature was introduced, like:
- graduated sanctions (e.g. temporary block for activities, or signing in), based on Ostrom's principle for governing the commons.
- escalating model to mediate conflicts, starting on a smaller scale involving less members of the group before it reaches the whole group
- and in more recent discussion with groups some new ideas, like anonymous flagging and guiding people towards non-violent communication.

## Collecting user feedback and revisiting the feature

Different from our two previous design processes, this one was not about creating a new feature, so it did not make much sense to follow the basic stages and methods by the book (whatever the book is). Things played out much more organically, because the feature for removing a user has been there since 2019 and discussions have been taking place at least since 2018. What we did was basically revisit the topic, go through old threads and prepare a session during Karrot Days to discuss more broadly with people from different groups. We from the Karrot team had also a few sessions dedicated exclusively to the topic. Additionally, I had myself some first-hand experience from my group and Vasilis had a few interview so we could collect some feedback of how people used or reacted to this feature. 

We quickly realized there was a low-hanging fruit that could be picked, so we proposed to fix the [notification system](https://community.karrot.world/t/conflict-resolution-with-possibility-to-remove-user-from-group/201/40). Not only was it creating confusion when people got e-mail notifications which seemed out of context, because everybody in the group got subscribed to the chat (that would probably make sense in a group of few people). It also caused reactions *against* the people who initiated the process because they felt it was exposing others unnecessarily and that the matter could be handled in a more discrete matter. Social sensibilities played therefore a strong role in this and the design question was about how to involve people in the discussion without being a nuisance or intrusive, and at the same time not letting the person being targeted feel too exposed. The change we made is that everybody in the group should get a bell notification to let them know a process to review someone's membership has started, without letting them get e-mail notifications for every message sent in the chat, unless they opt in of course. Another little tweak to make people aware of an ongoing process was to add a count on the ongoing "issues", visible at the main menu.

![screenshot_issues_notification|690x390](https://community.karrot.world/uploads/default/original/1X/0ce4d32e82679f4b6641e16f22ab96c42e66af33.jpeg)


Another change was about renaming the feature, so we went through all the texts where "conflict" and "conflict resolution" is mentioned and changed it to membership review. That might seem not very significant, but put into the context explained above, it should make more sense to groups that the feature is more about reviewing the membership of a user and so it can be plugged into the manifold ways they choose to deal with conflicts. Indeed, we discovered that many groups have their own policy for dealing with conflicts and that the feature is rarely used to *solve* a conflict in any other way than suggesting someone's removal from the group, because it's reached that point already.

![image|616x500](https://community.karrot.world/uploads/default/original/1X/4a145010c7259010791048ea9da134f4ccb2c552.jpeg)


One last thing we considered was to change the voting system. We got a couple of feedback from people who thought that score voting and its result were not easy to understand. However, we felt we did not have enough time and information to make a decision to change at this point. It's amazing how much there is to consider from other voting systems, even if it's single choice. We changed a bit of wording and we'll continue following the user experience with the voting system to reconsider this in the future.

![screenshot voting issue|386x500](https://community.karrot.world/uploads/default/original/1X/c74ebb9ebefa191a673d363893412c847de6fb3d.png)


## Final considerations on the process

The most valuable thing about taking up this topic again was to put things in perspective and re-model a vision for future designs and development of a more encompassing set of features for group governance and actual conflict resolution. Sometimes the valuable pieces of feedback and information are a bit scattered through time, on different threads, notes and conversations. It's been worth not only gathering "old" information, but having renewed talks with different groups on their current experience using this feature and gathering people on a focused session like we had during Karrot Days. One thing I noticed though is that there was some kind of fatigue in trying to engage the community on this topic. Besides the session we had and some interviews conducted by Vasilis, it was mainly the Karrot team participating and deciding on the improvements. My feeling was that people got a bit tired of discussing this topic and felt they said everything that had to be said. It's tricky to find the right balance between having a nice and inclusive participatory process to design and decide on improvements and to not be nagging the people who are part of this community. Nonetheless, the important thing is to take up the role of reaching out to make informed decisions that reflect the needs of different groups while aligning those needs with the value proposal of our project. And do it explicitly! That is why I dedicated some space in the beginning of this text to put the feature into this broader context. Looking forward to design and implement new ideas in the future!



References:
https://community.karrot.world/t/conflict-resolution-with-possibility-to-remove-user-from-group/201/ - long thread, since the feature was first designed
https://github.com/karrot-dev/karrot-frontend/issues/798 - the first documented request
https://github.com/karrot-dev/karrot-frontend/issues/853 - first design and mockup, with discussion
https://community.karrot.world/t/improving-conflict-resolution-feature/979/ - notes
_____________________________________

*This text was written as a milestone for the NlNet funding*