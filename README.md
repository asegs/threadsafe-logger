# threadsafe-logger
a concurrent logger for Golang programs

Just add a logs directory and you are good to go.  To use, add this file to your program and call the method as a goroutine from your main method.  Open to any improvements, but it's clearly very simple (ie. no buffering)

Anywhere you want to log, just call LogString(string) with the string you would like to log, it will automatically save the exact time.
