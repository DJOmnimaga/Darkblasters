# Darkblasters
Open-world, turn-based role-playing game for the TI-83 Plus, TI-84 Plus and TI-82 Advanced calculators
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

######     #    ######  #    # ######  #          #     #####  ####### ####### ######   #####  
#     #   # #   #     # #   #  #     # #         # #   #     #    #    #       #     # #     # 
#     #  #   #  #     # #  #   #     # #        #   #  #          #    #       #     # #       
#     # #     # ######  ###    ######  #       #     #  #####     #    #####   ######   #####  
#     # ####### #   #   #  #   #     # #       #######       #    #    #       #   #         # 
#     # #     # #    #  #   #  #     # #       #     # #     #    #    #       #    #  #     # 
######  #     # #     # #    # ######  ####### #     #  #####     #    ####### #     #  #####  
                                           v.1.1.0
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ 

(c)2021 DJ Omnimaga Music
https://djomnimaga.music-2000.com


****************
* INTRODUCTION *
****************
Thank you for downloading Darkblaster for TI graphing calculators. Inspired by Lufia, Quest 64,
Dragon Quest, Illusiat and Mana Force series, Darkblasters is a role-playing game meant to
showcase pure TI-BASIC graphical capabilities while trying to keep speed as fast as possible.
It features over 390 rooms to explore, NPC's, some items and magic spells, many monsters and
sprite-based graphics. No ASM/Axe/Grammer lib were used, in order to ensure full compatibility
with 15 MHz z80 calculator models that lacks official ASM support.


*******************
* GETTING STARTED *
*******************
Before installing, make sure to have enough RAM for the game. The game file takes 16 KB and
you need an extra 3 or 4 KB during runtime.

=======================
Recommended Calculators
=======================
TI-82 Advanced
TI-83 Plus Silver Edition (OS 1.15 or higher required or the game won't run at all)
TI-83 Plus.Fr USB
TI-84 Plus
TI-84 Plus Silver Edition
TI-84 Plus-T
TI-84 Pocket SE
TI-84 Pocket.Fr
TI-Nspire Clickpad with TI-84 Plus keypad on

================================================
Minimum Requirement (OS 1.15 or higher required)
================================================
TI-82 Plus (twice slower)
TI-83 Plus (twice slower)
TI-83 Plus.Fr (twice slower)

======================
Installing and Playing
======================
-Simply send DBLASTER.8xp to your calculator using your favorite linking software or website.
-To launch the game, go to the PRGM menu, choose DBLASTER then hit enter twice.
-Press 2nd once the title screen has loaded to bring up the menu then choose an option.


*************
* THE STORY *
*************
A long time ago, mankind became nearly extinct after the entire world population did the Tide Pod
eating challenge simultaneously. From the dead rose a new illness that transformed animals into
monsters and many humnan survivors into Darkblasters, evil mages that look like knights.

Today, the Darkblasters stole the three crystals protecting the Kingdom of Walritia. You must defeat
the mages before they take over the world.


************
* GAMEPLAY *
************
========
Controls
========
-F1-F5: Select options on screen when available/applicable
-2ND & ALPHA: 1) Open/close menu or cancel an option when applicable
-Arrows: Move around
-MODE: Save your game (only works inside the menu or while exploring)
-CLEAR: Quit the game (only works during battle, inside the in-game menu or the title screen)

======================
Exploring and Fighting
======================
When wandering around, you will find non-playable characters that can give you items or information
to progress in your quest. There may be switches to activate in order to open secret paths. You will
also occasionally run into monsters or even bosses!

During battle, you can use up to four magic spells and items and the former increases in strenght as
you use them. If you defeat the enemy, your max hit points (HP) and magic points (MP) increase, as well
as your skills points (SP). If your HP reaches zero, then it's game over and the game reboots.

Some enemies can also make you sick, causing you to lose extra HP twice per turn and healing received
can be reduced.

While exploring, if you press 2ND, this will bring up the menu, where you can heal yourself and view
extra stats.

====
Menu
====
When in the in-game menu you can view your maximum HP and MP, your learned magic spells and inventory.
Healing items can be used there and you can save your game by pressing MODE.

