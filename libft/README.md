```
# Libft - 42 Network Project

🔒 **Password-Protected Code**  
The project is distributed as `libft.zip` with password: `pth-XXC12`.

---

📚 **About Libft**  
Libft is a foundational project in the 42 curriculum where students reimplement standard C library functions  
and additional helper functions from scratch. This library serves as a toolbox for future C projects.

---

🛠 **Skills Developed**  
- C programming  
- Memory management  
- Algorithm design  
- Makefile automation  
- Testing & debugging  

---

📝 **Recoded Functions**  
The project includes two categories of functions:  

1. **Libc Functions**  
   - `memset`, `memcpy`, `strlen`, `strdup`, `atoi`, etc.  
   - *Why?* To understand low-level memory manipulation and string operations.  

2. **Additional Functions**  
   - `ft_substr`, `ft_strjoin`, `ft_split`, `ft_itoa`, `ft_lstnew`, etc.  
   - *Why?* To build utilities for handling dynamic data structures (linked lists) and complex string operations.  

---

🔗 **Learning Resources**  
Key concepts to master for this project:  

1. **Memory Overlap**  
   - [memcpy vs. memmove](https://www.geeksforgeeks.org/memcpy-vs-memmove/) - Explains handling overlapping memory regions.  
   - [CERT C Secure Coding: Memory Management](https://wiki.sei.cmu.edu/confluence/display/c/MEM00-C.+Allocate+and+free+memory+in+the+same+module,+at+the+same+level+of+abstraction) - Best practices for safe memory operations.  

2. **Linked Lists**  
   - [Linked Lists in C](https://www.learn-c.org/en/Linked_lists) - Basics of node creation and traversal.  
   - [42 Linked List Guide](https://github.com/agavrel/42_CheatSheet?tab=readme-ov-file#linked-lists) - Practical examples for 42 projects.  

3. **Makefiles**  
   - [GNU Make Manual](https://www.gnu.org/software/make/manual/make.html) - Official documentation for writing Makefiles.  
   - [Makefile Tutorial](https://makefiletutorial.com/) - Simplified guide for beginners.  

4. **General C Programming**  
   - [C Programming FAQs](https://c-faq.com/) - Common pitfalls and solutions.  
   - [IBM C Standard Library](https://www.ibm.com/docs/en/zos/2.4.0?topic=functions-standard-library) - Detailed explanations of libc functions.  

---

🚀 **Why Use This Library?**  
- Lightweight and efficient.  
- No external dependencies.  
- Fully tested for edge cases.  
- Compliant with 42's strict coding standards.  

---

🔧 **Installation**  
1. Download the `libft.zip` file from this repository.  
2. Extract with the password `pth-XXC12`:  
   ```bash  
   unzip -P pth-XXC12 libft.zip -d libft  
   ```  
3. Compile the library:  
   ```bash  
   cd libft && make  
   ```  
4. Include `libft.a` in your project and link it during compilation.  

---

📂 **Project Structure**  
```  
libft/  
├── includes/  
│   └── libft.h           # Header file (function prototypes)  
├── src/  
│   ├── string/           # String functions (strlen, substr, etc.)  
│   ├── memory/           # Memory functions (memset, memcpy, etc.)  
│   ├── lists/            # Linked list utilities (lstnew, lstadd_back, etc.)  
│   └── ...               # Other source files  
├── Makefile              # Build automation (compile with `make`)  
└── libft.a               # Compiled library (generated after `make`)  
```  

---

✅ **Compatibility**  
Tested on macOS and Linux. Requires `gcc`, `make`, and `unzip`.  
```
