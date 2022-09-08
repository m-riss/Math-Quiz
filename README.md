# Math-Quiz
Just a math quiz I've been writing over the last several months.

To compile this, follow these steps:

1. Download the source code as a zip file (you can also clone this repo if you want to contribute)

2. If you downloaded as a zip, unpack it in whatever directory your downloads go to for your OS.

3. Open your terminal of choice and change the working directory to where you unpacked the source code (Command is: "cd [path\of\directory]" where "[path\to\directory]" is where you would put your path).

4. With the working directory now set to where you have the source code, and assuming you have GCC installed correctly, run "g++ -s Math_Quiz.cpp" to compile the code into an executable for your OS.

5. (OPTIONAL): If you want to name the executable something other than the default, append " -oYourFileNameHere" (YourFileNameHere being whatever name you want to give the executable) to the end of the command previously listed. (So that would be: "g++ -s Math_Quiz.cpp -oYourFileNameHere")

6. (OPTIONAL): If you want to apply optimizations to have the code run faster, append one of the following: -O1, -O2, -O3, -Os, or -Ofast, to the end of the new command. The command with whatever optimization level you want is: "g++ -s Math_Quiz.cpp -oYourFileNameHere -O1".
