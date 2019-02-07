# distributed-systems-exercises

A list of programming exercises for Distributed Systems, inspired by reading lists like [awesome-distributed-systems](https://github.com/theanalyst/awesome-distributed-systems), but with a more practical focus.

The exercises are taken from various university courses on Distributed Systems. I don't plan to follow the instructions exactly as given - they may rely on tools that aren't available outside the university, and they use a variety of languages where I'd prefer to stick to one or two. However, I still find them useful to provide a bit more structure to each task.

## MapReduce

#### Exercises

* [MapReduce](https://github.com/Columbia-COMS-4113-Fall-18/assignments/blob/master/instructions/Assignment1.md), Columbia University, Go
* [Sequential Map/Reduce](https://www.cs.princeton.edu/courses/archive/fall16/cos418/a1.html) and [Distributed Map/Reduce](https://www.cs.princeton.edu/courses/archive/fall16/cos418/a2.htmle), Princeton University, Go

#### Reading

* [Can Your Programming Language Do This?](https://www.joelonsoftware.com/2006/08/01/can-your-programming-language-do-this/)
* [MapReduce: Simplified Data Processing on Large Clusters](http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
* [The Elephant was a Trojan Horse: On the Death of Map-Reduce at Google](https://www.the-paper-trail.org/post/2014-06-25-the-elephant-was-a-trojan-horse-on-the-death-of-map-reduce-at-google/) from [The Paper Trail](https://www.the-paper-trail.org/) (see also [Hacker News discussion](https://news.ycombinator.com/item?id=7947782))

## Time and clocks

#### Exercises

* Part 1 of [Vector clocks and causal multicast](https://www.cs.helsinki.fi/u/jakangas/Teaching/DSP-11/DSP-Assignment2.pdf), University of Helsinki
* [UDP-based time synchronization client](https://courses.cs.washington.edu/courses/csep552/13sp/assignments/a1.html), University of Washington

#### Reading

* [Chapter 3: Time and Order](http://book.mixu.net/distsys/time.html) from [Distributed systems for fun and profit](http://book.mixu.net/distsys/)
* [Time, Clocks, and the Ordering of Events in a Distributed System](https://amturing.acm.org/p558-lamport.pdf) - the original Lamport paper
* [Vector clock](https://en.wikipedia.org/wiki/Vector_clock) (Wikipedia)
* [Why Vector Clocks are Easy](http://basho.com/posts/technical/why-vector-clocks-are-easy/) / [Why Vector Clocks are Hard](http://basho.com/posts/technical/why-vector-clocks-are-hard/) - 2 articles from Basho Technologies, the makers of [Riak](http://basho.com/products/riak-kv/)
* [Internet Time Synchronization: the Network Time Protocol](https://www.rfc-editor.org/rfc/rfc1129.pdf)

## Two-phase commit

#### Exercises

* [Two phase commit](https://courses.cs.washington.edu/courses/csep552/13sp/assignments/a2.html), University of Washington

#### Reading

* [Chapter 4: Replication](http://book.mixu.net/distsys/replication.html) from Distributed systems for fun and profit
* [Concurrency control and recovery in database systems](https://courses.cs.washington.edu/courses/cse551/09au/papers/CSE550BHG-Ch7.pdf)
* [Consensus Protocols: Two-Phase Commit](https://www.the-paper-trail.org/post/2008-11-27-consensus-protocols-two-phase-commit/) from The Paper Trail

## Paxos / Raft

#### Exercises

* [Paxos-based Key/Value Service](https://columbia.github.io/ds1-class/homeworks/Assignment3/), Columbia University, Go
* [Raft Leader Election](https://www.cs.princeton.edu/courses/archive/fall16/cos418/a3.html) and [Raft Log Consensus](https://www.cs.princeton.edu/courses/archive/fall16/cos418/a4.html), Princeton University, Go

#### Reading

* [Paxos made simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) - not the [original paper](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf), because no one understood that, but the next one
* [Paxos Made Live: An Engineering Perspective](https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf)
* [Consensus Protocols: Paxos](https://www.the-paper-trail.org/post/2009-02-03-consensus-protocols-paxos/) from The Paper Trail
* [The Raft Consensus Algorithm](https://raft.github.io/)
* [Raft: Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/) (visualization)

## Filesystems

#### Exercises

* [Labs 0 - 5](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-824-distributed-computer-systems-engineering-spring-2006/labs/), MIT OCW, C 

#### Reading

* [Files are hard](http://danluu.com/file-consistency/) - blog post on filesystem consistency
* [Frangipani: A Scalable Distributed File System](https://pdos.csail.mit.edu/6.824/papers/thekkath-frangipani.pdf)
* [The Google File System](http://static.googleusercontent.com/media/research.google.com/en/us/archive/gfs-sosp2003.pdf) - the original paper
* [The Google File System](https://www.the-paper-trail.org/post/2008-10-01-the-google-file-system/) from The Paper Trail

## Key-value stores

#### Exercises

* [Sharded Key/Value Service](https://columbia.github.io/ds1-class/homeworks/Assignment4/), Columbia University, Go
* [Key-Value Storage Service](https://www.cs.princeton.edu/courses/archive/fall16/cos418/a5.html), Princeton University, Go

#### Reading

* [Chapter 5: Replication: weak consistency model protocols](http://book.mixu.net/distsys/eventual.html) from Distributed systems for fun and profit
* [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
* [BigTable: Google's Distributed Data Store](https://www.the-paper-trail.org/post/2008-10-29-bigtable-googles-distributed-data-store/) from The Paper Trail
* [Dynamo: Amazon’s Highly Available Key-value Store](http://bnrg.eecs.berkeley.edu/~randy/Courses/CS294.F07/Dynamo.pdf)
* [Spanner: Google's Globally-Distributed Database](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-16.pdf)

## P2P

#### Exercises

* [Implement a P2P client](https://courses.cs.washington.edu/courses/csep552/13sp/assignments/a3.html), University of Washington
* [Tribbler](https://github.com/cmu440/p2) (no instructions, source only), Carnegie Mellon University, Go
* [Gossiping with PeerSim](https://www.uio.no/studier/emner/matnat/ifi/INF5040/h12/group/fourthassignment.pdf), University of Oslo, Java

#### Reading

* [Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf)
* [Do incentives build robustness in BitTorrent?](http://sing.stanford.edu/cs303-sp11/papers/BitTyrant.pdf)
* [Democratizing Content Publication with Coral](https://courses.cs.washington.edu/courses/csep552/13sp/papers/freedman-coral.pdf)
* [A Lightweight, Robust P2P System to Handle Flash Crowds](https://cs.gmu.edu/~astavrou/research/Stavrou2004%20PROOFS.pdf)

