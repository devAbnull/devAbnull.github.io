---
layout: post
title: GSoC Week#4 Late Post
---

Week 4 has been started. So a few stats of my work till week 3.

**Features Implemented:**

* Project ListView
    * Filtering list to show only Projects
* Add New Project
* Project View
    * Filtering the whole list to get entries under corresponding *project*
* Add New Entry to project
    * ActivityChooser View (to select activity to work with)
* Add New Participant to project
    * FriendList Pop-up (to select the friends to send invite)
* Sending invite to friends to join the project

**In Progress:**<br>
ProjectWrapper to collab and sync project shared among buddies

<h2>Goal for this week:</h2> To complete the collabwrapper thing such that online syncing is implemented.<br>
In brief, When a user sends invite to other users to join the project and if the other user accepts the invite then it directs new user to join all the activities under that project. Sync must be such that whenever any of the user adds new activity to the project this activity is directly shared among all the users of the project without any invite this time!<br>

Planned to send my patch for reviews to the community the next week just before the MidTerm evaluations.

**Source code:** [gsoc-branch](https://github.com/sugarlabs/sugar/compare/master...AbrahmAB:gsoc-projectlist-view)<br>
Discussion on setting up collab system for Project could be found [here](https://etherpad.net/p/journal-projects)