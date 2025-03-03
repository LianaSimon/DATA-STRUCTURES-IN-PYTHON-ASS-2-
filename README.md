# DATA-STRUCTURES IN PYTHON (ASS-2)

This repository contains Python exercises demonstrating the use of fundamental data structures: lists, dictionaries, sets, and tuples, implemented in a Jupyter Notebook.

## Overview

This project provides hands-on practice with basic data structures in Python. Each section of the notebook focuses on a specific data structure and includes exercises to reinforce understanding.

## Contents

-   `ASS 2-DATA STRUCTURES.ipynb`: Jupyter Notebook containing the exercises and solutions.

## Data Structures Covered

-   **Lists:** Ordered, mutable sequences.
-   **Dictionaries:** Key-value pairs, mutable.
-   **Sets:** Unordered collections of unique elements, mutable.
-   **Tuples:** Ordered, immutable sequences.




## Topic :List

### Exercise

#### Q1. Create a list of 5 random numbers and print the list.

import random

new_list=[random.randint(1,100) for _ in range(5)]

print("List of five random numbers=",new_list)

![image](https://github.com/user-attachments/assets/9ce26cf2-9e77-48ef-b202-32df86808bec)


#### Q2. Insert 3 new values to the list and print the updated list.

import random

new_list=[random.randint(1,100) for _ in range(5)]

print("List of five random numbers=",new_list)

new_list.extend([201,301,401])  # Append 3 values

print("The updated list is",new_list)


![image](https://github.com/user-attachments/assets/e43d3022-db87-4cd2-b559-baef4df2fe7a)


#### Q3. Try to use a for loop to print each element in the list.

print("The elements in the list are:")

for element in new_list:

    print(element)


![image](https://github.com/user-attachments/assets/131983ac-b64f-44f2-9cad-c45c3e775076)


## Topic: Dictionary

### Exercise 

#### Q1. Create a dictionary with keys 'name', 'age', and 'address' and values 'John', 25, and 'New York' respectively.

dict={'Name':'John','Age':25,'Address':'New York'}

print("The dictionary is",dict)


![image](https://github.com/user-attachments/assets/e38cc5fd-5a80-4508-ad6e-3f55d69018ea)


#### Q2. Add a new key-value pair to the dictionary created in Q1 with key 'phone' and value '1234567890'.

dict['Phone']=1234567890

print("The new dictionary is \n",dict)

![image](https://github.com/user-attachments/assets/e050a96e-599b-4e4a-b51e-6e10797fcc96)


## Topic: Set

### Exercise  

#### Q1.Create a set with values 1, 2, 3, 4, and 5.

my_set={1,2,3,4,5}

print("The set values are:",my_set)

![image](https://github.com/user-attachments/assets/837f4565-9a38-4426-91e3-1adfc950052f)


#### Q2. Add the value 6 to the set created in Q1.

my_set.add(6)

print("The updated set is:",my_set)

![image](https://github.com/user-attachments/assets/b3e40c36-7771-4efa-8dd0-7b03818eee0e)


#### Q3. Remove the value 3 from the set created in Q1.

my_set.discard(3)

print("The new list after removing 3 is: ",my_set)

![image](https://github.com/user-attachments/assets/0f2ad8ef-6a44-48a0-b028-a48a91c0d1b3)


## Topic:Tuple

### Exercise 

#### Q1. Create a tuple with values 1, 2, 3, and 4

the_tuple=(1,2,3,4)

print("The tuple is: ",the_tuple)

type(the_tuple)

![image](https://github.com/user-attachments/assets/a7fbef76-8116-4452-ae40-3d227b1e7dcf)


#### Q2. Print the length of the tuple created in Q1.

print("The length of the tuple is :",len(the_tuple))

![image](https://github.com/user-attachments/assets/d981f56b-30ab-488b-ab57-d566bc94437c)



## Getting Started

1.  **Clone the repository**

2.  **Ensure you have Python and Jupyter Notebook installed.** If not, install Anaconda

3.  **Open the Jupyter Notebook**

4.  **Run the cells** 

## Usage

Feel free to modify and experiment with the code in the Jupyter Notebook. You can add more exercises or explore different methods for each data structure.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.



## Author

Your Name - LIANA SIMON