============
Magic spells
============
Magic in this game requires the usage of MP (magic points) and requires more and more as you use each
spell. However, they also increase in strength in the process. Some enemies may be strong or weak against
offensive spells. You also need to find some spells by talking to NPC's.

-Gaia: Earth-elemental magic damage against the enemy
-Aura: Holy-elemental magic damage against the enemy
-Wall: Reduces damage taken for the entirety of the fight
-Cure: Restores some HP

=====
Items
=====
Items can be found either on the ground or by talking to NPC's.

-Herb: Restores all your HP.
-Potion: Cures sickness
-Elixir: Restores all your MP.
-Fairy: If you die, this automatically revives you to max HP.


**********
* F.A.Q. *
**********
1) Q: When did you start working on this project?
   A: I started in late 2012, shortly after the color screen TI-84 Plus C Silver Edition got announced.
      It remained under indefinite hiatus as I moved to the CSE and later CE, though, but it got revived
      in Early September 2021.
2) Q: How did you get the idea for this project?
   A: At first I wanted to make a small RPG using advanced TI-BASIC graphics to prepare myself for the CSE,
      but as it turns out, the CSE did not support this game's drawing technique. In September 2021,
      Illusiat 20th anniversary was approaching and I happened to find a new TI-84 Plus for cheap somewhere,
      so nostalgia kicked in but instead of doing a remake of the first Illusiat games in the series
      I decided to create a new game, so I revived this project. The name Darkblasters was decided all the way
      back in 2012, although The Game, with a title screen 8xi file where the monster data is part of the pic
      was also considered before being scrapped for a more serious name.
3) Q: How I tren my clac on
   A: Very carefully.
4) Q: How do i tern my clauacter on
   A: Go away!
5) Q: What does F.A.Q stand for?
   A: I said go away!
6) Q: How are advanced sprite graphics displayed this fast?
   A: By drawing a set of ASCII characters, storing the result into a picture, drawing a second set of
      characters on top of the others, preferably shifted 1 pixel to the right, then the picture is
      recalled so that the combined characters become sprites. Character combos were found either 
      using trial and error or using Builderboy's java TileMaker program from Omnimaga.
7) Q: How to make games like this?
   A: Sorry, I am a very bad teacher without the required patience to help you guide you through the code,
      but the code remains open and I also included the 2012 demo in the zip file if you want to focus
      more on the map engine. However, to draw double-layer text sprites, it works a bit like this
      (SourceCoder syntax):

      Text(~1,0,0,"<-=
      StorePic 0
      Text(~1,0,1,"=->     //In my game, I shift one layer by one pixel to the right.
      RecallPic 0          //White pixels inside pictures are transparent.
      
      There you got some double-lance weapon sprite! Note that one major limitation of layered text sprites
      is that when you move them around they flicker a lot, so using this technique to draw the main hero
      isn't recommended. This technique also doesn't work on color screen calculator models, the TI-76.Fr,
      the TI-82 Stats and the TI-83 (non-plus).


***********
* CREDITS *
***********
-Feel free to use any part of the code if you give me some credits, but I would like to thanks
 everyone who contributed into getting TI-BASIC documentation and tricks out there, some of
 which made this game possible.
-Tide Pod is a registered trademark and property of Procter & Gamble. Do not eat their products!


***************
* DISCLAIMERS *
***************
-I will not be held responsible if any damage occurs to your calculator via the use of this product.
-No animals, including walruses, were harmed during the making of this game.


*************
* CHANGELOG *
*************
v1.1.0 (10/01/2021)
-Doors CS 7 icon added.
-The town is now much smaller and its NPCs easier to find.
-If you save in town, reloading the game now respawns you in the middle.
-Another string variable is no longer in use.

v1.0.3 (09/28/2021)
-Some minor speed improvements.
-More optimizing done.
-The game now uses fewer real variables, lists and strings.
-The disintegrating boss animation for the last two bosses is now smoother and flickers much less.

v1.0.2 (09/23/2021)
-More optimizing done. Saved about 140 bytes.

v1.0.1 (09/20/2021)
-Some minor optimizations done
-Now appears in MirageOS

v1.0.0 (09/15/2021)
-Initial release
