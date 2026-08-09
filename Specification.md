| C- Language Specification

|----------------------------------------------

Heya! It's C-pooky boo again! 👻

I'm writing the FULL Language Specification of C-!



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

"save wifi as bool true;" -> makes the Boolean for 'wifi' as **true**.

"save ethernet as bool false;" -> makes the Boolean for 'ethernet' as **false**.

"label SamsungWashingMachine \[

&#x20;std::beep\[];

&#x20;std::cout >> "Laundry is complete!"

&#x20;]" -> labels this specific block "SamsungWashingMachine", then beeps and prints "Laundry Is Complete!". Labels are needed for the 'repeat' option.

"repeat \[label: SamsungWashingMachine] 8 times;" -> repeats SamsungWashingMachine for 8 times.

"run \[label: SamsungWashingMachine];" -> Runs SamsungWashingMachine.

"filesystem create file aeiou.txt\[content:"aeiou i love this so much"];" -> makes a file named aeiou and adds in its content "aeiou i love this so much".

"filesystem delete file uoiea.txt\[];" -> **deletes** uoiea.txt, **BUT** places it in the recycle bin.

"filesystem chdir "C:\\Windows\\System32"\[];" -> changes directory to C:\\Windows\\System32.

"filesystem purge file auauauahi.txt\[];" -> deletes auauauahi.txt **permanently**. doesn't move it to the recycle bin. Will ask for permission by default unless force mode is enabled and User Permissions are set.

The question for permission is like this:
"Line NA, Col NA: Needs Permission \[ERR:410]

&#x20;C-pooky boo has found some destructive content in your code. Would you like to run it?
Code: 'filesystem purge file homework.folder;'.

&#x20;\[Yes]/\[No]  ?"

"filesystem rename file ntldr.exe\[to: ntloader.exe];" -> renames ntldr.exe to ntloader.exe.

"filesystem replace file \[

&#x20;fileToBeReplaced "C= (Demo).folder",

&#x20;fileReplacement "C- (Demo).folder" {keepFolderName$};" -> replaces C= (Demo) folder with C- (Demo) folder. Keeps C- (Demo) folder's name.

"network connect \[

&#x20;network: "PrimeTel12",

&#x20;password: "RandomPasswordIdk",

&#x20;networkSecurity: WPA2;

&#x20;];" -> Connects to PrimeTel12. You might need Administrator permissions or it may fail.

"network disconnect \[network: PrimeTel12];" -> disconnects from PrimeTel12. Also needs Admin permissions.

"network searchForNetworks\[];" -> Prints available networks.

"network setToAirplaneMode\[];" -> Sets to Airplane Mode. Also needs Admin permissions.

