Explorer's Stair Event
=======

Stair events are often boring, but not this one! After a few simple jumps the players are taken through an underwater tunnel, followed by a confusing path of spirals, jumps and elevators. If they survive the first part, they can start their travel through the mountains to the sorcerer's tower. Don't be misguided by the pretty environment though, a simple misstep can quickly lead to a character's death.

After passing through the tower, players are taken to a large platform. This is to make sure a mistake at the end doesn't force them to start all over. The platform serves as some kind of checkpoint. At this platform starts the very last but also most tricky part of the stair event. Luckily a nice prize is waiting for them at the sky pirate ship above (or not, but that part is up to you ;)).

**Event information:**

*   **Type:** stair event
*   **Difficulty:** medium
*   **Length:** long
*   **Location:** Shatterspear Village (Darkshore)
*   **Decoration/theme:** just beautiful in general ;)

**Requirements:**

*   **Emulator:** TrinityCore
*   **Game version:** 3.3.5
*   Players running the stair will need a somewhat decent computer. The large amount of visual effects in this event is known to cause issues on some older setups.

This event will definitely not work for cataclysm or higher, due to a different layout of the area and because of flying being enabled. It might work on vanilla and TBC, but that has not yet been tested.



Screenshots and videos
-------

Unfortunately, no event video has been made yet. If you have one, please let me know!

**Screenshots:**

[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 1.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 1.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 2.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 2.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 3.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 3.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 4.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 4.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 5.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 5.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 6.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 6.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 07.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 07.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 08.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 08.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 09.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 09.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 10.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 10.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 11.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 11.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 12.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 12.jpg)
[![](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 13.thumb.jpg)](https://filedump.chocochaos.com/GitHub/Events/Explorer's Stair 13.jpg)

If you run the event on your server, I'd appreciate if you could make some screenshots or videos and send them to me (gmgenie [at] chocochaos [dot] com).



Usage instructions
-------

1.  Download the event SQL: https://raw.githubusercontent.com/chocochaos/events/master/Explorer%27s%20Stair%20Event/Explorer%27s%20Stair%20Event.sql
2.  Edit the file with notepad (or an other text editor, but certainly NOT word) and review the configuration variables at the top.
3.  Check if the event id you configured is available in the database. Also check if the guids in the gameobject table are not taken yet.
4.  Execute the SQL file on your database.
5.  Restart the server (unfortunately reloading gameobjects is not possible in-game).
6.  When the server is back up, you can start/spawn the event with *.event start \[event_id\]*. When you are finished use *.event stop \[event_id\]* to despawn it again.



Reposts and modifications
-------

Since Explorer's Stair Event is under an open source license (GPLv3), any modifications and redistributions of the SQL are explicitly allowed, as long as copyright and license notices remain intact.

However, I would appreciate it if you could drop me a message if you post/publish this event somewhere. Partly because I like to know where it is being spread, but also so I can add new versions to those threads when they are released. It would be a shame if everyone keeps using some ancient version because it was once posted on a forum, and never updated there.

You can drop me an e-mail at gmgenie [at] chocochaos [dot] com

It's not a requirement to inform me, but I would appreciate it =)



Changelog
-------

**September 13th 2014:**

*   Public event release.

**2012:**

*   Event created on Crusade Gaming.
