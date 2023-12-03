# Gaming Guide for Linux Mint 2023 by GDev-Peter

Welcome to the world of gaming on Linux Mint! Whether you're new to Linux or a seasoned user, this unified guide will walk you through the steps to install games on Linux Mint or any Debian-based distribution.

# Guide
## Part I - Check the game avalability

### Step A - Check [ProtonDB](https://protondb.com)
1. Go to the site > Search games... > (search the title you want to play) > 
2. You will have in front of you a tag for the game, regarding playability of the game on linux.
3. It is either native, platinum, gold, silver, bronze, or broken

### Step B - Make a decision, depending on the score
The following cases are:
- NATIVE or PLATINUM = you will have an easy time with the installation progress 
- GOLD = it is still ok to install, you may just run into some issues, but they can be easily solved 
- SILVER or BRONZE = you will have problems with the installation progress and may need to follow a guide if any problem rises. 
- BROKEN = you won't be able to play it, this problem is probably caused by an anti-cheat software that dosen't support linux

#### Step C - What next?

#### Outcome 1. The game is native
You can easly install the game, regardless of the platform you own the game.

#### Outcome 2. The game is Platinum or Gold
The game will installed ussing a tool named wine. Check the section about wine or, if you have the game on steam or epic games, can can skip that entierly and jump right to the step about this platforms

#### Outcome 3. The game is below gold
The game will installed ussing a tool named wine. Check the section about wine or, if you have the game on steam or epic games, can can skip that entierly and jump right to the step about this platforms. Different from the higher non-native tiers, you may have to check the common ways to solve bugs section and try that if the game dosen't work proprierly

#### Outcome 4. The game is broken
The game wont work on linux, whatever you try. The only solution is dual-boot with windows 


## Part II - Wine

### Part A - What is Wine?
will be updated
### Part B - What apps uses Wine?
will be updated
### Part C - What is Proton?
will be updated
### Part D - Do you need to know what wine is?
No

## Part III - Gaming Platforms

### Platform A: Steam (dif. easy)
- **install steam**
	- for this you will need to check the software manager > search "steam" > install flatpack version
- **log in with your steam account**
	- keep in mind that this is a flatpack, so it isn't packaged my the official valve team
	- this is still a safe method of instaling steam games, that is used by many
* **If the game is native**, install the game.
* **If the game is native**, but has problems in-game (low optimisations, for example), go into the game settings > compatibility > force the use of a specific steam play contability tool > play
* **If the game in non-native**, go into the game settings > compatibility > force the use of a specific steam play contability tool > play

### Platform B: Epic Games (dif. easy)
- **install the heroic launcher**, 
	- for this you will need to check the software manager > search "heroic game launcher" > install it
- **connect with epic games account**, 
	- open the app > connect with account > enter account credantials ( keep in mind that this is a safe metod used by many )
- **install the game on disk**;
- **press play**.

### Platform C: GOG Games (dif. easy)
- **install the heroic launcher**, 
	- for this you will need to check the software manager > search "heroic game launcher" > install it
- **connect with gog account**, 
	- open the app > connect with account > enter account credantials ( keep in mind that this is a safe metod used by many )
- **install the game on disk**;
- **press play**.

### Platform D: Itch.io (dif. medium)
- check the download section for the game
- **if the game has a downloadable for linux**, then download and check any guide atached / use bash (bash app)
- **if the game dosen't have a download for linux**, you need to check Platform F: Local Installer

### Platform E: Other (dif. medium)
- will be updated (PlayOnLinux / Lutris)

### Platform F: Local Installer (dif. hard)
- will be updated (PlayOnLinux / Lutris)
