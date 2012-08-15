Create a Note Service for Mac OS X 10.8
=======================================

A Mac OS X text service for Mountain Lion which will create a note in the Notes application from the selected text.

In most versions of Mac OS X you can press Shift+Cmd+Y and the highlighted text will be imported into the Sticky Note application.
Since the introduction of the Notes feature on the iPhone I've wanted a quick shortcut that allowed sending a note from Mac OS X to
my iPhone. Now with Mountain Lion's separate Notes application which can sync via iCloud or any IMAP account this can be done.

Credits
=======
I got the concept of using textutil and tidy from this post on MacScripter.net: http://macscripter.net/viewtopic.php?id=39166 which does a very similar thing with files instead of as a text service

A video is available here: http://www.youtube.com/watch?v=T-I-z37N3P0&feature=g-upl

Requirements
============
- Mountain Lion
- An iCloud account setup on both iPhone and Mac.
- OR the same IMAP email account on both iPhone and Mac.

Installation
============
- Open the "Create a Note from Selection.workflow" and you should be asked to install the workflow or open it in Automator.
- Select "Install"
- If an older version of the service already exists, you'll be prompted to replace the existing one.

Usage
=====
Most applications should support Mac OS X services now. Simply highlight a piece of text and then secondary click. Select "Create a Note from Selection"


Limitations
===========
It currently does not support multiple accounts or folders. The note will always be created in the first folder of the first account. However, from there it can be moved around to any folder you would like.