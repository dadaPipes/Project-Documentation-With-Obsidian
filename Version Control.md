1. Open Obsidian

2. Create a new vault by clicking the 'Open another vault' in the lower left corner

3. Enter a name for your vault

4. Click on the 'Browse' button and find the directory where your want to store your vault
	- to keep it with other project your can chose `C:\Users\user\source\repos\`

5. Click on the 'Create' button

6. Open Powershell and navigate to the vaults directory
	- `C:\Users\user\source\repos`

7. Navigate to the Vaults directory using Powershell
	- `cd C:\Users\user\source\repos\YourVaultName`

8. Initialize the directory as a Git repository
	 `git init`

9. Go to Github and create an empty repository ( you can add a Readme.md later )

10. In Powershell navigate to the vaults directory and add the remote Github repository you just created
	- `git remote add origin https://github.com/yourusername/yourrepository.git`

11. Create a .gitignore file in the vaults root directory
	- `New-Item -Path . -Name ".gitignore" -ItemType "file"`

12. Open the created file with notepad
	- `notepad .\.gitignore`

13. Paste this in to notepad or create your own

- Example `.gitignore` for Collaborative Development:

````
# OS-specific files
.DS_Store
Thumbs.db

# Obsidian cache and workspace
.obsidian/workspace
.obsidian/cache

# Log files
*.log
````


15. Create a Github repository 
- Go to Github and create a new repository without a Readme.md

16. Connect the local repository to Github
- In your vault´s directory, add the remote Github repository to you just created

```` https://github.com/yourusername/yourrepository.git ````  ( or use ssh )


