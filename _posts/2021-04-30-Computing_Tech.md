---
layout: post
category: blog
title: Emerging Computing Techniques with Artificial Intelligence
tagline: This post details new computing styles (High Performance, Neuromorphic, and Quantum Computing) and discusses their relevance to AI.
permalink: /blog/computing_tech
excerpt_separator: <!--more-->
author:
  name: Dillon Ranwala
  email: "dranwal@clemson.edu"
image: assets/img/2021-04-30-Computing_Tech/title_image.jpg
---

The proliferation of artificial intelligence (AI) technologies in recent
decades has been pushing the limits of our computing architectures. AI
technologies have expanded rapidly into research and business domains
with continual improvements in efficiency and effectiveness.
Nevertheless, the swift growth of this technology is already pushing the
limits of classical computing architectures, and eventually, we may
reach a point where the needs of complex AI systems will exceed the
current resources of our hardware and computing systems. Even as these
current AI systems and algorithms have grown in complexity and
resource-intensiveness, they continue to operate on the traditional
computer systems that we are familiar with. Even as we move into the
cloud and decentralized systems, the underlying hardware and algorithms
of our AI computing systems remain fairly unchanged.

<p align="center">  
<img height = "450" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/statista_graph.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Image by Statista.</i>
</p>
<br/><br/> To meet the growing computational demands of AI, businesses
and researchers alike have been investing in emergent technologies based
in High Performance, Neuromorphic, and Quantum computing. These
computing areas have the potential to not only to alleviate
computational shortcomings but also to provide structures for new
innovations to grow. Before analyzing how these new computing styles can
revolutionize AI, we should understand the limitations of current
systems.

Building AI From Classical Computing
------------------------------------

Most of our computer architecture falls under the umbrella of 'classical
computing' which is the traditional computing approach involving binary
logic and what is known as the von Neumann architecture. Nearly every
modern computer utilizes this basic architecture which involves multiple
physically disconnected functional parts that are connected by data
paths. The physical disconnect between parts like memory and CPU
requires information to be repeatedly transferred between the units, but
allows them to have their own specialized functions. By following this
structure, our ecosystem of computing devices consist of many universal
machines that are similar enough to deploy the high-level programming
languages that are the basis for modern AI systems.

<p align="center">  
<img height = "300" width = "450" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/basic_structure.png?raw=true" alt="Image">
</p>
<p align="center"> 
<i>A basic Von Neumann Architecture. Image by GeeksforGeeks.</i>
</p>
<br/><br/>

Despite the immense progress built upon classical computing that has led
to the current state of AI, the increasing complexity of some machine
learning algorithms can demand too much of our von Neumann
architectures. This problem is described as the ‘von Neumann bottleneck’
which occurs when the performance of our systems becomes limited by the
speed of accessing memory. Memory access speed is much slower than
processing speeds, and due to the need to shuttle information across
data paths, this causes the processors in our systems not to work
efficiently. Also, the need to physically move memory between our units
creates heavy energy consumption. Multithreading and parallel processing
have mitigated these problems somewhat, but in order to truly surpass
this bottleneck, completely new hardware chips and memory processing may
be needed.
<p align="center">  
<img height = "300" width = "550" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/bottleneck.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Image by Android Authority.</i>
</p>
<br/><br/> AI in particular demands a lot of memory usage to train
machine learning models, so this bottleneck can be a limiting factor for
high-level AI tools. Furthermore, Stanford University
<a href="https://www.computerweekly.com/news/252475371/Stanford-University-finds-that-AI-is-outpacing-Moores-Law">has
found </a> that the growth of AI has surpassed the growth of processing
speeds outlined by Moore’s Law. These constraints have led to
developments in new computing styles that can incorporate AI systems
more efficiently, the most accessible being High Performance Computing.

High performance computing (HPC)
--------------------------------

One of the more concrete developments in recent decades that have
alleviated some of the shortcomings of classical computers is High
Performance computing (HPC). HPC involves the development of new
hardware for computer systems that are built to handle more intensive
and complex activities. Specifically, this involves utilizing parallel
processing and supercomputers to meet the demand for higher processing
speeds. This new hardware is built upon the familiar components of
classical computers (CPU, RAM, memory, etc.), but greatly increases the
number of components and organizes these systems into optimized, in-sync
clusters that are connected to each other. These large-scale systems can
compute, communicate with each other, and store data as needed.
<p align="center">  
<img height = "425" width = "600" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/hpc_example.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Example devices and servers for a HPC system. Image by Accolade
Technology.</i>
</p>
<br/><br/>

