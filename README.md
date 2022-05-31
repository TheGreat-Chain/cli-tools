# cli-tools
Some cli tools I coded and use everyday :)

## Make these scripts usable everywhere in the CLI
* Add the script in a $PATH directory
* To modify the $PATH : 
  * Temporarily : ```export PATH="[directory]:$PATH"```
  * Permanently : 
    *  Open ~/.bashrc
    *  Add ```export PATH="[directory]:$PATH"```
    *  Refresh using ```source ~/.bashrc```

## timer
To set an alarm that will ring after specified time.<br>
3 options :<br>
* ```-h``` : hours<br>
* ```-m``` : minuts<br>
* ```-s``` : seconds<br>

Usage : ```timer [number]```

## tempslibre
"tempslibre" means free time in french. <br>
I launch this program when I have free time and don't know what to do.<br>
It tells me an activity and for how long to do it.
I can add and remove activities.

4 options :<br>
 * ```-add``` : adds an activity to do in free time<br>
 * ```-remove``` : remove an activity<br>
 * ```-list``` : list the activities<br> 
 * ```-h``` : help<br>

Usage : ``` tempslibre [option] [activity] ```





