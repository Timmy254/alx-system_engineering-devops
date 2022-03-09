#This directory focuses on shell expansions

#Shell expansions are executed before commands hence why we acquire different values.
#To expound more on this let's have an example
#   when we type "ls *"
# we get files and directories in our system
#For the above command the "*" is executed first through expansion and the result(which is files
#and directories in our system) is passed to the ls command and displayed.