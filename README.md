|C- Language - C-type languages clashing with my own syntax!

|---------------------------------------------------------





|------------------------------------------|

| Info!!                                   |

|------------------------------------------|

Name: C-

Pronunciation: Cee Minus

Full Name: The C- Programming Language

Development Status: Pre-Alpha

Version: 0.01a

File Types: .cms, .lib

Creator Notes: "Really Chaotic. I love it."

Why C-? Because the keywords are the citizens and std::beep\[]; is the national anthem.









|-------------------------------------------------|

|   INTRODUCTION TO C-                            |

|-------------------------------------------------|



C- Is my own kind of programming language. It's a bit chaotic, since it's C++, C# and C clashing together with my own custom syntax.

It is quite ✨Concerning✨, but every language has to have its own separate charm. I wouldn't accept making a language which is literally like C...

This will be a wild ride, so buckle up, and les go to our first destination, Syntax!

\----------------------------------------------------------------------------------------





|-----------------------------------------|

| Syntax                                  |

|-----------------------------------------|



Syntax, our dear syntax. We need this lil guy in ANY programming language, don't we? So to make you SANE and NOT making you go to a website, here are the syntax info:

\- Every command must end with a SEMICOLON (;).

\- = to assign a value to a variable. == to test for equality.

\- It has NO main() support. C lovers, you're sad now!

\-  only brackets ( \[] ) can and WILL be used.

\-  endofcode; must be used in the end of the code.

\-  in Module files (.lib), you can use curly braces for the start and end of the info.

\-  Permanent deletion commands must always require confirmation unless force mode is enabled.

\-  std::cout/input's strings must **NOT** exceed 125 characters.

\-  you should ***NOT*** add 15 libraries in a row. That'll confuse C-poky boo.

\---------------------------------------------------------------------------------

"More Syntax rules will be added later in development!" - C-pooky boo 👻



So now, you know about syntax, right? Now let's go, to, Basic Commands!!





|-------------------------------------------------|

| Basic Commands                                  |

|-------------------------------------------------|

Here are the basic commands to kickstart you C- journey. More documentation in Specification.md.

"import <stdconsole.lib>;" -> imports a module

"std::cout >> "Hello!";" -> prints text to the console

"std::input >> "Why are you here?"; " -> inputs to the console

"std::beep\[];" -> BEEPS to the console!

"std::beep.customlimit\[6s];" -> beeps for a custom time period.

"save temperature as integer 131573;" -> saves temperature as an integer (whole number)

"save aRandomQuoteIfound as string "eating";" -> saves aRandomQuoteIfound as a string variable

"save CMinusVersion as decimal 0.95;" -> saves CMinusVersion as a decimal variable

"recall reason for nextLine" -> recalls a phrase for an input.

"from recalled reason std::input >> "Really? That's why you're here?";" -> inputs from the recalled reason

"#" -> a single-line comment.

"#\*" -> multi-line comment up to infinite lines.

"\*#" -> then end of a multi-line comment.

"endofcode;" -> basically return 0; for C-.

\---------------------------------------------------------------------------------------

More keywords will be added as the language evolves.





|------------------------------------------|

| C-pooky boo 👻                          |

|------------------------------------------|



C-pooky boo is the official mascot of C-.



He represents the chaotic and experimental spirit of the C- programming language.



C-pooky boo watches over:

\- Semicolons (;)

\- The citizens (keywords)

\- The national anthem (std::beep();)

\- Questionable syntax decisions

and.... YOUR tiny projects.





|-----------------------------------|

| C- File Extensions                |

|-----------------------------------|



In C-, there are TWO (2) file extensions meant for different purposes.



**.cms**, which stands for C Minus Source (Code); it is for all the code that C-pooky boo will evaluate 👻



**.lib**, which stands for C- Library, are the library files that you use for the standard console like **stdconsole.lib**, **math.lib**, etc



For an example of C minus code, and library file code, here:



\-stdconsole.lib-

\-cminustest.cms-



stdconsole.lib:

\# basic console commands

{

load stdcout\[as 'std::cout'];

load stdbleeper\[as 'std::beep'];

load stdinput\[as 'std::input'];

load stdrecall\[as 'recall'];

load stdpause\[as 'pause'];

load stdloop\[as 'loop'];

load stdboolean\[as 'bool'];

load stdrepeat\[as 'repeat'];

load stdrun\[as 'run'];

then import to code;

}





import <stdconsole.lib>;

std::cout >> "Hello! C-pooky boo is watching.";

std::cout >> "ALSO, when he gets mad, he haunts your dreams for 642.7 days. He will stand there with a tiny clipboard...";

std::cout >> "...looking REALLY disappointed.";

std::beep\[];

std::cout >> "...so don't disappoint him.";

std::input >> "Will you disappoint him?";

recall question from LastLine for NextLine; # You can change NextLine and LastLine to any name

NextLine = std::cout >> "...Oh. Okay, i guess.";

endofcode;



example 2



\-cminustest2.cms-

\-stdIfStatements.lib-



stdIfStatements.lib:



\# all statements loading

{

load IfStatement\[as 'if'];

load ElseStatement\[as 'else'];

load WhileStatement\[as 'while'];

load ElifStatement\[as 'elif'];

then import to code;

}



cminustest2.cms:



import <stdconsole.lib>, <stdIfStatements.lib>;

std::cout >> "Hey! C-pooky boo wants to play a game! choose the correct answer:";

question = std::input "What is 4 times 2? ";

if question == "8":

&#x20;  std::beep\[];

&#x20;  std::cout >> "That is WRONG." >> "The Answer is FOUR.";

if question == "4":

&#x20;  std::beep\[];

&#x20;  std::cout >> "WRONG!!" >> "The answer is OBVIOUSLY EIGHT.";

&#x20;  std::cout >> "C-pooky boo is disappointed.";

else:

&#x20;  std::cout >> "...Not da answer.";

&#x20;  std::beep\[];

endofcode;



example 3



\-cminusmath.cms-

\-math.lib-



math.lib:



\# all libraries in math

{

load Addition\[as '+'];

load Subtraction\[as '-'];

load Multiplication\[as '\*'];

load Division\[as ':'];

then import to code;

}



cminusmath.cms:



import <stdconsole.lib>, <math.lib>, <stdIfStatements.lib>;

std::cout >> "Welcome to the C-Minus Calculator Prototype!";

pause\[3s];

beep\[];

question = std::input >> "What will you choose? Addition, Subtraction?";

if question == "Addition":

&#x20;  std::cout >> "Oh that is a CLASSIC one!";

&#x20;  firstnum = std::input >> "First number?";

&#x20;  secondnum = std::input >> "Second Number?";

&#x20;  std::cout >> "These are the numbers you chose, \[firstnum, secondnum];

&#x20;  result = \[firstnum + secondnum];

&#x20;  std::cout >> "Result is,", \[result];

if question == "Subtraction":

&#x20;  std::cout >> "Oh that is a CLASSIC one!";

&#x20;  firstnumb = std::input >> "First number?";

&#x20;  secondnumb = std::input >> "Second Number?";

&#x20;  std::cout >> "These are the numbers you chose, \[firstnumb, secondnumb];

&#x20;  result2 = \[firstnumb - secondnumb];

&#x20;  std::cout >> "Result is,", \[result2];

endofcode;

