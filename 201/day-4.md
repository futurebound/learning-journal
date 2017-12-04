There was a lot of confusion today in my pair programming session around forking.
We literally lost 70+ minutes to a process that could have been bugged, but was most likely just housekeeping mistakes on our end.
The problem seemed to originate from not taking things slower than we did.
This was the first day I didn't write down the instructions in my own words for myself to go through, and I kept having to refer back to them and swapping windows when I could have just written them down on my notebook.
^^ PRETTY IMPORTANT, at least for right now until I become oriented and practiced in this arena.

Because we failed to fork each others repositories, we updated all the code as required by adding and calling functions for the questions in the little guessing game exercise, but then realized we needed to copy and paste that updated code into a newly forked repository. This created a problem with doubling up directories, with very similar directory names, and the exact same filename from the original repository.

Because of this, when pushing our changes (working in navigator/driver pairs) we didn't ensure that the directories we were pushing from were the correct directories that had been created after realizing the lack of a fork.

This may or may not have caused us to push from the wrong directory, although it may have been a bug on GitHub or our own computer terminals side, but considering our lack of experience and having already made a clinical error it's much more likely we were creating the problem.

This created an unresolvable (from our experience level) difference between the fork and masters that were attempting to merge properly. We ultimately had to start over, with a new properly labelled separate directory and repository, and start the process from scratch (although we just copied our correct code into the new repository).

My main takeaway from today was the emphasis I need to place on moving slowly and accurately in the command prompt and GitHub, both of which are still relatively foreign to me and thus prone to such accidents.
/
