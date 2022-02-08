# Sauce's Showdown Music Mod
[![GreasyFork](https://img.shields.io/badge/dynamic/json?color=%23990000&label=GreasyFork&query=total_installs&suffix=%20installs&url=https%3A%2F%2Fgreasyfork.org%2Fscripts%2F439680.json)](https://greasyfork.org/en/scripts/439680-sauce-s-showdown-music-mod)

This userscript modifies the default battle soundtrack selection of Pokemon Showdown.
The music tracks that are suffled through are the following:
- X and Y Elite Four Theme
- N's Final Battle Theme from Black and White
- Sun and Moon Trainer Battle Theme
- Brilliant Diamond and Shining Pearl's Giratina theme
- Neo Team Plasma's theme from Black 2 and White 2
- Team Galactic Admin from Brilliant Diamond and Shining Pearl

And more will be added soon!

The reason why the amount of code in this script is so egregiously large is because to get this custom music to load properly, many of the game's functions had to be tweaked. In this case, replacing the functions necessary involved copying massive portions of the game's code and making slight adjustments. This is, however, allowed under the Pokemon Showdown Client's license on GitHub. The actual custom music stuff is from lines 2077 to 2112; The rest of the file is just tweaks to get the audio files to load properly.

This userscript is not finished, and more additions and tweaks will be made soon
