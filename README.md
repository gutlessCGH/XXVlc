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
- Playlist, Repeat, Shuffle, and mute on bottom (increase and decrease playback speed can be enabled from option button in maximized window)
- Playlist button deploys 360 pixel wide scrollable playlist on the right side of the center window (alternate 720 pixel wide jumbo playlist option can be enabled in maximized window)
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
- Skinned VLC windows will not automatically snap to one quarter or one half of the screen in windows.  The minimal player maintains a separate layout from the main player in this skin so I keep mine at 1080p.  When I want video on 1/4 of my 4k monitor, I just switch to the minimal player.

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
- Search/scroll to  <Font "playlists" file="overpass-mono-regular.ttf" size="15"/>
- Change size
- Recompress folder as zip or tar; change extension to .vlt
- This will only affect the playlists.  They are spaced based just on the font size so this won't break anything.
- If you want a less-styled title font, try Overpass-Black.ttf as "titles" at size 28. https://fontmeme.com/fonts/overpass-font/

Started this as an edit of the VeLoCity Skin by dmtiir
https://github.com/dmtiir/VeLoCity-Skin-for-VLC
