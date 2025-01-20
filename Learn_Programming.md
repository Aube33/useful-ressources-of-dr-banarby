# My universal path to learn programming / a programming language

#### This list is my personal path when I want to learn a new programming language.

## 1 - Fucking World (Difficulty: 0)
Filename: `hello_world.xx`

Create a simple program to write "Hello World !" in the terminal.

Example: 
```py
>>> hello_world()
"Hello World !"
```

## 2 - Add this, substract there (Difficulty: 0)
Filename: `add_substract.xx`

Create 2 functions:
- An `addition` function, that take **2 parameters** (a, b) and returns the sum of **a+b**.
- A `substract` function, that take **2 parameters** (a, b) and returns the substraction of **a-b**.

Example: 
```py
>>> addition(3+90)
93
>>> substract(3-10)
-7
```

## 3 - Concatenate (Difficulty: 0)
Filename: `concatenate.xx`

Create a function named `concat`, that take **2 parameters** (str1, str2) and returns the concatenation of str1 with str2 with a space between.

Example: 
```py
>>> concat("My name is", "Destroyer")
"My name is Destroyer"
```

## 5 - Ask User (Difficulty: 0)
Filename: `ask_user.xx`

Create a function named `ask_name`, that take **0 parameters** and ask the name of the user to say to Hello to him.

Example: 
```py
>>> ask_name()
> Enter your name: Max
"Hello Max"
```

## 4 - Higer or Lower (Difficulty 1)
Filename: `higherlower.xx`

You need to create a Higher-Lower game. Your program chooses a **random number between 0 and 100**, and you **ask the user** to guess a number in this range. **While** the number chosen by the user is not equal to the one chosen by the program, the game continues. The program guides the user with 'Lower' or 'Higher' depending on the user's guess.

Example: 
```py
>>> play()
> Choose a number [0 - 100]: 90
"Lower !"
> Choose a number [0 - 100]: 10
"Higher !"
> Choose a number [0 - 100]: 54
"You win !"
```

## 5 - Replace the bad ones (Difficulty 1)
Filename: `replace_odd.xx`

Create a function named `replace_odd`, that take **1 parameter**. This parameter must be an array / a list. The function **removes all the odd numbers** from the array.

Example: 
```py
>>> replace_odd([1,2,3,4,5])
[2,4]
```

## 6 - Bubble Sort (Difficulty 2)
Filename: `bubble_sort.xx`

Bubble sort is a very simple sorting algorithm for sorting an array.

[Bubble sort - Wikipedia](https://en.wikipedia.org/wiki/Bubble_sort)

Create a function named `bubble_sort`, that take **1 parameter**. This parameter must be an array. The function returns the array sorted in ascending order **using bubble algorithm**.

Example: 
```py
>>> bubble_sort([90,5,3,18,23])
[3,5,18,23,90]
```

## 7 - Olivier from CarClass (Difficulty 2)
Filename: `car_class.xx`

Create a class `Car`, that takes:
- 2 attributes:
    - `color_name` : This will be the **color** of our car.
    - `brand_name` : This will be the **brand** of our car.

- 1 constructor:
    - That takes **2 parameters**, and sets `color_name` and `brand_name` to these parameters.

- And 4 methods:
    - `get_color` : Returns the value of attribute `color_name`.
    - `set_color` : Takes **1 parameter** and update the value of `color_name` with this paramter.
    - `get_brand` : Returns the value of attribute `brand_name`.
    - `ToString` : Returns a text describing the car with `color_name` and `brand_name`.


Example: 
```py
>>> car_1 = Car("Yellow", "Volvo")
>>> car_2 = Car("Red", "Renault")
>>> car_1.get_color()
"Yellow"
>>> car_2.get_color()
"Red"
>>> car_2.set_brand("Tesla")
>>> car_2.get_brand()
"Tesla"
>>> car_2.ToString()
"The car is Red, and its brand is Tesla"
```

## 8 - Recursive Fibonacci (Difficulty 3)
Filename: `fibonacci.xx`

Create a function named `fibonacci`. This function must display the **first 50 numbers** of **Fibonacci series** using a **recursive** algorithm.

Example: 
```py
>>> fibonacci()
[0,1,1,2,3,5,8,13,21,34,55,89,...]
```

## 9 - Merge Sort (Difficulty 4)
Filename: `merge_sort.xx`

Merge sort is an advanced sorting algorithm for sorting an array.

[Merge sort - Wikipedia](https://en.wikipedia.org/wiki/Merge_sort)

Implement the **Merge sort** algorithm. The program returns the array sorted in ascending order **using the merge sort algorithm** 

Example: 
```py
>>> merge_sort([90,5,3,18,23])
[3,5,18,23,90]
```

# More

## Pointers (Difficulty 2)
Filename: `pointers.xx`

I do that later

## XOR (Difficulty 3)
Filename: `xor.xx`

Create a function named `xor_basic`, that takes **2 parameter**. These parameters must be a series of 0 and 1 with same length. The function returns the XOR operation to the parameters.

Example: 
```py
>>> xor_basic("1100", "1010")
'0110'
```