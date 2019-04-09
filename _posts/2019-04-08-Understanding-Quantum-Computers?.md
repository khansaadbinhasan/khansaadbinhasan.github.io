---
layout: post
title: Understanding Quantum Computers
---

Even though it is not necessary to go over the classical computers to understand how quantum computers work, but it is quite interesting how computers evolved and how there are so many misconception around quantum computers, I find it necessary to go over how classical computers became what they are today and how they have little to do with quantum computers. 

![Quantum Meme]( https://khansaadbinhasan.github.io/images/QuantumBlogs/QuantumMeme.gif "QuantumMeme")

# Brief Discussion on Computers

"Computer". That word may not seem so special these days, heck its become so popular that it seems strange when people say they don't know how to use a computer. Computers are everywhere, they can fit almost everywhere- from your lap to your hands(or [inside your hand](https://www.dailymail.co.uk/sciencetech/article-3221287/Would-microchipped-Kaspersky-implants-chip-man-s-hand-one-day-used-pay-goods-unlock-home.html)!!!) but this was not always the case. The computer that sits on your lap may not have fit into the whole world in the 19th century and barely fit football fields in the second half of twentieth century. It is intriguing as to how did this change came about. Lets have a brief look at the journey of computers but before that lets define what a computer is.

Most people know what a computer is but it is very hard for them to define it. In the most rudimentary sense of the word, computer is anything that computes i.e, can do simple arithmetic calculations, Here is a more formal definition from [wikipedia](https://en.wikipedia.org/wiki/Computer):

>*A computer is a device that can be instructed to carry out sequences of arithmetic or logical operations automatically via computer programming. Modern computers have the ability to follow generalized sets of operations, called programs. These programs enable computers to perform an extremely wide range of tasks. A "complete" computer including the hardware, the operating system (main software), and peripheral equipment required and used for "full" operation can be referred to as a computer system. This term may as well be used for a group of computers that are connected and work together, in particular a computer network or computer cluster.*
      

<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/TheDifferenceEngine.jpeg" alt="The Difference Engine" width="720px" height="auto" />
	<figcaption>The Difference Engine</figcaption>
</figure>

<br><br>


     
     
Although the journey for the modern computer starts somewhere in the twentieth century, a need for such a machine was felt way back in the 19th century and great inventors/scientists tried their hands on [building such a machine](https://en.wikipedia.org/wiki/Difference_engine). Mechanical computers were designed at that time(most famously by [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage)) and first programs were written by many people including [lady Ada Lovelace](http://mentalfloss.com/article/53131/ada-lovelace-first-computer-programmer). But some computers were only conceived in designs as they were far beyond the reach of the technology at that time and were very costly and we would be better off using humans instead. Babbage's computer was constructed in the 1990s by History Museum in Mountain View, California, USA, Here is a [good video](https://www.youtube.com/watch?v=BlbQsKpq3Ak&t=1279s) that shows the actual difference engine designed by Babbage.

<br><br>

<iframe width="720" height="405" src="https://www.youtube.com/embed/BlbQsKpq3Ak" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br><br>

The focus then shifted to Electro-Mechanical computers and wires and mercury were used with punch cards and IBM(International Business Machines) came into existence, the computers became better and better and could now perform very complex calculations, this was further accelerated by the twin world wars where computers were needed by military to gain strategic advantage. But these were still not enough to quench the thirst for ever increasing demand of computation and hence computers got bigger and bigger. Larger computers meant more complex structures and it became increasingly difficult to manage them.(fun fact: It was at this time when bugs would fly into these computers causing issues in the results, hence the use of the word "**bugs**" in modern computer science).      
       
       
      
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/Bombe.jpg" alt="The Bombe" width="720px" height="auto" />
		<figcaption>The Bombe</figcaption>
</figure>

<br><br>

     
     
This all changed with the introduction of electronic transistors and now the computer started shrinking, their potential was now known and a great amount of fierce competition(coupled with a lot of scifi) lead to the development of smaller and smaller computers all thanks to shrinking transistor sizes. This was noticed by everyone but Gordon Moore condensed this observation and formulated it-"The number of transistors on a dense integrated circuit doubles every two years".

Moore's law as it came to be called held true for many years(and still does) but here is a problem with Moore's law: Transistors can't keep shrinking, they are bound to hit that spot where quantum effects come into the picture and when quantum physics come into the picture there is a large amount of uncertainty associated(get it!). Computers need to be dead certain about the answer, else computers will not be very useful. 

>*Moore's law is the observation that the number of transistors in a dense integrated circuit doubles about every two years. The observation is named after Gordon Moore, the co-founder of Fairchild Semiconductor and CEO of Intel, whose 1965 paper described a doubling every year in the number of components per integrated circuit, and projected this rate of growth would continue for at least another decade. In 1975, looking forward to the next decade, he revised the forecast to doubling every two years. The period is often quoted as 18 months because of a prediction by Intel executive David House (being a combination of the effect of more transistors and the transistors being faster).* - [wikipedia](ttps://en.wikipedia.org/wiki/Moore%27s_law)

According to current estimates the transistors will stop getting any smaller around 2024. Since around that period an individual transistor will be small enough that quantum effects will be significant, if we were to make the transistor any smaller quantum effects will come into play, hence the traditional(or classical) approaches to computing will stop their exponential march in terms of improve in performance.

To overcome this hurdle in performance enhancement we can use new types of computing aka quantum computing. Quantum computing can help us do large number of calculations in seconds. This can help in solving problems previously impossible to solve with classical computers. Many people use this as an argument to say that this is one of the reasons quantum computers are necessary and they can help replace the classical computers but this is entirely false. The reason for their existence and need is far more complex and fascinating as we shall see.

The above information(and many other things) can be found in a more detailed and structured way in this [youtube course](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)

# Into the Quantum World

Quantum computers are not here to replace classical computing, that is not what they are meant for. They are pretty different from classical computers and have their own style of computing. They may never be able to beat normal computers at most of the problems we solve with classical computers. Then why are they needed?

The reason is that quantum computers are here to solve some bigger problems and not for watching cat videos on the internet(_sigh_). Quantum computers can be used to solve problems that will be unsolvable by classical computers. Problems like breaking RSA encryption and problems where a quantum solution is needed like quantum modelling. Actually one of the first applications for which quantum computers were conceived(by the great physicist Richard Feynman) was to study quantum particles. Since, if we can model a quantum particle mathematically and then create its simulation in the computer, then we can perform all sort of experiment on them which would be impossible otherwise.

So what are these problems? And why can't our normal computers help in this? There are some problems that need extremely large computation power and space e.g, finding factors of very huge prime numbers, simulating molecules, simulating quantum phenomenons etc. In computer science we divide problems into different classes, depending on how they grow(i.e, how many computations are needed) as we increase the number of input values. These are called polynomial time, nondeterministic-polynomial time and np hard problems. NP problems can be solved by classical computers for very small number of inputs but for large values of N the time taken for computation becomes very large and hence computation becomes infeasible. But there are some problems that are in NP class but can still be solved in finite amount of time by a quantum computer. These problems are called **B**ounded-error **Q**uantum **P**olynomial time problems. But till now these kinds of problems are limited and you will be better off solving these problems on a classical computer rather than a quantum computer. But some problems(like prime factorization for large numbers) can only be solved by quantum computers(very powerful ones though).

       
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/BQP.jpg" alt="The Problem Heirarchy" width="720px" height="auto" />
	<figcaption>The Problem Heirarchy</figcaption>
</figure>

<br><br>

     
     
To understand computers, we first look at the stuff that its made of i.e, silicon and then we build from it ground up from diodes to gates to registers to more complex architectures like ALUs and CPUs that can perform more complex calculations and then we put a layer of abstraction over it, to write programs for it, to instruct it to do tasks we want it to perform. We shall take a similar approach to understanding the internal working of a quantum computer. But before we do that, we need to understand some of the strange physics that quantum computers make use of.

## Prerequisite physics

Quantum physics is an extremely huge and interesting subject in its own, but to understand quantum computers we don't need to understand it fully, we only need to look at some of the quantum phenomenons(namely quantum entanglement and quantum superposition) and develop an abstract understanding of the concepts to understand the working of quantum computers.

**Quantum Superposition** is a very counter-intuitive physical phenomenon, it suggests that quantum particles such as electrons can appear in more than one state at the same time i.e, an electron can be at two places at the same time or can have different momentum or energy at the same time. This is not observable in our everyday life, since one thing should be at only one place, if it were at many places at the same time, it would disobey the laws of classical physics. But this is indeed possible with quantum particles owing to their dual nature i.e, wave like as well as particle like. Quantum particles are said to be waves and particles at the same time(it is to be noted that "same time" is only for understanding, because there is no concept of time or actuality in quantum world) hence have dual nature. Now waves have this superposition principle as you may be aware i.e, two waves can superpose on each other to produce another wave. This is the definition of quantum superposition as per [wikipedia](https://en.wikipedia.org/wiki/Quantum_superposition):

>*It states that, much like waves in classical physics, any two (or more) quantum states can be added together ("superposed") and the result will be another valid quantum state; and conversely, that every quantum state can be represented as a sum of two or more other distinct states. Mathematically, it refers to a property of solutions to the Schrödinger equation; since the Schrödinger equation is linear, any linear combination of solutions will also be a solution.*

Here is a more mathematical explanation of quantum superposition from [Dirac's](https://en.wikipedia.org/wiki/Paul_Dirac) book[1]:

1. Consider the superposition of two states, A and B, which on observation give results a and b.

2. The observation made on system in superposed state will be sometimes a and sometimes b, according to a probability law depending on the relative weights of A and B in the superposition process.

To get a better understanding of quantum superposition, you may want to look at the accompanying video for the [quantum superposition wiki page](https://en.wikipedia.org/wiki/Quantum_superposition), I find that video very helpful to understand quantum superposition. If you are still having trouble here is a [great video](https://www.youtube.com/watch?v=hkmoZ8e5Qn0) that explains quantum superposition or look at this [quora thread](https://www.quora.com/Do-quantum-objects-actually-exist-in-multiple-states-at-once-when-unobserved-or-is-this-some-analogy-of-some-kind) to further clear your understanding
       
      
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/QuantumEffects.jpeg " alt="Quantum Effects" width="720px" height="auto" />
	<figcaption>Quantum Effects</figcaption> 
</figure>

<br><br>
     
     
**Quantum Entanglement** is one of the most fascinating quantum phenomenon, It is one of the reasons that Einstein was skeptical of Quantum mechanics and led him to call it ["spooky action at a distance".](https://dragallur.wordpress.com/2016/02/14/spooky-action-at-a-distance/)
       
      
     
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/QuoteEinstein3.jpg" alt="Quantum Quote" width="480px" height=auto/>
</figure>

<br><br>



     
     
Lets say you have two particles in an isolated universe created out of energy, now let us consider their angular momentum, the sum of their angular momentum should be constant(Law of conservation of angular momentum). Let us say they are then seperated by a very large distance, again their angular momentum sum should be the same(since angular momentum is conserved). So for example if a particle is in up direction, then the other particle should be in the opposite direction. Now let us consider that we measure the spin of first particle and find that it is in up direction then the spin of other particle must be in down direction(conservation of angular momentum), contacting each other with the help of some unknown passage(hypothetically) or they are communicating with something faster than light(which is not possible because physics).

       
      
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/Entanglement.gif" alt="Quantum Entanglement gif" width="480px" height=auto  />
	<figcaption>Quantum Entanglement gif</figcaption> 
</figure>

<br><br>
     
I find the above thought experiment quite useful in understanding why quantum entanglement is so weird, But here is a more [formal definition](https://en.wikipedia.org/wiki/Quantum_entanglement) for quantum entanglement:

>*Quantum entanglement is a physical phenomenon that occurs when pairs or groups of particles are generated, interact, or share spatial proximity in ways such that the quantum state of each particle cannot be described independently of the state of the other(s), even when the particles are separated by a large distance.*

Quantum entanglement has been demonstrated experimentally with photons, neutrinos, electrons, molecules as large as buckyballs, and even small diamonds. The utilization of entanglement in communication and computation is a very active area of research. Here is a [good video](https://www.youtube.com/watch?time_continue=99&v=IOYyCHGWJq4) that explains both quantum entanglement and quantum superposition clearly.

<iframe width="720" height="405" src="https://www.youtube.com/embed/IOYyCHGWJq4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Even though quantum entanglement seems strange it still works and that is what matters when it comes to quantum computers, There have been many experiments that prove that quantum entanglement does exist and a chinese satellite (called Micius) was sent in 2011 to facilitate communication using quantum entanglement, and a [video conference call](https://www.sciencenews.org/article/quantum-video-chat-links-scientists-two-different-continents) was conducted in 2017. 

With the above information in mind we can now proceed further to understand how the internal of quantum computers work. We will start with information storage and retreival and see how computations may be performed using quantum effects. We then see how these tools are put together to make quantum logic gates. These gates can then be combined to perform even more complex calculations. We can then put layers of abstraction and finally arrive at the final model of a quantum computer.

## Qubits

In classical computers the information is stored in the form of bits, These **bi**nary digi**ts** can represent 0 or 1 states, We have developed quite sophisticated system just by using this simple form of storage but we can still do a lot better with a **Qu**antum **bit**, Unlike bits which can only store 0s and 1s qubits can store a third and very important state that is the superposition of 0 and 1. This superposition of states is what helps a quantum computers do things that a classical computer may not be able to do. When a qubit is in one of the superposition states, it can be said to be in both 0 and 1 states at the same time but this is hardly the case. For example consider you move 3m North and then 4m West, now you are 5m in the North-West Direction or you are in a superposition of North and West. To put it another way- "You are in north and west at the same time!", It doesn't sound so delicious anymore does it? The same is with superposition of quantum states. Even though a qubit is not in any of 1 or 0 state but it is in say 80% 1 state and 40% 0 state. Hence, it is in the superposition of two states at once.

Here is a good answer that explains [how qubits can hold both 0 and 1 at the same time?](https://www.quora.com/How-can-a-qubit-hold-0-and-1-at-same-time)

A Qubit is generally made up of silicon and phosphorus and sometimes of photon! People are also trying to exploit the spins of nuclei to make qubits.
But what makes a qubit special from a classical bit? The answer lies in the principle of quantum superposition. Let us consider an example- 


Lets say you have two bits now they can be either `00, 01, 10, 11` i.e, they can be in one of four states. Now consider two qubits, they can be- (&uarr;,&uarr;), (&darr;,&darr;), ((&uarr;,&darr;) + (&darr;,&uarr;)) OR ((&darr;,&uarr;) - (&uarr;,&darr;)) where, + and - represent either coherent or decoherent superposition as shown in figure. 

Now assume that the probability of each of the above states is given by alpha, beta, gamma, delta. Now here is the fun part- The Qubit is not in one of these states but in a superposition of these states. i.e, its state is 

&alpha;(&uarr;,&uarr;) + &beta;((&darr;,&uarr;)-(&uarr;,&darr;)) + &gamma;((&darr;,&uarr;)+(&uarr;,&darr;)) + &delta;(&uarr;,&uarr;) 

Hence, if we perform a calculation now, we will in effect be performing the calculation on all these states simultaneouly instead of each state individually, leading to remarkable improvements in performance of certain algorithms.

       
      
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/veritasium1.jpg" alt="States of a two qubit system" width="720px" height="auto" />
	<figcaption>States of a two qubit system</figcaption> 
</figure>

<br><br>

      
     
     
One of the most impressive things about qubits is that, it doesn't take much to increase the computation power. So for example you wanted to double the computation power of the above system to represent 8-states, Now to do this we need to add only one more qubit resulting in the doubling of the number of represented states. Now lets say we need to represent the above system with classical bits, to do this we would need four individual states(composed of bits), now to double it i.e, represent 8-states we need double the states i.e, 4 more representations. So, in order to double the computation power of a classical computer we would need to double its size. But it is impractical with- say supercomputers which are already huge. But with quantum computers you can get away by only adding one qubit.

Even though, in principle we can perform these operations simultaneously, it is not possible for us to measure these states, since superposition breaks as soon as we measure the states. Hence, in effect we can only get one answer and if we measure a qubit we are most likely to end up with a random answer which is not going to be useful. To counter this, we devise algorithms in such a way that the wrong states interfere and cancel each other while the right answer is promoted by interference(as is done in [shor's algorithm](https://en.wikipedia.org/wiki/Shor's_algorithm)). And in the end we are left with answers that have more probability of being right than wrong. This can be done by [Quantum Fourier Transform](https://en.wikipedia.org/wiki/Quantum_Fourier_transform). Here is a [great video](https://www.youtube.com/watch?v=wUwZZaI5u0c) to understand how quantum algorithms work.

<br><br>

<iframe width="720" height="405" src="https://www.youtube.com/embed/wUwZZaI5u0c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br><br>

## Information Storage and Retreival

One of the most important things that a computing machine does is- reading and writing data, since if it is possible it can do anything as shown by [Alan Turing](https://en.wikipedia.org/wiki/Turing_machine). The concept of Turing Machine has been taken further for Quantum Computers and [Quantum Turing Machines](https://en.wikipedia.org/wiki/Quantum_Turing_machine) have been proposed. Let us understand how a quantum computer reads and writes data.

       
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/QuantumEntanglementMicrowave.jpg " alt="Quantum Entanglement Microwave" width="480px" height=auto  />
	<figcaption>States of a two qubit system</figcaption> 
</figure>

<br><br>


Qubits are embedded among transistors. Now all qubits have energy, lets say we have an electron in down state, then it will have low energy, now with a precise microwave(precise means at the right place with the right frequency) we can give that electron enough energy to make it spin in the up direction. This will result in a change of voltage in the transistor and we can now say on its basis, that it has indeed increased. Hence we have changed the state of a qubit from 0 to 1 and we have now successfully written to a qubit. 

Reading from a qubit is similar but we have to keep in mind that it is not so easy, We cannot just have a good microwave generator and read/write from/into qubits. Since at room temperature, there is too much energy for a quantum particle and it will generate random patterns, but we need very precise patterns, so we need to cool the substance down to almost zero kelvin so we can record the qubit data. Here is a [great video by veritasium](https://www.youtube.com/watch?v=zNzzGgr2mhk&list=PLkahZjV5wKe_dajngssVLffaCh2gbq55_&index=6) that illustrate the above in great detail

<br><br>

<iframe width="720" height="405" src="https://www.youtube.com/embed/zNzzGgr2mhk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br><br>

## The Big Picture

----
add about gates here

----

With the above knowledge of the internal workings of quantum computers, we can combine these to form bigger, more useful parts of a computer(as in classical computers). These then form our quantum computer. Now we need all the things that are available in a classical computer, starting from a compiler, Operating system, programming languages etc. Since classical computers have a rich history, we can leverage this to our advantage and without much work, build a working quantum computing software. Currently most companies have their own architectures, but this needs to change soon if we want to increase the speed of research in this area. We need standarized architectures, so it is easy for researchers to develop and test new things. Here is one of the proposed architectures.

       
<br><br>

<figure style = " float: right;
				  width: 720px;
				  text-align: center;
				  font-style: italic;
				  font-size: 120%;
				  text-indent: 0;
				  border: thin silver solid;
				  margin: 0.5em;
				  padding: 0.5em; ">
	<img src="https://khansaadbinhasan.github.io/images/QuantumBlogs/QuantumArch.gif" alt="Quantum Computer Architecture" width="480px" height=auto  />
	<figcaption>States of a two qubit system</figcaption> 
</figure>

<br><br>


As may be seen this seems like a classical computer architecture with the term quantum associated with it, It indeed is.

---
add about algorithms here

---

## Challenges and Shortcomings

Quantum computers are very prone to error. Indeed, we never get accurate results from quantum computers. We get right results sometime and sometimes wrong results, when we get more right results than wrong we say that our quantum computer is giving us good answers. Quantum error correction is a field in itself. It is very essential to decrease the uncertainty in results, since only after that we would be able to make quantum computers usable.

One more problem with quantum computers is that once you observe a state it loses all its information since it has to collapse to only one state. Now, observation does not mean observation by humans, it means any interaction with the quantum particles that may lead to exchange of photons. Now this can be done by interaction with almost anything, this is known as **quantum decoherence**. Here is a more formal definition from [wikipedia](https://en.wikipedia.org/wiki/Quantum_decoherence)

>*Quantum decoherence is the loss of quantum coherence. In quantum mechanics, particles such as electrons are described by a wave function, a mathematical representation of the quantum state of a system; a probabilistic interpretation of the wave function is used to explain various quantum effects. As long as there exists a definite phase relation between different states, the system is said to be coherent. Coherence is preserved under the laws of quantum physics, and this is necessary for the functioning of quantum computers. However, when a quantum system is not perfectly isolated (in which case it would be impossible to manipulate or investigate it), coherence is shared with the environment and appears to be lost with time, a process called quantum decoherence. As a result of this process, quantum behavior is apparently lost, just as energy appears to be lost by friction in classical mechanics.*

Decoherence leads to another problem- The multiple qubits are useful in a quantum computer only if they can be mutually entangled. In today’s quantum computers by the time you attempt to entangle 10 qubits they have lost their coherence. The coherence lifetime of today’s quits is just a few microseconds which is much less than what is needed to perform meaningful computational tasks. Hence decoherence limits the growth of computational power of quantum computers.

To overcome decoherence we need very sophisticated and very well insulated(even from waves(signals) present in the air) systems to protect qubits from any external effects. Needless to say, this is extremely difficult and requires great amount of resources and clever engineering, leading to investment of huge sums of money. Add to it the difficulty and dangers of setting it up and you can say goodbye to your dream of having a quantum computer in your home.

## The Road ahead

Even though quantum computers provide us with a great perspective, there is a lot of false hype around them, there are some conspiracy theories that see quantum computers as a passage to other dimensions(lol!!!), This hype is natural given any new technology and the quantity of science fiction concentrated around quantum physics. But we need to be realistic about quantum computers, since we do not even know whether we would ever have quantum computers that can be used for practical purposes(like simulation of molecules). It is very difficult to increase the number of qubits in quantum computers due to decoherence, and even though the quality of qubits has gone up in the past decade, there is still a great need of research and focus on quantum computers and the need to educate people before we can expect some results from quantum computers.

Most of the quantum computing research has been focussed around breaking cryptography(due to its implications), this is due to [Shor's algorithm](https://en.wikipedia.org/wiki/Shor%27s_algorithm), but it is unrealistic to expect quantum computers to break cryptography in the near future since we need thousands of qubits to break cryptography, and we are barely in the two digits these days. With time many new applications for quantum computers have emerged, ranging from quatum internet to the simulation of quantum mechanical systems which may lead to the formation of new materials that can be used to fight cancer, make nanoparticles, make superconducting materials etc. Quantum Cryptography is emerging as one of the more advance areas in applications of quantum effects.

     
     
<br><br>

![Quantum Crypto]( https://khansaadbinhasan.github.io/images/QuantumBlogs/QuantumCrypto.gif "Quantum Crypto")
          
<br><br>

Jian-Wei Pan of the University of Science and Technology of China, hopes that by 2030 quantum communications will span multiple countries. In around 10 years, you can expect quantum internet. Intel recently announced a 49 bit quantum computer named ‘Tangle Lake’, Google has reportedly built a 72-bit quantum computer chip called ‘Bristlecone’, IBM unveiled world’s first commercial quantum computer named the IBM Q System One. Alibaba is also making great advances in this field.


-------
give conclusion


All in all the road ahead for quantum computers seems bright, couple that with great competitions among giant companies and you have the recipe for living in great history. 


[great video](https://www.youtube.com/watch?v=F8U1d2Hqark)
[computer history](https://www.computerhistory.org/timeline/1950/)
[very detailed series on quantum computers](https://medium.com/@jonathan_hui/qc-quantum-computing-series-10ddd7977abd)
[long blog](https://medium.com/@jackkrupansky/the-greatest-challenges-for-quantum-computing-are-hardware-and-algorithms-c61061fa1210)
[hackernoon blog](https://hackernoon.com/quantum-computing-explained-a114999299ca)

[1]  P.A.M. Dirac (1947). The Principles of Quantum Mechanics (2nd edition). Clarendon Press. p. 12. 