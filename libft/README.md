# Libft - 42 Network Project  
**Password-Protected Code**: The project is distributed as `libft.zip` with password: `pth-XXC12`.  

---

## 📚 About Libft  
Libft is a foundational project in the 42 curriculum where students reimplement **standard C library functions** and **custom utilities** from scratch. It serves as a toolbox for future C projects.  

---

## 🛠 Skills Developed  
- **C programming**  
- **Memory management** (handling overlap, leaks, etc.)  
- **Linked lists** (creation, traversal, deletion)  
- **Makefile automation**  
- **Algorithm design**  

---

## 📝 Recoded Functions  
### 1. **Libc Functions**  
`memset`, `memcpy`, `strlen`, `strdup`, `atoi`, and more.  
**Why?** Master low-level memory/string operations.  

### 2. **Additional Functions**  
`ft_substr`, `ft_strjoin`, `ft_split`, `ft_itoa`, `ft_lstnew`, etc.  
**Why?** Build utilities for dynamic data structures (e.g., linked lists).  

---

## 🔗 Key Concepts & Resources  
### Memory Overlap  
- [memcpy vs. memmove](https://www.geeksforgeeks.org/memcpy-vs-memmove/)  
- [CERT C Secure Coding: Memory Management](https://wiki.sei.cmu.edu/confluence/display/c/MEM00-C.+Allocate+and+free+memory+in+the+same+module,+at+the+same+level+of+abstraction)  

### Linked Lists  
- [Linked Lists in C (Tutorial)](https://www.learn-c.org/en/Linked_lists)  
- [42 Linked List Cheat Sheet](https://github.com/agavrel/42_CheatSheet?tab=readme-ov-file#linked-lists)  

### Makefiles  
- [GNU Make Manual](https://www.gnu.org/software/make/manual/make.html)  
- [Makefile Basics](https://makefiletutorial.com/)  

---

## 🔧 Installation  
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

✅ **Compatibility**: macOS, Linux. Requires `gcc`, `make`, and `unzip`.  
