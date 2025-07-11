# AM2R Audial Tribute Mod 
A nearly full music replacement mod for AM2R with a heavy focus on Metroid 2 and its remakes.  

Originally started as a personal project to replace a mod I got from someone else a long time ago that exclusively used the gameboy soundtrack, now turned into a much more involved full-blown public release with way more work put into it than I had ever imagined.  

**Current Track Count by Game:**  
Gameboy - 20  
AM2R - 7  
DS - 9  
NES - 1  
Super - 5  
Fusion - 3  
Prime - 4  
Prime 2 - 5 

---

Almost every music track in AM2R has been replaced and edited in some way, and are still a work in-progress though now mostly complete. Some were re-recorded because nothing available was good enough, some were restored from the best recordings I could find, and everything was laboured over to be made as clear, seamless, and true to the source as possible. I grew up with these games in their eras and accuracy is paramount.

Every track from the Gameboy game is here. The DUNDUNDUNDUNdundundun is gone though for now along with the "Metroid Eliminated" fanfare.  

Because of the way Gamemaker handles looping, songs with intros were extended to 30mins in hopes that you don't loop back around to the intro even if you pause for a bit. For all songs, the footprint has been kept from approximately .5 to 1mb/min of music time.

Many room music transitions and starting BGMs in save rooms have been changed around for better continuity and to better fit all the new stuff in. Many scripts and objects were also altered to better facilitate more loops and reduce the need for extensions.

INSTALLATION
---
-Download the mod from this git.  
-Place the zip into the "mods" folder of the launcher.  
-Open the launcher -> Mod Settings Tab -> Add New Mod -> Select the zip.  
-Once added, navigate back to the "Play" tab, select the mod from the dropdown if not already selected, hit "Install"  
-Play  

All releases can now generate an Android apk via the launcher to play on your phone or other Android device. Please note that the apk will not work on Android 14+ due to 32bit deprecation.  

***THE AM2R LAUNCHER IS REQUIRED TO FULLY UTILIZE THIS MOD:*** https://github.com/AM2R-Community-Developers/AM2RLauncher  

***I CANNOT ASSIST YOU WITH GETTING THINGS TO WORK ON YOUR RESPECTIVE OS.***

***AM2R V1.1 IS NOT AND WILL NEVER BE INCLUDED IN THE DOWNLOAD FOR THIS MOD.***  

***JOIN THE OFFICIAL AM2R DISCORD FOR BASE GAME AND MOD DEVELOPMENT UPDATES*** https://discord.gg/eJt9PTd

CHANGES & ADDITIONS
---

8 new tracks added to code:  
-musCaveAmbienceA2 (Gameboy "Deep Caverns 2")  
-musCaveAmbienceA3 (Gameboy "Deep Caverns 3")  
-musCaveAmbienceA3C (DS "Deep Caverns 3")  
-musCaveAmbienceA6 (Gameboy "Deep Caverns 4")  
-musCaveAmbienceA7 (AM2R "Omega Metroid Territory")  
-musCaveAmbienceA8 (DS Crateria Super Metroid Rendition)  
-musItemAmbS (Super Metroid "Item Room")  
-musMonsterAppear2 (AM2R "Vs. Metroid" Intro)  
 
2 songs remixed/arranged/spliced/stitched/whatever you want to call it:  
-musArea3A (DS "Ancient Chozo Ruins V.2")  
-musTester (Prime 2 "Vs. Amorbis")  
 
7 tracks kept from AM2R with 5 changes:  
-musArea2A (Formerly 1A. Cleaned up fade in/out)  
-musCaveAmbienceA7 (Formerly musArea6A)  
-musMonsterAppear2 (Formerly MonsterAppear)  
-musGammaFight (Formerly OmegaFight)  
-musQueen2 (Formerly Queen3)  
-musQueenBreak (Unchanged and unedited)  
-musEnding (Unchanged and unedited)  
 
4 tracks from Super Metroid restored with nearly all background noise and clipping removed:  
-musIntroSeq (Intro Theme. Faded out to fit AM2R's intro length)  
-musArea8 (Crateria Underground)  
-musGenesis (Mini Boss Confrontation/Spore Spawn)  
-musItemAmbS (Item Room)  
 
One sound file replaced:  
-sndTLM (The Last Metroid Is In Captivity...) changed to original Super Metroid sound.  
 
Everything else is something else and either looped or extended by me.    
 
BGM FLOW  
---

Behold, the most gorgeous progression timeline and Gantt chart you've ever seen:

![image](https://github.com/user-attachments/assets/4f0e0fd5-d362-4aa2-8108-530d5dcb2825)
  
A1  
-Gameboy "Surface of SR388"  
-Gameboy "Deep Caverns 1"  
-Gameboy "Ancient Chozo Ruins"  
-DS "Deep Caverns 1"  
-Fusion "Vs. Nightmare"  

A2  
-Gameboy "Deep Caverns 2"  
-AM2R "Ancient Chozo Ruins"  
-DS "Deep Caverns 2"  
-Fusion "Vs. Cyclops"  

A3  
-Gameboy "Deep Caverns 3"  
-DS "Ancient Chozo Ruins V.2"  
-DS "Ancient Chozo Ruins V.1"  
-Prime 2 "Vs. Emperor Ing"  
-Prime 2 "Vs. Mutated Emperor Ing"  
-DS "Deep Daverns 3"  

Lab + A4  
-DS "Crateria Underground" (Currently unused until a transition is fixed and even then I'm not sure...)  
-Prime "Space Pirates Main Lab"  
-DS "Surface of SR388 (Ambient)"  
-Prime "Ancient Chozo Ruins"  
-Prime "Chozo Ruins Main Plaza"  
-Prime "Chozo Ruins"  
-Prime 2 "Vs. Amorbis"  

A5  
-Prime 2 "Torvus Catacombs"  
-DS “Area 7”  
-NES "Item Room"  
-Super "Item Room"  
-Fusion "Vs. Serris"  

A6  
-Gameboy "Deep Caverns 4"  
-Super "Big Boss Confrontation 2"  
-Gameboy "Omega Metroid Territory"  

A7  
-AM2R "Omega Metroid Territory"  
-Gameboy "Metroid Nest"  
-Gameboy "The Last Metroids"  
-Gameboy "Metroid Queen Lair"  
-Gameboy "Vs. Metroid Queen"  
-AM2R "Vs. Metroid Queen"  
-DS "Vs. Metroid Queen"  
-Gameboy "The Infant Metroid"  
-Gameboy "Ending"  
-DAN FREAKIN' OWSEN!!  
-AM2R "Ending"  

A8 (Thoth)  
-Super "Crateria Underground"  
-Super "Mini Boss Confrontation/Spore Spawn"  

---

To-Do before 1.0:  
-Area 8 decisions.  
-Add DUNDUNDUNDUNdundundun and the Metroid Defeated fanfare if possible.  
-Final script adjustments and quality pass.  
-Add things to the title screen. Credits(maybe). Trailer(maybe).  

1.1  
-Make it a dark and stormy night on Thoth and then add one more song.  
