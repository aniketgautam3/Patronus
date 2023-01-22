#  Patronus

#### 1. Creating a new folder called Patronus.

```bash
mkdir Patronus
```
#### 2. Initialing a new git repo inside of the Patronus folder (make sure you're not already inside of a Git repo!)

```bash
git init
```

#### 3. Make a new file called patronus.txt

```bash
touch patronus.txt
```

#### 4. Add and commit the empty file, with the message "add empty patronus file"

```bash
git status
git add .
git commit -m "add empty patronus file"
git push origin main
```

#### 5. Immediately make a new branch called harry and another branch called snape (both based on the master branch)

```git
git branch harry main
git branch snape main 
```

#### 6. Move to the harry branch using the "new" command to change branches

```git
git checkout harry
```

#### 7.In the patronus.txt file, add the following:

```
HARRY'S PATRONUS

   /|       |\
`__\\       //__'
   ||      ||
 \__`\     |'__/
   `_\\   //_'
   _.,:---;,._
   \_:     :_/
     |@. .@|
     |     |
     ,\.-./ \
     ;;`-'   `---__________-----.-.
     ;;;                         \_\
     ';;;                         |
      ;    |                      ;
       \   \     \        |      /
        \_, \    /        \     |\
          |';|  |,,,,,,,,/ \    \ \_
          |  |  |           \   /   |
          \  \  |           |  / \  |
           | || |           | |   | |
           | || |           | |   | |
           | || |           | |   | |
           |_||_|           |_|   |_|
          /_//_/           /_/   /_/
```

#### 8. 8. Add and commit the changes, with the commit message "add harry's stag patronus"

```git
git status
git add .
git commit -m "add harry's stag patronus"
git push origin harry
```
#### 9. Move over to the snape branch using the "older" command to change branches.

```git
git checkout snape
```
#### 10.Put the following text in the patronus.txt file:

```
SNAPE'S PATRONUS
                   .     _,
                   |`\__/ /
                   \  . .(
                    | __T|
                   /   |
      _.---======='    |
     //               {}
    `|      ,   ,     {}
     \      /___;    ,'
      ) ,-;`    `\  //
     | / (        ;||
     ||`\\        |||
     ||  \\       |||
     )\   )\      )||
     `"   `"      `""
```

#### 11. Add and commit the changes on the snape branch with the commit message "add snape's doe patronus"

```
git status
git add .
git commit -m "add snape's doe patronus"
git push origin snape
```

#### 12. Next, create a new branch based upon the snape branch called lily

```git
git branch lily snape
```

#### 13 .Move to the lily branch

```git
git checkout lily
```

#### 14. Edited the patronus.txt file so that it says LILY'S PATRONUS at the top instead of SNAPE'S PATRONUS (leave the doe ascii-art alone)


#### 15. Add and commit the change with the message "add lily's doe patronus"

```
git status
git add .
git commit -m "add lily's doe patronus"
git push origin lily
```

#### 16.Run a git command to list all branches (you should see 4)

```git
git branch
```

#### 17. Bonus: delete the snape branch (poor Snape)

```git
git branch -d snape
```
 

