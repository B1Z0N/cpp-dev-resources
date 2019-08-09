# C++

Is a general-purpose programming language created by [Bjarne Stroustrup](http://www.stroustrup.com/). C++ was designed with a bias towards system programming and embedded. Generally it is used everywhere where needed maximal performance or minimal memory consumption. 

So this means that C++ is about performance, it is a nice part. But you should understand that we must sacrifice something. And this sacrifice is simplicity. C++ is not simple as we wish it to be, even when you have enough experience there are something that will surprise you, because there are a lot of corner cases, due to increased performance.

Other C++ feature is that it understands that "We are all adults here". And it won't stop you from shooting yourself in the leg. In other words, you are allowed to do a lot here, but you should be aware of what you are doing, it is your responsibility. 

When comparing C++ and C, former is much safer than the later. C++ enables you to do more things and it has bigger standard library. Moreover C++ [`std`](https://en.wikipedia.org/wiki/C%2B%2B_Standard_Library) contains C standard library and generally all C++ is compatible with C(which means that almost all C code is valid C++ code). C is used today because there are a huge code-base written in C, and C++'s [OOP](https://searchmicroservices.techtarget.com/definition/object-oriented-programming-OOP)(object-oriented programming) not needed everywhere, as it seems at first glance.

There are a lot of [paradigms](https://en.wikipedia.org/wiki/Programming_paradigm) of software development. The most wide known is [procedural](https://en.wikipedia.org/wiki/Procedural_programming), OOP, [functional](https://en.wikipedia.org/wiki/Functional_programming). C++ is multi-paradigm programming language, it uses [generic](https://en.wikipedia.org/wiki/Generic_programming), object-oriented, functional, procedural paradigms.

As one bight mind of cppdev once said: 

> The easiest way is to view C++ not as a single language but as a federation of related languages. Within a particular sublanguage, the rules tend to be simple, straightforward, and easy to remember.									
>
> (c) Scott Meyers

## :heavy_plus_sign:
- Huge language supports most everything
- Teaches fundamental OOP
- Compatibility with C
- Excellent compiler optimization
  
    At the time of the program being translated to machine code, 
    compiler does a big job of making it faster and shorter for you.
    
- Teaches low-level programming, but doesn't have as many pitfalls as C
- Universal, portable, best complexity/efficiency trade-off
## :heavy_minus_sign:
- Module system is not great

    C++ uses old `#include` system, inherited from C  
    
- Language is full of corner cases and undefined behaviors

    [Undefined behavior](https://en.wikipedia.org/wiki/Undefined_behavior) in a program can cause unexpected results,
    making it hard to [debug](https://en.wikipedia.org/wiki/Debugging).

- Huge language gets in the way of learning

    While learning something using C++, for example algorithms and data structures, you always need to think about
    dozens of language aspects, for unexperienced programmers it quickly becomes annoying.

- Retains nearly all bad habits of C

  See C item in this down here for detail.
  
- Tough to learn as the first language
- Memory bugs are hard to find

    It uses [manual memory management](https://en.wikipedia.org/wiki/Manual_memory_management), just like C.
  
- Painfully slow compilation

    While optimizier does a big job, it costs in time of compilation.

## C++ is used in

- Games
- Search engines
- Browsers
- Server backend
- Auto industry
- Desktop apps
- Animation
- Compilers, interpreters, virtual machines, databases
- Operating systems
- Drivers
- Embedded
- Science 
- Factories
- and many others

# Author's thoughts

I had two attempts of learning C++. First without any programming background. I used only procedural paradigm, even without a use of `std`. I didn't have a clue that i was doing something wrong. It was hard to read literature and I had a lack of motivation, since my programs was hard to [compile](https://en.wikipedia.org/wiki/Compiler)(create running programs)(yeah it was a total beginner level). So i stopped.

Second attempt was when i already knew C and Python(also Assembler a bit). Moving to C++ PL(programming language) was much easier, and that's why: C helped in understanding of how PC works, Python helped in developing application logic.

When talking about programming in general some topics are not covered at all in universities or in books about C++. And you must learn from real-world projects. Major part of this topics is about development tools. Linux environment knowledge helped a lot the second time. This topics you can find in this repository.

## C++ suits for

People that like challenges and people with enough background in programming. Also after learning of  C++ PL it is relatively easy to switch to another common programming language.

If in doubt, read [this](http://www.bestprogramminglanguagefor.me/why-learn-c-plus-plus).

# First PL?

C++ is relatively hard to learn as the first programming language. Most of experienced C++ programmers had previous experience before learning C++. So maybe it is better to learn something else before C plus plus. 

Here are suggestions of some PLs that are suitable choice as the first one:

- [Python](https://www.python.org/)

  :heavy_plus_sign:
  
  - Lots of tutorials
  - Easily readable(very similar to [pseudo-code](https://www.geeksforgeeks.org/how-to-write-a-pseudo-code/))
  - Lots of libraries
  - Easy to find a job
  
  :heavy_minus_sign:
  
  - Language fragmentation and not backward compatible
      
      Currently there are  3 versions of python, and they are used by different people, so it is harder to support 
      all them in your work. You must choose, moreover they are not backward compatible. 
      This means that not all Python 2 code is valid in Python 3 for example.
  - No true parallelism
  - Code should be intensively tested
      
      It is a dynamically-typed language, which means that it allows a lot more scenarios to be interpreted without any
      errors, so you should write a lot of tests to assure yourself in right behavior of the program. 
  - Too opinionated for a general-purpose programming language
      
      One of the mottos of Python is(not precise quote):
      > There should be only one right way to do things - the "Pythonic way"
      So while learning it is pretty easy, you are getting to "tuned" to the "Pythonic way".
  - Relatively hard to switch to another language
      
      Hard to stop thinking in the "Pythonic way".
      
  Read more about Python [here](https://www.python.org/about/gettingstarted/). **Read a lot** to be high-qualified python
  developer.

- [C](https://en.wikipedia.org/wiki/C_(programming_language))

  :heavy_plus_sign:

  - Computer knowledge
  
      Writing in C helps to understand low level computer programming.
      
  - Industry standard
  
      Every experienced programmer at some point learns C, because it has huge code-base.
      
  - Easier to learn other languages
  
      All common modern PLs was developed on the basis of C. Their's syntax developed from C. Moreover, their's
      compilers/interpreters likely to be written in C.
      
  - Simplicity
  
    C is simple with lesser rules than any other modern programming language.

  :heavy_minus_sign:

  - Language is full of corner cases and undefined behaviors
      
      [Undefined behavior](https://en.wikipedia.org/wiki/Undefined_behavior) in a program can cause unexpected results,
      making it hard to
      [debug](https://en.wikipedia.org/wiki/Debugging).
     
  - Long learning curve
  
      C will require you to learn concepts too advanced for most beginners. While the language compliments knowledge of
      computer components very well, and gives a deeper understanding, it is also quite difficult to learn, and to use 
      correctly, especially without aforementioned knowledge.
      
      This con includes subcons: 
      requires [manual memory management](https://en.wikipedia.org/wiki/Manual_memory_management), 
      [low-level PL](https://www.computerhope.com/jargon/l/lowlangu.htm).
     
  - Relatively hard to find a job
  
  - Old
  
      C programming language was developed between 1972-1973, so it can't be considered as a modern one. C lacks a large
      majority of programming concepts that modern languages make use of today. The existing functionality of C makes use of
      outdated and deprecated methodologies which can be of great annoyance to the modern day programmer.
      
      This con includes subcons like: 
      [C structs](https://en.wikipedia.org/wiki/Struct_(C_programming_language)) are very weak and outdated,
      weak limited [type safety](https://en.wikipedia.org/wiki/Type_safety),
      arrays are not [first class](https://stackoverflow.com/questions/245192/what-are-first-class-objects) objects, 
      lack of support for [first class](https://stackoverflow.com/questions/245192/what-are-first-class-objects) strings.
   
  Despite all this cons, C is the language that seems to be in use for a long time, so you should check it out. 
  Books for this PL you could find in this repository, in the list of books for C++.
 
- [Java](https://en.wikipedia.org/wiki/Java_(programming_language))

  This part is about to be completed, since author don't have experience in this PL yet, but still considers it as one of the
  best to learn for beginners. For now just read [this](https://www.slant.co/options/112/~java-review).

<!--- Uncomment this, delete what is written down here, if you want to edit this part
  :heavy_plus_sign:

  - p

  :heavy_minus_sign:

  - c
-->

- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

  This part is about to be completed, since author don't have experience in this PL yet, but still considers it as one of the
  best to learn for beginners. For now just read [this](https://www.slant.co/options/111/~javascript-review).

<!--- Uncomment this, delete what is written up here in this section, if you want to edit this part.
  :heavy_plus_sign:

  - p

  :heavy_minus_sign:

  - c
-->

- [C#](https://en.wikipedia.org/wiki/C_Sharp_(programming_language))

  This part is about to be completed, since author don't have experience in this PL yet, but still considers it as one of the
  best to learn for beginners. For now just read [this](https://www.slant.co/options/115/~c-review).
  
<!--- Uncomment this, delete what is written up here in this section, if you want to edit this part.
  :heavy_plus_sign:

  - p

  :heavy_minus_sign:

  - c
-->
  
There are a lot of other programming languages for beginners, so you should check this links:
  - [index](https://www.tiobe.com/tiobe-index/) of programming languages by popularity
  - [site](http://www.bestprogramminglanguagefor.me/) that picks you a programming language depending on your needs
  - [rating](https://www.slant.co/topics/25/~best-programming-language-to-learn-first) of the best programming languages to
  learn first depending on community opinions
  
# Okay! What's next?
If you are sure about the choice of C++, then start reading books/tutorials and writing code. Create [pet projects](https://en.wiktionary.org/wiki/pet_project). But you should be aware of the fact, that for creating pet projects in C++, you should have good imgaination. 

This repo could provide you with books/tutorials.
So continue reading, go to the [C++ resources](futurelink) section. 
