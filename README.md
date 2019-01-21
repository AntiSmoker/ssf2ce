SSF2: Community Edition
========================================================================

Navigation: Download (public DL coming soon) | **Server repository** 
  
Introduction
------------------------------------------------------------------------

This changelog for SSF2 Beta: CE, a mod of the Smash Bros fangame [Super Smash Flash 2][3]. SSF2: CE aims to change the game to better fit the tastes of the competitive and modding community, through engine, aesthetic, and balance changes throughout the board.

This repository will soon contain the latest CE releases once the mod is public, however for now it shall only contain the changelog of the game.

  [3]: http://mcleodgaming.com/games/ssf2


Engine Changes
------------------------------------------------------------------------
-  Certain stages now have alternate skins/music , look below at "Stage Changes" for more
-  After a match, vs or online, a replay saving prompt will automatically appear so you never miss saving a replay
-  Online now has a private lobby so you will no longer see regular SSF2 rooms
-  Debug/hitbox menu in offline modes, including replays
-  Shield stopping out of initial dash
-  Letting go of shield has less lag (8 --> 6 frames)
-  Attacks now beat grabs
-  SDI base increased from (6 --> 8 units)
-  Items(such as turnips) can no longer stuff out actual moves' hitboxes, as a trade between an attack's hitbox and an item will always result in the item being destroyed
-  Smash tossing an item for most chars is now lowered in throwing distance
-  CPUs now always DI randomly (with the exception on entirely vertical moves, like fox uthrow) and always tech randomly
-  The Character Select Screen has been changed to have icons on bottom and character selected on top, and to only show characters currently changed
-  The title screen has been changed to include a "Community Edition"
-  The background in all menus has been changed, and the main music has been changed
-  The swf is now named SSF2CE.swf

Stage Changes
------------------------------------------------------------------------
#### Final Destination 
-  New alternate music if Stage Alts are turned on
#### Battlefield
-  Alternate stage alt skin : Night Battlefield 
-  Alternate music if Stage Alts are turned on
#### Smashville
-  Alternate stage alt skin : Winter Smashville
-  Alternate music if Stage Alts are turned on
#### Waiting Room
-  Alternate stage alt skin : Halloween Waiting Room
-  Alternate music if Stage Alts are turned on
#### Tower of Salvation
-  Alternate stage alt skin : Tower Of Heaven (Rivals of Aether) 
-  Alternate music if Stage Alts are turned on
#### Nintendo 3DS
-  Alternate stage alt skin : Golden 3DS (Current visual bug with ledges, will be fixed next tester version)
-  Alternate music if Stage Alts are turned on

Character Changes (Subject to change)
------------------------------------------------------------------------

- The game now only shows changed characters on the CSS, the ones below:

#### Mario
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Back Air hitbox has been reduced
- Grab's hitbox has been reduced
- Forward Throw endlag has been increased
- Neutral B endlag & landing lag has been increased

#### Luigi
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Back Air hitbox and knockback have been reduced
- Down Air hitbox & knockback have been reduced
- Up Air hitbox has been reduced
- Grab's hitbox has been reduced
- Neutral Air hitbox has been reduced
- Up Throw & Down Throw knockback have been altered 
- Dash Attack hitbox has been reduced
- Up B hitbox & knockback have been reduced

#### Peach
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Hover timing has been reduced
- Throwing an item backwards in the air with Peach will now result in peach turning around
- Item throwing distance has been reduced in both the air and on the ground, to better match console smash games
- Rolling with Peach is now slower and more delayed
- Grab, Neutral Air, Down Air and Back Air have all had their hitboxes reduced 
- Down Smash has more end lag, deals less damage, and links together worse to better prevent overusage
- Forward Throw has had its knockback adjusted to deal with Peach having multiple kill throws

#### Donkey Kong
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Dash Attack can now fall off of the stage/platforms like its Project M counterpart
- Back Air hitbox has been modified
- Both Forward & Upward Cargo Throw have had their KB/angles modified
- Upward Cargo Throw now has more hitstun akin to 1.0.3.2, however it's not nearly as easy to combo off of as that versions
- Up Throw has had its KB modified
- Giant Punch has had its KB reduced

#### Sheik
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Back throw has been adjusted to be a mixup combo throw to dthrow
- Dthrow has been adjusted in KB and endlag
- Upthrow and Dthrow have had their KB angles adjusted slightly
- Grab has had its hitbox reduced
- Sheik's short hop in specific has been reverted to a .3 and prior esque short hop
- Bouncing fish is now weaker

#### Zelda
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Up Smash, Down Smash, Up Tilt, Forward Smash, Jab and Din's Fire now all have more end lag
- Forward Air, Neutral Air and Back Air have had their landing lag increased by 1-3 frames each
- Up Smash, Down Smash, Neutral Air, Grab have all had their hitboxes reduced
- Bthrow's knockback has been adjusted
- Din's Fire has received a massive overhaul which serves as a buff. Din's Fire acts as Project M's Din's does in the sense that it sticks around in the air until someone runs into it, or until time runs out. Acting as a potential trap and stage control tactic. However, it now destroys itself upon contact with the ground or a platform

