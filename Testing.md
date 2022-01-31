# Testing

### tools
  test runner: allows you to organize tests
    mocha

  assertion library: variety of functions that test values for equality
    node assert, chai

  mocking: create a test double of production code libraries
    sinon

### philosophy

TDD:
  - test the public methods of the class

BDD:
  - test the behaviour of the class


===
  ---
  jest: test runner, assertion library, mocking
    - optimized for large numbers of tests
    - configurable output
    - much easier mocking setup
    cons:
      - complexity of setup and configuration

---
    debugging:
      isolate
      investigate
      eliminate


  /*
  bug replacing all the html instead of just the text portion of the li
    isolate:
      view.js:75
    investigate:
      what does the code actually do? replaces everything
      what we want it to do? replace the text node only
    eliminate:
      discover the root cause

      try out different options
        - children
        node
        // firstchild
   */

  /*
  The DOM Node interface is an abstract base class upon which many other DOM API objects are based, thus letting those object types to be used similarly and often interchangeably. --- Liskov Substitution 
   
   As an abstract class, there is no such thing as a plain Node object. --- what an abstract clas is
   
    All objects that implement Node functionality are based on one of its subclasses. Most notable are 
  Document, Element, and DocumentFragment.

  DOM
  DOM Node -
    - its what we are reading about. we dont understand it yet

  DOM Node interface
    "is an abstract base class"

  abstract class:
    - the only thing you can do to an abstract class is inherit it
    - no objects of this class type can exist

  base class:
    - the very first parent class. it does not derive from anything

  class: 
    - a class is a blueprint
    - a class creates objects using that blueprint
    - there can be numerous objects that the class stamps out
    - a class can inherit from a parent class
    - the very first parent is the base class





  terminology:
    class
    inheritance
    base class
    abstract class
    class interface
    the four pillars of oop
    
  */