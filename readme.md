## Understanding our repo

Take a look at our folders and files. We have a readme file, a src folder, a docs folder, and a bin folder
This will be the general setup for our repos in this class. Let's walk through what each of these is.

- readme.md: This file gets displayed on the GitHub Repo main page (you're looking at it now!). It should describe the repository and have any important information about it.
- src: This is the folder where our code goes (src stands for source as in source code).
- src/.gitkeep: .gitkeep is a file that exists only to keep a folder in the repository. If a folder is empty, it will not be stored in git. Once you add code to the src folder, you can delete this file.
- bin: This is the folder where our compiled code goes (.class files). We don't want those clogging up our src directory so we send them here.
- bin/.gitkeep: This .gitkeep file functions the same as the one in src, but we do NOT want to delete it. We will keep our .class files out of the repo since they are generated whenever the project is compiled and don't need to be saved. Therefore, this folder will always be empty in the repo. We still need it to be there since our command to compile code won't work if it doesn't exist
- docs: This is the folder where any relevant documentation about our project goes. We could have outlines, diagrams, and other such materials here. In this case we have the instructions for this project.