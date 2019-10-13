# Updates

###### Makebot's last update: 10/12/19, 2019 Build Update
###### GitHub's last update: 10/12/2019 at 6:17 PM

### 2019 Build Update Log (Minor)

> Summary: Mostly visual updates.

#### Code Changes
* Edited some sentences to reduce clutter.
  * ex. "Don't see anything? Click the text at the very top of the embed." is now "Don't see anything? Click (what the text at the top says)"
* Deleted 2 commands because both were considered plain useless.

#### GitHub Changes
* Edited every single command description to be easier to read.
* Put said command descriptions in folders to be more organized.
* Added an Updates file to document updates, starting 7/19/2019 at 2:01 AM.

### 2019 Build Update Log 2 (Minor)

> Summary: Minor updates to the GitHub page.

#### Code Changes
* None.

#### GitHub Changes
* Edited [m.play](https://github.com/makebot-help/Command-Info/blob/master/music/play.md) to mention a known bug that can happen if makebot is disconnected.
* Updated the Updates file (INVALID, SEE BELOW. v)
* Replaced the Updates file with this README.md file so it shows up at the front page.

### 2019 Build Update Log 3 (Major)

> Summary: Major code updates that changes lots of things.

#### Code Changes
* Merged both the NSFW and the SFW commands together. Now if you type out the NSFW variant of a command, if there is a SFW alternative, makebot will instead search that. Otherwise if there is no alternative, that command will only work in an NSFW channel. (ex. m.gel in a sfw channel searches Safebooru instead.)
* Deleted the code for all non-search NSFW commands because you could search the tags used for those commands on the sites they search for said tags on.
* Wiped the SFW help page clean and instead added a link redirecting to [here](https://github.com/makebot-help/Command-Info/blob/master/sfw/what_changed.md)

#### GitHub Changes
* Deleted all the documentation for all SFW commands.
* Deleted all the documentation for all non-search NSFW commands.

### 2019 Build Update Log 4 (Major(?))

> Summary: 1 new command is introduced.

#### Code Changes
* Added an [m.purple](https://github.com/makebot-help/Command-Info/blob/master/fun/purple.md) command.

#### GitHub Changes
* Added documentation for said command above.

### 2019 Build Update Log 5 (Major(?))

> Summary: 1 new command is introduced, 1 useless help page has been deleted.

#### Code Changes
* Added an [m.paheal](https://github.com/makebot-help/Command-Info/blob/master/nsfw/paheal.md) command.
* Deleted the SFW help page, as there's no use for it anymore.

#### GitHub Changes
* Added documentation for said command above.
* Deleted the SFW folder.

### 2019 Build Update Log 6 (Minor)

> Summary: The Help command has been revamped, welcome message actually works now.

#### Code Changes
* Revamped the m.help command, now every command is in one embed instead of seperated into help pages.
* The welcome message meant to be sent when it first joins a server works properly now.

#### GitHub Changes
None.

### 2019 Build Update Log 7 (Minor)

> Summary: Some of the music commands need to have the user have a specific permission to work.

#### Code Changes
* m.skip, m.leave, m.volume, m.pause, and m.resume can only be used by users with the "Manage Server" permission.

#### GitHub Changes
None.
