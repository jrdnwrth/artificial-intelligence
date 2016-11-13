Page 1
======

    add, subtract, multipy, divide
V.S.

    propotional or inversly proportional

### An 'Event'
    
    An event is the *difference* between two states*.

    It is the 'Effect' in a cause-effect relationship.

*collections of variables, and their linked collections (see Combining Events below.)

##### For Example: Consider our particle simulator -

Three events are witnessed which result in a particle turning white:
1. hot and red *and wet*
1. hot and red *and dry*
1. cold and blue and 5 minutes

These all result in a white particle.

Note:
1. The first two examples show that dry or wet does not matter, so it is dicarded.
    * This can be determined statistically.
2. Time is stored at the moment of transition.
    * Both `average` time and `std.dev` and `number_of_samples` could be stored for the statistical model.    

* Start correlations storing every change.
* Trim down what appears unrelated.

###### Combinding *Sequences* of Events
    Series
```
   A       B       C       D
X----> X ----> X ----> X ----> X    
  95%     95%     98%     80%

           becomes
           
              AD
X ---------------------------> X
        75% likelihood

A: Effect labeled 'A'
X: States (collections of properties and linked collections)
t: Store frequently successive sequences of events as a new event containing
the collection of sub events.
```
    
##### Combining *Concurrent* Events
    Parallel
```
    A
X ----> X
    B
X ----> X
    C
X ----> X
    D
X ----> X

becomes

    E
X ====> X

Store simultaneous events as a single event containing a *collection* of sub events.
```
This allows for abstract application. For example: 

>*(1) Close proximity to a flame* statistically shows (2) an increase
>in the temperature property.

1. Property Collection
2. Event
