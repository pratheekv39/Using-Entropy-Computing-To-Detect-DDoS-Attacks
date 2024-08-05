Instructions to Setup and Run the Program:
1) Open VSCode (Recommended)
2) Open Folder "ddos-detection" from " Open Folder " present in the File dropdown(Top navigation Bar)
3) Open Terminal ( Shortcut : ctrl+ Shift + `)
4) Go to the ddos directory using the command:  cd ddos-detection (Note : If you are confused , just use pwd command to know in which directory you are present).
5) Once you are in the ddos-directory , enter the following command: ls
6) This lists all the files and directories present in the currect folder.
7) Check whether client.py and server.py are present after entering the ls command.
8) Now you can split the current terminal into 2 parts. Press ctrl+shift+5 for this.
9) In one terminal , press the following command : python server.py
10) This enables the server side to receive packets using flask framework of python.
11) In the other terminal, enter the following command: python client.py
12) This enables the client side to send packets, which simulates a DDoS Attack by sending 100 packets to the server.
13) If any error pops up like "Flask module not found" , please install the corresponding Libraries using the following command in the terminal:
14) For example:  pip install flask
15) If any other error regrading libraries pop up , just use pip install <library_name> where <library_name> is the name of the library to be insatlled.
16) After successfully running the program , the accuracy is provided for every 50 packets sent to the server.It also provides the Entropy value and outputs whetehr the DDoS attack has been carried out or not.