This hardware when used in combination with AI software, allows for
performance of the necessary calculations at much faster speeds than any
isolated, classical systems. It is important to note that HPC keeps the
von Neumann architectures we know, but makes them faster, more
efficient, and more accessible through the use of thousands of CPUs/GPUs
and cloud platforms. By using these large-scale centers for AI training
and deployment, HPC can store, process, and output considerable amounts
of data at an exceptional speed. However, HPC still relies on the
traditional computer principles that have been used for decades and
while it alleviates some issues with the costs of AI technologies, it is
still a question if these architectures are going to be sufficient for
the most complex AI networks.
<p align="center">  
<img height = "400" width = "550" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/hpc_lab.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>GE's high performance computing lab in Niskayuna, NY. Image by
General Electric.</i>
</p>
<br/><br/>

Neuromorphic Computing
----------------------

Beginning in the early 90s, researchers investigated the potential for
computers inspired by biological nervous systems that could mimic such
behaviors of organisms as image/speech recognition tasks that our
traditional computing systems had trouble with. From this early
research, we have seen the rise of artificial neural networks that can
explore new tasks. However, the resulting deep learning neural networks
have grown to demand massive amounts of computational resources for
training. For example, the GPT-3 developed by OpenAI is currently one of
the most prolific machine learning language models which is capable of
high-level text generation. This 175-billion-parameter neural network
requires roughly \$12 million and needs around 3.114E23 floating-point
operations to train (which would take centuries to compute on a normal
GPU server). As our AI models continue to push the limits of classical
hardware, the need for more power-efficient, spontaneous computing
devices has led to developments in Neuromorphic computing.

<p align="center">  
<img src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/spiking_neuron.png?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Multiple neurons communicating with a spiking neuron to output a
single encoding. Image by Navin Anwani and B. Rajendran.</i>
</p>
<br/><br/>

These systems involve the creation of artificial neurons based upon the
neurons of the human brain. They try to mimic the brain through spiked
neural networks (SNNs) where one of these artificial neurons 'spikes’
and sends an electric signal to other neurons. These signals contain
encoded information based on the electrical state and the timing of the
spikes. What is unique about these spikes is that the information is not
stored in the traditional binary sense (0 or 1) but can represent a
range of values in between. This interaction between neurons in a
neuromorphic chip more closely resembles the human brain than any
classical computing device. Furthermore, these neurons save power by
only working when spiked. Altogether, neuromorphic devices have the
potential to support AI applications that involve more complex problems
and unstructured data including higher-level interpretation and
adaptation.

Click here for an quick introduction to a neuromorphic chip
<a href="https://www.youtube.com/watch?v=gXNCz26UhyY">(Intel’s
Loihi)</a>

By transitioning to this new architecture, AI systems can potentially
benefit from computational and energy efficiency. A single SNN neuron
can replicate the efficiency of hundreds of traditional neural networks
as not all neurons have to fire every time. Moreover, neuromorphic chips
show promising results in unsupervised learning problems by learning
quickly without many examples. Based on the SNN architecture, we could
see higher response times and quicker training speed than our current
deep learning models. Most importantly, these chips have no von Neumann
bottleneck as the communication between neurons is much more streamlined
and responsive to each other.

<p align="center">  
<img height = "250" width = "800" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/classical_vs_neuro.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Differences between classical and neuromorphic architectures. Image
from Faraday Discussions Journal.</i>
</p>
<br/><br/> While HPC systems are currently more established,
neuromorphic systems are rising in production and already have some
real-world applications. For instance, neuromorphic devices can
revolutionize smart devices and edge computing. Smart devices like home
appliances and industry equipment utilize AI methods for decision
making, speech recognition, and more, but these devices must be run from
a remote data center. To run these low-power devices and supply enough
energy for power-demanding AI applications, neuromorphic chips and SNNs
can be deployed. These devices save energy and can continually process
data (without the need to transfer to a remote center) and learn from
this data using the unique capabilities of the neuron’s architecture.
<p align="center">  
<img height = "350" width = "800" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/edge_computing.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Current edge computing process, neuromorphic chips can expedite this
communication process and save energy. Image from SemiConductor
Engineering.</i>
</p>
<br/><br/> The upside of SNNs lies in the fact that they can work with
the same efficiency of some HPC supercomputers while being much easier
to implement on widespread systems. The spontaneous firing systems of
SNNs can bring unique learning capabilities for unsupervised learning
and reinforcement learning algorithms. One concrete example of this
technology lies in autonomous vehicles which could utilize neuromorphic
chips to process image data in real-time. SNNs could operate quicker and
not need to communicate with some remote server location to facilitate
efficient autonomous vehicle functions like object detection and image
segmentation.
<p align="center">  
<img src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/neuron.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Neuromorphic chips similarities to biological systems. Image from
Yole Développement.</i>
</p>
<br/><br/>

