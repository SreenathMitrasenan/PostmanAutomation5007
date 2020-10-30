Agenda : log csv or json responses of postman in specific directory

Prerequisites : node js should be installed and should be able to open node js command prompt

Notes/Info on this package

This is a listener library which will listen to ports and capture response information when a postman request is send from its UI or a newman script is fired from node js command line.


Steps to log responses 

1. Listener server should be up
	a. Extract the PostmanListener.zip  into any directory.
	b. You should be able to see a java script file named 'script'
	c. Open node js command line & navigate to the directory where 'script' file resides
	d. run command  'node script' on command line
	e. Server will be up & running will get a message where the responses will be logged.
2. Open postman UI & copy the 'Logger.txt' in 'Test' Session of postman
	Note : You can customize the resposne body in the logger script, currenlty its designed to log full responses.

3. Fire one sample request in postman & verify the response is logged in location dispalyed in listener server.(refer session 'e')