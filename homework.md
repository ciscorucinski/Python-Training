# Table of Contents
- [x] [Week 1](#week-1)
- [x] [Week 2](#week-2)
- [x] Week 3 - skip
- [x] [Week 4](#week-4)
- [x] [Week 5](#week-5)
- [x] Skip weeks 6 - 7, and week 8
- [x] [Week 9](#week-9)
- [x] [Week 10](#week-10)
- [x] [Week 11](#week-11)
- [ ] [Week 12](#week-12)

# Homework

## Week 1

<details>
 <summary>Click to expand...</summary>

### Summarize Vocabular Words

- [x] In your own words, try to explain the following vocabulary words...

  - [x] Decomposition
  - [x] Pattern Recognition
  - [ ] Abstraction *(Skip for week 1)*
  - [x] Algorithms
  - [x] Debugging
 
 **Note:** 
 - [x] Also, explain why these ideas are important in terms of computing / programming.
 
 </details>
 
 ## Week 2
 
 <details>
 <summary>Click to expand...</summary>
  
 ### Code Combat Online Python Coding Game
 
 This is an online game where you have to use real Python code to progress farther.
 
 - [x] Visit [Code Combat](www.codecombat.com/play)
   - [x] Play the first area (Kithgard Dungeon) and pass the first 12 out of 39 quests.
   
 ### Review the 'Crash Course: Computer Science' videos 
 
 - [x] [#1 (Early Computing)](https://www.youtube.com/watch?v=O5nskjZ_GoI), 
 - [x] [#2 (Electronic Computing)](https://www.youtube.com/watch?v=LN0ucKNX0hc), 
 - [x] [#3 (Boolean Logic & Logic Gates)](https://www.youtube.com/watch?v=gI-qXk7XojA)
   
 ### Answer question 
 
 Based on the above 'Crash Course: Computer Science' videos , answer the following question
    
  - [x] Why is binary (2-states) better in computers compared to 3-states or 5-states? <br />**2 accetable answers**
  - [x] Why is 5-states better than 2-states? <br /> **Opinion question**
  - [x] What number of states do you think the English letters are in?  <br /> **Opinion question. Don't think too much**
    
 In *Math* the **values** are `numbers` and **operations** are `+`, `-`, `×`, `÷`, etc. So...
  - [x] For *Boolean Algebra*, what are the **values** and **operations**?
    
 Give the **Logic Tables** for the following operators. Use the tables below for help
  - [x] `And` operators
  - [x] `Or` operators
  - [x] `Not` operators
    
  Here is the template for the NOT operator
  
  | Input | Output |
  | :---: | :----: |
  | false |        |
  | true  |        |
  
  Here is the combined template for the AND and OR operators
  
  | Input 1 | Input 2 | Output <br />And | Output <br />Or |
  | :-----: | :-----: | :--------------: | :-------------: |
  | false   | false   |                  |                 |  
  | false   | true    |                  |                 | 
  | true    | false   |                  |                 | 
  | true    | true    |                  |                 | 
  
  Moving onto Transistors...
  - [x] What are transistors?
  - [x] What are Logic gates? <br /> **2 possible answers**
  - [x] What are the 3 Logic gates talked about in the video?

</details>

## Week 4

<details>
<summary>Click to expand...</summary>
 
This week, you were taught that computers don't work with random numbers of bits. They read a certain number of bits each time. The oldest computers read **8 bits** at a time. Today, 64-bit computers will only read **64 bits** at a time; not 63, not 8, just 64-bits.

For this reason, whenever you write in binary, you should write *8 bits at a time* ( 0100 1101 ) divided into 2 groups of 4 bits.

**Fun Fact:** a group of 4 bits is called a **nibble**.

### Terminology

Define the following terms 

 - [x] `bit`
 - [x] `byte`
 
 **Also** give a few examples of the following 
 
 - [x] `digits` - these are single numeral values of a base *(i.e base-10)* that make up numbers. <br /> **Examples:** `0`, `1`, ..., `9` 
 
 - [x] `int`
 - [x] `float`
 - [x] `char`
 - [x] `String`
 
 - [x] `overflow`
 
 ### Questions
 
Decimal numbers are in base-10 and use 10 digits (0 - 9). This is a human-centered number system mostly because humans have 10 fingers. Computers don't have fingers and use a different base.
 
 - [x] What is the main base that computers use?
 
Humans CAN use base-10 numbers when writing software; the computer will simply convert it to base-2 for you. However, if humans have to work with bits / bytes, they don't use base-10, and they usually don't use base-2 because you have to type a lot of zeros and ones. So, humans use a different base when working with bits / bytes.

 - [x] What is the base that humans usually use when working with bits and bytes? <br /> **Hint: it is a 'power of 2'**
 - [x] What is the name of 'that base'? <br /> **Note: Base-10 is called 'decimal'**
 - [x] What are the digits of 'that base'?
 - [x] What is the prefix to tell the computer this is a number in 'that base'? <br /> **Note: Binary numbers have the prefix `0b` (zero-b) (i.e. `0b10000000`)** <br /> **This number is binary `1000 0000`, not decimal `10,000,000` (ten million)**
 
 ### Base Conversion
 Numbers have `digits` and are in specific `positions`. The number `280` has 3 digits `2`, `8`, and `0`. The `0` is in the `ones` position, `8` in the `tens` position, and `2` in the `hundreds` position.

 #### Binary to Decimal Conversion
 This conversion is easier to calculate. When going from a smaller base to a larger base all you need is addition.
 
 Do the following conversions into `decimal`
 
  - [x] 0000 0011
  - [x] 0000 0110
  - [x] 0000 1100
  - [x] 0111 0000
  - [x] 1110 0000
 
 ##### Pattern Review 
 Look at the 1st three and the last two. What patterns do you notice?
 
 - [x] What do you notice about their decimal values?
 - [x] What do you notice about their binary values?
 
 #### Decimal to Binary Conversion
 
 This conversion is a little harder to calculate. When going from a bigger base to a smaller base you need to use subtraction with a running-tally.
 
 Do the following conversions into `binary`. Should be easy if you found the pattern in the previous section!!
 
- [x] 13
- [x] 26 **Note: this is `13 * 2`**. 
- [x] 52 **Note: this is `13 * 4` or `13 * 2 * 2`**.
- [x] 127
- [x] 128
- [x] 31415962 **Note: Go to [Google](google.com) and type in the search box `31415962 to binary`. Google will give you the answer!! Don't forget to remove the `0b` prefix**

- [x] 31415962 **Note: Give me the number as 4 bytes (32 bits) with spaces between each nibble (i.e. 2 bytes -> 0000 0000 0000 0000)**

#### Ascii Conversion
Look at this [Ascii chart](http://sticksandstones.kstrom.com/appen.html) and do the following conversion

 - [x] 97 to Ascii
 - [x] 65 to Ascii
 - [x] 0110 1111 to Ascii
 - [x] 0100 1111 to Ascii
 
</details>

## Week 5

<details>
<summary>Click to expand...</summary>

Last Friday, we downloaded and installed 2 items

 - **JetBrains Toolbox App:** JetBrain is the name of a company that makes software for developers. JetBrains Toolbox is an app that is like a software manager for all JetBrain's products. It lets you launch their IDE's and your software projects in one spot. It also lets you easily update all the IDE's in one spot.
 
 - **PyCharm:** an IDE that has all the tools required for a person or team to write, test, and run many different types of Python programs.
 
We still need to download one more piece of software so you can actually write Python programs.

 - [ ] Download [Python 3.6 SDK](https://www.python.org/downloads/). Make sure you select Python 3.6+ (NOT 2.7+). 
 - [ ] Install Python 3.6. Use all default locations for installation!

### Quick review of last week's homework

- [ ] Base-10 uses the numerals `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, and `9`. What are the numerals of `Hexidecimal`?
- [ ] Binary numbers use the prefix `0b`. What is the prefix of `Hexidecimal` numbers?

- [ ] Give me 3 examples of the following `int`, `float`, `char`, `string`, `byte` <br /> **Example of integer is `1`**

#### Base Conversions Review

Computers only read bytes. A 32-bit computer will read 4 bytes at a time (8 bits * 4 = 32 bits). An 8-bit computer will only read 1 byte at a time. 

- [ ] Step 1: Give the decimal number `195` as a 1-byte binary number.
- [ ] Step 2: Convert the 1 byte number above to 2 bytes.
- [ ] Step 3: Convert the 1 byte number above to 3 bytes.

-----------

- [ ] Step 1: Give the number `31415962` as a 4-byte number.<br />**Note: Use Microsoft Calculator or Google Search to convert this number.**
- [ ] Step 2: Convert the 4 byte number `314159623` to 1 byte. 
- [ ] Step 3: Convert the 1 byte binary number above to decimal (`314159623` as 1 bytes to decimal) <br />**Note: the number will change and will become a different and smaller number. It will NOT have the decimal value of `314159623` anymore.**

Compare the above 1st three answers with the last three answers.
- [ ] What COULD happen to the decimal value if you convert a 4 byte number into a 3 byte (or 2 byte or 1 byte) number? Is that good or bad?
- [ ] What COULD happen to the decimal value if you convert a 1 byte number into a 2 byte (or 3 byte or 4 byte) number? Is that good or bad?

### Quick review of last week's videos

This is a 1-question review of [Crash Course Computer Science #6: Registers & RAM](https://www.youtube.com/watch?v=fpnE6UAfbtU), [Crash Course Computer Science #7: CPU & Clock Speed](https://www.youtube.com/watch?v=FZGugFqdr60), and [Crash Course Computer Science #8: Instructions & Programs](https://www.youtube.com/watch?v=zltgXvg6r3k)

`Registers` are small, indiviudal memory units that store just 1 byte of information (4 bytes for 32-bit machines). These are `Register A`, `Register B`, `Register C`, and `Register D` in the picture below. The "control unit" of the CPU only see these 4 registers. The control unit cannot see RAM.

`RAM` is called "Random Access Memory". It is a huge array of memory that stores programs and data. They allow for fast and easy access of any memory address byte value. Computers, nowadays, have 8GB or more of RAM memory.

 `Machine code` is what computers "speak". In order for a computer to do something, machine code needs to be put in a computers RAM. You saw this in an earlier video. Check out the `RAM` in the picture below...
 
 ![screenshot_2017-11-24-20-07-58](https://user-images.githubusercontent.com/8707125/33544552-92df19f2-d91e-11e7-837a-32208696e0df.png)
 
 `Assembly code` is a version of machine code that uses some English words with memory locations ("Load_A 14" or "Add B A"). Early programmers always programmed using Assembly code. You also saw this in an earlier video. Check out the `RAM` in the picture below...
 
 ![screenshot_2017-12-04-17-33-20](https://user-images.githubusercontent.com/8707125/33544542-8516a646-d91e-11e7-8fe2-821cd591a464.png)
 
 **Note:** Assembly code never gets stored in RAM! Only Machine Code (zeros and ones) gets stored in RAM. This picture is just an abstraction to help see what happens without converting all the binary numbers into "opcodes" and "memory addresses".
 
 - [ ] What is the difference between the `RAM` on both pictures? Both pictures have the same code; one is machine code and the other is Assembly code, but what is different between the two.
 
 ### Programming Languages
 
 Here is a summary of what programming languages are and why they were created.
 
 - [ ] Watch [Crash Course Computer Science #11: Programming Languages](https://www.youtube.com/watch?v=RU1u-js7db8)
 
 - [ ] Pay attention to keywords such as `Assembler`, and `Compiler`. Listen to what they are and the difference between them!
 - [ ] At 8:58, there is a snippet of text displayed in the video. Write the snippet down (19 words).
 
 Late in the video (9:25 and later), they list a lot of programming languages by decade. 
  - [ ] What are programming langauges that were created in the 1960's
  - [ ] ...1970's
  - [ ] ...1980's
  - [ ] ...1990's
  - [ ] ...2000's and 2010's
 
 #### Review of Video #11
 As you can see from the above pictures, there is a `one-to-one` relationship between `Machine code` and  `Assembly code`. That means that **one line** of Assembly code gives **one line** of Machine code. With Assembly code, you tell the computer to work with memory (`LOAD_A 14` - "Load byte value at RAM address 14 into register A", or `Store_A 13` - "Store byte value in register A into RAM address 13"). 
 
 This is what a `low-level language` is. Low-level programming languages have you working with memory at a very detailed level. They take Assembly code and use an `Assembler` to convert it into machine code.
 
 `High-level language`s are human readable and kind of read like English sentences. They hide the detail of the memory from the programmer by using `variables` and `control flow`. One line of a high-level programming language will result in many lines of machine code. This `one-to-many` lines of code is done by a `compiler`.
 
The following picture will show the difference between low-level and high-level programming languages. Keep in mind that Assembly code does NOT get stored in RAM. Only Machine code (zeros and ones) get stored in RAM!

![screenshot_2017-12-04-18-51-21](https://user-images.githubusercontent.com/8707125/33547112-4b5d8b1a-d926-11e7-8404-a1071ebb483b.png)
 
 Notice that Assembly Code uses 7 lines of code (Line 0, 1, 2, 3, 4, 14, and 15), but Python code only uses 3 lines of code. They are exactly the same code, but use different languages!!
 
 ### Statements and Functions
 
 Here is a summary of basic programming ideas that you must understand. These are the most basic of ideas. You will use all of these ideas over and over again! Go over this video 2 or 3 time if you must.
 
 **Note:** Python has a different "grammar" (syntax) then what is shown in the video below. 
 - [ ] Watch [Crash Course Computer Science #12: Statement & Functions](https://www.youtube.com/watch?v=l26oaHV7D40)
 
 Define the following
 - [ ] `Assignment Statement` + example code
 - [ ] `Variable` + What do you think a variable represents? Think of the last few videos!
 - [ ] `Initialize` + What do you initialize?
 - [ ] `Control Flow Statements`
 - [ ] `Conditional` + example code
 - [ ] `Function` + example code + `Return Statement` (**Note:** around 3/4 way through video)
 - [ ] `Libraries` (**Note:** near end of video)
 
 #### Programming Statements
 What is the general format of the following Conditional / Control-Flow Statements. Also give example usage.
 - [ ] `If Statement` (3:23 - general format. 3:28 - example usage)
 - [ ] `If-Else Statement` (3:44 - example usage only)
 
 **Note:** With all `If Statements`, there are no loops. It decides if it should 
 
 - [ ] `While Statement` (4:20 - general format. 4:44 - example usage)
 - [ ] `For Loop` (5:53 - general format. 6:52 - example usage) 
 
 **Note:** With all `While Statement`s and `For Loop`s, your code could loop many times!!
 
 </details>

## Week 6

Vacation

## Week 7

Vacation

## Week 8

Grok Learning
 
## Week 9

<details>
<summary>Click to expand...</summary>

### Types

So far you know about a few types

 1. **Integers** which are also called **ints** for short. They are *numbers* that contain the numerals `0 - 9` only.
 2. **Floating-point Numbers** which are called **floats**. They are *numbers* that contain the numerals `0 - 9` AND one decimal-point `.`
 3. **Strings** which are text. They are lists of *characters* that can contain `letters`, `numbers`, `spaces`, `symbols`, and text from other languages. 
 
 As a side note Strings NEED to be inside of...
 
  - `'...'` **single quotes** 
  - `"..."` **double quotes** 
  - `'''...'''` **triple single quotes** 
  - `"""..."""` **triple double quotes** 
  
 ### Operations 
 
 All the basic operators in Python work with numbers (`int`s and `float`s).
 
 Here are a list of the Operators. 
 
 - [ ] For `Python Result`, I want you to use `GrokLearning.com` or `Snakify.org` to figure out the answer! For Addition, type into Python `print(22 + 7)` and write the answer in the empty space. For Exponent, type in `print(22 ** 7)` and write down the answer!  
 
 | Operation        | Python  | Python Result | Math   | 
 | ---------------- | :-----: | :-----------: | :----: |
 | Addition         | 22 + 7  |             | 22 + 7
 | Subtraction      | 22 - 7  |             | 22 - 7
 | Multiplication   | 22 * 7  |            | ![22 multipled by 7](https://latex.codecogs.com/gif.latex?22&space;\times&space;7)
 | Division         | 22 / 7  |  | ![22 divided by 7](https://latex.codecogs.com/gif.latex?22&space;\div&space;7)
 | Integer Division | 22 // 7 |              | ![Floor of 22 divided by 7](https://latex.codecogs.com/gif.latex?\left&space;\lfloor&space;22&space;\div&space;7&space;\right&space;\rfloor)
 | Modulo           | 22 % 7  |              | 22 mod 7
 | Exponent         | 22 ** 7 |     | ![22 to the power of 7](https://latex.codecogs.com/gif.latex?22^{7})
 
 The above all work on numbers, but two of them also work with `strings`!
 
 - [ ] Which of the above operators work with `Strings`? Give an example of each. Also, what is the output out each?
 
 ### Functions
 
 You have learned from GrokLearning of 4 built-in Python functions plus one additional function from the teacher
 
 1. `print()`
 2. `input()`
 3. `len()`
 4. `int()`
 5. `float()`
 
 - [ ] What do the above 5 functions do? Try to describe as much as possible. 
 - [ ] What are the input `types` of each function? What goes between the parentheses `()`. Do `int`s work? `float`s? `String`s? All `String`s or special ones? What if there are no inputs?
 - [ ] What is the one output `type` of each function?

</details>

## Week 10

<details >
<summary>Click to expand...</summary>

### Snakify.org

#### Theory

In class, we went over the `Theory` section that went over how to input and output data using the `input()` and `print()` functions. We also went over what happens when we add `integers` and `strings`. We found out that...

 - Adding two integers does mathematical addition. `42 + 8` >> `50`
 - Adding two strings does `string concatenation`. It combines two string together. `"Hello " + "world!"` >> `"Hello world!"`

In the `Theory` section we also learned about `Casting`. Casting is changing one type of data to another type. Another word for casting is converting.

We can cast `integers` to `floats`, `floats` to `integers`. We can also cast certain `strings` to `integers` or `floats`. We do these casts by the `int()` and `float()` functions.

#### Steps (Homework)

For homework, I want you to do all the remaining steps. Please **read and understand** the instructions and notes!!

- [ ] Go to [Snakify.org >> Lesson 1. Input, print and numbers >> Steps](https://snakify.org/lessons/print_input_numbers/steps/1/).

You should have done Steps 1 - 3.

- [ ] For Sunday or Monday homework, I want you to finish `Step 4`. Do more if you want.
- [ ] For Wednesday homework, I want you to finish `Step 5`. Do more if you want.
- [ ] For Thrusday or Friday homework, I want you to finish `Step 6` - `Step 24`

#### Notes

What is **most important** for homework is that you **read and understand** the text of each problem. Just doing the coding is not enough. Also, **DON'T COPY AND PASTE** the code. You must type the code yourself and understand why you use that code or function.

In the picture below, the area I highlighted in green is **very important** to read and understand. Please make sure you understand it before you go to the next section!

![snakify](https://user-images.githubusercontent.com/8707125/34459747-96230870-ee3c-11e7-828a-290946e19035.PNG)

</details>

## Week 11

<details>
<summary>Click to expand...</summary>

### Review

What is the Python mathematically operators for the following items. What do you have to type into Python to do the following?

 - [ ] addition
 - [ ] subtraction
 - [ ] multiplication
 - [ ] division
 - [ ] exponents
 - [ ] integer division
 - [ ] modulus (remainder)

### Builtin Functions

You have learned about several built-in functions that come with Python. These include `print()`, `input()`, `len()`, `int()`, `float()`, and `str()`. There are a lot more that you will learn over time.

### Module Functions

When there isn't a function that you **need**, there **might** be some code that someone else wrote that you can use. 

This code that someone else wrote that you can use in your program is in a `module`. To add this code to your program, you use the `import x` statement.

#### Math Module

The import statement that you learned this past week is the `import math` statement. This is a bunch of functions and variables that you can use that deal with math.

You have access to Math constants such as the `math.PI` variable or to Math functions such as `math.sqrt()` function.

When ever you need to access these variables or functions, then you need to `import math`.

##### Review

- [ ] Filling in the missing **Math Notation** and **usage** columns and give 3 examples of use

| Function   | Math Notation | Usage | Description |
| ---------- | :-----------: | ----- | ----------- |
| `math.floor(x)` | ![Floor of x](https://latex.codecogs.com/gif.latex?\left&space;\lfloor&space;x&space;\right&space;\rfloor) |  `math.floor(4.01) == 4`</br> `math.floor(4.99) == 4`</br> `math.floor(4.01 + 4.99) == 9` | Return the floor of x. </br>Similar to always round down. |
| `math.ceil(x)`  | ![Ceiling of x](https://latex.codecogs.com/gif.latex?\left&space;\lceil&space;x&space;\right&space;\rceil) | `math.ceil(4.01) == 5`</br> `math.ceil(4.99) == 5`</br> `math.ceil(4.01 + 4.99) == 9` | Return the ceiling of x. </br>Similar to always round up. |
| `math.sqrt(x)`  |    |    | Return the square root of x. |
| `math.log(x)`   |    |    | Return the natural logarithm of x (base e). </br>The mathematical constant e = 2.71828... |
| `math.log(x, base)`| |    | Return the logarithm of x to the given base. |
| `math.sin(x)`   |    |    | Return the sine of x radians. |
| `math.asin(x)`  |    |    | Return the arcsine of x, in radians. </br>**Arcsine is the inverse of sine** |

</details>

## Week 12

<details open>
<summary>Click to expand...</summary>

### What We Did Last Class

<details>
<summary> <b>General Review ... (click to expand for a review) </b> </summary>

This week you learned how to program in the **PyCharm** IDE. Using this IDE allows you to save your programs and code to your computer. It also allows you to do many more things. Remember the <kbd>Alt</kbd> + <kbd>Enter</kbd> shortcut to fix issues? That is one of the many features of an IDE like PyCharm.

#### Code
Anyways, we started to build an actual program that **emulated** hardware boolean logic gates such as the `And Gate`, `Or Gate`, and `Not Gate`. Those were **basic** gates. We also created some **composite** gates that *used* those basic gates such as the `Xor Gate`, `Nand Gate`, and `Nor Gate`.

Next, we started to build some parts of the `Arithmetic and Logic Unit` (called the **ALU**). We built a simple `Half Adder` which only added 2 bits together.

#### Testing
I also showed you how to **test** your code. We did that with the `assert` keyword along with the **equals operator** (`==`). 

For testing, there are two ways to tests. You *could*...

 - Write your tests first, then your code. **(recommended)**
 - Write your code first, then your tests.

</details>

### What You Will Do (Homework)

You will write the code for a **Full Adder**. The **Full Adder** is used to add 3 bits together (bit 1 + bit 2 + carry bit). It will also output 2 bits (carry bit and sum bit)

So as a quick recap. The **Full Adder** should have the following...
 - Function Name: `full_adder`
 - Inputs: 3 (Carry, Bit A, Bit B)
 - Outputs: 2 (Carry, Sum)
 
 ![Full Adder](https://user-images.githubusercontent.com/8707125/35480013-60b36d66-0448-11e8-8787-115f339d6053.png)
 
#### Step 1
 - [ ] Write out the **definition** of the **Full Adder** function.
 
 
<details>
<summary> <b>Note 1: ... </b> </summary>

Here is what a function definition looks like... 
 
     def function_name(input1, input2):
         pass
         
</details>
<details>
<summary> <b>Note 2: ... </b> </summary>

The `def` keyword for **definition** You will **define a function**. Also, we will use the `pass` keyword to stop PyCharm from showing errors and warnings.
     
</details>

#### Step 2
 - [ ] Write your `assert` tests for the `Full Adder` in the test module. 
 - [ ] `import` the `full_adder` function into the test module
 
| Test # || Input </br>Carry | Input </br>A | Input </br>B || Output </br>Carry | Output </br>Sum |
| ------ | --- | --- | --- | --- | --- | --- | --- |
| Test 1 || 0 | 0 | 0 || 0 | 0 |
| Test 2 || 0 | 0 | 1 || 0 | 1 |
| Test 3 || 0 | 1 | 0 || 0 | 1 |
| Test 4 || 0 | 1 | 1 || 1 | 0 |
| Test 5 || 1 | 0 | 0 || 0 | 1 |
| Test 6 || 1 | 0 | 1 || 1 | 0 |
| Test 7 || 1 | 1 | 0 || 1 | 0 |
| Test 8 || 1 | 1 | 1 || 1 | 1 |

#### Step 3
 - [ ] Write your **Full Adder** code within the `Adder` module. *(Where the `Half Adder` is located)*
 
 Here is a diagram for the **Full Adder**
![Full Adder Diagram](https://user-images.githubusercontent.com/8707125/35480016-7474db50-0448-11e8-982f-0b55f6159008.png)

<details>
<summary> <b>Note 1: ... </b> </summary>

Using 5 variables might be useful here...

    half_adder1_result = ...    # Use the half_adder() function
    half_adder2_result = ...
    or_result = ...
    carry = ...
    sum = ...
    
    return carry, sum
    
</details>
<details>
<summary> <b>Note 2: ...</b> </summary>

 How do you get the **Carry Bit** or the **Sum bit** from a **half_adder()** result?
 
 If you look at the `half_adder()` function. You `return` the **carry bit** 1st, and the **sum bit** 2nd. Therefore...
  
     half_adder_result = half_adder(a, b)
     carry = half_adder_result[0]           # [0] means get 1st item
     sum = half_adder_result[1]             # [1] means get 2nd item
                                            # [2] menas 3rd item, but there is not 3rd item, so you will get an error
                                            # ...
                                            # [99] means 100th item 
                                            # ...
                                            # [n] means (n + 1) item 

</details>

#### Step 4
- [ ] Run your tests to make sure the code works. 
- [ ] Fix any issues that you find.

</details>


<!-- ------------------------------------------------- -->

<!--
## Week x

<details open>
<summary>Click to expand...</summary>

Content

</details>
-->
