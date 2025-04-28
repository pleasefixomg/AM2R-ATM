# AM2R (A)udial (T)ribute (M)od 
This is a nearly full music replacement mod with a heavy focus on Metroid 2 and its remakes.  

Originally started as a personal project to replace a mod I got from someone else a long time ago that exclusively used the gameboy soundtrack, now turned into a much more involved full-blown public release with way more work put into it than I had ever imagined.

---

Almost every music track in AM2R has been replaced and edited in some way, and are still a work in-progress though now mostly complete. You can see which files still need work by looking at the .ogg comments in the mod folder. Some were re-recorded because nothing available was good enough, some were restored from the best recordings I could find, and everything was laboured over to be made as clear, seamless, and true to the source as possible. I grew up with these games in their eras and accuracy is paramount.

Every track from the Gameboy game is here. The DUNDUNDUNDUNdundundun is gone though for now along with the "Metroid Eliminated" fanfare.  

Many room music transitions and starting bgms in save rooms have been changed around for better continuity and to better fit all the new stuff in.  

Because of the way Gamemaker handles looping, songs with intros were extended to 30mins in hopes that you don't loop back around to the intro even if you pause for a bit. For all songs, I kept the footprint to about 1mb/min of music time, and am looking to fix some of these looping issues in the future to reduce the mod size. 

---

***PLEASE REPORT ANY ISSUES WITH VOLUME OR OTHER ODDITIES. CHECK THE TO-DO LIST BEFORE REPORTING ANY FUNKY TRANSITIONS AS IT MAY ALREADY BE KNOWN. THERE SHOULD BE NO CRASHES.***

***THE AM2R LAUNCHER IS REQUIRED TO USE THIS MOD:*** https://github.com/AM2R-Community-Developers/AM2RLauncher  

***I CANNOT ASSIST YOU WITH GETTING THE LAUNCHER TO WORK ON YOUR RESPECTIVE OS***

***AM2R V1.1 IS NOT AND WILL NEVER BE INCLUDED IN THE DOWNLOAD FOR THIS MOD.***  

---

CHANGES & ADDITIONS:
  
8 new tracks added to code:  
-musCaveAmbienceA2 (Gameboy "Deep Caverns 2")  
-musCaveAmbienceA3 (Gameboy "Deep Caverns 3")  
-musCaveAmbienceA3C (DS "Deep Caverns 3")  
-musCaveAmbienceA6 (Gameboy "Deep Caverns 4")  
-musCaveAmbienceA7 (Gameboy "Omega Metroid Territory")  
-musCaveAmbienceA8 (DS Crateria Super Metroid Rendition)  
-musItemAmbS (Super Metroid "Item Room")  
-musMonsterAppear2 (AM2R "Vs. Metroid" Intro)  
 
2 songs remixed/arranged/spliced/stitched/whatever you want to call it:  
-musArea3A (DS "Ancient Chozo Ruins V.2")  
-musTester (Prime 2 "Vs. Amorbis")  
 
7 tracks kept from AM2R with 4 changes:  
-musArea2A (Formerly 1A. Cleaned up fade in/out)  
-musArea6A (Unedited)  
-musMonsterAppear2 (Formerly MonsterAppear)  
-musGammaFight (Formerly OmegaFight)  
-musQueen2 (Formerly Queen3)  
-musQueenBreak (Unedited)  
-musEnding (Unedited)  
 
4 tracks from Super Metroid restored with nearly all background noise and clipping removed:  
-musIntroSeq (Intro Theme. Faded out to fit AM2R's intro length)  
-musArea8 (Crateria Underground)  
-musGenesis (Mini Boss Confrontation/Spore Spawn)  
-musItemAmbS (Item Room)  
 
One sound file replaced:  
-sndTLM (The Last Metroid Is In Captivity...) changed to original Super Metroid sound.  
 
Everything else is something else and either looped or extended by me.    
 
---
 
BGM FLOW:  
  
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
-Prime "Chozo Ruins Gate"  
-Prime "Chozo Ruins"  
-Prime 2 "Vs. Amorbis"  

A5  
-Prime "Crashed Ship Frigate Orpheon"  
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
-AM2R "Ending"  
-DAN FREAKIN' OWSEN!!  

A8 (Thoth)  
-Super "Crateria Underground"  
-Super "Mini Boss Confrontation/Spore Spawn"  

---

To-Do:  
-Record and finish last few songs. Fix musAncientGuardian starting just a tad late. Complete any final touch-ups and normalization (0.9.2)  
-Final playthrough quality pass + a title screen?!¿ <-HELP ME (1.0)  
-Make it a dark and stormy night on Thoth so I can add one last song (1.1)  
-See about solving the looping issues to reduce the need for extensions and dramatically cut down the file size (1.2)  
-Sync up some events to reduce the need further (1.2.1)  
-Maybe see if the DUNDUNDUNDUNdundundun can be added back in as an extra track with some delays or something. Ditto to the "Metroid Eliminated" fanfare (1.3)  

Currently Considering:  
-Changing Frigate Orpheon to Torvus Catacombs. Opinions welcome.  

Things I'd like to do but can't figure out:  
-Make oEggTrigger play musArea7C right after 7B is done instead of the transition being on the next screen.  
-Make musOmegaFight begin playing as soon as the camera pan to the first Omega is done, while the gunfight is still happening.  
-Make the Thoth elevator transition seamless enough that CaveAmbience fades out quickly, allowing Area8 to play without being cut-off as you get to the top.  
(I want the opening couple seconds of Super Crateria Underground to be heard in the same fashion as when you hear it going down before the planet turns on basically. Maybe change the A8 portion of the elevator's speed to make it easier?)  

Anyone that has solutions to things I'm working on or is willing to help with a title screen because I will never, ever be an artist, feel free to reach out.
