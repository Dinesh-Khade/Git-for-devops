# Command Uses

## File and Directory Commands

1. **`ls`**
   - Lists the contents of the current directory. Options like `-l` show detailed information.

2. **`cd /`, `cd root`, `cd home`, `cd ubuntu`**
   - Changes the current directory to the specified path.

3. **`clear`**
   - Clears the terminal screen, improving readability.

## User and Group Management

4. **`sudo cat /etc/group`**
   - Displays the contents of the `/etc/group` file, which lists all system groups and their members.

5. **`sudo gpasswd -a linux1 Devops`**
   - Adds the user `linux1` to the group `Devops`, enabling them to access resources tied to this group.

6. **`sudo userdel -r dinesh`**
   - Deletes the user `dinesh` and removes their home directory.

7. **`sudo groupadd Demo1`**
   - Creates a new group called `Demo1` for organizing users.

8. **`sudo usermod -G Demo1 linux1`**
   - Assigns the user `linux1` to the group `Demo1`, overriding their other group memberships.

## File Permissions and Ownership

9. **`sudo chown linux1 zookiper.log`**
   - Changes the ownership of the file `zookiper.log` to the user `linux1`.

10. **`chmod 400 demo.txt`**
    - Changes file permissions so that only the owner can read the file.

11. **`chmod 774 1stscript.sh`**
    - Grants the owner read, write, and execute permissions and the group read and execute permissions.

12. **`chmod 774 backupscript.sh`**
    - Grants specific read, write, and execute permissions to the file.

## Git Commands

13. **`git clone https://github.com/Dinesh-Khade/Shell-Scripting-for-Devops.git`**
    - Downloads the repository from GitHub to your local system.

14. **`git add .`**
    - Stages all modified and new files in the current directory for a commit.

15. **`git commit -m "Add new changes"`**
    - Records the staged changes in the local repository with a commit message.

16. **`git push origin main`**
    - Uploads the committed changes to the `main` branch of the remote repository.

## Shell Script Management

17. **`vim 1stscript.sh`**
    - Opens the file `1stscript.sh` in the Vim text editor for editing.

18. **`bash 1stscript.sh`**
    - Executes the script `1stscript.sh`.

19. **`vim backupscript.sh`**
    - Opens or creates the `backupscript.sh` file in the Vim editor.

20. **`bash backupscript.sh`**
    - Executes the `backupscript.sh` script.

## File Archiving and Compression

21. **`zip -r script-backup.zip /home/ubuntu/Scripting`**
    - Compresses the `/home/ubuntu/Scripting` directory into a `script-backup.zip` archive.

22. **`unzip logs.zip`**
    - Extracts the contents of the `logs.zip` archive.

23. **`rm -r logs.zip`**
    - Removes the `logs.zip` file recursively.

24. **`zip logs-ka-backup.zip logs`**
    - Compresses the `logs` directory into a `logs-ka-backup.zip` archive.

## System Update

25. **`sudo apt update`**
    - Updates the list of available packages and their versions on Debian-based systems.