#### Pikachu:
- Airspeed, crawlspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Various hitbox and hurtbox adjustments(idle, grab, uptilt, dtilt, dash, Neutral Air, Up Air, Up B)- Mostly relating to adjusting tail moves to be easier to better match hurtboxes to the animation
- Up Air now starts on frame 3 instead of frame 2, the scooping hitbox on frame 2 has been removed. The knockback angle has also been altered
- Neutral Air is now smaller
- Up B's hitboxes have been slightly adjusted but not by much
- Grab is much smaller in order to match pikachu's animation and to create a character flaw of his stubby hands making grabbing harder
- Dtilt has more end lag alongside hitbox changes
- FSmash has more end lag
- Thunder now kills later in order to make cheese kills off the top harder until later percent
- Bthrow now can potentially kill easier
- UpSmash and Fsmash have slightly less KB, mainly Fsmash

#### Zero Suit Samus
- Airspeed, crawlspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Neutral Air's hitboxes have been adjust to better fit the animation (smaller)
- No longer has a tether grab, the new regular grab however does have a middling hitbox at best, in order to maintain the character flaw around grab viability
- Down Air has received an overhaul making it more along the lines of her Project M Down Air, bouncing off shields and bouncing as it hits people and no longer sending her spiraling downwards upon usage, accompanied with slightly less landing lag to fit
- Back Air, Side B and Forward Air have received subtle KB/angle adjustments
- Dthrow's angle has now been adjusted

#### Falco
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Aerial shine has slightly less KB so off the top kills are somewhat more rare
- Back Air no longer autocancels
- Forward Air no longer autocancels
- Fsmash is weaker and has more end lag
- Lasers travel slower and deal slightly less hitlag

#### Fox
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Neutral Air has had its KB changed & its selfhitlag reduced as well
- Down B selfhitlag on ground has been increased, and decreased in the air
- Upthrow Knockback has been increased
- Laser damage has been changed

#### Falcon
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Neutral Air now has 1 more frame of landing lag, Back Air now has 2 frames more of landing lag
- Jab now has 3 more frames of end lag
- Raptor boost and Falcon dive hitboxes have been adjusted
- Knee and Back Air have received KB nerfs. Can help knee combo better but overall a slight nerf to kill power
- Falcon Punch is no longer safe due to fixed hitlag adjustments

#### Marth
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Aerial Dancing Blade now automatically sends opponents into tumblefall
- Upthrow has had its angle adjusted
- Fthrow now has more initial knockback, however has 1 less frame of endlag
- Grab's hitbox has been severely reduced
- Dolphin Slash now has a moderately sized-small hitbox for 1 frame on Marth's back during startup, which allows for a variation of the "European ken combo" without necessarily having to turnaround up B to access the hitbox
- Aerial Dolphin Slash has a stronger, but more diagonally downward located hitbox on Marth's back which serves the same purpose as its grounded counterpart

#### Meta Knight
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Forward Smash has more landing lag
- Grab's hitbox has been modified
- Up Air has had its landing back hitbox reduced
- Fsmash, Dsmash, and Up Smash have had their endlag increased
- Back Throw has had its KB angle changed to a steeper one that is less suited for directly vertical combos, and has a better chance of killing
- Down Throw now launches into the air much like its Brawl & Smash 4 counterpart

#### Tails:
- Up B has been reverted to 0.2
- Tails now has 1 double jump instead of 5
- Airspeed, crawlspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated 
- Various hitbox and hurtbox adjustments(nearly every move + idle and air animations)- Mostly relating to adjusting tail moves to be easier to better match hurtboxes to the animation
- Down Tilt no longer moves Tails forward, and has had minor KB changes
- Forward Air, Foward Tilt, Down Smash & Down Air have had their knockback angles and KB amounts adjusted
- Forward B has more cooldown between times you can repeatedly use it & more endlag 
- Neutral B now goes to heavy landing lag instead of autocancelling, and has more ending lag overall
- Neutral B's projectile deals far less shield damage

#### Sonic:
- Entire character moveset/animation redesign made to fit his Sonic Fighters appearance 

#### Lloyd
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated
- Forward Air & Back Air have had their KB/angle reduced
- Demon Fang now moves slower horizontally
- No longer able to cancel aerials out of Up B

#### Pit
- Airspeed, and ground speed changes (lower values)
- Jump heights have been adjusted to be lower and less exaggerated
- Forward Air and Up Air have had their multihits changed to single hits much like their Project M incarnation
- Side B has had its knockback reduced
- Grab's hitbox has been reduced

Credits
------------------------------------------------------------------------

Owners

- Vash  - Ideas, Design
- AntiSmoker  - Programming/Development, Design

Contributors 

- TheOneMusaab - Sonic Redesign
- Happyfrozenfire - Initial stage alt concept
- NoS - Promotion
- Creptiqal - Promotion
