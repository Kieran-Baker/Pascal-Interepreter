# Pascal-Interepreter
A Pascal interpreter built in Python by following the tutorials at https://ruslanspivak.com/

At present the interpreter can ony handle simple Pascal programs that include variables and procedures. It is my 
goal with this project to have it dealing with classes and functions in the future.

Also at present the interpreter doesn't actually resolve the programs it reads, it examines the scopes and prints symbol tables
for each scope. It does have all the functionality to resolve programs and I'll add this back in next.

It can handle an unlimited number of nested scopes (procedures declared within procedures). It follows the tutorials almost
exactly though I did complete all the exercises myself and have a full understanding of all the code in the project.

To test it, clone the project and from a terminal/command line run:
"python main.py Pascal\ Examples/simpleExample.pas", or:
"python main.py Pascal\ Examples/complicatedExample.pas"
As mentioned above the program will not 'run' in that you can't assign values to the variables and apply the functions to them,
it will process all the Pascal code and print symbol tables for each scope level in the programs.
