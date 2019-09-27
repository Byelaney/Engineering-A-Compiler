## 1. Consider a simple Web browser that takes as input a textual string in html format and displays the specified graphics on the screen. Is the display process one of compilation or interpretation?

A: It should be interpretation.

## 2. In designing a compiler, you will face many tradeoffs. What are the five qualities that you, as a user, consider most important in a compiler that you purchase? Does that list change when you are the compiler writer? What does your list tell you about a compiler that you would implement?

**What are the five qualities that you, as a user, consider most important in a compiler that you purchase?**

A: The most important thing is the compiler should not change the source codes' intention, which means after compilation, the target machine code should do no more and no less than what the source code does.
   The left thing I care about is: Compiling speed, how much cpu/memory is consumed during compiling, the size of the compiled target machine code, how helpful the error message is.

**Does that list change when you are the compiler writer?**

A: To me it won't change much.

**What does your list tell you about a compiler that you would implement?**

A: Engineering a compiler is really hard, you have to separate it into different modules. You have to make decisions and trade-off, there's no best approach.

## 3. Compilers are used in many different circumstances. What differences might you expect in compilers designed for the following applications?

a. A just-in-time compiler used to translate user interface code downloaded over a network

b. A compiler that targets the embedded processor used in a cellular telephone

c. A compiler used in an introductory programming course at a high school

d. A compiler used to build wind-tunnel simulations that run on a massively parallel processor (where all processors are identical)

e. A compiler that targets numerically intensive programs to a large number of diverse machines
