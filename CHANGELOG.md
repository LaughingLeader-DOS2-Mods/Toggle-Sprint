Toggle Sprint Changelog
=======
# 2.4.1
* Added a "Clear Sprinting" Command to the Settings Book
	* Use this if updating on an existing save, or toggle off sprinting before updating.
	* Unfortunately, this doesn't seem to remove Sprinting if the status itself has become "corrupted" or whatever causes it to become "stuck". This seems to be a bug with the DOS2 engine itself, as if an update changes an existing status on a save, sometimes that status gets stuck and no amount of attempts at removing it appear to work, nor does overriding it with a new status using the same status stack. 

* Quick Fix for Older Saves
	* It seems changing the previous sprinting status hit the "unremovable status" bug from the DOS2 engine, making it impossible to remove with all the usual methods. 
		* Solutions:
			* Load a save before you updated to 2.4.0, toggle off sprinting, then update to 2.4.1.
				* Alternatively, you can use the new "Clear Sprinting" command after updating.
			* Try disabling ToggleSprint, load up your save, save under a new save name, then re-enable ToggleSprint and load up the new save. Unconfirmed if this will work for getting the Sprinting status "unstuck".

# 2.4.0
* New Settings Book
	* The game host can adjust the party's sprinting speed.
	* Auto-sprint can be toggled per character.
* More Sprinting Speeds
	* 4 Levels of sprinting speeds now available:
		* Default (50%)
		* Faster (100%)
		* Even Faster (150%)
		* Too Fast (200%)
* Removed Old Auto-Sprint Ball