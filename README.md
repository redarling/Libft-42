# 📚 Libft

## Project Description

Libft is a library of various C functions that are commonly used in programming. It contains functions for memory manipulation, string manipulation, linked lists, and more. This library is designed to be reusable across multiple projects, providing a foundation of common functionalities.

## 🛠️ Installation Instructions

1. Clone the repository using the command:

        git clone

2. Navigate to the project directory:

        cd Libft-42

3. Compile the library:

        make

## 💻 Usage

1. Include the header file in your project:

        # include "libft.h"

2. Now you can use a lot of functions from this library in your code:

        char  *line;
        chsr  **splited_line;
        int    i;

        i = -1;
        line = ft_strdup("Hello, World! It's my first code");
        if (!line)
          return (1);
        splited_line = ft_split(line);
        if (!splited_line)
          return (1);
        while (i++, splited_line[i])
               printf("%s\n", splited_line[i]);
        return (0);

## 📝 Author
- [asyvash](https://github.com/redarling)
