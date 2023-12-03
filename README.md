# Libft - My Very First Own Library

## Summary
Libft is a C library project that focuses on coding a collection of general-purpose functions that your programs can rely upon. This library will serve as a valuable tool for your C programming assignments, providing a set of functions that mimic the behavior of standard libc functions. The goal is to understand, implement, and learn to use these functions, creating your own library for future projects.

**Version:** 16

## Table of Contents
I. [Introduction](#introduction)  
II. [Common Instructions](#common-instructions)  
III. [Mandatory Part](#mandatory-part)  
   - III.1 [Technical Considerations](#technical-considerations)  
   - III.2 [Part 1 - Libc Functions](#part-1-libc-functions)  
   - III.3 [Part 2 - Additional Functions](#part-2-additional-functions)  
IV. [Bonus Part](#bonus-part)  
V. [Submission and Peer-evaluation](#submission-and-peer-evaluation)

## I. Introduction
C programming can be challenging without access to standard functions. Libft aims to address this by providing a custom C library with essential functions. As you create and expand your library throughout the year, ensure functions align with project guidelines when used in new assignments.

## II. Common Instructions
- Project must be written in C.
- Adhere to the Norm: Norm errors result in a grade of 0.
- Functions should not cause unexpected errors (e.g., segmentation faults).
- Free heap memory appropriately; no memory leaks are tolerated.
- Include a Makefile with required rules.
- Encouraged to create test programs, though not graded.
- Submit work to the assigned git repository for grading.

## III. Mandatory Part

### III.1 Technical Considerations
- No global variables allowed.
- Use static functions for helper functions.
- Place all files at the root of the repository.
- Do not turn in unused files.
- All `.c` files must compile with `-Wall -Wextra -Werror`.
- Use `ar` to create the library; `libtool` is forbidden.
- `libft.a` must be created at the root.

### III.2 Part 1 - Libc Functions
Implement custom versions of standard libc functions:
• `ft_isalpha`
• `ft_isdigit`
• `ft_isalnum`
• `ft_isascii`
• `ft_isprint`
• `ft_strlen`
• `ft_memset`
• `ft_bzero`
• `ft_memcpy`
• `ft_memmove`
• `ft_strlcpy`
• `ft_strlcat`
• `ft_toupper`
• `ft_tolower`
• `ft_strchr`
• `ft_strrchr`
• `ft_strncmp`
• `ft_memchr`
• `ft_memcmp`
• `ft_strnstr`
• `ft_atoi`
• `ft_calloc`
• `ft_strdup`

### III.3 Part 2 - Additional Functions
Develop new functions not in libc or with variations:
• `ft_substr`
• `ft_strjoin`
• `ft_strtrim`
• `ft_split`
• `ft_itoa`
• `ft_strmapi`
• `ft_striteri`
• `ft_putchar_fd`
• `ft_putstr_fd`
• `ft_putendl_fd`
• `ft_putnbr_fd`

## IV. Bonus Part
Extend functionality with linked list operations. Ensure perfection in the mandatory part for bonus evaluation. Use the provided `t_list` structure for linked lists.

## V. Submission and Peer-evaluation
Submit your work to the assigned git repository. Peer evaluations are followed by grading by Deepthought. Ensure perfection in the mandatory part for bonus evaluation.

Feel free to use this library for your future C projects, and enjoy coding!
