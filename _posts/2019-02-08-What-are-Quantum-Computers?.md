---
layout: post
title: History of Quantum Computers?
---

Even though it is not necessary to go over the classical computers to understand how quantum computers work, but it is quite interesting how computers evolved and how there are so many misconception around quantum computers, I find it necessary to go over how classical computers became what they are today and how they have little to do with quantum computers. 

## Brief Discussion on Computers

"Computer". That word may not seem so special these days, heck its become so popular that it seems strange when people say they don't know how to use a computer. Computers are everywhere, they can fit almost everywhere- from your lap to your hands(or [inside your hand](https://www.dailymail.co.uk/sciencetech/article-3221287/Would-microchipped-Kaspersky-implants-chip-man-s-hand-one-day-used-pay-goods-unlock-home.html)!!!) but this was not always the case. The computer that sits on your lap may not have fit into the whole world in the 19th century and barely fit football fields in the second half of twentieth century. It is intriguing as to how did this change came about. Lets have a brief look at the journey of computers but before that lets define what a computer is.

Most people know what a computer is but it is very hard for them to define it. In the most rudimentary sense of the word, computer is anything that computes i.e, can do simple arithmetic calculations, Here is a more formal definition from [wikipedia](https://en.wikipedia.org/wiki/Computer):

>_A computer is a device that can be instructed to carry out sequences of arithmetic or logical operations automatically via computer programming. Modern computers have the ability to follow generalized sets of operations, called programs. These programs enable computers to perform an extremely wide range of tasks. A "complete" computer including the hardware, the operating system (main software), and peripheral equipment required and used for "full" operation can be referred to as a computer system. This term may as well be used for a group of computers that are connected and work together, in particular a computer network or computer cluster._

<!-- 
{% include image.html url="{{ site.baseurl }}/images/DifferenceEngine.jpeg" description="Babbage's Differential engine(designed in 1822) constructed around 1990-" %}

[source](http://computersupportservicesnj.com/1822-babbage-designs-a-mechanical-computer/) -->

[<img src="{{ site.baseurl }}/images/DifferenceEngine.jpeg" alt="Image 
showing Babbage difference engine" style="width: 750px;"/>]({{ site.baseurl }}/)

<!-- ![an image alt text]({{ site.baseurl }}/images/jekyll-logo.png "an image title") -->



Although the journey for the modern computer starts somewhere in the twentieth century, a need for such a machine was felt way back in the 19th century and great inventors/scientists tried their hands on [building such a machine](https://en.wikipedia.org/wiki/Difference_engine). Mechanical computers were designed at that time(most famously by [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage)) and first programs were written by many people including [lady Ada Lovelace](http://mentalfloss.com/article/53131/ada-lovelace-first-computer-programmer). But some computers were only conceived in designs as they were far beyond the reach of the technology at that time and were very costly and we would be better off using humans instead. Babbage's computer was constructed in the 1990s by History Museum in Mountain View, California, USA, Here is a [good video](https://www.youtube.com/watch?v=BlbQsKpq3Ak&t=1279s) that shows the actual difference engine designed by Babbage.



The focus then shifted to Electro-Mechanical computers and wires and mercury were used with punch cards and IBM(International Business Machines) came into existence, the computers became better and better and could now perform very complex calculations, this was further accelerated by the twin world wars where computers were needed by military to gain strategic advantage. But these were still not enough to quench the thirst for ever increasing demand of computation and hence computers got bigger and bigger. Larger computers meant more complex structures and it became increasingly difficult to manage them.(fun fact: It was at this time when bugs would fly into these computers causing issues in the results, hence the use of the word bugs in modern computer science).


[<img src="{{ site.baseurl }}/images/Bombe.jpg" alt="Image 
showing Bombe Machine used in WWII" style="width: 750px;"/>]({{ site.baseurl }}/images/Bombe.jpg)


This all changed with the introduction of electronic transistors and now the computer started shrinking, their potential was now known and a great amount of fierce competition(coupled with a lot of scifi) lead to the development of smaller and smaller computers all thanks to shrinking transistor sizes. This was noticed by everyone but Gordon Moore quantized this and made the observation that "The number of transistors on a dense integrated circuit doubles every two years".

Moore's law as it came to be called held true for many years(and still does unless you are reading after 2020) but here is a problem with Moore's law: Transistors can't keep shrinking they are bound to hit that spot where quantum effects come into the picture and when quantum physics come into the picture there is a large amount of uncertainty associated(get it!). Computers need to be dead certain about the answer, else computers will be useless. [from wikipedia](ttps://en.wikipedia.org/wiki/Moore%27s_law)


[<img src="{{ site.baseurl }}/images/MooresLaw.jpg" alt="Image 
showing Graph for Moores law" style="width: 750px;"/>]({{ site.baseurl }}/)


>_Moore's law is the observation that the number of transistors in a dense integrated circuit doubles about every two years. The observation is named after Gordon Moore, the co-founder of Fairchild Semiconductor and CEO of Intel, whose 1965 paper described a doubling every year in the number of components per integrated circuit, and projected this rate of growth would continue for at least another decade. In 1975, looking forward to the next decade, he revised the forecast to doubling every two years. The period is often quoted as 18 months because of a prediction by Intel executive David House (being a combination of the effect of more transistors and the transistors being faster)._   

According to current estimates the transistors will stop getting any smaller around 2024. Since around that period an individual transistor will be small enough that quantum effects will be significant, if we were to make the transistor any smaller quantum effects will come into play, hence the traditional(or classical) approaches to computing will stop their exponential march in terms of improve in performance.

To overcome this hurdle in performance enhancement we can use new types of computing aka quantum computing. Quantum computing can help us do large number of calculations in seconds. This can help in solving problems previously impossible to solve with classical computers. Many people new to quantum computers use this as an argument to say that this is one of the reasons quantum computers are necessary and they can help replace the classical computers but this is entirely false. The reason for their existence and need is far more complex and fascinating as we shall see.

The above information(and many other things) can be found in a more detailed and structured way in this [youtube course](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)

## Into the Quantum World

Quantum computers are not here to replace classical computing, that is not what they are meant for, they are pretty different from classical computers and have their own style of functioning. They may never be able to beat normal computers at most of the problems we solve with classical computers. Then why are they needed?

The reason is that quantum computers are here to solve some bigger problems and not for watching cat videos on the internet(_sigh_). Quantum computers can be used to solve problems that will be unsolvable by classical computers. Problems like Travelling Salesman problem where the paths required to traverse increase exponentially and problems where a quantum solution is needed like quantum modelling. Actually one of the first applications for which quantum computers were conceived(by the great Richard Feinmann) was to study quantum particles. Since if we can model a quantum particle mathematically and then create its simulation in the computer, then we can perform all sort of experiment on them which would be impossible otherwise.

So what are these problems? And why can't our normal computers help in this? Imagine you want to send the number 7 to your friend but you don't want any person in the middle to know that this was the number you sent. One of the ways of doing this is to send the number 35 ....

Now, Imagine a travelling salesman who wants to optimize his trip and go to all the houses in a city, ....

The above problems define a class of problems known as .... these problems and similar problems are not solvable by classical computers but these problems need to be solved, Now Imagine if we could try all the numbers at once and take only the best one and hence break the code or travel along all possible paths at once and find the best possible route at once. This can be done with the help of quantum computers. The principles of quantum mechanics(on which quantum computers are based) do not follow the rules of physics we are so used to in our everyday life, but there are many unexplained phenomenon, particles can occur in many states at once and can affect each other at a distance as we shall see in the next section. Hence these problems can only be solved with quantum computers.

But the inception of the idea of quantum computers was not done for breaking cryptography(which may not be possible after all as we shall see in coming blogs), but it was conceived for more noble applications. One of the greatest physicist of the 20th century aka Richard Feinmann proposed the idea in a conference in 1982 that to model a quantum mechanical system we need a computer that works on the principle of quantum mechanics, this can then be used to conduct experiments on the quantum level.  

To understand computers, we first look at the stuff that its made of i.e, silicon and then we build from it ground up from diodes to gates to more complex architectures that can perform more complex calculations and then we put a layer of abstraction on it, to write programs for it to instruct it to do tasks we want it to perform, we shall take a similar approach to understanding the internal working of a quantum computer. But before we do that, we need to understand some of the strange physics that quantum computers make use of.

### Prerequisite physics

Quantum physics is an extremely huge and interesting subject in its own, but to understand quantum computers we don't need to understand it fully, we only need to look at some of the quantum phenomenons(namely quantum entanglement and quantum superposition) and develop an abstract understanding of the concepts and we should be good to go to understand the next stage.

*Quantum Superposition* is a very counter-intuitive physical phenomenon, it suggests that quantum particles such as electrons can appear in more than one state at the same time i.e, an electron can be at two places at the same time or can have different momentum or energy at the same time. This is not observable in our everyday life, since one thing should be at only one place, if it were at many places at the same time, it would disobey the laws of classical physics. But this is indeed possible with quantum particles owing to their dual nature i.e, wave like as well as particle like. Quantum particles are said to be waves and particles at the same time(it is to be noted that "same time" is only for understanding, because there is no concept of time or actuality in quantum world) hence have dual nature. Now waves have this superposition principle as you may be aware i.e, two waves can superpose on each other to produce another wave. This is the definition of quantum superposition as per [wikipedia](https://en.wikipedia.org/wiki/uantum_superposition):

>_ It states that, much like waves in classical physics, any two (or more) quantum states can be added together ("superposed") and the result will be another valid quantum state; and conversely, that every quantum state can be represented as a sum of two or more other distinct states. Mathematically, it refers to a property of solutions to the Schrödinger equation; since the Schrödinger equation is linear, any linear combination of solutions will also be a solution._

Here is a more mathematical explanation of quantum superposition from [Dirac's](link/to/dirac) book:

1. Consider the superposition of two states, A and B, which on observation give results a and b.[4]

2. The observation made on system in superposed state will be sometimes a and sometimes b, according to a probability law depending on the relative weights of A and B in the superposition process.[4]

To get a better understanding of quantum superposition, you may want to look at the accompanying video for the [quantum superposition wiki page](https://en.wikipedia.org/wiki/Quantum_superposition), I find that video very helpful to understand quantum superposition. If you are still having trouble here is a great video that explains quantum superposition

Even though quantum superposition is a strictly quantum phenomenon we can observe how it may work. An experiment was conducted by researchers at ..... in which they placed an oil droplet on acetone and the following pattern was observed. Many scientist believe that this is how quantum superposition works and it seems like a good way to visualize quantum superposition, please take a look at this video to get a better understanding of pilot waves.

pilotwave.gif 


*Quantum Entanglement* is one of the most fascinating and fiercely debated quantum phenomenon, It is one of the reasons that Einstein was skeptical of Quantum physics and led him to call it "spooky action at a distance".

Einstein_quote_entanglement.png
Einstein_quote_Quantum_Physics.png

So what is quantum entanglement and why is there so much fascination around it? 

Lets say you have only one nucleus in a universe, now this nucleus emits some particle, say an electron then a positron must also be emitted(since particles are generated in pairs), now let us consider there angular momentum, the sum of their angular momentum should be zero, let us say they are then seperated by a very large distance, again their angular momentum sum should be zero(since angular momentum is conserved), so for example if an electron is in up direction, then the positron should be in the opposite direction. Now let us consider that we measure the spin of electron and find that it is in up direction then the spin of positron must be in down direction(conservation of angular momentum), So we know about the state of a particle that may be thousands(or millions) of light years away just by looking at a particle in front of us. Now this is weird, since these particles are seperated by such a large distance there is little chance that they are communication to each other with the help of light(since if they did, how would they be able to communicate faster than light?) this suggests that these particles are somehow contacting each other with the help of some unknown passage(hypothetically) or they are communicating with something faster than light(which is not possible because physics).


I find the above thought experiment quite useful in understanding why quantum entanglement is so weird, But here is a more formal definition for quantum entanglement:

>_find definition of quantum entanglement from some reliable source_

Einstein_Sun_light_Gravity.png

Even though quantum entanglement seems strange it still works and that is what matters when it comes to quantum computers, There have been many experiments that prove that quantum entanglement does exist and a chinese satellite (called Micius) was sent in 2011 to facilitate communication using quantum entanglement, there was also this video conference call. Even though it has not been proved that the effect is faster than light(some reason), but we need not concern ourselves with that when trying to understand quantum computers. There are many applications for quantum entanglement that may be useful in the coming future e.g, quantum internet, give more examples.

With the above information in mind we can now proceed further to understand how the internal of quantum computers work. We will start with information storage and retreival and see how computations may be performed using quantum effects, We then see how these tools are put together to make quantum logic gates, these gates can then be combined to perform even more complex calculations. We can then put layers of abstraction and finally arrive at the final model of a quantum computer.

### Qubits

In classical computers the information is stored in the form of bits, These *bi*nary digi*ts* can represent 0 or 1 states, We have developed quite sophisticated system just by using this simple form of storage but we can still do a lot better with a *Qu*antum *bit*, Unlike bits which can only store 0s and 1s qubits can store a third and very important state that is the superposition of 0 and 1. This superposition of states is what helps a quantum computers do things that a classical computer may not be able to do. When a qubit is in one of the superposition states, it can be said to be in both 0 and 1 states at the same time but this is hardly the case. For example consider you move 3m North and then 4m West, now you are 5m in the North-West Direction or you are in a superposition of North and West. To put it another way- "You are in north and west at the same time!", It doesn't sound so delicious anymore does it? The same is with superposition of quantum states, Even though a qubit is not in any of 1 or 0 state but it is in say 60% 1 state and 40% 0 state, Hence it is in the superposition of two states at once?

Why does it matter that a qubit is in a superposition of two states though?

A Qubit is generally made up of silicon and phosphorus and sometimes of photon! People are also trying to exploit the spins of nuclei to make qubits  

But what makes a qubit special from a classical bit? The answer lies in the principle of quantum superposition. Let us consider and example- Lets say you have two bits now they can be either 00, 01, 10, 11 i.e, they can be in one of four states. Now consider two qubits, they can be (up,up), (down,down), (up,down) + (down,up) OR (down,up) - (up,down) {where + and - represent either coherent or decoherent superposition} as shown in figure. Now assume that the probability of each of the above states is given by alpha, beta, gamma, delta. Now here is the fun part- The Qubit is not in one of these states but in a superposition of these states. i.e, its state is alpha\*(up,up) + beta\*()....... Hence if we perform a calculation now, we will in effect be performing the calculation on all these states simultaneouly instead of each state individually, leading to remarkable improvements in performance of certain algorithms.

veritasium_image.png

One of the most impressive things about qubits is that, it doesn't take much to increase the computation power. So for example you wanted to double the computation power of the above system to represent 8-states, Now to do this we can only add one more qubit resulting in the doubling of the number of represented states. Now lets say we need to represent the above system with classical bits, to do this we would need four individual states(composed of bits), now two double it i.e, represent 8-states we need double the states i.e, 4 more representations. So, in order to double the computation power of a classical computer we would need to double its size. But it is impractical with- say a supercomputer which are already huge. But with quantum computers you can get away by only adding one qubit.

Even though, in principle we can perform these operations simultaneously, it is not possible for us to measure these states, since superposition breaks as soon as we measure the states. Hence in effect we can only get one answer and if we measure a qubit we are most likely to end up with a random answer which is not going to be useful. To counter this, we devise algorithms in such a way that the wrong states interfere and cancel each other while the right answer is promoted by interference. And in the end we are left with only the right answer. This can be done by <name the algo> 

Bloch_sphere.jpg

Quantum computers can be represented by a bloch sphere- A bloch sphere is a sphere that can represent the superposition of states(give more formal def). The north pole on a bloch sphere represents a 0 while the south pole represents a 1. Any intermediate point on the sphere represents a superposition of states- ....give equations..... 


### Information Storage and Retreival

One of the most important things that a computing machine does is reading and writing data(since if it is possible it can do anything refer to turing machine). Let us understand how a quantum computer reads and writes data.

Qubits are embedded in transistors, now all qubits have energy lets say we have an electron in down state, then it will have low energy, now with a precise microwave(precise means at the right place with the right frequency) we can give that electron enough energy to make it spin in the up direction. This will result in a change of voltage in the transistor and we can now say on the base of it, that it has indeed increased .Hence we have changed the state of a qubit from 0 to 1 and we have now successfully written to a qubit. 

that_transistor.jpg

Reading from a qubit is similar but we have to keep in mind that it is not so easy, We cannot just have a good microwave generator and read/write from/into qubits. Since at room temperature, there is too much energy for a quantum particle and it will generate random patterns, but we need very precise patterns, so we need to cool the substance down to almost zero kelvin so we can record the qubit data.

### Quantum logic

Now we have a good enough picture about the physics behind the quantum computers and the physical structure of a quantum computer. We are now ready to move ahead with quantum logic. We will not be further considering the physical model but instead in this section we shall develop what are know as quantum logic gates. These logic gates can perform operations on qubit states and are a very good model to hide unnecessary details while writing programs for quantum computers.

There are many gates available for quantum computers such as give, names, of, gates. But as in the case of classical computers we only need a few universal gates that can represent all the other gates(for classical computers we have NAND/NOR gates). In quantum computers these gates are Hadamard gate, Toffoli gate and CNOT gate. Before we look at these gates, it is important to note that quantum gates are reversible i.e, you can get the output from the input and the input from the output. There aren't any gates that are reversible in case of classical computers except NOT gate. So for example- we have a 1 as input then we get 0 as the output, and if we have a 0 as the output we know that 1 must be the input. 

Explain CNOT gate
CNOT_gate.png
CNOT_gate_table.png

Explain Hadamard gate
Hadamard_gate.png
Hadamard_gate_table.png

Explain Toffoli gate
Toffoli_gate.png
Toffoli_gate_table.png


### The Big Picture

With the above knowledge of the internal workings of quantum computers, we can combine these to form bigger more useful parts of a computer(as in classical computer). These then form our quantum computer. Now we need all the things that are available in a classical computer, starting from a compiler, Operating system, language etc. Since classical computers have a rich history, we can leverage this to our advantage and without much work, build a working quantum computing software. Currently most companies have their own architectures, but this needs to change soon if we want to increase the speed of research in this area. We need standarized architectures, so it is easy for researchers to develop and test new things. Here is one of the proposed architecture.

that_architecture.png

As may be seen this seems like a classical computer architecture with the term quantum associated with it, It indeed it.


### Challenges and Shortcomings

Quantum computers are very prone to error. Indeed, we never get accurate result from a quantum computers, We get right results sometime and sometimes wrong results, when we get more right results than wrong we say that our quantum computer is giving us good answers. Quantum error correction is a field in itself. It is very essential to decrease the uncertainty in results, since only after that we would be able to make quantum computers usable.

Quantum decoherence is when we combine too many qubits together and they start interfering with each other


### The Road ahead

Even though quantum computers provide us with a great perspective, there is a lot of false hype around them, there are some conspiracy theories that see quantum computers as a passage to other dimensions(lol!!!), This hype is natural given any new technology and the quantity of science fiction concentrated around quantum physics. But we need to be realistic about quantum computers, since we do not even know whether we would ever have quantum computers that can be used. It is very difficult to increase the number of qubits in quantum computers due to decoherence, and even though the quality of bits has gone up in the past decade, there is still a great need of research and focus on quantum computers and the need to educate people before we can expect some results from quantum computers.

Most of the quantum computer research has been focussed around breaking cryptography, this is due to Shor's algorithm, but it is unrealistic to expect quantum computers to break cryptography in the near future since we need more than a million qubits to break cryptography, and we are barely in the two digits these days. With time there have been many new applications for quantum computers have emerged, ranging from quatum internet, give, examples to give, some, more, examples.

That guy say that quantum internet will be around in 13 yrs, china is quite fast in this and google has developed besht quantum computers, intel, IBM etc.


[great video](https://www.youtube.com/watch?v=F8U1d2Hqark)
[computer history](https://www.computerhistory.org/timeline/1950/)