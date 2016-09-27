#### Testing success/failure of a command

A very common usage of the if condition is to test if a previous command exited successfully, indicated by an exit code of `0`.  ANything other than a `0` is considered to be an error condition.  The variable `$?` will contain the exit code from the last run command.  Here is a simple script that verifies a successful execution of the previous command.  

```
#! /bin/bash 

echo "This will work!"

if [ $? -eq 0 ]
then 
	echo "Yep it worked"
else 
	echo "It didn't work :( " 
fi

```

