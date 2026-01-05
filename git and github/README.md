## git and github

--> git and github allows us to maintain the history of our project
--> at what particular time which person made which change and where he  made change can be seen

## github
--> its is online platfrom that alows us to post our repository


## git is version control system and github and there are may other online platform used to host or publish our repositorys 



## commands 
1.git init--> inizalizse initialize a repo(means a folder) in it
    this git folder is hidden to see this folder we use a command called
    -->ls -a (this command shows all the hidden folder)
    -->ls (this command shows the list of all file in that folder)
    
    To see whats inside .git file the commmand is -->ls .git

2.git status--> this shows the status means it show which file are not add to repo and which file are untracked 
        for example:
            we made a change or wee added a new file in our folder so we made a change if it is untracked means this history is not  add to repo


3.git add . --> this is a command which puts all the untracked file in a staging state
        -- git add Filename --> puting a particular file in staging state


4.git commit -m "comment" --> it is command to save the history or the file or the changes made and which are in the "staging state" to the repo

5.git restore --staged filename --> this command is used to remove a staged status thing from staged status 