# libft

Codam [42 Network] project: the aim of this project is to code a C library which includes recoding standard C library functions as well as coding utility functions designed by 42. The bonus functions are specifically for linked lists.
<br/><br/>

## Instructions
- run `make` to compile and create the `libft.a` library
- write a simple main such as this:
``` C
#include "libft.h"
#include <stdio.h>
#include <stdlib.h>

int main()
{
  char  **str;
  int   i;
  
  str = ft_split("split,this,string,on,commas", ',');
  i = 0;
  while (str[i] != NULL)
  {
    printf("str[i] = %s\n", str[i]);
    free(str[i]);
    i++;
  }
  free(str);
  return(0);
}
```
- now compile with `gcc main.c -L. -lft` and run program `./a.out`
<br/><br/>

## Skills
- imperative programming
- algorithms and AI
<br/><br/>

## Objectives
- Unix logic  
<br/><br/>

## Functions
| libc | 42 utility | 42 linked list |
| :------------- | :------------| :------------------- |
| memset | ft_substr | ft_lstnew |
| bzero | ft_strjoin | ft_lstadd_front |
| memcpy | ft_strtrim | ft_lstsize |
| memccpy | ft_split | ft_lstlast |
| memmove | ft_itoa | ft_lstadd_back |
| memchr | ft_strmapi | ft_lstdelone |
| memcmp | ft_putchar_fd | ft_lstclear |
| strlen | ft_putstr_fd | ft_lstiter |
| strlcpy | ft_putendl_fd | ft_lstmap |
| strlcat | ft_putnbr_fd | |
| strchr ||
| strrchr ||
| strnstr ||
| strncmp ||
| atoi ||
| isalpha ||
| isdigit ||
| isalnum ||
| isascii ||
| isprint ||
| toupper ||
| tolower ||
| calloc ||
| strdup ||
