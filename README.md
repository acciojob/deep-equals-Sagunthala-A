# Deep Equals

### Write a deepEquals function that takes in two required values and returns if those two values are deeply equal to each other.For the purpose of this problem, deep equality is defined as follows:

- Values with different types are not equal.
- NaN is only equal to NaN
- [null] is only equal to [null], and undefined is only equal to undefined. These values are not equal to each other.
- Arrays are only equal if their entries are deeply equal to each other.
- Objects are equal only if their keys and values are deeply equal to each other (note that the order of the keys doesn't matter).


You can make the following assumptions:

- Functions will never be passed to deepEquals and will never be contained in objects or arrays passed to deepEquals
- Objects will only have string keys, and their values won't be recursive references to themselves.
- The prototype chain doesn't need to be considered when determining if two objects are deeply equal.
