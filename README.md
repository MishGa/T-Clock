T-Clock Redux
==============
<sup>MinGW</sup> [![Build Status](https://travis-ci.org/White-Tiger/T-Clock.svg?branch=yg-master)](https://travis-ci.org/White-Tiger/T-Clock) <sup>MSVC</sup> [![Build status](https://ci.appveyor.com/api/projects/status/b3qehrl4c8naisx4?svg=true)](https://ci.appveyor.com/project/White-Tiger/t-clock) [![Coverity Status](https://scan.coverity.com/projects/3794/badge.svg)](https://scan.coverity.com/projects/white-tiger-t-clock) <sub>(click picture below for full size)</sub>
![clockshowcase](https://cloud.githubusercontent.com/assets/1467733/4608572/71b48156-5283-11e4-960f-b0415b5b7cec.png)  
**T-Clock Redux** is an enhanced fork of [Stoic Joker's T-Clock 2010](http://www.stoicjoker.com/TClock/)  
with ISO week number support, bug fixes and the ability to use Windows' default calendar and tooltips.

T-Clock *(called TClock)*, originally written by Kazubon in the early 90's, was a popular classic that was on the edge of extinction when Windows started going 64bit. ... Stoic Joker simply chose not to let that happen. And now it's up to us to continue their efforts.

If you don't mind to read lots of text, and want to know more about T-Clock and its history: [check this page out!](http://greggdeselms.com/tclock.html) *(thanks Gregg)*


### Download (binaries)
* [**view all available**](//github.com/White-Tiger/T-Clock/releases)

#### Differences to Stoic Joker's T-Clock 2010 [Build 95/98](http://www.donationcoder.com/forum/index.php?topic=21944.0)
- [x] * improved file structure
- [x] + ISO-8601 week number support *(Wi)*
- [x] + original Windows calendar and tooltip usable
- [x] + support for clocks on every additional taskbar on Win8+
- [x] + system/user dependent default colors
- [x] + clock text angle freely adjustable
- [x] + live update of clock text related changes *(see what happens as you change it and before you apply it)*
- [x] + clock text always automatically centered
- [x] + right mouse click can be customized
- [x] + mouse button 4 and 5 supported
- [x] * improved taskbar support such as horizontal vs vertical and size
- [x] + calendar hides on 2nd click if opened before *(autohide must be enabled, Windows default behavior)*
- [x] + custom calendar can now show X past months, additional improvements
- [x] + extended right-click menu with more Windows like behavior  
*(hold down CTRL or SHIFT to get "Run ..." and "Exit Explorer" items)*
- [x] + simplified mouse click preferences page
- [x] + default configuration with Windows like behavior and clock with line-break on Vista+ *(easier for first-time users)*
- [x] + more mouse commands / customization
- [x] + overall improved settings dialog *(so many changes.. can't name them all)*
- [x] * improved Stopwatch *(hotkeys, export, stats)*
- [x] * improved drag&drop support
- [x] ! some bugfixes
- [x] * some minor and major rewrites and changes
- [x] ! can be compiled with MinGW/GCC *(allows more people to work on it and also fixed bugs)*
- [x] ! fixed clock text transparency issues on Vista+
- [x] + portable mode using .ini files as configuration storage *(v2.4.0)*
- [x] + inbuild update checker *(v2.4.0)*
- [ ] + enhanced time format editor incl. realtime preview *tbd*
- [ ] + ability to use different timezones on modifiers *tbd*
- [ ] + LClock formating options such as different fonts and positions for time and date *tbd*
- [ ] + working timezone identifiers *tbd*
- [ ] + multilingual version? *tbd*
- [ ] + resource usage % format option (CPU,RAM maybe GPU) *tbd*
- [ ] + improved time synchronization incl. autorun at startup (requires admin rights for "install") *tbd*
- [ ] + mouseover customization, for example different time format, color, border or even current weather *tbd*
- [ ] + switching clock text, eg. every 2 seconds another one *tbd*
- [ ] + multiple clock text presets? eg. switch between them on mouse click *tbd*
- [ ] + maybe current sun state picture as clock background (plugin) *tbd*
- [ ] + improved hotkey support *tbd*

### Requirements
* Windows 2000+ (up to Windows 10 as of 2014, Win2k requires static builds)
* [Microsoft Visual C++ 2010 Redistributable](http://microsoft.com/en-us/download/details.aspx?id=26999) (install **both** 32bit `vcredist_x86` +  64bit `vcredist_x64` **on 64bit** OS. Alternatively just use our \_static builds)

### Support
* [Forum Topic](http://donationcoder.com/forum/index.php?topic=21944.0)
* [Issue Tracker](//github.com/White-Tiger/T-Clock/issues)
* or send a mail to the email address in T-Clock's about screen *(just click on it)*

### License
* GPLv2 ? *(license is currently unknown, needs further research)*
~~~~
