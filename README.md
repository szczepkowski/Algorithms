algorithms-sem2
===============

Harris Ross Algorithms from beginning
=======
Algorithms
==========

Harris,Ross - Beginning Algorithms 

J2SE, JUnit, Eclipse

Project is based on book cited upper. It's its my own implementation of Data Structures like : ArrayList,LinkedList,Set,Map and Algorithms like QuickSort, ShellSort, BinarySearch.

I've learned here one of Agile methodology which is : Test-Driven Delevopment.

Every Class is made in same instructions :

1. Make JUnit test. Test all functionality that your Class should have. Test all method's which in fact doesn't exist's.
2. Make desired Class or Package.
3. Test until your Class will pass all JUnit test's.


One of more interesting subProject ? Lesson3.CallCenter

This subProject use one of Design Patterns called : Factory.

It's show functionality of BlockingQueue in CallCenter.
There is Factory Class called CallGenerator which generates Call objects.

Call are putted to BlockingQueue which have some maximum size. When Queue is full there is no exception but Queue wait until some object will be dequeued.

At the end of Queue there are 3 Constultants runned in multithread. Every Call has some small random time remaining. If Consultant realized Call he gets another.

Application have some time remaining - it must end one day.
