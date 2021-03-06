Mac Installation Guide
===========================

Macintosh installation uses the command line, but if you follow the instructions carefully, you should have no problem installing KA Lite. KA Lite uses the `git` program to distribute its software to developers and other users.

#. Download and install either Python2.6_ or Python2.7_ for Mac
	.. _Python2.6: https://www.python.org/download/releases/2.6/
	.. _Python2.7: https://www.python.org/download/releases/2.7/
#. You need to open the Terminal app. There are many ways to do this. We suggest the following:
	* Click the magnifier icon on the upper right corner and search "terminal".
	* Press *'Enter'* with the "Terminal" app selected and it should open.
#. In the Terminal, enter *Python -V* and press *'Enter'*. **The version number should reflect the Python version you just installed.**
#. Create the folder where you would like to install KA Lite.	
	* In the Terminal, type *cd* and then drag the folder you created into the Terminal.
	* This will copy the path name into the Terminal window.
	* Press *'Enter'*.
#. Now you can copy and paste this command into the terminal and press *'Enter'*.
	* *git clone https://github.com/learningequality/ka-lite.git*
#. Once it finishes downloading, enter *cd ka-lite* to move into the folder that was just downloaded.
#. To begin installation enter *./setup_mac.command*
#. During installation, you will be prompted to make an Admin account. Go ahead and follow along with the instructions.
#. To begin running the server.
	* Enter *./bin/kalite start*	
#. KA lite should be accessible from http://127.0.0.1:8008/
	* Replace *127.0.0.1* with the computer's external IP address or domain name to access it from another computer.
