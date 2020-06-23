This is has list of basic git commands
$git --version   - gets current version installed on your desktop
$git status - Tells if any commits or any recent changes
$code filename.md - creates a file on your default code editor
$git init - will initialize current directory as default git directory
$git config --global user.name Balaji Baskaran
$git config --global user.email balaji.b84@gmail.com
$git add filname.md -- tracks the changes so it can be committed. Adding commit before add will do no commit
$git commit -m "message" - lets you commit you work. -m can help you add message/comment to your commit
$git commit -am -- am switch is to say you want to track changes to the modified file as well as to write message/comments to your git commit
before adding add, the modifed file was in red color stating it wasn't tracked. after adding add or add. it changed to green stating it's being tracked
$git add. -- lets you track all the files that are in the directory, rather than having to type git -add "eachfilename.md"
$git config --edit --global - opens the global file using your default editor