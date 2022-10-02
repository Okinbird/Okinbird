0x03. Python - Data Structures: Lists, Tuples Python

    By: Guillaume
    Weight: 1
    Project over - took place from Sep 22, 2022 10:00 PM to Sep 26, 2022 10:00 PM
    An auto review will be launched at the deadline

In a nutshell...

    Auto QA review: 169.0/169 mandatory & 13.0/13 optional
    Altogether:  200.0%
        Mandatory: 100.0%
        Optional: 100.0%
        Calculation:  100.0% + (100.0% * 100.0%)  == 200.0%

Resources

Read or watch:

    3.1.3. Lists
    Data structures (until 5.3. Tuples and Sequences included)
    Learn to Program 6 : Lists

Learning Objectives

At the end of this project, you are expected to be able to explain to
anyone, without the help of Google: General

    Why Python programming is awesome
    What are lists and how to use them
    What are the differences and similarities between strings and lists
    What are the most common methods of lists and how to use them
    How to use lists as stacks and queues
    What are list comprehensions and how to use them
    What are tuples and how to use them
    When to use tuples versus lists
    What is a sequence
    What is tuple packing
    What is sequence unpacking
    What is the del statement and how to use it

Copyright - Plagiarism

    You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
    You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
    You are not allowed to publish any content of this project.
    Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements Python Scripts

    Allowed editors: vi, vim, emacs
    All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    All your files should end with a new line
    The first line of all your files should be exactly #!/usr/bin/python3
    A README.md file, at the root of the folder of the project, is mandatory
    Your code should use the pycodestyle (version 2.8.*)
    All your files must be executable
    The length of your files will be tested using wc

C

    Allowed editors: vi, vim, emacs
    All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    All your files should end with a new line
    Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
    You are not allowed to use global variables
    No more than 5 functions per file
    In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
    The prototypes of all your functions should be included in your header file called lists.h
    Don’t forget to push your header file
    All your header files should be include guarded

Quiz questions Great! You've completed the quiz successfully! Keep
going! (Show quiz) Tasks 0. Print a list of integers mandatory Score:
100.0% (Checks completed: 100.0%)

Write a function that prints all integers of a list.

    Prototype: def print_list_integer(my_list=[]):
    Format: one integer per line. See example
    You are not allowed to import any module
    You can assume that the list only contains integers
    You are not allowed to cast integers into strings
    You have to use str.format() to print integers

guillaume\@ubuntu:\~/0x03\$ cat 0-main.py \#!/usr/bin/python3
print\_list\_integer =
**import**('0-print\_list\_integer').print\_list\_integer

my\_list = \[1, 2, 3, 4, 5\] print\_list\_integer(my\_list)

guillaume\@ubuntu:\~/0x03\$ ./0-main.py 1 2 3 4 5
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 0-print_list_integer.py

1.  Secure access to an element in a list mandatory Score: 100.0%
    (Checks completed: 100.0%)

Write a function that retrieves an element from a list like in C.

    Prototype: def element_at(my_list, idx):
    If idx is negative, the function should return None
    If idx is out of range (> of number of element in my_list), the function should return None
    You are not allowed to import any module
    You are not allowed to use try/except

guillaume\@ubuntu:\~/0x03\$ cat 1-main.py \#!/usr/bin/python3
element\_at = **import**('1-element\_at').element\_at