While neuromorphic systems show promise for the future, their current
state has some limitations before they can become widely used.
Primarily, the way data is encoded and processed is different from the
von Neumann system (bits vs a neuron’s range of values), so we will need
to create new programming languages or libraries to fully harness the
potential of a neuromorphic chip. Due to this challenge, there is not an
optimal way to train SNNs for general machine learning purposes as
training requires a lot of data pre-processing and hyperparameter
tuning. Gradient descent which is utilized by current neural network
architectures does not work with spiking neurons as the information
encoded in their signals are non-differentiable. Consequently, current
systems rely on transfer learning, but will need more specialized
training procedures in the future.

Quantum Computing
-----------------

Another emerging computing style that has the potential to transform our
machine learning systems is quantum computing. The allure of this
technology lies in the fact that a problem that any classical computing
problem can be solved by a quantum computer while quantum systems
provide another level of computation that can transform our current
machine learning algorithms. The basis of this computing style lies in
its unique information storage process and its underlying architecture.

Click the image for a quick introduction to
<a href="https://www.youtube.com/watch?v=-ZNEzzDcllU"> quantum computing
and its potential power.</a>

While our classical machine learning systems utilize long strings of
bits (binary state of either a 0 or 1), quantum systems utilize what are
known as qubits which can exist as both a 0 and 1 or exist in a
‘superposition’ between the two.

<p align="center">  
<img height = "300" width = "350" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/superposition.png?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Image from Jeff Hecht - LaserFocusWorld.</i>
</p>
<br/><br/> We can leverage the power of these qubits to gain huge
amounts of processing power to more efficiently begin solving some of
these problems that have traditionally been locked behind exorbitant
computational needs or non-conventional data sets (those that pose a
unique challenge to a bit-centered logic). As our qubits can be in
multiple states, we can perform many tasks simultaneously while checking
all possible permutations needed. Before developing completely new
Quantum AI, the initial incorporation of quantum computing into our
current machine learning landscape will result in greater efficiency in
our current AI programs in what is known as Quantum Machine Learning.
This paradigm involves the combination with our familiar machine
learning programs and datasets with quantum algorithms to improve speed
and data storage needs.

<p align="center">  
<img src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/pipeline.png?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Abstract pipeline for training of a quantum-based discriminator model
with many similarities to the classical training process. Image by
Google</i>
</p>
<br/><br/>

For instance, the training of neural networks involves a wealth of
matrix multiplications and moving data for weights which must be kept in
storage, but by using a quantum algorithm we can train supervised
learning models like linear regression, support vector machines, and
gaussian process using the states of the qubits for more compact
encodings of a state’s outputs and inputs. Furthermore, for
reinforcement learning applications, some quantum agents can interact
with traditional environments and encode their qubits in a superposition
(as opposed to a 0 or 1) to more quickly adapt by reacting to multiple
states at once. As a whole, quantum computers are exceptionally suited
for optimization problems which translates to traditional stochastic
gradient descent algorithms for deep learning.

One specific case where quantum systems have already been implemented
can be seen by a group of AI researchers from Aston University in
Birmingham, UK where they investigated the effects of quantum random
number generators (QRNGs) on convolutional neural networks (CNNs) and
random forest classifiers. When utilizing QRNGs over traditional RNGs to
randomize the initial weight distributions for CNNS and for tree
generation in Random Forest, there was a noticeable difference in
performance. The implications of their findings show some promise in the
potential for true randomness derived by quantum systems (even though it
does not always result in greater accuracy) as pure randomness is
impossible to reach for classical RNGs.
<p align="center">  
<img height = "300" width = "400" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/qrng1.png?raw=true" alt="Image">
<img height = "300" width = "400" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/qrng2.png?raw=true" alt="Image">
</p>
<p align="center"> 
<i>Performance of models using quantum RNGs (True Random) vs normal RNGs
for different classification tasks. Image by Jordan J. Bird, Anikó Ekárt
and Diego R. Faria </i>
</p>
<br/><br/>

