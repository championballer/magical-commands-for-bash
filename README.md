<p align="center">
  <img src="https://user-images.githubusercontent.com/12611076/66220372-30a03280-e6cd-11e9-9263-55f1eb129b1d.png">
</p>


>Linux terminal commands replaced with Harry Potter spells

![Frame 2](https://user-images.githubusercontent.com/12611076/66304658-05e8f080-e8fe-11e9-8af1-e5876e29a740.png)

To use new commands in every terminal and in different terminal sessions type this row into your ~/.bashrc or ~/.zshrc 
```
. PATH_TO_SPELLS_SCRIPT 
```
For example, if I downloaded this project to my home/ folder, the command to put into bashrc would be:
```
. /home/spellcmds/.spells.sh 
```

If you want to run the script in a single terminal session you just have to go to the location where you've downloaded the project and run 
```
. PATH_TO_PROJECT/.spells.sh
```

The same way like above one, if I downloaded the project to my home/ folder, I have to type:
```
. /home/spellcmds/.spells.sh
```

or 

```
. ~/spellcmds/.spells.sh
```

You can use source command as well so:

```
source ~/spellcmds/.spells.sh 
```

![Frame 3](https://user-images.githubusercontent.com/12611076/66304662-084b4a80-e8fe-11e9-9cd1-547b6b981a67.png)

`avadakedavra` - xkill process

`obliviate` - clear screen

`apparate $1` - change directories 

`nox` - exit terminal

`horcrux $1 $2` - copy files 

`lumos` - list files

`revelio $1` - To view a single file

`immobulus $1` - freeze a process 

`accio $1` - Create directory

`wingardium_leviosa $1 $2` - Move file

`alohomora $1` - add universal file access

`telehanda $1` - tail a file

`ascendio` - go up one level of the directory tree

`stupefy $1` - Sleep terminal

`portus` - jump home

`confringo $1` - delete a file

`evanesco $1` - hide a file

`fideliuscharm $1` - use sudo in a command

`reparo` - fix broken dependencies

`riddikulus` - easter egg apt

`sectumsempra $1` - create a new file

```
diffindo [options] filename prefix

Options:
-a –suffix-length=N use suffixes of length N (default 2)
-b –bytes=SIZE put SIZE bytes per output file
-C –line-bytes=SIZE put at most SIZE bytes of lines per output file
-d –numeric-suffixes use numeric suffixes instead of alphabetic
-l –lines=NUMBER put NUMBER lines per output file
```
- split large files into smaller files

`bombarda dir` - remove a directory

`bombardamaxima dir` - remove a directory with --force
