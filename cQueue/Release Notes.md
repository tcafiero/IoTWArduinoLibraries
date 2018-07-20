cQueue: Queue handling library (written in plain c)
2017-2018 SMFSW

Feel free to share your thoughts @ xgarmanboziax@gmail.com about:
	- issues encountered
	- optimisations
	- improvements & new functionalities

------------

** Actual:

v1.3	14 March 2018:
- Init control value set back to 0 when queue is killed (prevents failure if killing twice the same queue)
- Added q_isInitialized inline to be able to check after init if queue has been properly allocated
- Changed q_nbRecs to q_getCount, but kept q_nbRecs as macro for compatibility with earlier versions
- Changed q_clean to q_flush, but kept q_clean as macro for compatibility with earlier versions
- Comments fixes

v1.2	12 November 2017:
- Use of const qualifier in some function parameters

v1.1	16 August 2017:
- Queue init function now returns queue address (enabling check for queue allocation success)
- q_pull & q_flush alias created for earlier versions and purists respectively

v1.0	14 July 2017:
- First release
