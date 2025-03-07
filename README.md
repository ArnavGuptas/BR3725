# BR3725
16 8 4 2 1
Explain how left-shifting a binary number by 'n' positions is equivalent to multiplying that number by 2^n. Then, design a function (in pseudocode or a language of your choice) that takes two positive integers as input and multiplies them using only bit-shifting and addition operations. You cannot use the standard multiplication operator (*). For example, to multiply 5 (101 in binary) by 3 (011 in binary), you'd use shifts and additions. Show your work on how your function would calculate this example."
Why this question is effective:
* Conceptual Understanding: It forces students to demonstrate their understanding of the relationship between bit manipulation and arithmetic operations.
* Problem-Solving: It requires them to develop an algorithm and translate it into code (or pseudocode).
* Binary Representation: It reinforces their knowledge of binary number representation.
* Efficiency: It encourages them to think about efficient ways to perform multiplication.
* Practical Application: Bit shifting is a fundamental technique used in low-level programming and hardware design.
* Decomposition: the question naturally decomposes into two parts. First, explaining the theory, and second, applying that theory to a practical problem.
```
Bitshifting left by one makes the number get doubled. Each shift left makes the number get doubled again because the place numbers also get doubled every digit(ex: 1, 2, 4, 6, 8, 16), so every left shift multiplies by two. This means that leftshifting by n means multiplying that number by 2^n.

I read the geeks for geeks page and the stack overflow exchange and the way to multiply the numbers was still confusing me. I did get how the shifts work though. I included instead a program to multiply by any power of 2, which is much more boring unfortunately.
```
