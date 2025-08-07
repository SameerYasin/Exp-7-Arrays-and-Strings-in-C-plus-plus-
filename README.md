# Exp-7-Arrays-and-Strings-in-C-plus-plus-

# **Experiment - Arrays and Strings in C++**

## **Aim**

To study and implement the concept of **Arrays** and **Strings** in C++ programming through various hands-on examples and use cases.


* **Software:** Visual Studio Code
* **Language:** C++

## **Theory**

### **Arrays**

An **array** in C++ is a data structure that stores a fixed-size sequential collection of elements of the same type. These elements are stored in **contiguous memory locations**, and each element can be accessed using its **index**.

Arrays help in:

* Storing a large amount of similar data efficiently.
* Accessing and modifying elements using loops.
* Performing bulk operations like sorting, searching, etc.

#### **Types of Arrays:**

**1. One-Dimensional Array**

* Declared as: `int arr[5];`
* Accessed using: `arr[0], arr[1], ..., arr[4]`

<img width="888" height="449" alt="474804885-66e5d96f-f8d1-41a0-be93-f260f123d047" src="https://github.com/user-attachments/assets/40b0dffc-03ea-4a79-b7bd-aef4b76b9260" />

**2. Multi-Dimensional Array**

* Example: 2D array
* Declared as: `int arr[3][3];`
* Accessed using: `arr[i][j]`

---

### **Strings**

Strings in C++ are handled in two ways:

1. **Character Arrays (`char str[]`)**
2. **C++ `string` Class (from STL)**

The `string` class is preferred due to its:

* Built-in flexibility
* Dynamic memory handling
* Useful functions like `length()`, `compare()`, `append()`, etc.


## **Implementation**

Below are the tasks performed with their **purpose** and **algorithm**:


### **1. Basic Array Declaration and Traversal**

**Objective:** Take 5 integer inputs and display them.

**Algorithm:**

1. Declare an array of size 5.
2. Loop to take input for all 5 elements.
3. Loop to display each element.


### **2. Array Element Search**

**Objective:** Search for a user-given element in the array.

**Algorithm:**

1. Initialize the array with values.
2. Take user input for the search key.
3. Loop through array:

   * If element equals key, print its index and stop.
4. If not found, inform the user.


### **3. Find Maximum and Minimum in Array**

**Objective:** Determine the largest and smallest values.

**Algorithm:**

1. Take user input to fill the array.
2. Initialize `min` and `max` with first element.
3. Loop through the array:

   * If `arr[i] > max`, update `max`
   * If `arr[i] < min`, update `min`
4. Print `min` and `max`


### **4. Reverse Array Elements**

**Objective:** Print array in reverse order.

**Algorithm:**

1. Take user input into array.
2. Loop from `size - 1` to `0`.
3. Print each element during reverse loop.


### **5. Sum and Average of Array Elements**

**Objective:** Compute sum and average of all elements.

**Algorithm:**

1. Initialize `sum = 0`
2. Take input for all array elements.
3. Add each to `sum` using a loop.
4. Compute `average = sum / count`
5. Display both `sum` and `average`


### **6. String Operations (Optional if included)**

**Objective:** Perform basic string manipulations.

**Algorithm:**

1. Declare string variables (using `string` or `char[]`)
2. Use standard functions (`strcpy`, `strcat`, etc.) or class methods (`compare()`, `append()`)
3. Display results after operations.

## **Conclusion**
By completing this experiment, I learned how to declare, initialize, and manipulate arrays effectively in C++. I understood the logic behind essential operations such as searching for elements, reversing arrays, and computing statistical data like minimum, maximum, sum, and average. Additionally, I practiced working with both character arrays and the more flexible STL string class to perform various string operations. Overall, this experiment strengthened my grasp of structured programming concepts in C++ and laid a strong foundation for data structure handling and algorithm design using arrays and strings.
