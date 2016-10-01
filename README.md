# Computer Science Book Recommend (Total 2 book) 
* 1 book on [Data structure and Algorithem]
* 1 book on [Hardware]

I read all of them cover to cover, and think these book are brilliant.   
very easy to understand, very good for self-taught people. very friendly for beginner.  
not advance topic that need a lot prerequisites.  
the order doesn't matter here, you shouldn't read these book one by one as how I list them.  
Here is my book list and my review, hope it help you. enjoy.  

<br/>
### 1. "Grokking Algorithms An illustrated guide for programmers and other curious people"
About 200 page  
[Data structure and Algorithm]    
https://www.amazon.com/Grokking-Algorithms-illustrated-programmers-curious/dp/1617292230  

### My Review
Very easy to understand, a lot of cartoon drawing , example and analogy.  
Best algorithm book I have read so far, other book just tedious, too much detail about math and just dull.  
This book use Python. I finally understand how BFS work.  
__If you are beginner on Data structure and Algorithm, this definitely should be your first book (instead of CLRS)__

### My Summary 
this is not copy&paste book chapter name, just my summary on the order of topic it cover.  
It may seem complex if you haven't read the book, go read it.  the topic below is not hard as you may think.  

1. Binary search: sort first
2. What is big O
3. Travel man problem
4. Array
1. List
1. Selection sort
1. Recursive
1. Quick sort
1. Hash
1. BFS
1. Dijkstra
1. Greedy
1. Dynamic programming: involves grid
1. k-neaest
1. last chapter: brief intro 10 algorithem: tree, invert index, map reduce, bloom filter and hyper log log, SHA, RSA


<br/>
### 2. "But How Do It Know? - The Basic Principles of Computers for Everyone"
About 200 page   
[Hardware]  
https://www.amazon.com/But-How-Know-Principles-Computers/dp/0615303765   

### My Review
Great book about how computer work, how "logic gate" combine together to perform certain behavior we want it to accomplish,  
How add two binary number, how computer "remember" a bit,    
How combine these thing that can "remember" bit into Memory.  etc,   
this book is more Computer Science than Electrical engineering, 
by that, I mean it's not talk about how these hardware are actually made in realy word, 
what process and machine and cost to make a transister, the history of electricity, who is faraday, light bulb analogy, history of telegram, etc.
It focus on these essential concept, that is how logic gate combine together to work.
and how these part combine again to perform even complex work.  
__Fantastic Book__


#### By the way
This book didn't contain homework or programing exercise, just concept.  


#### Topic (as order in book)
you should read this after you have read the book.  

1. Nand gate
1. Not gate: how to use one "nand gate" to make one "not gate"
1. And gate: how "nand gate" + "not gate" = "and gate"
1. Remember a bit: by using 4 nand gate (let's call this little chip "M")
1. Combine 8 "M" to remeber 8 bit (let's call this "B")
1. 8 "And gate" can make a Enabler: turn on Enabler, bit from input can go to output, turn off enabler, bit can not go though
  (let's call this "E")
1. B+E = Registor, a Registor just a storage place, it storage bit, that's it, it can remember 8 bit
1. what is "bus": just line to connect all different part, bit can travel though bus and get to other place, 
  we have 8 line here to make a bus. (transfer 8 bit at one time)
1. And gate: this time with 3 input, instead of 2 input
1. Decoder: 2x4 
1. one 8-bit Regisiter + one 2x4 Decoder = 256 byte memory
1. MAR = memory address register. this one regisiter + 256 register above = 257 register
1. FIRST TIME see a CPU: two missing part mark with "?"
1. Or gate: 2 not gate + 1 nand gate = 1 or gate
1. XOR gate, and 3 way to change one byte, and 5 way to change two byte, total 7 way
1. Shifter: left shifter SHL. right shifter SHR.
1. Noter: 8 not gate = 1 noter, just connect them together,
1. Ander
1. Orer
1. Xorer:  same, same, same. instead 1 bit, these "-er" is 8 bit. nothing fancy here.
1. Half Adder: 2 input: a, b. 2 output: sum, carry. 1 Xor + 1 Nand = 1 Half Adder
1. Full Adder: 3 input: a, b, carry. 
1. Comparter: equal? 'a' larger?
1. Zero: all these 8 bit are zero? 1 Orer + 1 not gate = 1 Zero
1. how to combine XOR, OR, AND, NOT, SHL, SHR, ADD, 7 gate to make a ALU: hint: use a 3x8 decoder with 7 enabler.
1. a little devise call "Bus 1", this little chip have 2 input, 1 output. one of input also call "bus 1"
  when "bus 1" = 0, input go to output, nothing changed,
  when "bus 1" = 1, ignore input, just output binary 1 (which is 0000 0001)
1. when we first introduct CPU, we have two "?" mark, now we know one is ALU, one is "Bus 1"
1. Clock: all compoent work at same pace.
1. Stepper
1. wire Close + Stepper + couple thing to do a ADD operation, add two binary number 
1. First Great Invention: Instruction Register, IR. Instruction Address Register, IAR.
1. instruction code: ALU code start with a 1 (1xxx xxxx)
1. command for ALU start with 1, not for ALU start with 0
1. Load and Store
1. Data instruction: load stuff from RAM to one register
1. Second Great Invention: JUMP instruction
1. Third Great Invention: JUMP IF, FLAG
1. A Few More words on Arithmetic: Subtraction and Multiplication
1. The Outside Word: IO
1. Keyboard
1. Screen
1. Last chapter: "Philoshphy"

#### The Last Sentence of the Book 
> Now that we know what is in a computer, and how it works, I think it is fairly obvious that the   
> answer to the question "But How do it Know?"
> is simply "It donesn't know anything!"

#### Summary
1. this book build a 8 bit computer
1. the CPU graph would get more and more complex, not just in that chapter with 2 question mark and just done.

#### Topic this book didn't cover 
this book only cover essential topic to help you understand how computer work,   
So I am not blame author here, I just list what topic this book didn't says.    

* how computer represent negative number like -3
* how computer represent dicimal number like 6.78


<br/><br/>
<br/>
## eh
English is not my native language, so if there are any grammar error or spell error or just any kind of wrong use.  
Please point out help my improve :D

## About me
Ruby on Rails developer living in GuangZhou China.  
self-taught programmer, 2 year experience  
