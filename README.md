![Logo](https://media.discordapp.net/attachments/925835552937345076/962580170542313472/Logo.png?width=1440&height=351)

An Among Us mod containing a bunch of roles !!
Join our [Discord](https://discord.gg/ujjxgNxaa8) if you have any problems or want to find people to play with!

**Crewmate Roles**
- [Spy](#spy)
- [Sheriff](#sheriff)
- [Medic](#medic)
- [StopTime](#stop-time)

**Neutral Roles**
- [Jester](#jester)

**Impostor Roles**
- [Camouflager](#camouflager)
- [Grenadier](#grenadier)

**Modifiers**
- [Lovers](#lovers)

-----------------------
# Releases
| Among Us - Version| Mod Version | Link |
|----------|-------------|-----------------|
| 2021.12.15s & 2021.12.15e & 2022.2.8s & 2022.2.23s | v0.0.1 | [Download]() |

-----------------------
# Installation
## Requirements 
- Among Us
- Steam or Epic Games

## Installation Guide (Steam)
**1. [Download](#releases) the Town of Us version corresponding to the installed Among Us version.**\
\
**2. Go to your Steam library.**\
\
**3. Right-click Among Us > click `Manage` > click `Browse local files`.**\
\
**4. In the File Explorer, delete the entire `Among Us` folder.**\
\
**5. Go back to your Steam library.**\
\
**6. Right-Click Among Us > click `Properties...` > click `LOCAL FILES`.**\
\
**7. Click on `VERIFY INTEGRITY OF GAME FILES...`.**\
\
**8. Wait for Steam to download a clean version of Among Us.**\
\
**9. Duplicate the new Among Us Folder.**\
\
**10. Rename it to `Among Us - ToU`.**\
\
**11. Double-click on the zip file you downloaded.**\
\
**12. Drag all the files from the zip file in the new ToU folder.**\
\
**13. Finally, launch `Among Us.exe` from that folder.**\
\
A first launch may take up to 5 minutes, so be patient if it doesn't launch immediately.<br/>
<br/>

## Installation Guide (Epic Games)
**1. [Download](#releases) the Town of Us version corresponding to the installed Among Us version.**\
\
**2. Go to your Epic Games library.**\
\
**3. Find Among Us and click on the 3 dots `...` > click `Uninstall`.**\
\
**4. Confirm you want to Uninstall Among Us.**\
\
**5. In the Epic library, click on Among Us to install.**\
\
**6. Copy the Folder Path.**\
\
**7. Uncheck Auto-Update.**\
\
**8. Click on Install.**\
\
**9. Click Yes on the Windows popup.**\
\
**10. Paste the folder path in Windows search bar.**\
\
**11. Click on Enter.**\
\
**12. Copy or move the contents of the Town Of Us zip file into the AmongUs folder.**\
\
**13. Finally, launch Among Us from Epic Games library.**\
\
A first launch may take up to 5 minutes, so be patient if it doesn't launch immediately.<br/>
<br/>

![Install](https://i.imgur.com/pvBAyZN.png)

-----------------------
# Roles
# Crewmate Roles
-----------------------
## Spy
### **Team: Crewmates**

The Spy is a Crewmate that gains more information when on Admin Table and Vitals.\
On Admin Table, the Spy can see the colors of every person on the map.\
On Vitals, the Spy can see how long killed bodies have been dead for.
### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Spy | The percentage probability of the Spy appearing | Percentage | 0% |

-----------------------
## Sheriff
### **Team: Crewmates**
The Sheriff is a Crewmate that has the ability to eliminate the Impostors using their kill button.\
However, if they kill a Crewmate or a Neutral player they can't kill, they instead die themselves.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Sheriff | The percentage probability of the Sheriff appearing | Percentage | 0% |
| Sheriff Miskill Kills Crewmate | Whether the other player is killed if the Sheriff Misfires | Toggle | False |
| Sheriff Kills Jester | Whether the Sheriff is able to kill the Jester | Toggle | False |
| Sheriff Kills The Glitch | Whether the Sheriff is able to kill The Glitch | Toggle | False |
| Sheriff Kills Executioner | Whether the Sheriff is able to kill the Executioner | Toggle | False |
| Sheriff Kills Arsonist | Whether the Sheriff is able to kill the Arsonist | Toggle | False |
| Sheriff Kill Cooldown | The cooldown on the Sheriff's kill button | Time | 25s |
| Sheriff can report who they've killed | Whether the Sheriff is able to report their own kills | Toggle | True |

-----------------------
## Medic
### **Team: Crewmates**
The Medic is a Crewmate that can give any player a shield that will make them immortal until the Medic dies.\
A Shielded player cannot be Shifted into, Hacked or Killed by anyone, unless by suicide.\
If the Medic reports a dead body, they can get a report containing clues to the Killer's identity.\
A report can contain the name of the killer or the color type (Darker/Lighter)


### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Medic | The percentage probability of the Medic appearing | Percentage | 0% |
| Show Shielded Player | Who should be able to see who is Shielded | Self / Medic / Self + Medic / Everyone | Self |
| Show Medic Reports | Whether the Medic should get information when reporting a body | Toggle | True |
| Time Where Medic Reports Will Have Name | If a body has been dead for shorter than this amount, the Medic's report will contain the killer's name | Time | 0s |
| Time Where Medic Reports Will Have Color Type | If a body has been dead for shorter than this amount, the Medic's report will have the type of color | Time | 15s |
| Who gets murder attempt indicator | Who will receive an indicator when someone tries to Shift into, Hack or Kill them | Medic / Shielded / Everyone / Nobody | Medic |
| Shield breaks on murder attempt | Whether the Shield breaks when someone attempts to Shift into, Hack or Kill them | Toggle | False |

-----------------------
## Time Lord
### **Team: Crewmates**
The Time Lord is a Crewmate that can rewind time and reverse the positions of all players.\
If enabled, any players killed during this time will be revived.\
Nothing but movements and kills are affected.\
If enabled, the Time Lord can't use Vitals to make things more balanced.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Time Lord | The percentage probability of the Time Lord appearing | Percentage | 0% |
| Revive During Rewind | Whether the Time Lord revives dead players when rewinding | Toggle | False |
| Rewind Duration | How far the rewind goes back in time | Time | 2s |
| Rewind Cooldown | The cooldown of the Time Lord's Rewind button | Time | 25s |
| Max Uses | The amount of times the Rewind ability can be used | Number | 5 |
| Time Lord can use Vitals | Whether the Time Lord has the ability to use Vitals | Toggle | False |

-----------------------
# Neutral Roles
## Jester
### **Team: Neutral**
The Jester is a Neutral role with its own win condition.\
If they are voted out after a meeting, the game finishes and they win.\
However, the Jester does not win if the Crewmates, Impostors or another Neutral role wins.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Jester | The percentage probability of the Jester appearing | Percentage | 0% |
| Jester Can Button | Whether the Jester Can Press the Button | Toggle | True |
| Jester Can Vent | Whether the Jester Can Vent | Toggle | False |

-----------------------
# Impostor Roles
## Camouflager
### **Team: Impostors**

The Camouflager is an Impostor that can turn everyone into colorless characters.\
Everyone then goes grey for a certain period of time, along with their names disappearing, making them become unrecognizable.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Camouflager | The percentage probability of the Camouflager appearing | Percentage | 0% |
| Camouflage Cooldown | The cooldown of the Camouflager's Camouflage button | Time | 25s |
| Camouflage Duration | How long the Camouflage lasts for | Time | 10s |

-----------------------
## Grenadier
### **Team: Impostors**

The Grenadier is an Impostor that can throw smoke grenades.\
During the game, the Grenadier has the option to throw down a smoke grenade which blinds crewmates so they can't see.\
However, a sabotage and a smoke grenade can not be active at the same time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Grenadier | The percentage probability of the Grenadier appearing | Percentage | 0% |
| Flash Grenade Cooldown | The cooldown of the Grenadier's Flash button | Time | 25s |
| Flash Grenade Duration | How long the Flash Grenade lasts for | Time | 10s |
| Grenadier can Vent | Whether the Grenadier can Vent | Toggle | False |
-----------------------
## Morphling
### **Team: Impostors**

The Morphling is an Impostor that can Morph into another player.\
At the beginning of the game and after every meeting, they can choose someone to Sample.\
They can then Morph into that person at any time for a limited amount of time.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Morphling | The percentage probability of the Morphling appearing | Percentage | 0% |
| Morph Cooldown | The cooldown of the Morphling's Morph button | Time | 25s |
| Morph Duration | How long the Morph lasts for | Time | 10s |
| Morphling can Vent | Whether the Morphling can Vent | Toggle | False |

----------------------- 
# Modifiers
Modifiers are added on top of players' roles.
## Lovers
### **Applied to All**
The Lovers are two players who are linked together.\
These two players get picked randomly between Crewmates and Impostors.\
They gain the primary objective to stay alive together.\
If they are both among the last 3 players, they win.\
In order to so, they gain access to a private chat, only visible by them in between meetings.\
However, they can also win with their respective team, hence why the Lovers do not know the role of the other lover.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Lovers | The percentage probability of the Lovers appearing | Percentage | 0% |
| Both Lovers Die | Whether the other Lover automatically dies if the other does | Toggle | True |
| Loving Impostor Probability | The chances of one lover being an Impostor | Percentage | 20% |
| Neutral Roles Can Be Lovers | Whether a Lover can be a Neutral Role | Toggle | True |

-----------------------
# Custom Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Camouflaged Comms | Whether everyone becomes camouflaged when Comms are sabotaged | Toggle | False |
| Camouflaged Meetings | Whether everyone is camouflaged during meetings while Comms are sabotaged | Toggle | False |
| Impostors can see the roles of their team | Whether Impostors are able to see which Impostor roles their teammates have | Toggle | False |
| Dead can see everyone's roles and Votes | Whether dead players are able to see the roles and votes of everyone else | Toggle | False |
| Max Neutral Roles | The maximum number of Neutral roles a game can have | Number | 1 |
| Probability of a completely vanilla game | The percentage probability of a vanilla Among Us game happening | Percentage | 0% |
| Game Start Cooldowns | The cooldown for all roles at the start of the game (excluding Impostor's Kill Cooldown) | Time | 10s |
| Parallel Medbay Scans | Whether players have to wait for others to scan | Toggle | False |
| Disable Level Icons | Whether all level icons are removed in meetings | Toggle | False |
| Disable Player Nameplates | Whether all decorative nameplates are disabled in meetings | Toggle | False |

-----------------------
# Task Tracking Settings
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| See Tasks During Round | Whether people see their tasks update in game | Toggle | False |
| See Tasks During Meetings | Whether people see their task count during meetings | Toggle | False |
| See Tasks When Dead | Whether people see everyone's tasks when they're dead | Toggle | False |

-----------------------
## Assassin Ability
### **Team: Impostors**

The Assassin Ability is given to a certain number of Impostors.\
This ability gives the Impostors a chance to kill during meetings by guessing the role of non-Impostors.\
If they guessed wrong, they die instead.

### Game Options
| Name | Description | Type | Default |
|----------|:-------------:|:------:|:------:|
| Number of Assassins | How many Impostors can Assassinate | Number | 1 |
| Amnesiac Turned Impostor Can Assassinate | Whether former Amnesiacs now Impostor can Assassinate | Toggle | False |
| Traitor Can Assassinate | If someone turns into a Traitor they can Assassinate | Toggle | False |
| Assassin Kill | The number of kill the Assassin can do with his ability | Number | 1 |
| Assassin Guess Crewmate | Whether the Assassin can Guess "Crewmate" | Toggle | False |
| Assassin Guess Neutral  | Whether the Assassin can Guess Neutral roles | Toggle | False |
| Assassin Multiple Kill  | Whether the Assassin can kill more than once per meeting | Toggle | False |
| Assassinate Snitch via Crewmate Guess  | Whether the Assassin can kill the Snitch by Guessing Crewmate | Toggle | False |

-----------------------
# Extras
## New Colors!
New colors are added for crewmates to pick from: watermelon, chocolate, sky blue, beige, hot pink, turquoise and lilac.
## Rainbow Color!
A rainbow color has also been added. Anyone who equips this color will constantly switch between the colors of the rainbow.

## Colors
- Red - Darker
- Blue - Darker
- Green - Darker
- Pink - Lighter
- Orange - Lighter
- Yellow - Lighter
- Black - Darker
- White - Lighter
- Purple - Darker
- Brown - Darker
- Cyan - Lighter
- Lime - Lighter
- Maroon - Darker
- Rose - Lighter
- Banana - Lighter
- Gray - Darker
- Tan - Darker
- Coral - Lighter
- Watermelon - Darker
- Chocolate - Darker
- Sky Blue - Lighter
- Beige - Darker
- Hot Pink - Lighter
- Turquoise - Lighter
- Lilac - Lighter
- Olive - Darker
- Azure - Lighter
- Rainbow - Lighter

## Custom Hats!
Custom hats have been added, made by some very talented artists. These are mostly hats for streamers.

-----------------------
# Bug / Suggestions
If you have any bugs or any need to contact me, join the [Discord Server](https://discord.gg/ugyc4EVUYZ) or create a ticket on GitHub.

-----------------------
