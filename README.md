# 📚 Libft

## Project Description

'Libft is a library of various C functions that are commonly used in programming. It contains functions for memory manipulation, string manipulation, linked lists, and more. This library is designed to be reusable across multiple projects, providing a foundation of common functionalities.'

## 🛠️ Installation Instructions

1. Clone the repository using the command:

        git clone https://github.com/redarling/Libft-42.git

2. Navigate to the project directory:

        cd Libft-42

3. Compile the library:

        make

## 💻 Usage

1. Create your main file (you should be in the Libft-42 folder):

        touch main.c

2. Go into this .c file:

        vim main.c

3. Include the header file in your project:

        # include "libft.h"

4. Now you can use a lot of functions from this library in your code (here is an example):

        #include "libft.h"
        #include <stdio.h>

        int main(void)
        {
                char    *line;
                char    **splited_line;
                int             i;

                i = -1;
                line = ft_strdup("Hello, World! It's my first code");
                if (!line)
                        return (1);
                splited_line = ft_split(line, ' ');
                if (!splited_line)
                        return (1);
                while (i++, splited_line[i])
                        printf("%s\n", splited_line[i]);
                return (0);
        }

5. Save and close, then type the following commands:

        cc main.c libft.a

        ./a.out

7. Output:

        Hello,
        World!
        It's
        my
        first
        code

## 📝 Author
- [asyvash](https://github.com/redarling)
