# CodingBatHints
mostly created by Sam Powers


# FinalExamProject
By Sam Powers

## Warmup-1

#### Problem: stringE-
Hint: Try using a for loop to count the number of e's.

#### Problem: front3-
Hint: What string length(s) can you just return as is? Try to create an if statement for those specific lengths, so you don't run into an StringIndexOutOfBoundsException.

#### Problem: backAround-
Hint: Try declaring a variable for the length of the string `int x = str.length() - 1;`. The -1 in the code is necessary if you want to use indexing.

#### Problem: everyNth-
Hint: Declare an empty string and add a character every nth index in a for loop.

#### Problem: mixStart-
Hint: Declare a string to compare to a specific location in the original string. For example `String mix = str.substring(x, y);`.

#### Problem: lastDigit-
Hint: Compare variable "a" % to a specific number and variable "b" % to that same number.

## String-1

#### Problem: withouEnd2-
Hint: You can use an "if" statement to exclude the string if its length is less than or equal to two.

#### Problem: atFirst-
Hint: Use "if" statements to ensure that @ symbols will be used if the string length is 0 or 1.

#### Problem: nTwice-
Hint: `str.substring(str.length() - n);` creates a string from n index to the end of the string.

## Logic-1

#### Problem: dateFashion-
Hint: If you or your date are less than or equal to two, then you are not allowed a table. Example: `if (you <= 2 || date <= 2)`.

#### Problem: specialEleven-
Hint: The `%` or mod operand is used to find the remainder of a number divided by another. So, 10 % 7 would be 3. And 4 % 2 would be 0. You can use the mod operand in this code to see if a number is a multiple of 11 by simply coding something similar to this: 
`if(n % 11 == 0)`.


#### Problem: in1To10-

```java
public boolean in1To10(int n, boolean outsideMode) {
  
  if (outsideMode == _____ && (n ___ 1 && n ___ 10)) {
    return _____;
  }
  
  if (outsideMode == _____ && (n ___ 1 || n ___ 10)) {
    return _____;
  }
  
  return _____;
  
}
```
#### Problem: twoAsOne-

```java
public boolean twoAsOne(int a, int b, int c) {
  
  if (________ || ________ || ________) {
    return ____;
  }
  
  return false;
  
}
```

## Logic-2

#### Problem: makeBricks-
Hint: Think of the two scenarios that would allow makeBricks to be false. One of them is if `goal % 5 > small`, because you do not have enough bricks to extend to the length you would want.

## AP-1

#### Problem: mergeTwo-
Hint: Try the following as the beginning lines of a solution:
```jsva
  String[] output = new String[n];
  int nextA = 0;
  int nextB = 0;
  for(int i = 0; i < output.length; i++) {
    if (a[nextA].compareTo(b[nextB]) < 0) {
```

#### Problem: commonTwo-
Hint: Try the following as the beginning lines of a solution:
```jsva
  int nextA = 0;
  int nextB = 0;
  String found = "";
  while (nextA < a.length && nextB < b.length) {
    if (a[nextA].compareTo(b[nextB]) < 0 || found.contains(a[nextA])) {
```
