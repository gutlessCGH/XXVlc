# XXVlc
XXVlc Skins for VLC



All modes:
- Cover art
- Jet black backgrounds for OLED Displays
- Buttons & sliders highlight on hover, simulate being depressed when clicked, fade when unavailable
- Fonts that minimize kerning issues

Main Player:
- Resizable, 360x110 pixels and up
- Pin, Load, Save Playlist, Record, Snapshot, Media Info, Minimize, Maximize, Full Screen buttons on top
- Playlist, Repeat, Shuffle, and mute on bottom
- Playlist button deploys 360 pixel wide scrollable playlist on the right side of the media window
- Cover art & title (auto-scrolling) or video shift to the left of playlist

Small Player:
- 300 pixels wide
- Cycle through 3 modes (basic, w/ playlist, w/ video/art window & playlist)
- Playlists deploy from the bottom and are expandable, scrollable
- Pin, Repeat, Shuffle, Mute, Volume Slider, and Minimize on top
- Titles scroll across full width

Minimal Player:
- Resizable video player window with 14 pixel top & bottom bars
- Additional blackout mode darkens buttons/sliders (still highlight on hover)

Known issues:
- Fullscreen controller won't show up immediately after applying the skin.  Close VLC and reopen to fix.
- Right clicking on a pinned window that is playing video will result in the menu being hidden under the player.
- Dragging & right clicking will not work on areas around the title text, timers, and buttons.  Grab the top bar, bottom corners, or cover art to drag.
- Title font has a limited character set.

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
