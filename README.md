# GTA-AlienCity
Fixes for GTA: Alien City<br>
*Tested on a Windows 7 Professional (EN) Virtual Machine with 4GB of RAM and 2 CPU cores.*<br>

***GTA Alien City.7z** obtained from [mixmods.com.br](https://www.mixmods.com.br/2021/03/gta-alien-city-anderius-repack-modloader-traducao/)* (use an adblocker)<br>
```
The site is in portuguese so scroll down past the screenshots until you find the 2 gray "Download" buttons
- Download the top one (554MB)
- It should take you to mediafire.com
```
⚠️You will also need an **unmodded** copy of San Andreas.⚠️

## 1. Installing the game
```
1.1. Open GTA Alien City [MixMods].7z
1.2. Open the (mod)-folder
1.3. Drag everything here to an unmodded copy of San Andreas
      Windows will ask if you want to replace files, select "yes"
1.4. Open the (bonus)-folder and open the folders
      Drag "american.gxt" into the "text"-folder in your GTA San Andreas folder.
```

## 2. Starting the game for the first time
```
2.1. Open up GTA_SA.exe (NOT gta-sa.exe)
      Depending on which version of Windows and Visual C++ you have installed, you might get errors for some .dll files, such as MSVCP100.dll
      Just press "OK" on all of them.
      If the game won't launch, or crashes when starting a new game:
        Option 1:
            - Google the name of the files
            - You should find names of what Visual C++ versions you should install
        Option 2:
            - Google the name of the files
            - Download the .dll files and place them in your GTA San Andreas folder.
            - (Downloading random .dll's of the internet is just as risky as downloading random .exe's so option 1 very recommended unless you're running on a virtual machine.)
2.2. Toggle english subtitles on at:
      Options -> Display Setup -> Subtitles ON
```

**--The game should work now!--**<br>
*...but the unpatched San Andreas experience on modern hardware is shit.<br>
See below for content warnings, fixes, notes and a list of missions*<br>

## 3. Patching the game
**WARNING:** ⚠️This game contains porn and edgy humor. See below for fixes.⚠️<br> 
**IMPORTANT:** ⚠️Updating CLEO _might_ break shit.⚠️<br>
  - The download page says it's exclusively CLEO 3
  - I updated it to 4.4.4 and nothing broke but who knows?
```
3.1. Toggle ON the frame limiter
    Menu -> Options -> Display Setup -> Advanced -> Frame limiter (ON)
      (Playing without frame limiter may cause small physics glitches,
        but also softlock the game during/when entering cutscenes)

3.2. Fix the janky ass mouse
    You can fix it manually every time you play, or download mousefix.asi
    Manual way:
      - Open up task manager (CTRL+SHIFT+ESC)
      - Find GTA_SA.exe and right click it
      - Click "select affinity" and make sure only CPU 0 is ticked on
    Mousefix.asi:
      - Download https://gamemodding.com/en/gta-san-andreas/others/26842-mouse-fix.html
      - Open the folders inside the .zip file and drag mousefix.asi to your GTA San Andreas folder

3.3. ⚠️WARNING FOR STREAMERS/YOUTUBERS⚠️
      This game contains porn and edgy humor.
      To fix this, make a "skins" folder inside the modloader,
        and replace the following skins with any mods of your choosing:
      - bfypro.dff/.txd (stripper with a big ass bush down there)
      - hfypro.dff/.txd (stripper with a big ass bush down there)
      - vwfycrp.dff/.txd (alien woman with nipples out)
      - wmyammo.dff/.txd (certain german political symbol on t-shirt)
      - sbfori.dff/.txd (britney spears with mspaint tits out)
      - sfypro.dff/.txd (prostitute with see-through top)

      Some TV screens in the game reportedly have low resolution porn images on them?
      I couldn't find any, so god speed. 🫡
      OBS has a feature to add a stream delay, so you can just cut the stream if you spot anything
        File > Settings > Advanced > Stream Delay

3.4. Update CLEO (Optional & Dangerous)
      - If you want to install custom scripts, you should update CLEO
      - Get the newest version from https://cleo.li (I used 4.4.4 for San Andreas)
      - Extract all that into the GTA San Andreas folder
        - You will get a new warning for "bass.dll" every time you open up San Andreas
        - Just press OK and ignore it
      
3.5. If you want to play User Tracks, you can put them in now.
      (GTA San Andreas/userfiles/User Tracks/)
        (This mod includes portablegta.asi which doesn't use the normal "My Documents"-folder)
```

Some of the missions can get HARD, so I recommend installing these to help you out:<br>
⚠️Note: You WILL have to install CLEO as per step 3.4 above⚠️<br>
- Cheat menu:<br>
      - Download [https://www.gtagarage.com/mods/show.php?id=16581](https://www.gtagarage.com/mods/show.php?id=16581)<br>
      - Open the folders inside the .zip file and drag cheats.cs and cheats.fxt inside the "CLEO"-folder.<br>
- Visual Car Spawner:<br>
      - Download [https://www.gtainside.com/en/sanandreas/mods/116355-visual-car-spawner-v3-3/](https://www.gtainside.com/en/sanandreas/mods/116355-visual-car-spawner-v3-3/)<br>
      - Drag the "cleo" and "models" folders to your GTA San Andreas folder<br>
- Skin selector:<br>
      - Download [https://www.gtainside.com/en/sanandreas/mods/119973-skin-selector-v2-0/](https://www.gtainside.com/en/sanandreas/mods/119973-skin-selector-v2-0/)<br>
      - Drag the "CLEO" folder to your GTA San Andreas folder<br>

## 4. Gameplay Tips
```
The game starts off by following a linear mission structure.
This means that you can't free roam until you've completed the first ~1 hour of the game.
If you wish to just get to the free roam you can download a save file:
  All but last mission: (Folder called "Сохранение перед последней миссией")
    https://libertycity.net/files/gta-san-andreas/62266-2-sokhranenija-dlja-gta-alien-city.html
  All main storyline missions:
    https://www.gtagarage.com/mods/show.php?id=14956
  100%:
    https://gamemodding.com/en/gta-san-andreas/saves/70402-save-for-alien-city.html
...and put it _inside your GTA San Andreas folder_ (GTA SA/userfiles/)
  (This mod includes portablegta.asi which doesn't use the normal "My Documents"-folder for game saves)
```

## 5. Tested Missions
```
- Prepare for some unskippable cutscenes and slow ass escort missions
- The first 7 missions are linear and you can't free roam.
- Most of the missions are on a timer and if you attempt to leave
  you will fail mission and get teleported back to the alien base
- Alot of the missions also have a SHORT timer so you might have to retry some missions.
```
### Alien Base
<details><summary>Mission 1 - Killer Test/Welcome To Anderius (Follow Greedo)</summary>
     <pre>
- Gameplay: https://www.youtube.com/watch?v=BtlQSutMYYY
- Follow Greedo through the alien base
- Do NOT go too far away from him or you will fail the mission
- Go upstairs and get into the car marked on the map
- Drive to the target on the map and kill him
- Drive back to the alien base
     </pre>
</details>
<details><summary>Mission 2 - Monster's Shaft (Protect Greedo)</summary>
     <pre>
⚠️IMPORTANT: This mission may softlock after ending. Here's how to avoid it.⚠️
  1. Press CTRL+SHIFT+ESC and right click on GTA_SA.exe
  2. Select "affinity" and untick every box except for "CPU 0".
  3. Open the games pause menu
  4. Go to Options -> Display Setup -> Advanced and toggle Frame Limiter OFF
- Gameplay: https://www.youtube.com/watch?v=XjPRst4OQQE
- Follow Greedo to the car
- Follow the dots on the map and drive to your location
- Exit the car and follow him down the elevator
- Greedo will give you a shotgun to protect him while he's fixing the elevator
  - Do NOT leave the platform
  - The shotgun has a fair spread so just keep turning and shoot whatever's close
  - Do NOT waste time with far away or big groups of zombies to prevent them from sneaking close
     </pre>
</details>
<details>
      <summary>Mission 3 - Kill Professor (Car Chase)</summary>
      <pre>
- Gameplay: https://www.youtube.com/watch?v=jkmq7RnWdHA
- Follow Greedo to the car
- Drive to an underground parking garage
- Watch a shoot-out cutscene
- Chase some guy with the car
- Watch another shoot-out cutscene
      </pre>
</details>
<details>
      <summary>Mission 4 - Right Choise (Drive the 4WD)</summary>
      <pre>
- Gameplay: https://www.youtube.com/watch?v=lBifjubU_oA
- Drive to the desert
- Take the truck
- Drive to a place in the middle of nowhere
- Watch a cutscene of CJ taking a piss
      </pre>
</details>

### The Professors Bunker
<details>
      <summary>Mission 5 - Sebastian (Racing)</summary>
      <pre>
- Gameplay: https://www.youtube.com/watch?v=hu9f2hO_CaI
- Drive the professor to his friends garage
- Choose a car
- Race through the city
      </pre>
</details>
<details>
      <summary>Mission 6 - Phil (Shootout)</summary>
      <pre>
- Gameplay: https://www.youtube.com/watch?v=EnXNNSH_Bik
- Drive the professor to his friends cookout
- Some aliens come do a shootout
- Drive to the next spot
- Leave the car and sneakily follow some guy (kill a bunch of alien guards)
- Kill the guy you're following
- Drive back home
      </pre>
</details>
<details>
      <summary>Mission 7 - Kill Mayor (Blow up the car)</summary>
      <pre>
- Gameplay: https://www.youtube.com/watch?v=1hniqoeVc0U
- Drive to the other side of the city
- Take the van
- Drive it towards the convoy
- Drive the van into the limo
- Jump out before the cars hit because it's gonna blow up
- You will get shot at so quickly go to the marker on the map (jump over the fence)
- Go to the marker and get launched to the sky
- Skydive to the car marked on the map
- Drive to the safe house
           
From this point on free roam will be enabled.
You're free to do whatever around Alien City!
      </pre>
</details>

The full game has many missions, and the main story (not including side missions) has [about 5 hours worth of content.](https://www.youtube.com/watch?v=15ZiZr7Eios)<br>
This was just some of the missions to give you a general idea of how the game works.

## 6. More Bootlegs
If you're interested in more weird GTA:SA Bootlegs with custom missions,<br>
You should check out my other Github repos!<br>
