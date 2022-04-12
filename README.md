# Concept AV Work Projects

Find code in the above; as this becomes more populated, code may be reorganised to be folders of clients instead of specific jobs. We will see.

Download files by either using the GitHub CLI or by clicking on the file and clicking "download"; please note that files can only be downloaded one by one this way.

## Initial Setup with the Git CLI (Windows)

1. Download and install the GitHub CLI.
2. Navigate to the folder you would like to use to store code locally.
3. Right click on empty space in the folder, and click "Git Bash Here"
4. Initialise a local repository using `git init`
5. Add the remote repository using `git remote add cav https://github.com/jbedwany/work-projects.git`

## Using Git CLI to download files
1. Navigate to the folder you would like to use to store code locally.
2. Right click on empty space in the folder, and click "Git Bash Here"
3. Prepare download of remote content with `git fetch cav`
4. Complete download using `git checkout cav/main -- <location>`
    * Location is the repository location for the code you want, using backslashes where spaces occur; for example, to download code for UoS G12 Zoom Rooms, `<location>` would be `./UoS\ G12\ Zoom Rooms`
    * Location is case sensitive; you must match the name exactly.