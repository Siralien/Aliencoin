Aliencoin - a fork of Litecoin version with fast block time and faster confirmations (2 confirmations needed instead of 6). Like Litecoin it uses scrypt as a proof of work scheme.

	- 30 second block target
	- Difficulty retargets every 1 hour
	- Total coins will be around 200 million. 
	- Each block will have 40 coins per block
	- Block subsidy halves once per year.
	- The default ports are 52112 (connect) and 52111 (json rpc).


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Aliencoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
