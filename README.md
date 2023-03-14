# Banshee v2

## Brief
**Banshee v2** is an update to the previously available BattleDawn discord bot **Banshee** (now currently discontinued and offline)

## Commands
_Banshee v2 does not support discord bot slash commands. It's an old bot revived using discordjs 14._
```
?hi : Hello !
?help : Shows this menu.
?dist : Distance Calculator w/ some added tools
    -Aruguments ---> Cords1 Cords2 (optinal -radar)(to check if one cordinate is in radar range of the other cordinate.)
    -Eg: ?dist N:1111 E:22222 N:3333 E:44444
    -Note: additonal whitespace may result in an error
    -If Cordinates are not in N:xxxxx E:xxxxx format, this tool may fail.
?mil : Returns the upper & lower bounds of a military scan report.
    -If more than 1 scan result is given as an argument, sample mean of the scans is returned.
?adv : Returns the upper & lower bounds of an advance scan report.
    -If more than 1 scan result is given as an argument, sample mean of the scans is returned.
?op : Returns cordinates of perfect op cords with a provided ETA and angle
    -Eg: ?op N:1111 E:22222 2 30 <----- Here the first 2 arguments are reserved for the origin cordinates, the 3rd argument stands for the ETA(friendly) and the 4th argument stands for the Angle in counterclockwise fashion.
?opspot : If given 3-6 cordinates of ops, will return if opspot is available and if so will return the cordinate found.
?shield : If given tick # of since when shield was visible, will return all possible tick #s of when sheid may drop.
?spyprot : If given CT of the op and # of agents(optional), will calc the max spy prot needed for safety.
```
## Support and Feedback
You can contact me on discord - __SKrish#8524__ for any queries and suggestions.
