# get_next_line - 42 Network Project  
**Password**: `fpl-GHT985623` (required to extract `get_next_line.zip`).  

---  

## 📚 About get_next_line  
This project implements a function `get_next_line` that reads a line from a file descriptor (e.g., file, stdin, or socket) efficiently. It handles static buffers, memory leaks, and variable buffer sizes.  

---  

## 🛠 Skills Developed  
- **File I/O operations** (reading from file descriptors).  
- **Static variables** (persisting buffer data between function calls).  
- **Memory management** (dynamic allocation, freeing leaks).  
- **Edge-case handling** (empty files, large buffers, multi-fd support).  

---  

## 🔗 Key Concepts & Resources  
### Static Variables  
- [Static Variables in C](https://www.geeksforgeeks.org/static-variables-in-c/)  
- [Persistent State Management](https://www.tutorialspoint.com/c-programming-static-variables)  

### File Descriptors  
- [File I/O in C](https://www.gnu.org/software/libc/manual/html_node/I_002fO-on-Streams.html)  
- [Understanding File Descriptors](https://en.wikipedia.org/wiki/File_descriptor)  

### Memory Management  
- [Dynamic Memory Allocation](https://www.geeksforgeeks.org/dynamic-memory-allocation-in-c-using-malloc-calloc-free-and-realloc/)  
- [Memory Leak Detection](https://valgrind.org/docs/manual/quick-start.html)  

---  

## 🔧 Installation  
### 1. Download get_next_line.zip  
wget https://<your-repo-url>/get_next_line.zip  

### 2. Extract with password  
unzip -P fpl-GHT985623 get_next_line.zip  

### 3. Compile  
cd get_next_line && make  

---

## 📂 Project Structure

get_next_line/  
├── get_next_line.c        # Main logic (reads lines, manages buffers)  
├── get_next_line.h        # Header (BUFFER_SIZE macro, prototypes)  
└── get_next_line_utils.c  # Helper functions (e.g., strlen, strjoin)  

---

## Key Files:
get_next_line.c: Core logic for reading lines and handling buffers.

get_next_line_utils.c: Custom utilities (e.g., ft_strjoin, ft_strlen).

get_next_line.h: Defines BUFFER_SIZE (configurable) and function prototypes.

---

## 🚀 How It Works
Reads data from the file descriptor into a buffer.

Appends buffer content to a static variable to persist between calls.

Extracts lines from the static buffer (until \n or EOF).

Returns the line and retains leftover buffer data for the next call.

---

✅ Compatibility: macOS, Linux. Requires gcc, make, and unzip.
