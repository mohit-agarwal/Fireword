FireWord
--------
This is an app which enables the users to play scrabble with their peers on LAN.It is intranet based and was basically built for Mozilla OS.

------------------------------------------------------------------------

This app has been built using Node.js for realtime playing and HTML5 for the layout.Right now I have used a text with about 10 lakh words to serve as dictionary for the scrabble, but later on I will integrate it with the cloud.

------------------------------------------------------------------------

How to Play?

2 users connect to a common server and play with each other.They have to make correct words in order to continue with the game.One with maximum score wins the game.

-------------------------------------------------------------------------

How to run?

1.Unzip the zip file.
2.There is one node_modules folder which is needed to run the server.
3.Go to res/index.html and replace the IP address(line 496) with the IP address of the machine on which you want to host the game.Currently,it is hosted on localhost,so you can test it on your own machine.
4.Now go to terminal,and type the following command:
	node app1.js
	(you should be in Firefox folder)
5.Now go to browser and enter the ip on which the game is hosted.
	your ip:8082
Currently it is http://localhost:8082
6.Now enjoy the game!

