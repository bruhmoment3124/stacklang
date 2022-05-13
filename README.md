## keywords
### stack manipulation:

``` push ```: 

**push a value (numbers, string literals, characters) onto the top of the stack.**

``` pop ```: 

**pop a value (numbers, string literals, characters) off of the stack.**

``` swp ```: 

**swap the top and next to top values on the stack.**

``` cmp ```:

**compare the top and next to top values, if they are the same push 1, if they are not push 0.**

``` top ```:

**alter the meaning of certain operations, will be described later.**

### blocks:

``` sub ```:

**defines a subroutine.**

``` loop ```:

**defines a loop.**

``` cond ```:

**defines a conditional.**

``` begin ```:

**begins defined blocks.**

``` end ```:

**ends defined blocks.**

``` jmp ```:

**jump to a certain line or in a direction using + or - (I.E, 'jmp +3' jumps three lines forward and 'jmp -3' jumps three lines backward)**

### I/O:

``` put ```:

**outputs the top value of the stack to a buffer.**

``` take ```:

**takes input from a buffer and pushes it onto the top of the stack.**

## operators

``` + - * / ^ % ```:

**perform the operation on the top two values and replace the values with the result, unless top is used.**

``` top ```:

**pushes the result of an operation onto the stack.**
