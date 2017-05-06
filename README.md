# UMLSequenceParser

UML SequenceParser utilize AspectJ and Plantuml to draw the sequence diagram.

UML SequenceParser is used to create UMLSequence Diagram given the java files.
The java files has a main.java and should be put into the src folder. In the SequenceDiagram folder, it includes the AspectJ file (SequenceTracer.aj)- which is aspect-oriented programing, that is called automatically during the execution of a program like a method call. Then the AspectJ file adds a string that fits plantuml input string format and creates a sequence diagram.

To run it with the given example:
git clone https://github.com/anna199/UMLSequenceParser.git

java -jar UMLSeqParser.jar

To run it with other file example:
include other examples in the src and add AspectJ.jar and Plantuml.jar into the library build path. Then run the main.java

Then the UMLSequenceParser.png will be created.