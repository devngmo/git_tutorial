# Add new file:
- Add new file to your project folder
- Add changes (new added file or modified file) to staging environment so it will be ready for commit by:
    + command line: ```git add relative_file_path```
        + Example: ```git add step2_update.md```
    + Visual studio Code:
        + In source control panel, move the mouse cursor to the file you have just added, click button with plus icon "+" to stage change ( add file )

- Save all staged files to git:
    + by command: ```git commit -m "Commit message here"

- Or you can commit directly without command staging: 
```
git commit -a -m "commit message here"
-a: auto stage all changes before commit
```
    
