# TernaryAdder

There are 10 kinds of people: those who understand ternary, those who don't, and those who are uncertain.

Q & A for those wishing to learn about the scope of this project:

Q: Why are you doing this?<br>
A: The reason for this experiment is to determine whether or not a ternary adder can surpass a binary adder in terms of speed.

Q: How are you going to test this?<br>
A: Emulating both a binary and ternary adder, and testing the speed of each under different constraints using a set of pseudorandomly generated decimal integers. The emulator will be responsible for generating and converting the numbers.

Q: Different Constraints? Elaborate.<br>
A: The constraints will be a constant and a variable. The constant is the amount of instructions generated by the emulator, and the variable is the digit count of each number.

Q: What about lookahead or other control functions?<br>
A: Lookahead in the emulator is seperate from the class of the ternary adder itself. It is a data structure that functions for both the binary and ternary adders. As for other control circuits: the scope of this project does not extend into that area.

Q: What language and source control are you using to build the emulator?<br>
A: C++ with Visual Studio.

Q: What's with using NOR and NAND gates instead of just OR and AND?<br>
A: In binary, the NOR and NAND operations have a unique property that allows them to form any other logic gate (including each other) using a certain combination of themselves. While that property may not exist in my ternary model, the versatility of NAND and NOR proved useful while constructing the adder. More information on the universal nature of these gates can be found in the "sources" readme.
