---
layout: post
title: Back to Collab
---
After the midterms I focused on getting the UI code merged and a few days ago Sam has merged my patchset.

My patches are:

* [sugar/pull/697](https://github.com/sugarlabs/sugar/pull/697)
* [sugar-artwork/pull/91](https://github.com/sugarlabs/sugar-artwork/pull/91)
* [sugar-datastore/pull/6](https://github.com/sugarlabs/sugar-datastore/pull/6)

Now getting back to collab code.
This week figured out how to debug the Salut. Improved the sugar-docs regarding the same [[1]](https://github.com/sugarlabs/sugar-docs/pull/100).

Still understanding the Salut log by comparing the logs of Physics collab. Looks like channel gets disconnected.
Logs shows this error: 

gibber-transport.c:226:gibber_transport_send: assertion failed: (transport->state == GIBBER_TRANSPORT_CONNECTED)

WIP branch: [sugar/collab](https://github.com/sugarlabs/sugar/compare/master...AbrahmAB:collab)
