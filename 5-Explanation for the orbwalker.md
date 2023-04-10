# Explanation for the orbwalker

![orb](https://i.imgur.com/yUkvydf.png)

 In this tab i will explain everything about the Orbwalker.

Lets start with the "Orbwalker speed settings".

## "Extra windup time"

 In league exists a windup and a winddown animation when you do attacks. Example for Ashe:
You will turn up your bow, load the arrow, shoot the arrow and release your bow again. Everything after the "shoot the arrow" is the 'winddown animation' that u can cancel without worries.
If you cancel the steps before u shot the arrow, u will cancel your autoattack. That is not a problem because we are scripting and the orbwalker handles it. The 'extra windup time' option is good when you have high MS for example.
If you recognize that you cancel autoattacks its because u have high MS, just increase the extra windup time.

## "Orbwalking speed"
 Sets the speed how fast you will orbwalking. 110% = more attacks than 90%.

## "Missile check"  
Bypasses the "extra windup time" setting. It checks if your missile is released before u do the next movement command, Depending on your "extra windup time" setting it can be a bit slower than setting it manually.

## "Use Anti-Stutter" 
removes stuttering movement when enemy is at max AA range.


## "Lasthit" 
If you press X, u will only attack minions when they're killable.

## "Freeze wave"
This is a toggle key.
If you press X, u will only attack minions when they're killable in the last possible moment.

## "Mixed" aka "Harass"
This is the 'harass' mode. You will lasthit minions and attack enemy champions. Combined with a championscript u will use spells on the enemy aswell.

## "Laneclear" 
If you press V u will attack minions regardless of their HP but u will still lasthit them. Combined with a championscript you will use spells on the minions.

## "Fast laneclear" 
This is a toggle key. If enabled, u will attack minions regardless of their HP but the orbwalker isn't waiting with attacks to lasthit the minion. Its possible that you will miss CS.

## "Combo"
If you press spacebar, u will use spells from your loaded championscripts on enemys. Of course you will autoattack them aswell.

## "Flee"
 If u hold Z, u will run towards your mouse. If the championscript supports it, u will use spells like Ezreal E, Trynda E, Kayle W etc. You wont attack enemys, just run.


# Drawings
![drawings](https://i.imgur.com/hWQByiG.png)

## "Draw overlay damage on minions"
u will see a little, white, square on the minions HP bar what shows you, how much damage u will do with one autoattack.
![miniondmg](https://i.imgur.com/Hw5SnVb.png)

## "Last hit indicator"
It will draw a white square to the HP bar when a minion is killable with one autoattack.

## "Use glow"
Instead of the square, the minion will glow green if its killable.
![glow](https://i.imgur.com/cQsUAEE.png)

## "Draw AA circle"
You have a circle around your champion what shows you your autoattack range.

## "AA circle color"
sets the color from the circle.

## "AA circle thickness" 
sets the thickness from the circle.

## "Glow"
 you have a glow effect on your own champion.

# Misc
![misc](https://i.imgur.com/vd1DugR.png)

## "Auto attack wards" 
You will attack wards in laneclear mode, in laneclear & lasthit mode or never

## "Auto attack gangplank barrels"
 You will attack GP barrels when they're killable in combo and farmingmode, in farmingmode or never

## "Attack plants"
You will attack jungle plants (visionplant, fruitplant or jumpplant) in laneclear mode

# Farming Settings
![farmingsettings](https://i.imgur.com/ySJd7i4.png)

## "Farm delay"
You will wait x MS before you kill the next minion

## "Prioritize farm over harass"
in harassmode u can choose if you wanna hit the enemy instead of the killable minion or not

## "Prioritize enemy plants/boxes/turrets over minions in Laneclear" 
Attacking a Shacobox, Jhintraps, Zyraplants, Heimerturrets.... have higher priority than minions.

## "Jungle clear small first"
You will attack the small wolves first instead of the big one.

## "Focus structures over minions"
Attacking turrets have higher priority than minions. You will still lasthit them.

# Extras

![extras](https://i.imgur.com/9W4XheY.png)
## "Disable autoattacks after x level"
U wont use autoattacks when you're above Level X

## "Block walk in walls"
There is no function for it. Looks like it's bugged since months,

## "Anti AFK"
You will move every few seconds to not be AFK flagged. U will still receive a penalty for being AFK cause Riot checks for things like goldincome, damage etc, you're just not kicked from the game.

## "Support mode"
You wont attack minions in harassmode.

## "Hold position radius"
If you're in a orbwalker mode (harass, lasthit...) and your mouse is in x range from your champ, u wont move and stand still.

## "Laneclear delay"
You will wait x MS before u attack the next minion.