Surprisingly, there are already quantum AI systems being used for
business applications right now. Some of these initial products are
powered by D-Wave Systems’ quantum computers (the first commercially
available quantum infrastructure). Since 2010, Lockheed Martin has been
employing quantum processors for aerospace modeling to test all possible
permutations for routing and scheduling of flight plans. Similarly, the
Quantum Artificial Intelligence Lab (QuAIL) is a joint effort between
NASA, the Universities Space Research Association, and Google that
utilizes D-Wave next generation quantum systems for a variety of machine
learning and optimization problems.
<p align="center">  
<img height = "300" width = "350" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/dwave.jpg?raw=true" alt="Image">
 </p>
<p align="center"> 
<i>One of D-Wave's 1000 qubit processors. Image by D-Wave Systems</i>
</p>
<br/><br/>

Click here for more information about
<a href="https://ti.arc.nasa.gov/tech/dash/groups/quail/"> QuAIL </a>
Click here for more projects using
<a href="https://www.dwavesys.com/applications"> D-Wave Quantum Systems
</a>

Some of the problems that classical AI optimization algorithms struggle
with involve speech/recognition and the traveling salesman problem. This
is due to needing to check every possible answer or path which can
quickly grow inefficient and resource consuming. However, quantum AI
systems excel at these optimization problems as they can use
superposition to check all possible answers at the same time, instead of
one-by-one. We can see this in practice with Volkswagen's attempts to
find the shortest possible routes based on real-time traffic data using
quantum algorithms.
<a href="https://www.volkswagen-newsroom.com/en/press-releases/volkswagen-optimizes-traffic-flow-with-quantum-computers-5507">
Their trial </a> of nine buses which followed these ‘Quantum Routing’
paths were successfully able to avoid traffic jams.
<p align="center">  
<img height = "400" width = "700" src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/volkswagon.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>One of the routes showing traffic jams and bus locations. Image by
Volkswagen Group.</i>
</p>
<br/><br/> As a whole, quantum AI systems can provide a efficiency boost
to our current machine learning algorithms by reducing the time needed
to perform brute-force searches and mass vector calculations. Moreover,
they can handle large datasets and pick out small patterns and can
perform better with incomplete datasets, all due to the unique states of
qubits. We have not yet seen completely novel Quantum AI, but by
building from this new quantum infrastructure, we may see a new
generation of hyper-efficient AI models. <br/><br/> Nevertheless, more
research and experimentation is needed before we can reach widespread
quantum artificial intelligence. On the hardware side, quantum computers
are still hard to develop and maintain due to difficulties in keeping
all qubits in a coherent state with environmental interference and other
degradation when scaling up to more than 100 qubit systems. Similar to
neuromorphic computing, quantum systems also need different programming
languages or development kits to properly use qubits. However, there has
already been some progress here with Google’s TensorFlow Quantum library
and IBM’s open source SDK named Qiskit. Lastly, there are no completely
quantum-based AI algorithms that perform tasks better than a classical
algorithm. The development of these quantum algorithms will follow as
the accessibility to quantum computers and knowledge of the power of
qubits grow, but we currently lack any fully quantum applications to
test the depth of this technology.

Hybrid systems
--------------

<p align="center">  
<img src="{{site.url}}/assets/img/2021-04-30-Computing_Tech/hybrid.jpg?raw=true" alt="Image">
</p>
<p align="center"> 
<i>An example ultra-hybrid deep learning system. Image by Oak Ridge
National Lab.</i>
</p>
<br/><br/>

While each one of the three computing styles show promise for pushing
the scope of modern AI, our future systems may benefit from a more
holistic approach to these emerging disciplines. While High Performance
Computing is the most fleshed out system that is immediately applicable
to current machine learning code and algorithms, they require a high
cost to create and maintain these large-scale servers. Conversely,
neuromorphic and quantum computing have some basic hardware solutions
already, but none that have been in widespread production. Also, to
harness the complete power of these two systems, we will have to adjust
some of our programming languages to work alongside the complete
potential of spiking neurons and qubits. As all these systems progress,
the future of AI may look like a combination of bits, neurons, and
qubits that can specialize in a single device or pipeline to solve
complex problems.
