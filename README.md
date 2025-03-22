# XXVlc
XXVlc Skin for VLC

Flexible multi-mode skin specialized for OLED displays

![XXVlc_Blush_Preview](https://i.imgur.com/l0TUTNI.jpeg)

![XXVlc_Mushroom_Preview](https://i.imgur.com/YagEq9u.jpeg)

All modes:
- Cover art
- Jet black backgrounds
- Buttons & sliders highlight on hover, simulate being depressed when clicked, fade when unavailable
- Fonts that minimize kerning issues inherent to VLC skins

Main Player:
- Resizable, 360x110 pixels and up
- Pin, Load, Save Playlist, Record, Snapshot, Media Info, Minimize, Maximize, Full Screen buttons on top
- Playlist, Repeat, Shuffle, and mute on bottom
- Playlist button deploys 360 pixel wide scrollable playlist on the right side of the center window
- Media (Cover art & title (auto-scrolling) or video) shift to the left of playlist

Small Player:
- 300 pixels wide
- Cycle through 3 modes (basic, w/ playlist, w/ video/art window & playlist)
- Playlists deploy from the bottom and are expandable, scrollable, and track the currently playing file
- Pin, Repeat, Shuffle, Mute, Volume Slider, and Minimize on top
- Titles scroll across full width

Minimal Player:
- Resizable video player window with 14 pixel wide top & bottom bars
- Additional blackout mode darkens the buttons/sliders (they still highlight on hover)

Known issues:
- Fullscreen controller won't show up immediately after applying the skin.  Close VLC and reopen to fix.
- Right clicking on a pinned window that is playing video will result in the menu being hidden under the player.
- Dragging & right clicking will not work on the title text, timers, and videos.  Grab the top bar, bottom corners, or cover art to drag.
- Players can only be expanded down and to the right, a core weakness of VLC skins.
- Title font has a limited character set.

Installation:
- Place .vlt file in \Program Files\VideoLAN\VLC\skins
- Open VLC preferences, In the "Interface Menu" select "Use custom skin", and choose the .vlt file

Text is too small/large?
- Extract theme with 7zip
- Open theme.xml with editor/notepad
- Search/scroll to  <Font "playlists" file="consolas.ttf" size="16"/>
- Change size
- Recompress as zip or tar; change extension to .vlt
- This will only affect the playlists.  They are spaced based just on the font size so this won't break anything.
- You can also try other fonts by changing the string or just name another .ttf font "consolas.ttf" and replace the original.  Fonts without a default double-space put way too little space between words.

Started this as an edit of the VeLoCity Skin by dmtiir
https://github.com/dmtiir/VeLoCity-Skin-for-VLC
