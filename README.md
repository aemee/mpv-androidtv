This is just a couple of tweaks of build 2025-12-27 that I find useful for my android tv.
- removed UP button from dpad navigation so that it can be used with input.conf
  - have no idea if this was necessary for script-binding
- removed long press function of the audio and subtitle buttons
  - long press may not work as intended with some cec remotes and are treated as spamming a key instead
- replaced on press function of audio and subtitle buttons
  - from cycling audio and subtitle to bringing up their respecting selection dialog
    - I find the cycling to be redundant, not to mention, painful to cycle through expecially when you cant long press
- added audio and subtitle codec information to the selection dialog
  - mostly so I can select my desired audio/subtitle track
---
These changes are messy since it was tweaked for an earlier build but they seem to work how I want it to on this build as well. I also recommend using the following lua scripts:
- [SmartSkip](https://github.com/Eisa01/mpv-scripts/?tab=readme-ov-file#smartskip)
  - super useful for anime or tv series that are properly chaptered/bookmarked
    - otherwise, it even has silence skip built in
- and [pause indicator](https://github.com/oltodosel/mpv-scripts?tab=readme-ov-file#pause-indicatorlua)
  - so that you know its actually paused since pausing doesnt bring up the ui/osd
---
# [Click here for the original mpv-android github page.](https://github.com/mpv-android/mpv-android)
