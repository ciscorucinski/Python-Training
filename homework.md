# Table of Contents
- [x] [Week 1](#week-1)
- [x] [Week 2](#week-2)
- [x] Week 3 - skip
- [ ] [Week 4](#week-4)

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

This week, you were taught that computers don't work with random numbers of bits. They read a certain number of bits each time. The oldest computers read **8 bits** at a time. Today, 64-bit computers will only read **64 bits** at a time; not 63, not 8, just 64-bits.

For this reason, whenever you write in binary, you should write *8 bits at a time* ( 0100 1101 ) divided into 2 groups of 4 bits.

**Fun Fact:** a group of 4 bits is called a **nibble**.

### Terminology

Define the following terms 

 - [ ] `bit`
 - [ ] `byte`
 
 **Also** give a few examples of the following 
 
 - [x] `digits` - these are single numeral values of a base *(i.e base-10)* that make up numbers. <br /> **Examples:** `0`, `1`, ..., `9` 
 
 - [ ] `int`
 - [ ] `float`
 - [ ] `char`
 - [ ] `String`
 
 - [ ] `overflow`
 
 ### Questions
 
Decimal numbers are in base-10 and use 10 digits (0 - 9). This is a human-centered number system mostly because humans have 10 fingers. Computers don't have fingers and use a different base.
 
 - [ ] What is the main base that computers use?
 
Humans CAN use base-10 numbers when writing software; the computer will simply convert it to base-2 for you. However, if humans have to work with bits / bytes, they don't use base-10, and they usually don't use base-2 because you have to type a lot of zeros and ones. So, humans use a different base when working with bits / bytes.

 - [ ] What is the base that humans usually use when working with bits and bytes? <br /> **Hint: it is a 'power of 2'**
 - [ ] What is the name of 'that base'? <br /> **Note: Base-10 is called 'decimal'**
 - [ ] What are the digits of 'that base'?
 - [ ] What is the prefix to tell the computer this is a number in 'that base'? <br /> **Note: Binary numbers have the prefix `0b` (zero-b) (i.e. `0b10000000`)** <br /> **This number is binary `1000 0000`, not decimal `10,000,000` (ten million)**
 
 ### Base Conversion
 Numbers have `digits` and are in specific `positions`. The number `280` has 3 digits `2`, `8`, and `0`. The `0` is in the `ones` position, `8` in the `tens` position, and `2` in the `hundreds` position.

 #### Binary to Decimal Conversion
 This conversion is easier to calculate. When going from a smaller base to a larger base all you need is addition.
 
 Do the following conversions into `decimal`
 
  - [ ] 0000 0011
  - [ ] 0000 0110
  - [ ] 0000 1100
  - [ ] 0111 0000
  - [ ] 1110 0000
 
 ##### Pattern Review 
 Look at the 1st three and the last two. What patterns do you notice?
 
 - [ ] What do you notice about their decimal values?
 - [ ] What do you notice about their binary values?
 
 #### Decimal to Binary Conversion
 
 This conversion is a little harder to calculate. When going from a bigger base to a smaller base you need to use subtraction with a running-tally.
 
 Do the following conversions into `binary`. Should be easy if you found the pattern in the previous section!!
 
- [ ] 13
- [ ] 26 **Note: this is `13 * 2`**. 
- [ ] 52 **Note: this is `13 * 4` or `13 * 2 * 2`**.
- [ ] 127
- [ ] 128
- [ ] 31415962 **Note: Go to [Google](google.com) and type in the search box `31415962 to binary`. Google will give you the answer!! Don't forget to remove the `0b` prefix**

- [ ] 31415962 **Note: Give me the number as 4 bytes (32 bits) with spaces between each nibble (i.e. 2 bytes -> 0000 0000 0000 0000)**

#### Ascii Conversion
Look at this [Ascii chart](http://sticksandstones.kstrom.com/appen.html) and do the following conversion

 - [ ] 97 to Ascii
 - [ ] 65 to Ascii
 - [ ] 0110 1111 to Ascii
 - [ ] 0100 1111 to Ascii
 
 <!--
 ##### Pattern Review
 Look at the Ascii values and the decimal or binary numbers from above...
 
 - [ ] What is the difference between `97` and `65`? **Note: do subtraction**
 - [ ] What is the difference between `0110 1111` and `0100 1111`? **Note: do subtraction (bit subtraction)**
 - [ ] What decimal value is the difference between `0110 1111` and `0100 1111`?
-->
