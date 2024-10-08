# SortedLinkedList

## Assigned Specifications:
Implement a program that reads a list of Integer numbers from the scanned input and saves them into a Linked List sorted from the smallest to the largest. Be sure to use the Collections Framework and follow code guidelines and document your code accordingly.

## Program Description

Per the assignment, this program created a LinkedList, recieves input from a user, and orders the recieved numbers in ascending order, and stores those numbers into the Linked List.
The program uses the Collections framework.

Sorting functionality, printing functionality, and input functionality are separated into their own encapsulated classes: NumberSorter, NumberPrinter, and NumberInput, respectively.

The NumberProcessor class coordinates the overall process of receiving user input, sorting the numbers, and printing the sorted list. It holds instances of the NumberInput, NumberSorter, and NumberPrinter classes, and calls their respective methods to perform the complete task. 

The UML has been included to help visualize created classes and methods and the relationships between them.

## Running Instructions

This code can be run from the command line with java NumberProcessor
after compiling with: javac NumberInput.java NumberSorter.java NumberPrinter.java NumberProcessor.java

## Documentation Information

Generated JavaDoc folder is included.
This documentation can also be generated withj: javadoc -d doc NumberInput.java NumberSorter.java NumberPrinter.java NumberProcessor.java
