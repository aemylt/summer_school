# Introduction

Welcome to the GitHub repositry for day four of [Quantum in the Summer](http://www.bristol.ac.uk/physics/research/quantum/engagement/qsummer/)! Within here are a bunch of resources written by [Dom Moylett](http://research-information.bristol.ac.uk/en/persons/dom-j-moylett(4dda1234-ac14-43cf-9192-b1332f7ead2e).html) and [Sam Pallister](http://research-information.bristol.ac.uk/en/persons/sam-pallister(c76f8f71-77c2-4e76-a67c-4ce14c935a8c).html) on the subject of quantum computing.

These worksheets were written for students aged 16 or over who had spent the previous three days learning about quantum physics -- in particular linear optics -- and had learned about the concepts of bizarre effects such as superposition and entanglement.These bizarre properties make quantum physics very hard to simulate, to the extent that we build massive supercomputers -- such as the University of Bristol's own [Blue Crystal](https://www.acrc.bris.ac.uk/) -- for the purpose of simulating physical effects. This irritated a lot of physicists in the 1980s. After all, quantum mechanics describes a collection of physical effects, and a computer is a purely physical device. If simulating these effects on a computer is so hard, why don't we build computers which take advantage of these same effects?

It is from this question that the subject of quantum computing arose. Over the following thirty years, many people have researched what problems quantum computers might be able to solve better than our current machines, from cryptographic attacks to simulation and even machine learning. Alongside this research, groups have been working around the globe to try and build large quantum computers.

But we are jumping the gun here. It's nice seeing the developments of quantum computers, but first we need to understand what a quantum computer actually is. We shall answer this question by comparing it to a classical computer, such as the machine you're reading this on. Fundamentally, a classical computer has two parts to it:

* Firstly, we have data. This data is represented as binary digits, or bits, which can be 0 or 1.

* And secondly, we have operations that we want to apply that data. This is done in the form of logic gates, which take bits as input and produce bits as output.

In quantum computing, we have analogues to these fundamental concepts: We store data in quantum bits, or qubits, and operate on that data using quantum gates. However, there are significant differences between these classical ideas and their quantum versions. For example, quantum bits can, like their classical counterpart, be |0> or |1>. but they can also be in a superposition of these two states, where looking at the qubit might say that it is |0>, or that it is |1>, with some probability.

To learn about these concepts in an active manner, we have given examples and tasks for you to complete using [QCEngine](http://machinelevel.com/qc/), a simulation of a quantum computer that runs in your own web browser developed by [Eric Johnston](http://www.bristol.ac.uk/physics/people/eric-r-johnston/) of the University of Bristol.

The worksheets themselves are divided up into four parts:

* [Part One](https://github.com/djmylt/summer_school/blob/master/programming_a_qc.pdf) will explain the basics of quantum bits and quantum gates, as well as some of their simple applications.
* [Part Two](https://github.com/djmylt/summer_school/blob/master/Summer_School_Lab_Script___Algorithms_Session.pdf) will describe some quantum algorithms that can solve problems faster than possible on classical computers.
* [Part Three](https://github.com/djmylt/summer_school/blob/master/photonic_qc.pdf) will describe how we can implement some of the necessary gates for a quantum computer using linear optics.
* [Part Four](https://github.com/djmylt/summer_school/blob/master/Summer_School_Lab_Script___Superconducting_Session.pdf) will finish off by explaining how you can take the code written from the earlier worksheets and translate it to IBM's [Quantum Experience](https://quantumexperience.ng.bluemix.net/), a quantum computer based on superconducting qubits that anyone can run code on.

While we have written these worksheets to make them friendly for people without programming experience, there are some caveats to take note of. In particular, try to ensure you copy what is given in the code examples closely, as even changing a lowercase letter to an uppercase letter can cause your code to not work. Other than that: make your way through the worksheets; drop us an email if you are stuck or really curious about something; when writing code try to think of what the code might do before running it; and, most importantly, have fun!