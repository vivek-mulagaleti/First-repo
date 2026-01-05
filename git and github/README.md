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
    
    ---To see whats inside .git file the commmand is -->ls .git

2.git status--> this shows the status means it show which file are not add to repo and which file are untracked 
        for example:
            we made a change or wee added a new file in our folder so we made a change if it is untracked means this history is not  add to repo


3.git add . --> this is a command which puts all the untracked file in a staging state
        -- git add Filename --> puting a particular file in staging state


4.git commit -m "comment" --> it is command to save the history or the file or the changes made and which are in the "staging state" to the repo

5.git restore --staged filename --> this command is used to remove a staged status thing from staged status 

6.git log --> to see all the commits made in the history


7.git reset hashid --> if u deleted some file and you want to restore ur history just copy the below hashid and use this command 


## if you dont want to commit and in same time if u dont want to lose those we can use following command 

8.git stash --> it will backstage the changes made

9.git stash pop --> make all backstage to unstaged state 

10.git stash clear --> delete all the backstage change



## to connect github repo to our project

1.git remote add origin url
    here -remote means ur are working with url
        --add means ur adding a new url
       ---origin means what is the name of the url (in this case name of the url is "origin")


2.git remote -v this command show all the urls connect with the project 

## command 

1.git push origin master 
        -- push means pushing on which url that is "origin" on which branch that is "master"
        ----- push into the origin url into the master branchs

2.git branch branchname 
        --> used to create new branch
        ---> now head is pointing to this branch 
                --> head is a pointer that says all commits you made will be added on head 

3.git checkout main
        ---> to go back to the main branch


4.git merge branchname 
        --> merge to the main branch

5.git clone url
        --> clone the repo

## from where we have forked is called upstream url
        --> fork means taking a copy of that project in our account because we cant directly make changes in another ones