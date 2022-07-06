# Whistle Plugin for Counter-Strike: Source
Press E (use-key) to whistle to player. Pretty funny, I think...
<br><br>

Whistle hear only you and target.

There is chance `1:50` to play fun sound.

Chance `1:5` to loose money after whistle.
<br><br>

Possible to set `min/max pitch` to sounds for fun. Basically its used to slightly tweak played sound to hear it different.
<br><br>

If you want to add your own sounds, check:
```
#define SOUNDFORMAT ".mp3"
#define SOUNDQUANTITY 4	// except zero
```
whistle0 is fun sound played when fun chance shots. If you dont have whistle0 sound, set `whs_funnychance "0"`

## Console Variariables:
<details>
  <summary>Autogenerated .cfg file</summary>
  
```
// Cooldown to whistle (in secs) {1, inf}
// -
// Default: "5"
// Minimum: "1.000000"
whs_cooldown "5"

// Enable whistle plugin. {0/1}
// -
// Default: "1"
// Minimum: "0.000000"
// Maximum: "1.000000"
whs_enable "1"

// 1/n  Chance to play fun whistle. 0 - disabled {0, inf}
// -
// Default: "50"
// Minimum: "0.000000"
whs_funnychance "50"

// 1/n  Chance to loose money by whistle. 0 - disabled {0, inf}
// -
// Default: "5"
// Minimum: "0.000000"
whs_loosechance "5"

// Max distance to whistle. (in units) {0, inf}
// -
// Default: "800"
// Minimum: "0.000000"
whs_maxdistance "800"

// Message to target of whistle. 0 - disable chat messages, 1 - enable chat mesages, 2 - anonimyze chat messages. {0/1/2}
// -
// Default: "1"
// Minimum: "0.000000"
// Maximum: "2.000000"
whs_message "1"

// Money to loose by whistle
// -
// Default: "100"
whs_moneytoloose "100"

// Upper border of pitch (in %) {1, inf}
// -
// Default: "120"
// Minimum: "1.000000"
whs_pitchmax "120"

// Lower border of pitch (in %) {1, inf}
// -
// Default: "85"
// Minimum: "1.000000"
whs_pitchmin "85"

// Can whistle to: 0 - everyone, 1 - only ally, 2 - only enemy. {0/1/2}
// -
// Default: "0"
// Minimum: "0.000000"
// Maximum: "2.000000"
whs_restrictteam "0"
```
</details>
