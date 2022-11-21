# Biological-Command-Line-Interpreter
## Biological Command Line Interpreter Simulator in python.
# The Input:
The input to your project will be a command to execute along with any parameters the command demands (this will be more clarified in the following section). 
You MUST use the getopt functionality to parse the input because you will run your python file as follows:
python myfile.py command_name parameter_1 parameter_2 –o option_1 –x option_2
You can see that the command can is divided into two sections the first one is your program itself as an argument to python to be parsed and interpreted. The second part is the command your program shall consume and parse to be executed.
The parsing step should be done using getopt functionality to identify the command to be execute, get each argument and each option to be execute the command.
Your program should call the correct function in your code, that correspond to the given command, and pass it the given parameters needed to execute this command. E.g. calc_gc(args[1])

