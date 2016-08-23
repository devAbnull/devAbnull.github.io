---
layout: post
title: GSOC Final Submissions
---

The project was about adding Project View a platform for project-based activities.

Brief Description
-----------------
**Whats completed?** The Project-View UI code is completed and is merged.

The commits link are given below:

* Added new popwindow module in sugar3.graphics[sugar-toolkit-gtk3](https://github.com/sugarlabs/sugar-toolkit-gtk3/pull/313/commits)

* Journal Project View[sugar](https://github.com/sugarlabs/sugar/pull/697/commits)

* Filter using project_id[sugar-datastore](https://github.com/sugarlabs/sugar-datastore/pull/6/commits)

* Project icon added to icons/scalable/mimetypes[sugar-artwork](https://github.com/sugarlabs/sugar-artwork/pull/91/commits)

**Goals were changed** Due to the use of deprecated telepathy-dbus code in Sugar collab the progress on setting up collab for new Project system introduced. So now focus was to refactor the present collab system in Sugar.

**Work in progress** The project of refactoring the collab system is to be completed.

Till now I have implemented the sharing of an activity(Physics) instance among buddies using avahi and zmq libraries.<br>Buddies come together and can share activtiy(here physics) and work on it. Any buddy (but not all) can get disconnected or stop activity and can again come back and resume the shared activity. Only issue is that not all buddies together at a single time get disconnected from the network at least one of them must be connected to network.

TODO: Resuming the shared activity once ALL the buddies get disconnected.

TOFIX: Sometimes we get inet6 addr (like  fe80::665a:4ff:fe2d:2cb9) instead of inet addr (like 192.168.0.105) that causes traceback when connecting to sockets!

WIP branches:
* [sugar/activity-collab](https://github.com/sugarlabs/sugar/compare/master...AbrahmAB:activity-collab)
* [sugar-toolkit-gtk3/activity-collab-gtk](https://github.com/sugarlabs/sugar-toolkit-gtk3/compare/master...AbrahmAB:activity-collab-gtk)
* [physics/master](https://github.com/sugarlabs/physics/compare/master...AbrahmAB:master)
 

