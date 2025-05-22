# 🖨️ ft_printf

> A custom implementation of the standard C `printf()` function — fully formatted output, rebuilt from scratch.

## 📘 Project Description

**ft_printf** is a recreation of the C `printf()` function. The challenge is to handle formatted output with variable arguments, conversions, and flags — without relying on standard library formatting functions.

The goal is to understand variadic functions, string formatting, memory management, and output handling at a lower level.

---

## ✅ Supported Conversions

The following format specifiers are implemented:

| Specifier | Description               |
|-----------|---------------------------|
| `%c`      | Character                 |
| `%s`      | String                    |
| `%p`      | Pointer address           |
| `%d`      | Decimal (signed)          |
| `%i`      | Integer (signed)          |
| `%u`      | Unsigned decimal          |
| `%x`      | Hexadecimal (lowercase)   |
| `%X`      | Hexadecimal (uppercase)   |
| `%%`      | Percent sign              |

---

## 🛠️ Skills Learned

- Variadic functions with `<stdarg.h>`
- String and number conversion
- Manual parsing of format strings
- File descriptor output using `write()`
- Modular programming and memory safety

---

## 🔧 Compilation

```bash
make
