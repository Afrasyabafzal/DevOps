# Git-and-Linux-Commands
# **Afrasyab Afzal** 
**19i-0627**

# Git Commands:
![Git](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)




Initialize a local Git repository:

    git init


Add files to the staging area:
    
    git add <filename>
    git add *

Commit changes to the local repository:
    
    git commit -m "Commit message"
    git commit -a

Add a remote repository:
            
    git remote add origin <url>

List all the remote connections to your local repository:
                    
    git remote -v

Show information about a remote connection:
                        
    git remote show origin

Rename a remote connection:
                            
    git remote rename origin <newname>


Remove a remote connection:

    git remote rm origin  


Push changes to the remote repository:
        
    git push origin master
    git push

Pull changes from the remote repository:
            
    git pull

Clone a repository into a new directory:
                
    git clone <url>

Check the status of the local repository:
                    
    git status
                    
Check the log of the local repository:
                        
    git log
                        
Check the difference between the files in the local repository and the staging area:
                            
    git diff

List all the branches in the local repository:
                                
    git branch

Create a new branch:
                                    
    git branch <branchname>

Switch to a branch:
                                        
    git checkout <branchname>

Merge a branch into the active branch:
                                            
    git merge <branchname>

Delete a branch:
                                                
    git branch -d <branchname>

Push a branch to your remote repository:
                                                    
    git push origin <branchname>

Push all branches to your remote repository:
                                                        
    git push --all origin

Undo the last commit and keep the changes:
    
    git reset --soft HEAD~1

Undo the last commit and move the changes to the staging area:
                                                                    
    git reset --mixed HEAD~1

Undo the last commit and remove the changes:
                                                                        
    git reset --hard HEAD~1

Reset the local repository to the last commit:
                                                                            
    git reset --hard HEAD

Reset the local repository to a specific commit:
                                                                                
    git reset --hard <commit>

Reset the local repository to the last commit on the remote repository:
                                                                                    
    git reset --hard origin/master

Reset the local repository and staging area to the last commit on the remote repository:
                                                                                        
    git reset --hard origin/master


# Linux Commands:

<!-- Linux logo -->
![Linux](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/1200px-Tux.svg.png)

## Basic Commands:
Make a directory:

    mkdir <directory name>

Remove a directory:
    
    rmdir <directory name>

Change directory:

    cd <directory name>

List directory contents:

    ls

List directory contents with hidden files:

    ls -a

List directory contents with file size:
    
    ls -l

List directory contents with file size and hidden files:

    ls -la

Create a file:

    touch <file name>

Remove a file:
    
    rm <file name>

Remove a file without confirmation:
    
    rm -f <file name>

Remove a directory and all its contents:
        
    rm -r <directory name>

Remove a directory and all its contents without confirmation:
            
    rm -rf <directory name>

Copy a file:
    
    cp <source file> <destination file>

Copy a directory:
        
    cp -r <source directory> <destination directory>

Move a file:

    mv <source file> <destination file>

Move a directory:

    mv <source directory> <destination directory>

Display the contents of a file:

    cat <file name>

Display the contents of a file in real time:
    
    tail -f <file name>

Display the contents of a file in real time with line numbers:
            
    tail -f -n +1 <file name>

Display the contents of a file in real time with line numbers and file name:
                
    tail -f -n +1 -q <file name>

Displat the first 10 lines of a file:

    head <file name>

Display the first 10 lines of a file with line numbers:
    
    head -n <file name>

Display the first 10 lines of a file with line numbers and file name:
            
    head -n -q <file name>

Make a symbolic link:

    ln -s <source file> <destination file>

Make a hard link:
    
    ln <source file> <destination file>

Search for a file in a directory:

    find <directory name> -name <file name>

Search for a file in a directory and all its subdirectories:
    
    find <directory name> -name <file name> -print

Print the current working directory:

    pwd

Print the current working directory with file size:
    
    pwd -l

Print lines matching a pattern:

    grep <pattern> <file name>

Print lines matching a pattern with line numbers:
        
    grep -n <pattern> <file name>
