---
layout: post
title: History of Quantum Computers?
---

Even though it is not necessary to go over the classical computers to understand how quantum computers work, but it is quite interesting how computers evolved and how there are so many misconception around quantum computers, I find it necessary to go over how classical computers became what they are today and how they have little to do with quantum computers. 

## Brief Discussion on Computers

"Computer". That word may not seem so special these days, heck its become so popular that it seems strange when people say they don't know how to use a computer. Computers are everywhere, they can fit almost everywhere- from your lap to your hands(or [inside your hand](https://www.dailymail.co.uk/sciencetech/article-3221287/Would-microchipped-Kaspersky-implants-chip-man-s-hand-one-day-used-pay-goods-unlock-home.html)!!!) but this was not always the case. The computer that sits on your lap may not have fit into the whole world in the 19th century and barely fit football fields in the second half of twentieth century. It is intriguing as to how did this change came about. Lets have a brief look at the journey of computers but before that lets define what a computer is.

Most people know what a computer is but it is very hard for them to define it. In the most rudimentary sense of the word, computer is anything that computes i.e, can do simple arithmetic calculations, Here is a more formal definition from [wikipedia](https://en.wikipedia.org/wiki/Computer):

>_A computer is a device that can be instructed to carry out sequences of arithmetic or logical operations automatically via computer programming. Modern computers have the ability to follow generalized sets of operations, called programs. These programs enable computers to perform an extremely wide range of tasks. A "complete" computer including the hardware, the operating system (main software), and peripheral equipment required and used for "full" operation can be referred to as a computer system. This term may as well be used for a group of computers that are connected and work together, in particular a computer network or computer cluster._

[<img src="{{ site.baseurl }}/images/DiffereneEngine.jpeg" alt="Image showing Babbage difference engine" style="width: 400px;"/>]({{ site.baseurl }}/)

Although the journey for the modern computer starts somewhere in the twentieth century, a need for such a machine was felt way back in the 19th century and great inventors/scientists tried their hands on [building such a machine](https://en.wikipedia.org/wiki/Difference_engine). Mechanical computers were designed at that time(most famously by [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage)) and first programs were written by many people including [lady Ada Lovelace](http://mentalfloss.com/article/53131/ada-lovelace-first-computer-programmer). But some computers were only conceived in designs as they were far beyond the reach of the technology at that time and were very costly and we would be better off using humans instead. Babbage's computer was constructed in the 1990s by History Museum in Mountain View, California, USA, Here is a [good video](https://www.youtube.com/watch?v=BlbQsKpq3Ak&t=1279s) that shows the actual difference engine designed by Babbage.

The focus then shifted to Electro-Mechanical computers and wires and mercury were used with punch cards and IBM(International Business Machines) came into existence, the computers became better and better and could now perform very complex calculations, this was further accelerated by the twin world wars where computers were needed by military to gain strategic advantage. But these were still not enough to quench the thirst for ever increasing demand of computation and hence computers got bigger and bigger. Larger computers meant more complex structures and it became increasingly difficult to manage them.(fun fact: It was at this time when bugs would fly into these computers causing issues in the results, hence the use of the word bugs in modern computer science).

This all changed with the introduction of electronic transistors and now the computer started shrinking, their potential was now known and a great amount of fierce competition(coupled with a lot of scifi) lead to the development of smaller and smaller computers all thanks to shrinking transistor sizes. This was noticed by everyone but Gordon Moore quantized this and made the observation that "The number of transistors on a dense integrated circuit doubles every two years".

Moore's law as it came to be called held true for many years(and still does unless you are reading after 2020) but here is a problem with Moore's law: Transistors can't keep shrinking they are bound to hit that spot where quantum effects come into the picture and when quantum physics come into the picture there is a large amount of uncertainty associated(get it!). Computers need to be dead certain about the answer, else computers will be useless. [from wikipedia](ttps://en.wikipedia.org/wiki/Moore%27s_law)

>_Moore's law is the observation that the number of transistors in a dense integrated circuit doubles about every two years. The observation is named after Gordon Moore, the co-founder of Fairchild Semiconductor and CEO of Intel, whose 1965 paper described a doubling every year in the number of components per integrated circuit, and projected this rate of growth would continue for at least another decade. In 1975, looking forward to the next decade, he revised the forecast to doubling every two years. The period is often quoted as 18 months because of a prediction by Intel executive David House (being a combination of the effect of more transistors and the transistors being faster)._   

According to current estimates the transistors will stop getting any smaller around 2024. Since around that period an individual transistor will be small enough that quantum effects will be significant, if we were to make the transistor any smaller quantum effects will come into play, hence the traditional(or classical) approaches to computing will stop their exponential march in terms of improve in performance.

To overcome this hurdle in performance enhancement we can use new types of computing aka quantum computing. Quantum computing can help us do large number of calculations in seconds. This can help in solving problems previously impossible to solve with classical computers. Many people new to quantum computers use this as an argument to say that this is one of the reasons quantum computers are necessary and they can help replace the classical computers but this is entirely false. The reason for their existence and need is far more complex and fascinating as we shall see.

The above information(and many other things) can be found in a more detailed and structured way in this [youtube course](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)

## Into the Quantum World

Quantum computers are not here to replace classical computing, that is not what they are meant for, they are pretty different from classical computers and have their own style of functioning. They may never be able to beat normal computers at most of the problems we solve with classical computers. Then why are they needed?

The reason is that quantum computers are here to solve some bigger problems and not for watching cat videos on the internet(_sigh_). Quantum computers can be used to solve problems that will be unsolvable by classical computers. Problems like Travelling Salesman problem where the paths required to traverse increase exponentially and problems where a quantum solution is needed like quantum modelling. Actually one of the first applications for which quantum computers were conceived(by the great Richard Feinmann) was to study quantum particles. Since if we can model a quantum particle mathematically and then create its simulation in the computer, then we can perform all sort of experiment on them which would be impossible otherwise.

So what are these problems? And why can't our normal computers help in this? Imagine you want to send the number 7 to your friend but you don't want any person in the middle to know that this was the number you sent. One of the ways of doing this is to send the number 35 ....

Now, Imagine a travelling salesman who wants to optimize his trip and go to all the houses in a city, ....

The above problems define a class of problems known as .... these problems and similar problems are not solvable by classical computers but these problems need to be solved, Now Imagine if we could try all the numbers at once and take only the best one and hence break the code or travel along all possible paths at once and find the best possible route at once. This can be done with the help of quantum computers. The principles of quantum mechanics(on which quantum computers are based) do not follow the rules of physics we are so used to in our everyday life, but there are many unexplained phenomenon, particles can occur in many states at once and can affect each other at a distance(this is topic for another blog post). Hence these problems can only be solved with quantum computers.

But the inception of the idea of quantum computers was not done for breaking cryptography(which may not be possible after all as we shall see in coming blogs), but it was conceived for more noble applications. One of the greatest physicist of the 20th century aka Richard Feinmann proposed the idea in a conference in 1982 that to model a quantum mechanical system we need a computer that works on the principle of quantum mechanics, this can then be used to conduct experiments on the quantum level.  


[great video](https://www.youtube.com/watch?v=F8U1d2Hqark)


What is the physical structure of a qubit?
How does a qubit work on a physical level?
How are qubits combined to perform calcuations?
What are the different gates available?
How can we combine these gates to make other gates?


[computer history](https://www.computerhistory.org/timeline/1950/)