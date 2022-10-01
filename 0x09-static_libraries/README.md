# C - Static libraries

In this project, I learned what static libraries are and practiced creating and
using them with `ar`, `ranlib`, and `nm`.

## Tests 

* [tests](./tests): Folder of test files. Provided by Holberton School.

## Tasks :page_with_curl:

* **0. A library is not a luxury but one of the necessities of life**
  * [libmy.a](./libmy.a): C Static library containing functions
 

  * [main.h](./main.h): Header file containing the prototypes of all functions
  included in `libmy.a`.

* **1. Without libraries what have we? We have no past and no future**
  * [create_static_lib.sh](./create_static_lib.sh): Bash script that creates a static
  library called `liball.a` from all the `.c` files in the current directory.
