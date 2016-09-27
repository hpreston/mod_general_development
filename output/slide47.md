#### Common use of While loop... waiting for something to happen

In a script, you may want to wait for some previous command to have its full effect, or some other condition to come about.  You can use the while loop for this to test your condition, but it's a good idea to insert a `sleep` command in the loop to prevent your script from testing a condition to rapidly.  You can quickly have a negative effect on your own or remote machines by loops that are uncontrolled.  Here's an example with a sleep inserted to pause 5 seconds between entries.  

