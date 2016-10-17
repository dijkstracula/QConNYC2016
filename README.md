# Beyond Breakpoints: A Tour Of Dynamic Analysis 

## Abstract
> Despite advances in software design and static analysis techniques, software remains incredibly complicated and difficult to reason about. Understanding highly-concurrent, kernel-level, and intentionally-obfuscated programs are among the problem domains that spawned the field of dynamic program analysis. More than mere debuggers, the challenge of dynamic analysis tools is to be able record, analyze, and replay execution without sacrificing performance. This talk will provide an introduction to the dynamic analysis research space and hopefully inspire you to consider integrating these techniques into your own internal tools.

## Presentation materials

* [Slides](https://github.com/dijkstracula/QConNYC2016/blob/master/presentation.pdf) | [Slides w/ speaker notes](https://github.com/dijkstracula/QConNYC2016/blob/master/pres_with_notes.pdf)
* [Video](https://www.infoq.com/presentations/dynamic-analysis-tools)

## Dynamic Analysis Tools / Source Code

* [GDB Reverse Debugging](https://www.gnu.org/software/gdb/news/reversible.html)
* [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool)
* [Valgrind](http://valgrind.org)
* [ReVirt](http://web.eecs.umich.edu/virtual/software.html)
* [ThreadSanitizer](http://clang.llvm.org/docs/ThreadSanitizer.html)
* [librip](https://github.com/fastly/librip)

## Supplimental Papers

### Overview, Dynamic Analysis, and Tools

* [The Concept of Dynamic Analysis](http://research.microsoft.com/en-us/um/people/tball/papers/fse-concept.pdf)
* [The Night's Watch](scholar.harvard.edu/files/mickens/files/thenightwatch.pdf)
* [Framework for Instruction-level Tracing and Analysis of Program Executions](https://www.usenix.org/legacy/events/vee06/full_papers/p154-bhansali.pdf)

* [Vx32: Lightweight, User-level Sandboxing on the x86](https://pdos.csail.mit.edu/papers/vx32:usenix08/)
* [QEMU: A Fast and Portable Dynamic Translator](http://archives.cse.iitd.ernet.in/~sbansal/csl862-virt/2010/readings/bellard.pdf)
* [Pin: Building Customized Program Analysis Tools with Dynamic Instrumentation](http://www.cs.virginia.edu/kim/courses/cs851/papers/luk05pin.pdf)
* [Valgrind: A Framework for Heavyweight Dynamic Binary Instrumentation](http://valgrind.org/docs/valgrind2007.pdf)

### Time-Travel Debugging, Record & Replay, and Taint Analysis

* [Design and Implementation of a Backwards-In-Time Debugger](http://www.marcusdenker.de/publications/Hofe06aUnstuckNode.pdf)
* [Debugging Through Time with the Tralfamadore Debugger](http://www.dcs.gla.ac.uk/conferences/resolve12/papers/session4_paper1.pdf)
* [Scalable Omniscient Debugging](http://pleiad.dcc.uchile.cl/papers/2007/pothierAl-oopsla2007.pdf)

* [ReVirt: Enabling Intrusion Analysis through Virtual-Machine Logging and Replay](https://cse.umich.edu/cse/awards/pdfs/ReVirt.pdf)
* [Debugging Operating Systems with Time-Traveling Virtual Machines](https://www.usenix.org/legacy/event/usenix05/tech/general/king/king.pdf)

* [Understanding Data Lifetime via Whole System Simulations](http://benpfaff.org/papers/taint.pdf)
* [Pointless Tainting? Evaluating the Practicality of Pointer Tainting](http://ssrg.nicta.com.au/publications/papers/Slowinska_Bos_09.pdf)

### Multiprocessor Replay and Race Detection

* [Time, Clocks, and the Ordering of Events in a Distributed System](http://research.microsoft.com/en-us/um/people/lamport/pubs/time-clocks.pdf)
* [A "Flight Data Recorder" for Enabling Full-System Multiprocessor Deterministic Replay](https://minds.wisconsin.edu/handle/1793/8664)
* [Execution Replay for Multiprocessor Virtual Machines](http://web.eecs.umich.edu/virtual/papers/dunlap08.pdf)
* [PRES: Probabilistic Replay with Execution Sketching on Multiprocessors](http://www.cs.columbia.edu/~junfeng/12fa-e6121/papers/pres.pdf)
* [ODR: Output-Deterministic Replay for Multicore Debugging](www.sigops.org/sosp/sosp09/papers/altekar-sosp09.pdf)
* [Hardware-Assisted Replay of Multiprocessor Programs](http://www.cs.cmu.edu/~seth/papers/bacon-wpdd91.pdf)

* [Eraser: A Dynamic Data Race Detector for Multithreaded Programs](http://homes.cs.washington.edu/~tom/pubs/eraser.pdf)
* [Hybrid Dynamic Data Race Detection](http://www.cs.columbia.edu/~junfeng/10fa-e6998/papers/hybrid.pdf)
* [ThreadSanitizer – data race detection in practice](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/35604.pdf)
* [FastTrack: Efficient and Precise Dynamic Race Detection](https://users.soe.ucsc.edu/~cormac/papers/pldi09.pdf)

## Photo Credits

* ["Sherlock" (CC BY-NC 2.0)](https://www.flickr.com/photos/zufallsfaktor/12352262723/)
* [Cover, "Conan Doyle's best books, in three volumes. V.I."](https://archive.org/details/conandoylesbestb00doyl)

## Licences

* [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/)

## Special thanks

* [Elaine Greenberg](https://twitter.com/ejgreenberg)
* [Devon O'Dell](https://twitter.com/dhobsd)
* [Frederik Deweerdt](https://github.com/deweerdt)
* [Jerry Kuch](https://twitter.com/jerrykuch)
* [Mihir Nanavati](http://www.cs.ubc.ca/~mihirn/)
* [Ines Sombra](https://twitter.com/randommood)
* [Andy Warfield](https://twitter.com/andywarfield)
