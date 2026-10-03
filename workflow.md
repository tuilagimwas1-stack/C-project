# C Username Greeting Project

This project is a simple C application that prompts the user to enter a username and outputs a personalized greeting.

---

### 📷 Program Execution

![Program Screenshot](./asset/project1.png)[cite: 2]

---

### 📝 Code Explanation

* **`#include <stdio.h>`**: Includes the standard input-output library necessary for using `printf` and `scanf`[cite: 2].
* **`char Harun[50];`**: Declares a character array (string buffer) named `Harun` capable of holding up to 50 characters[cite: 2].
* **`printf("please enter username");`**: Displays a prompt on the screen asking the user to input their name[cite: 2].
* **`scanf("%s", Harun);`**: Reads the string entered by the user from the console and stores it in the `Harun` variable[cite: 2].
* **`printf("hello %s", Harun);`**: Outputs "hello " followed by the stored username to the screen[cite: 2].
* **`return 0;`**: Signals that the program has executed successfully[cite: 2].
