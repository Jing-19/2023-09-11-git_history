# 2023-09-11-git_history
‘add<FILENAMES>’: adding the <FILENAMES> to stating area

‘commit -m “Message”’: commit with a message everything in the stating are

‘push <where> <what>’: pushes the history/commits to the remote(where) using the commits from the specified branch(main) 

‘pull <where> <what>’: pulls (updates) the local repo with conents in the remote(where) using the information in the specified branch (what)

"log": shows the log
    - "log -- oneline"L show the log in condenced format
    - this may open a terminal program called "less" that lets you scroll, use "q" to quit out of less 

"diff": show you every change has been made, and what the changes are 
    - show you the difference between your changes and the last know git state
    - "diff --staged" shows you the diff of the files in the staging area

'restore --staged <FILE>': undo the git add step, unstages <FILES> from the staging area

problamatics code, that i dont want it to happen

added a line from vscode web on github 