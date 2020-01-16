Function - block of code that runs a specific task, an action/verb (ex: touch zsh-cheatsheet.md (touch would be the function))

Argument - The subject of a code. Object passed into a function, noun (ex: touch zsh-cheatsheet.md (zsh-cheatsheet.md would be the argument))

Option/Flag - Modifies operation of a command. Adverb. (ex: mkdir -p test1  -p would be the option) 

ls - List stuff in current folder/directory. (ex: ls ~ will return terminal to home directory)

cd - Change directory (ex: cd codeimmersives will switch current directory to codeimmersives)
    1. cd .  takes you to current directory.
    2. cd .. takes you up one directory

pwd - print working directory, the where am I feature (ex: pwd in the ~ directory would result in /Users/username)

mkdir - make directory/folder (ex: mkdir here will make the here directory)
    1. " " - makes directory name based off quote input (ex: mkdir "test" - will make the directory test)
    2. -p -makes parent directory (ex: mkdir -p test2  - will make directory test2)
            a. ex: mkdir -p test/test2  will create directory test with test2 directory within test. 

 rm - remove files. will not remove directory. (ex: rm test.md will remove test.md file)
    1. rm -rf - will remove directory (ex: rm -rf test  will remove test directory.)

touch - creates files (ex: touch test.md - will create test.md file) 
    1. ex: touch test/file.html  will create directory named test with a file named file in it.)

cp - copy file. must have destination (ex: cp test test1  - will copy test file and create test1 file)

mv - move file. (ex: style.css Downloads - will move style.css file to Downloads directory) can also rename file. (ex: mv style.css style2.css - will copy and create new file called style2.css and delete old style.css file)

git add - adds revisions to repo

git commit - records changes to repo

git push - upload local repo to remote repo

git pull - download and integrate with another repo

git status - shows changes to be committed

git log - shows git log