Unfed - uses scrypt as a proof of work scheme. The unfed name comes from the fact that each block has 1 grand coins (1000 coins).

	- Each normal block has 1 grand coins (1000)
	- 45 seconds block time
	- Difficulty retargets every 30 blocks 
	- Expected total coins will be 1,427,621,642.
	- 6 confirmations for transaction
	- 50 confirmations for minted blocks
	- Low transaction fees.
	- Every day (on average) there is a random superblock with 5000-10000 coins.
	- Every week (on average) (7 days) there is a random super+ block with 50000-100000 coins.
	- The prize will be halved every year.
	- First 3 days are bonus days with 5x, 3x, and 2x the normal prizes.

	- The default ports are 12387(Connect) and 12388(RPC).

The official website is: http://unfedcurrency.byethost9.com/


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
official, stable release versions of Unfed.

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
