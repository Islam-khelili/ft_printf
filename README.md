# 🖨️ ft_printf

## 🧠 About

`ft_printf` is a custom implementation of the standard C function `printf`, developed as part of the 42 curriculum.
The goal of this project is to understand variadic functions, formatted output, and low-level data handling in C.

---

## 🚀 Features

* Reimplementation of `printf`
* Support for multiple format specifiers
* Handling of variadic arguments using `stdarg.h`
* Modular and reusable code structure

---

## 📌 Supported Format Specifiers

| Specifier | Description             |
| --------- | ----------------------- |
| `%c`      | Character               |
| `%s`      | String                  |
| `%p`      | Pointer                 |
| `%d`      | Decimal (int)           |
| `%i`      | Integer                 |
| `%u`      | Unsigned integer        |
| `%x`      | Hexadecimal (lowercase) |
| `%X`      | Hexadecimal (uppercase) |
| `%%`      | Percent sign            |

---

## ⚙️ Compilation

To compile the project:

```bash
make
```

This will generate the executable or object files depending on your Makefile.

---

## 🧪 Usage

Include the header:

```c
#include "ft_printf.h"
```

Example:

```c
ft_printf("Hello %s! Number: %d\n", "World", 42);
```

---

## 🧩 Project Structure

* `ft_printf.c` → main function
* `ft_printf_char.c` → character handling
* `ft_printf_hex.c` → hexadecimal conversion
* `ft_printf_nbr.c` → numbers
* `ft_printf_ptr.c` → pointer handling
* `ft_printf_u.c` → unsigned integers
* `ft_itoa.c` → integer to string conversion

---

## 🎯 Purpose

This project helps to:

* Understand variadic functions (`va_list`, `va_start`, `va_arg`, `va_end`)
* Improve low-level programming skills
* Learn how formatted output works internally

---

## 📌 Author

👤 Islam Khelili
42 Codam Student

---

⭐ If you like this project, feel free to star it!
