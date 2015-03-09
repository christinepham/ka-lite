Linux Installation Guide
===========================
.. note:: You will need to make sure *sudo* is installed for both Debian and Ubuntu. These commands can then be used for both operating systems. 

.. note:: Type the following commands in a terminal.

#. Check if Python is already installed with *python -V*.
#. If not already installed or outdated, install Python v2.6 (*sudo apt-get install python2.6*) or v2.7 (*sudo apt-get install python2.7*).
	* Or use your Distro's Package Manager by searching for *Python*.
#. If not already installed or outdated, install Git with *apt-get install git-core*.
	* Or use your Distro's Package Manager by searching for *Git*.
#. Switch to the directory in which you wish to install KA-Lite.
#. Enter *git clone https://github.com/learningequality/ka-lite.git* to download KA Lite.

	.. image:: LinuxStep0.png
		:align: center
	
	.. image:: LinuxStep1.png
		:align: center
		
#. Switch into the newly downloaded ka-lite directory.
#. Run the install script with *./setup_unix.sh*.

	.. image:: LinuxStep2.png
		:align: center
		
#. **IF** you want the server to start automatically in the background answer 'Y' or 'N'.
	
	.. image:: LinuxStep3.png
		:align: center
		
#. **IF** the automatic background option was not chosen, start the server by running *./start.sh* in the ka-lite directory.
#. KA Lite should be accessible from http://127.0.0.1:8008/ 
	* Replace *127.0.0.1* with the computer's external IP address or domain name to access it from another computer.
	
	.. image:: LinuxStep4.png
		:align: center


