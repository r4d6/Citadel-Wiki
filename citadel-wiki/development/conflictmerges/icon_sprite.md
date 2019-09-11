### Sprite conflict! 

Tools that are used to resolve said confliction in files

Gitdesk Top - Confirmed to work

Git Bash -?

TortoiseGit -?


#### Gitdesk Top

1. Open the .dmi file that is causing the conflict in Dream Maker

2. Ctrl + Click any sprites/icons that have been modified or added.

3. Right click on the selected sprites/icons, and click export. 

4. Export the sprites/icons to any location outside of the repository folder that you will be able to locate later. 

5. Close all instances of Dream Maker

6. Using GitHub desktop, or alternative, locate the tab titled "branch", click it to bring up a drop down menu. Find and select "merge into current branch" or equivalent.

7. A menu will open up asking you which branch you'd like to merge from. Select "master".

8. At this point you will be told that there are conflicts. Find the drop down selection, and select "use modified file from master". Then click "merge" or equivalent.

9. Your .dmi has been replaced with an up to date master branch version. You will now want to reopen the .dmi in dream maker.

10. At this point, you will want to remember which sprites/icons you've modified. Select and delete all sprites that you will replace with the modified versions at this time.

11. Now that dream maker is open and conflicting sprites, if any, have been deleted, right click anywhere on the Sprite/icon portion of the screen, and select "import"

12. Find the exported sprites from earlier, and select them. Click "okay" or equivalent.

13. You will now have the new sprites in your .dmi file. Make sure to save your work and then close it.

14. Select your repo, and commit your change. Remember to push it to your GitHub branch. At this point, there should be no conflicts and your PR should be good to go.


#### Git Bash

#### Git Trutle
