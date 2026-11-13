# Doxygen – Basic Introduction

## 1. What is Doxygen?

Doxygen is an open-source documentation generator. It extracts information from specially formatted comments in source code and generates documentation automatically.

It supports programming languages such as C, C++, Python and Java.

## 2. Why Do We Use Doxygen?

- To explain the purpose of classes and functions.
- To document function parameters and return values.
- To generate documentation automatically.
- To make code easier to understand and maintain.

## 3. Basic Doxygen Syntax

Doxygen comments can be written using:

```cpp
/**
 * Documentation goes here.
 */
```

### Common Doxygen Tags

| Tag | Purpose |
|---|---|
| `\brief` | Short description |
| `\param` | Describes a parameter |
| `\return` | Describes the return value |
| `\class` | Documents a class |
| `\file` | Documents a source file |
| `\author` | Specifies the author |
| `\version` | Specifies the version |
| `\note` | Adds an additional note |
| `\see` | References related items |

## 4. Example

See `example.cpp` for a simple Calculator class documented using Doxygen comments.

## 5. How Does Doxygen Work?

1. Write specially formatted comments in your source code.
2. Create a configuration file using `doxygen -g Doxyfile`.
3. Run Doxygen using `doxygen Doxyfile`.
4. Open the generated HTML documentation in a browser.

## 6. Output Formats

Doxygen can generate:
- HTML documentation
- LaTeX/PDF documentation
- XML
- RTF

## 7. Learning Reference

Based on the MNIT Jaipur lecture: *Introduction to Documentation Tools: Doxygen & Google Docs*.