my\_list = \[1, 2, 3, 4, 5\] idx = 3 print("Element at index {:d} is
{}".format(idx, element\_at(my\_list, idx)))

guillaume\@ubuntu:\~/0x03\$ ./1-main.py Element at index 3 is 4
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 1-element_at.py

2.  Replace element mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that replaces an element of a list at a specific
position (like in C).

    Prototype: def replace_in_list(my_list, idx, element):
    If idx is negative, the function should not modify anything, and returns the original list
    If idx is out of range (> of number of element in my_list), the function should not modify anything, and returns the original list
    You are not allowed to import any module
    You are not allowed to use try/except

guillaume\@ubuntu:\~/0x03\$ cat 2-main.py \#!/usr/bin/python3
replace\_in\_list = **import**('2-replace\_in\_list').replace\_in\_list

my\_list = \[1, 2, 3, 4, 5\] idx = 3 new\_element = 9 new\_list =
replace\_in\_list(my\_list, idx, new\_element)

print(new\_list) print(my\_list)

guillaume\@ubuntu:\~/0x03\$ ./2-main.py \[1, 2, 3, 9, 5\] \[1, 2, 3, 9,
5\] guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 2-replace_in_list.py

3.  Print a list of integers... in reverse! mandatory Score: 100.0%
    (Checks completed: 100.0%)

Write a function that prints all integers of a list, in reverse order.

    Prototype: def print_reversed_list_integer(my_list=[]):
    Format: one integer per line. See example
    You are not allowed to import any module
    You can assume that the list only contains integers
    You are not allowed to cast integers into strings
    You have to use str.format() to print integers

guillaume\@ubuntu:\~/0x03\$ cat 3-main.py \#!/usr/bin/python3
print\_reversed\_list\_integer =
**import**('3-print\_reversed\_list\_integer').print\_reversed\_list\_integer

my\_list = \[1, 2, 3, 4, 5\] print\_reversed\_list\_integer(my\_list)

guillaume\@ubuntu:\~/0x03\$ ./3-main.py 5 4 3 2 1
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 3-print_reversed_list_integer.py

4.  Replace in a copy mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that replaces an element in a list at a specific
position without modifying the original list (like in C).

    Prototype: def new_in_list(my_list, idx, element):
    If idx is negative, the function should return a copy of the original list
    If idx is out of range (> of number of element in my_list), the function should return a copy of the original list
    You are not allowed to import any module
    You are not allowed to use try/except

guillaume\@ubuntu:\~/0x03\$ cat 4-main.py \#!/usr/bin/python3
new\_in\_list = **import**('4-new\_in\_list').new\_in\_list

my\_list = \[1, 2, 3, 4, 5\] idx = 3 new\_element = 9 new\_list =
new\_in\_list(my\_list, idx, new\_element)

print(new\_list) print(my\_list)

guillaume\@ubuntu:\~/0x03\$ ./4-main.py \[1, 2, 3, 9, 5\] \[1, 2, 3, 4,
5\] guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 4-new_in_list.py

5.  Can you C me now? mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that removes all characters c and C from a string.

    Prototype: def no_c(my_string):
    The function should return the new string
    You are not allowed to import any module
    You are not allowed to use str.replace()

guillaume\@ubuntu:\~/0x03\$ cat 5-main.py \#!/usr/bin/env python3 no\_c
= **import**('5-no\_c').no\_c

print(no\_c("Best School")) print(no\_c("Chicago")) print(no\_c("C is
fun!"))

guillaume\@ubuntu:\~/0x03\$ ./5-main.py Best Shool hiago is fun!
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 5-no_c.py

6.  Lists of lists = Matrix mandatory Score: 100.0% (Checks completed:
    100.0%)

Write a function that prints a matrix of integers.

    Prototype: def print_matrix_integer(matrix=[[]]):
    Format: see example
    You are not allowed to import any module
    You can assume that the list only contains integers
    You are not allowed to cast integers into strings
    You have to use str.format() to print integers

guillaume\@ubuntu:\~/0x03\$ cat 6-main.py \#!/usr/bin/python3
print\_matrix\_integer =
**import**('6-print\_matrix\_integer').print\_matrix\_integer

matrix = \[ \[1, 2, 3\], \[4, 5, 6\], \[7, 8, 9\]\]

print\_matrix\_integer(matrix) print("--") print\_matrix\_integer()

guillaume\@ubuntu:\~/0x03\$ ./6-main.py \| cat -e 1 2 3\$ 4 5 6\$ 7 8
9\$ --\$ \$ guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 6-print_matrix_integer.py

7.  Tuples addition mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that adds 2 tuples.

    Prototype: def add_tuple(tuple_a=(), tuple_b=()):
    Returns a tuple with 2 integers:
        The first element should be the addition of the first element of each argument
        The second element should be the addition of the second element of each argument
    You are not allowed to import any module
    You can assume that the two tuples will only contain integers
    If a tuple is smaller than 2, use the value 0 for each missing integer
    If a tuple is bigger than 2, use only the first 2 integers

guillaume\@ubuntu:\~/0x03\$ cat 7-main.py \#!/usr/bin/python3 add\_tuple
= **import**('7-add\_tuple').add\_tuple

tuple\_a = (1, 89) tuple\_b = (88, 11) new\_tuple = add\_tuple(tuple\_a,
tuple\_b) print(new\_tuple)

print(add\_tuple(tuple\_a, (1, ))) print(add\_tuple(tuple\_a, ()))

guillaume\@ubuntu:\~/0x03\$ ./7-main.py (89, 100) (2, 89) (1, 89)
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 7-add_tuple.py

8.  More returns! mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that returns a tuple with the length of a string and
its first character.

    Prototype: def multiple_returns(sentence):
    If the sentence is empty, the first character should be equal to None
    You are not allowed to import any module

guillaume\@ubuntu:\~/0x03\$ cat 8-main.py \#!/usr/bin/python3
multiple\_returns = **import**('8-multiple\_returns').multiple\_returns

sentence = "At school, I learnt C!" length, first =
multiple\_returns(sentence) print("Length: {:d} - First character:
{}".format(length, first))

guillaume\@ubuntu:\~/0x03\$ ./8-main.py Length: 22 - First character: A
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 8-multiple_returns.py

9.  Find the max mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that finds the biggest integer of a list.

    Prototype: def max_integer(my_list=[]):
    If the list is empty, return None
    You can assume that the list only contains integers
    You are not allowed to import any module
    You are not allowed to use the builtin max()

guillaume\@ubuntu:\~/0x03\$ cat 9-main.py \#!/usr/bin/python3
max\_integer = **import**('9-max\_integer').max\_integer

my\_list = \[1, 90, 2, 13, 34, 5, -13, 3\] max\_value =
max\_integer(my\_list) print("Max: {}".format(max\_value))

guillaume\@ubuntu:\~/0x03\$ ./9-main.py Max: 90
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 9-max_integer.py

10. Only by 2 mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that finds all multiples of 2 in a list.

    Prototype: def divisible_by_2(my_list=[]):
    Return a new list with True or False, depending on whether the integer at the same position in the original list is a multiple of 2
    The new list should have the same size as the original list
    You are not allowed to import any module

guillaume\@ubuntu:\~/0x03\$ cat 10-main.py \#!/usr/bin/python3
divisible\_by\_2 = **import**('10-divisible\_by\_2').divisible\_by\_2

my\_list = \[0, 1, 2, 3, 4, 5, 6\] list\_result =
divisible\_by\_2(my\_list)

i = 0 while i \< len(list\_result): print("{:d} {:s} divisible by
2".format(my\_list\[i\], "is" if list\_result\[i\] else "is not")) i +=
1

guillaume\@ubuntu:\~/0x03\$ ./10-main.py 0 is divisible by 2 1 is not
divisible by 2 2 is divisible by 2 3 is not divisible by 2 4 is
divisible by 2 5 is not divisible by 2 6 is divisible by 2
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 10-divisible_by_2.py

11. Delete at mandatory Score: 100.0% (Checks completed: 100.0%)

Write a function that deletes the item at a specific position in a list.

    Prototype: def delete_at(my_list=[], idx=0):
    If idx is negative or out of range, nothing change (returns the same list)
    You are not allowed to use pop()
    You are not allowed to import any module

guillaume\@ubuntu:\~/0x03\$ cat 11-main.py \#!/usr/bin/python3
delete\_at = **import**('11-delete\_at').delete\_at

my\_list = \[1, 2, 3, 4, 5\] idx = 3 new\_list = delete\_at(my\_list,
idx) print(new\_list) print(my\_list)

guillaume\@ubuntu:\~/0x03\$ ./11-main.py \[1, 2, 3, 5\] \[1, 2, 3, 5\]
guillaume\@ubuntu:\~/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 11-delete_at.py

12. Switch mandatory Score: 100.0% (Checks completed: 100.0%)

Complete the source code in order to switch value of a and b

    You can find the source code here
    Your code should be inserted where the comment is (line 4)
    Your program should be exactly 5 lines long

guillaume\@ubuntu:\~/py/0x03\$ ./12-switch.py a=10 - b=89
guillaume\@ubuntu:\~/py/0x03\$ wc -l 12-switch.py 5 12-switch.py
guillaume\@ubuntu:\~/py/0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 12-switch.py

13. Linked list palindrome mandatory Score: 100.0% (Checks completed:
    100.0%)

Technical interview preparation:

    You are not allowed to google anything
    Whiteboard first

Write a function in C that checks if a singly linked list is a
palindrome.

    Prototype: int is_palindrome(listint_t **head);
    Return: 0 if it is not a palindrome, 1 if it is a palindrome
    An empty list is considered a palindrome

carrie\@ubuntu:0x03\$ cat lists.h \#ifndef LISTS\_H \#define LISTS\_H

/\*\* \* struct listint\_s - singly linked list \* @n: integer \* @next:
points to the next node * * Description: singly linked list node
structure \* for project */ typedef struct listint\_s { int n; struct
listint\_s *next; } listint\_t;

size\_t print\_listint(const listint\_t *h); listint\_t
*add\_nodeint\_end(listint\_t \*\*head, const int n); void
free\_listint(listint\_t \*head);

int is\_palindrome(listint\_t \*\*head);

\#endif /\* LISTS\_H \*/ carrie\@ubuntu:0x03\$

carrie\@ubuntu:0x03\$ cat linked\_lists.c \#include \<stdio.h\>
\#include \<stdlib.h\> \#include "lists.h"

/\*\* \* print\_listint - prints all elements of a listint\_t list \*
@h: pointer to head of list \* Return: number of nodes */ size\_t
print\_listint(const listint\_t *h) { const listint\_t *current;
unsigned int n; /* number of nodes \*/

    current = h;
    n = 0;
    while (current != NULL)
    {
        printf("%i\n", current->n);
        current = current->next;
        n++;
    }

    return (n);

}

/** \* add\_nodeint\_end - adds a new node at the end of a listint\_t
list \* @head: pointer to pointer of first node of listint\_t list \*
@n: integer to be included in new node \* Return: address of the new
element or NULL if it fails */ listint\_t *add\_nodeint\_end(listint\_t
**head, const int n) { listint\_t *new; listint\_t *current;

    current = *head;

    new = malloc(sizeof(listint_t));
    if (new == NULL)
        return (NULL);

    new->n = n;
    new->next = NULL;

    if (*head == NULL)
        *head = new;
    else
    {
        while (current->next != NULL)
            current = current->next;
        current->next = new;
    }

    return (new);

}

/\*\* \* free\_listint - frees a listint\_t list \* @head: pointer to
list to be freed \* Return: void */ void free\_listint(listint\_t *head)
{ listint\_t \*current;

    while (head != NULL)
    {
        current = head;
        head = head->next;
        free(current);
    }

} carrie\@ubuntu:0x03\$

carrie\@ubuntu:0x03\$ cat 13-main.c \#include \<stdio.h\> \#include
\<stdlib.h\> \#include "lists.h"

/\*\* \* main - check the code for * * Return: Always 0. */ int
main(void) { listint\_t *head;

    head = NULL;
    add_nodeint_end(&head, 1);
    add_nodeint_end(&head, 17);
    add_nodeint_end(&head, 972);
    add_nodeint_end(&head, 50);
    add_nodeint_end(&head, 98);
    add_nodeint_end(&head, 98);
    add_nodeint_end(&head, 50);
    add_nodeint_end(&head, 972);
    add_nodeint_end(&head, 17);
    add_nodeint_end(&head, 1);
    print_listint(head);

    if (is_palindrome(&head) == 1)
        printf("Linked list is a palindrome\n");
    else
        printf("Linked list is not a palindrome\n");

    free_listint(head);

    return (0);

} carrie\@ubuntu:0x03\$

carrie\@ubuntu:0x03\$ gcc -Wall -Werror -Wextra -pedantic 13-main.c
linked\_lists.c 13-is\_palindrome.c -o palindrome carrie\@ubuntu:0x03\$
./palindrome 1 17 972 50 98 98 50 972 17 1 Linked list is a palindrome
carrie\@ubuntu:0x03\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 13-is_palindrome.c, lists.h

14. CPython \#0: Python lists \#advanced Score: 100.0% (Checks
    completed: 100.0%)

CPython is the reference implementation of the Python programming
language. Written in C, CPython is the default and most widely used
implementation of the language. Since we now know a bit of C, we can
look at what is happening under the hood of Python. Let's have fun with
Python and C, and let's look at what makes Python so easy to use.

    All your files will be interpreted/compiled on Ubuntu 14.04 LTS

Create a C function that prints some basic info about Python lists.

    Prototype: void print_python_list_info(PyObject *p);
    Format: see example
    Python version: 3.4
    Your shared library will be compiled with this command line: gcc -Wall -Werror -Wextra -pedantic -std=c99 -shared -Wl,-soname,PyList -o libPyList.so -fPIC -I/usr/include/python3.4 100-print_python_list_info.c
    OS: Ubuntu 14.04 LTS
    Start by reading:
        listobject.h
        object.h
        Common Object Structures
        List Objects

julien\@ubuntu:\~/CPython\$ gcc -Wall -Werror -Wextra -pedantic -std=c99
-shared -Wl,-soname,PyList -o libPyList.so -fPIC
-I/usr/include/python3.4 100-print\_python\_list\_info.c
julien\@ubuntu:\~/CPython\$ cat 100-test\_lists.py import ctypes

lib = ctypes.CDLL('./libPyList.so')
lib.print\_python\_list\_info.argtypes = \[ctypes.py\_object\] l =
\['hello', 'World'\] lib.print\_python\_list\_info(l) del l\[1\]
lib.print\_python\_list\_info(l) l = l + \[4, 5, 6.0, (9, 8), \[9, 8,
1024\], "My string"\] lib.print\_python\_list\_info(l) l = \[\]
lib.print\_python\_list\_info(l) l.append(0)
lib.print\_python\_list\_info(l) l.append(1) l.append(2) l.append(3)
l.append(4) lib.print\_python\_list\_info(l) l.pop()
lib.print\_python\_list\_info(l) julien\@ubuntu:\~/CPython\$ python3
100-test\_lists.py \[\*\] Size of the Python List = 2 \[\*\] Allocated =
2 Element 0: str Element 1: str \[\*\] Size of the Python List = 1
\[\*\] Allocated = 2 Element 0: str \[\*\] Size of the Python List = 7
\[\*\] Allocated = 7 Element 0: str Element 1: int Element 2: int
Element 3: float Element 4: tuple Element 5: list Element 6: str \[\*\]
Size of the Python List = 0 \[\*\] Allocated = 0 \[\*\] Size of the
Python List = 1 \[\*\] Allocated = 4 Element 0: int \[\*\] Size of the
Python List = 5 \[\*\] Allocated = 8 Element 0: int Element 1: int
Element 2: int Element 3: int Element 4: int \[\*\] Size of the Python
List = 4 \[\*\] Allocated = 8 Element 0: int Element 1: int Element 2:
int Element 3: int julien\@CPython:\~/CPython\$

Repo:

    GitHub repository: alx-higher_level_programming
    Directory: 0x03-python-data_structures
    File: 100-print_python_list_info.c

Copyright © 2022 ALX, All rights reserved.
