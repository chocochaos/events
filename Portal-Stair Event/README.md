Portal-Stair Event
=======

Portal-Stair Event is a stair event with an additional puzzle in the middle. It was originally made by Chocochaos for Crusade Gaming in 2012.

**Event information:**

*   **Type:** stair event with portal puzzle
*   **Difficulty:** advanced
*   **Length:** short
*   **Location:** Shatterspear Village (Darkshore)
*   **Decoration/theme:** none

**Server requirements:**

*   **Emulator:** TrinityCore
*   **Game version:** 3.3.5

It might be possible to use the event on other emulators/game versions, this has not been tested so far though. If you have successfully imported the event on an other emulator/version, please let me know (gmgenie [at] chocochaos [dot] com).

Please note that this event takes place on Kalimdor, if you are running Cataclysm or higher, or if you are using some custom fly-patch, this event will be in a flying zone, and thus not usable for you.



Screenshots and videos
-------

Unfortunately, no event video has been made yet. If you have one, please let me know!

*   **Portal puzzle:** [![Screenshot of Portal Puzzle](http://www.chocochaos.com/gmgenie/events/Portal-Stair Event.thumb.jpg)](http://www.chocochaos.com/gmgenie/events/Portal-Stair Event.jpg)

If you run the event on your server, I'd appreciate if you could make some screenshots or videos and send them to me (gmgenie [at] chocochaos [dot] com).



Usage instructions
-------

1.  Download the event SQL: https://raw.githubusercontent.com/chocochaos/events/master/Portal-Stair%20Event/Portal-Stair%20Event.sql
2.  Edit the file with notepad (or an other text editor, but certainly NOT word) and review the configuration variables at the top.
3.  Check if the event and gameobject_template ids you configured are available in the database. Also check if the guids in the gameobject table are not taken yet.
4.  Execute the SQL file on your database.
5.  Restart the server (unfortunately reloading gameobjects is not possible in-game).
6.  When the server is back up, you can start/spawn the event with *.event start \[event_id\]*. When you are finished use *.event stop \[event_id\]* to despawn it again.



Reposts and modifications
-------

Since Portal-Stair Event is under an open source license (GPLv3), any modifications and redistributions of the SQL are explicitly allowed, as long as copyright and license notices remain intact.

However, I would appreciate it if you could drop me a message if you post/publish this event somewhere. Partly because I like to know where it is being spread, but also so I can add new versions to those threads when they are released. It would be a shame if everyone keeps using some ancient version because it was once posted on a forum, and never updated there.

You can drop me an e-mail at gmgenie [at] chocochaos [dot] com

It's not a requirement to inform me, but I would appreciate it =)



Changelog
-------

**September 7th 2014:**

*   Public event release.

**2012:**

*   Event created on Crusade Gaming.
