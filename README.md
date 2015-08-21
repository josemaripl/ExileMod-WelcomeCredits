# Welcome Credits For ExileMod - [Download](https://github.com/Gr8z/ExileMod-WelcomeCredits/archive/master.zip)
Introducing Credit Styled Welcome Messages For The NEW ExileMod. Whenever a new player or a Bambi spawns in and parashoots, You get these Beautiful Credits for a Warm Welcome to every new spawn. These can work in any map and compatible with the ExileMod Spawn Selection Menu

### Install Intructions ###

- Add this at the end of your **initPlayerLocal.sqf** in your missions PBO
```
// Welcome Credits by Gr8
[] execVM "custom\welcome.sqf";
```

- Copy the **custom** folder in your Mission PBO

- In your **Description.ext** add this at the bottom:
```
class cfgMusic{ 
class intro {  
	name = "intro";
	sound = {"IntroSong.ogg", db+1,1}; 
  };
};
```
### BattlEye Filters ###

COMING SOON !
