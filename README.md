# DELAYS OF PUBLIC TRANSPORT PROJECT

## DESCRIPTION :memo:
This is a simply process communication project focused on learning some C# features like:
* IEnumerable,
* Generics and covariant,
* Attributes,
* LINQ,
* Asynchronous programming by using async and await,
* Regular expressions,
* IDisposable,
* Synchronization primitives (in my case Monitor).

## WHAT THIS PROJECT DOES :question:

Project was created in two-person team to complete classes at the Military University of Technology.
The project consists of two processes. The first one is the passenger process where the user can select the means of transport 
that he is interested in, the line number, etc. 
The second process is the process of the transport system. After getting inforamtions from the user this procces calculate the delay of choosen tranpsort 
including random delays and during the ride and send answer to passenger.
The time is also random and cannot be choose by the user.
In addition each mean of transport has diverent hours of work for example all buses rides from 6:00 AM to 12:00 PM.
communication between two processes is done through files which are deleted by using IDisposable interface.

## TECHNOLOGIES :satellite:
* .Net 6.0
