# Computer Science

scalar: one piece of data. eg: integer, float, one letter (character)
data group: multiple scalars grouped together.
  c, c++: struct
  ```c
  struct Person {
    char name[50];
    int citNo;
    float salary;
  };
  ```
  js: object
  ```javascript
  const Person = {
    name: '',
    citiNo: 1,
    salary: 12.00,
  }
  java: POJO
  ```java
  public class Person {
    public String name;
    public int citiNo;
    public int salary;
  }
  ```

data structure: the individual items (elements) of these data structures are called nodes
  priority queue
  red-black tree

OOP:
  is-a relationship
    TodoItem is-a NestedTree
    everything that is-a NestedTree has the same methods()
    therefore they can be substituted for each other

    Another way of saying this...
    Every subclass of NestedTree is-a NestedTree
    Liskov Substitution: Every subclass should work in a function where the superclass works.

  has-a relationship

### todo

