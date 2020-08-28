Tutorial found here: https://linuxconfig.org/bash-scripting-tutorial-for-beginners

To tell the shell to interpret a command as bash, start with a SHEBANG #!

which:
-locates a command
-e.g: which bash - will give us the path to a command
(this usually resolves to /bin/bash)

chmod:
-changes mode of a file
-change whether it can be read, written, or executed
-chmod -x means I cannot run the command in the directory
-chmod +x means I can run the command in the directory
