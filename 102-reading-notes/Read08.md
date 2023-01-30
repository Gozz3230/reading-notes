### Assigning to Properties:

```
const obj = {};

obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj[key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5 }.
```

The left hand side of an assignment expression is able to make assignments to properties of that expression as shown above.

Assignments are typically used within a variable declaration.

The result value is typically not used, however, this allows the result value to be used by another expression.

Chaining assignments or nesting assignment can result in behavior that is unexpedted. This is why JavaScript guides discourage it. Sometimes assignment chaining and nesting occurs so it is still important to understand it.

**Bitwise Operators** treat their operands as a set of 32 bits(zeros and ones). An example of this would be that nine has a binary representation of 1001. If you are familiar with networking technologies you may remember IP addresses as being binary representations such as 192.168.1.1 which equates to 11000000.10101000.00000001.00000001 in binary. The way this is converted is as follows:
x.x.x.x  each x is 8 bits. 1 is on and 0 is off. if all 8 bits are on it is as such: 11111111 which is equal to the numberic value of 255.
 If this confuses you, don't worry about it. But if you are familiar with this, it may help in your understanding. 



