# Software Architecture ft_7 2015-2016
## Lab: Quality Care Robot

For reading and building our code Eclipse Mars should be used with the newest stable release of Java 8.
For comparison we implemented the pipe-filter pattern in a more functional and a more imperative way. Since this code is just an implementation of something that could be used in a real implementation of our system, both implementation are simply in their own Eclipse projects (the complete projects, not just the sources).

Functional:
	src: /dev/src/nl.uva.se.funcpipes

	To run, load the Eclipse project and build; alternatively build all Java source files and run the program.
	The Program.java class holds several functional examples which guide the reader through the functionality of the pipeline.
	In the `functional' pipeline universe, we have:
	  - Pipelines carrying data of some type
	  - Filters, which when given data decide if it should flow through
	  - Functions which modify or replace elements
	  - Functions which transform elements into elements of a different data type
	  - Buffers, which aggregate into a new type

Imperative:
	src: /dev/src/nl.uva.se.imppipes

For running  a complete test, run the main method in Test in a project. For more test options, consult the documentation of the Test class.