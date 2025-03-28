# ft_printf - 42 Network Project  
**Password**: `gth-VXC3365` (required to extract `ft_printf.zip`).  

---  

## 📚 About ft_printf  
This project reimplements **`printf`** from scratch, supporting format specifiers like `%c`, `%s`, `%d`, `%x`, `%X`, `%p`, `%u`, and `%%`. It emphasizes parsing format strings, handling variadic arguments, and type conversions.  

---  

## 🛠 Skills Developed  
- **Variadic functions** (e.g., `va_start`, `va_arg`)  
- **Memory-safe string handling**  
- **Hexadecimal and pointer address formatting**  
- **Modular code design**  
- **Makefile automation**  

---  

## 📝 Supported Specifiers  
| Specifier | Function                   | Example Output          |  
|-----------|----------------------------|-------------------------|  
| `%c`      | `print_character.c`        | Prints a single character. |  
| `%s`      | `print_string.c`           | Prints a string.        |  
| `%d`, `%i`| `print_base_10.c`          | Signed base-10 integers.|  
| `%u`      | `print_uns_base_10.c`      | Unsigned base-10 integers.|  
| `%x`      | `print_hex_lower.c`        | Lowercase hexadecimal.  |  
| `%X`      | `print_hex_upper.c`        | Uppercase hexadecimal.  |  
| `%p`      | `get_pointer_address.c`    | Pointer address.        |  
| `%%`      | `print_character.c`        | Literal `%` character.  |  

---  

## 🔗 Key Concepts & Resources  
### Variadic Functions  
- [stdarg.h Documentation](https://en.cppreference.com/w/c/variadic)  
- [How Variadic Functions Work](https://www.gnu.org/software/libc/manual/html_node/Variadic-Functions.html)  

### Format Specifiers  
- [printf Format Specifiers](https://www.cplusplus.com/reference/cstdio/printf/)  

### Hexadecimal & Pointer Handling  
- [Hex Conversion in C](https://www.permadi.com/tutorial/numDecToHex/)  
- [Pointer Address Formatting](https://www.geeksforgeeks.org/format-specifiers-in-c/)  

---  

## 🔧 Installation  
```bash  
# 1. Download ft_printf.zip  
wget https://<your-repo-url>/ft_printf.zip  

# 2. Extract with password  
unzip -P gth-VXC3365 ft_printf.zip  

# 3. Compile  
cd ft_printf && make
```
## 📂 Project Structure

ft_printf/  
├── Makefile                 # Build rules  
├── ft_printf.h              # Header (macros, prototypes)  
├── ft_printf.c              # Main logic (format string parsing)  
├── builder.c                # Constructs the output string  
├── get_pointer_address.c    # %p specifier (pointer addresses)  
├── print_character.c        # %c and %%  
├── print_string.c           # %s  
├── print_base_10.c          # %d, %i (signed integers)  
├── print_hex_lower.c        # %x (lowercase hex)  
├── print_hex_upper.c        # %X (uppercase hex)  
└── print_uns_base_10.c      # %u (unsigned integers)  

## ✅ Compatibility: macOS, Linux. Requires gcc, make, and unzip.
