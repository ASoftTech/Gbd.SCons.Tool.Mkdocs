# Readme

## Overview

The code for this tool was originally sourced from

  * https://bitbucket.org/russel/scons_doxygen/overview

That in turn was based n the builder from:

  * http://www.scons.org/wiki/DoxygenBuilder by Matthew Nicolson 2006-03-31
 
## History

Attached to this wiki page were two other files, both of which are in the repository history
although removed from being in the working tree: doxygen_reiners_2007-02-26.py, and
doxygen_boehme_2007-07-18.py.  Boehme's version seems to include many of the changes in Reiners but many of
Reiners changes are missing from Boehme.  It is not clear why Reiner's changes have been reverted by Boehme.
it seems appropriate to merge in Boehme's directly rather than Reiner's and then Boehme's.

Robert Smallshire in his email of
http://scons.tigris.org/ds/viewMessage.do?dsForumId=1272&dsMessageId=2383574 supports the move to use
Boehme's version as the next iteration.  It may then be that a version he has can be merged in.

Apart from one change to the builder command line, Norton's version seems to be Boehme's version with all
the TAGFILE stuff removed.

Since then others have made contributions, see the log for the history.