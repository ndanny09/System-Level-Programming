For the Hunger Games portion of the assignment, I was going to use the search function, "/string" and then replace the words manually until I found that there were
hundreds of entries found. At this point, I decided to see if there was a simpler command to do that would allow me to easily substitute each name for one Character.
On VimEditor Wiki, I was able to find such a command, ":%s/Prim/Danny/g". What this command does is that it tells the editor to substitute each instance of Prim
with Danny on ALL lines (globally) of this document.

Two commands could have been used to change the ownership and viewing permissions of the Submissions folder. Both of the two commands chown and chgrp
changes the ownership of the folder. 
chown :eg-mu-coas@gsuad.gsu.edu Submissions
chgrp eg-mu-coas@gsuad.gsu.edu Submissions
This would change the ownership of the Submissions folder to a group only the TA and the Professor have access to view.
