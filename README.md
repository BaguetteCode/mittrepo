Script Explanation

The script takes a message (--message) and a logging level (--log) as input. 
The message gets converted to uppercase and is logged to the terminal with a timestamp and log level (using logging). It then prints the message directly to terminal (using print).

The script says it supports 4 logging levels: 
DEBUG, INFO, WARNING and ERROR. 
Logging in this context means the script outputs a message depending on which log level the user selects (or if the user provides a custom message). 
But only INFO is actually defined in the code, so there's just a default message regardless of which log level the user chooses.

Users can run different commands with the script. Here are 5 examples:

1: python3 advanced_assignment.py (Prints the default value: "HELLO, GITHUB ASSIGNMENT!")

2: python3 advanced_assignment.py --message "Hello World" (prints "HELLO WORLD")

3: python3 advanced_assignment.py --log DEBUG (Prints the default value: "HELLO, GITHUB ASSIGNMENT!")

4: python3 advanced_assignment.py --message "Test" --log WARNING (prints "TEST")

5: python3 advanced_assignment.py --help (Shows a help message explaining available arguments and what they do.)

Because the script has both a print function and a log function, the text gets printed twice.





