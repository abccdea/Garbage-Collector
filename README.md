## CppND-Garbage-Collector
The final project for this Memory Management course is to implement your own version of a smart pointer. You can think of this as implementing your own garbage collector, to use a concept from other programming languages. Building this project will help you understand both how to work with pointers and references, and also why smart pointers are so important to modern C++ programming. Complete the implementations and verify that your implementation does not have any memory leaks!

## Project TODO List:
- Complete `Pointer` constructor

Hints from peer students:
1. To implement the GC Pointer constructor, you need to create a PtrDetails object, and add it to the refContainer list. You also need to initialize Pointer member variables (addr, isArray and arraySize). Then you can create an iterator, findPtrInfo for the address, and increment the refcount. (by Levente H)

- Complete `Pointer` `operator=`

Hints from peer students:
1. You also have to check if this Pointer is already in the refContainer because it might have been initialized with another value or assigned another value before. (by Manfred K)

- Complete `Pointer` destructor
- Complete `PtrDetails` class


Thanks to all the classmates that provided valueble hints, which made this course not that dissappointing. 
