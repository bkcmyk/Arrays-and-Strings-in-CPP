# Arrays and Strings in C++

## Aim
To study and implement C++ Arrays and Strings using practical programs for traversal, searching, reversal, and manipulation.

---
## Apparatus

VS Code or Online C++ Compiler


## Theory

### Arrays in C++
An array is a collection of variables of the same type stored at contiguous memory locations. It is used to store multiple values under a single name and can be accessed using an index.

#### ➔ Declaration:
```cpp
int arr[5]; // Declares an array of 5 integers
```

#### ➔ Initialization:
```cpp
int arr[5] = {1000, 2, 3, 17, 50}; // Assigns values at declaration
```

#### ➔ Accessing Elements:
```cpp
int x = arr[2]; // Accesses the 3rd element (index starts from 0)
```

**Key Points:**
- Arrays are zero-indexed: the first element is at index 0.
- Elements are stored in consecutive memory locations.
- Useful for storing lists of data like numbers, names, marks, etc.

---

### Strings in C++
A string is a sequence of characters used to store and manipulate text. In C++, the `string` class (from `<string>`) simplifies handling text.

#### ➔ Declaration and Input:
```cpp
string name;
cin >> name; // Input a single word
```

#### ➔ Common Operations:
```cpp
string full = name1 + name2; // Concatenation
int len = name.length();     // Length of string
```

---

## Algorithms (Arrays)

### 1. Array Declaration and Traversal
1. Declare an array of fixed size.
2. Initialize the array using user input or hard-coded values.
3. Traverse the array using a loop and print each element.

### 2. Input and Output of Array
1. Read the size of the array.
2. Use a `for` loop to input values into the array.
3. Use a `for` or range-based loop to print all values.

### 3. Reverse an Array
1. Read `n` elements into an array.
2. Create another array to store reversed values.
3. Copy elements from the original array in reverse order.
4. Print the reversed array.

### 4. Search an Element in Array
1. Input an array of `n` elements.
2. Input a number to search.
3. Traverse the array.
4. If a match is found, print index and count occurrences.

---

## Algorithms (Strings)


### 1. Concatenation of Strings
1. Input two strings.
2. Use `+` operator to concatenate.
3. Output the result.



### 2. Palindrome Check
1. Input a string.
2. Compare characters from start and end moving towards center.
3. If all characters match, print "Palindrome".
4. Else, print "Not a Palindrome".


---

## Conclusion
In this experiment, we explored fundamental operations using arrays and strings in C++. Arrays provided an efficient way to store and process collections of data, while strings enabled manipulation of textual input. Through implementation of basic algorithms like reversal, searching, and average computation, we gained practical understanding of loop structures, indexing, and standard library usage in C++. This experiment built a strong foundation for future work in data structures and problem solving using C++.
