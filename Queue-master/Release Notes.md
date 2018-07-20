Queue handling library (designed on Arduino)
2017-2018 SMFSW

Feel free to share your thoughts @ xgarmanboziax@gmail.com about:
	- issues encountered
	- optimisations
	- improvements & new functionalities

------------

** Actual:

v1.5	14 March 2018:
- Added isInitialized inline to be able to check after init if queue has been properly allocated
- Added flush inline (to have the same functions as in cQueue library)
- LIFO peek temporary variable is uint16_t (same type as in variable)
- Comments fixes

v1.4	21 November 2017:
- Added const qualifier for function parameters

v1.3	12 July 2017:
- #2 fix for esp8266: reanamed cpp/h files : header name already used in compiler sys includes
- examples updated with new header file name (cppQueue.h)
- comply with Arduino v1.5+ IDE source located in src subfolder

v1.2	07 July 2017:
- #1 added pull inline for compatibility with older versions (v1.0)
- #2 surrounded c libs with extern C

v1.1	06 July 2017:
- pop keyword used (instead of pull)
- peek & drop functions added
- examples updated to reflect latest changes

v1.0	22 March 2017:
- First release
