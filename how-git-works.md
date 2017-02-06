
Git research:
The first source details the git structure along with how to install git. I learned my local repo contains three trees: my working directory with my files, I can then add my local files to the index or staging area. This will hold my files until i commit them into head, where git then starts tracking my files and will show the history. From the head I can push my files into a remote repository like our class repo on github. 
The basic commands are detailed in my second source. When I do git add my files are copied to the index or staging area. Git commit takes a snapshot of these files in the staging area and clears the staging area. The progression is from local files being added to the stage and then committed to track their history. A reverse progression is from history to stage with git reset which copies files from the last commit to the stage. Then from the stage to local files with git checkout which copies files from the stage to the local directory throwing away local changes. 

Sources:
https://www.youtube.com/watch?v=mYjZtU1-u9Y&list=PL1F56EA413018EEE1
http://marklodato.github.io/visual-git-guide/index-en.html

