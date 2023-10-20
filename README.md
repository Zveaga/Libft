# Libft
The project's aim is to create a custom C library by recoding functions of the C standard library and additional utility functions.

## Key Concepts
- Data structures
- String manipulation
- Memory manipulation
- Working with linked lists



## How To Use

## Library contents
### String manipulation functions

|                               Functions                              |
|                                   -                                  |
|[ft_isalnum](https://github.com/Zveaga/Libft/blob/master/ft_isalnum.c) -> alphanumeric character test|
|[ft_isalpha](https://github.com/Zveaga/Libft/blob/master/ft_isalpha.c) -> alphabetic character test|
|[ft_isascii](https://github.com/Zveaga/Libft/blob/master/ft_isascii.c) -> test for ASCII character|
|[ft_isdigit](https://github.com/Zveaga/Libft/blob/master/ft_isdigit.c) -> decimal-digit character test
|[ft_isprint](https://github.com/Zveaga/Libft/blob/master/ft_isprint.c) -> printing character test|
|[ft_strchr](https://github.com/Zveaga/Libft/blob/master/ft_strchr.c) -> locate character in string (first occurence)|
|[ft_strrchr](https://github.com/Zveaga/Libft/blob/master/ft_strrchr.c) -> locate character in string (last occurence)|
|[ft_strdup](https://github.com/Zveaga/Libft/blob/master/ft_strdup.c) -> create a copy of a string|
|[ft_strlcat](https://github.com/Zveaga/Libft/blob/master/ft_strlcat.c) -> size-bounded string concatenation|
|[ft_strlcpy](https://github.com/Zveaga/Libft/blob/master/ft_strlcpy.c) -> size-bounded string copying|
|[ft_strlen](https://github.com/Zveaga/Libft/blob/master/ft_strlen.c) -> find length of string|
|[ft_strncmp](https://github.com/Zveaga/Libft/blob/master/ft_strncmp.c) -> compare strings|
|[ft_strnstr](https://github.com/Zveaga/Libft/blob/master/ft_strnstr.c) -> locate a substring in a string|
|[ft_tolower](https://github.com/Zveaga/Libft/blob/master/ft_tolower.c) -> upper case to lower case letter conversion|
|[ft_toupper](https://github.com/Zveaga/Libft/blob/master/ft_toupper.c) -> lower case to upper case letter conversion|

### Memory manipulation functions

|                               Functions                              |
|                                   -                                  |
|[ft_bzero](https://github.com/Zveaga/Libft/blob/master/ft_bzero.c) -> erases data in a string by writing zeros ('\0')|
|[ft_calloc](https://github.com/Zveaga/Libft/blob/master/ft_calloc.c) -> dinnamically allocate memory and set the memory to zero ('\0')|
|[ft_memchr](https://github.com/Zveaga/Libft/blob/master/ft_memchr.c) -> scan memory for a character|
|[ft_memcmp](https://github.com/Zveaga/Libft/blob/master/ft_memcmp.c) -> compare memory areas|
|[ft_memcpy](https://github.com/Zveaga/Libft/blob/master/ft_memcpy.c) -> copy memory area (strings cannot overlap)|
|[ft_memmove](https://github.com/Zveaga/Libft/blob/master/ft_memmove.c) -> copy memory area (strings can overlap|
|[ft_memset](https://github.com/Zveaga/Libft/blob/master/ft_memset.c) -> fill a byte string with a byte value|



### Linked lists functions

|                               Functions                              |
|                                   -                                  |
|[ft_lstadd_front](https://github.com/Zveaga/Libft/blob/master/ft_lstadd_front.c) -> add a new node at the beginning of the list|
|[ft_lstlast](https://github.com/Zveaga/Libft/blob/master/ft_lstlast.c) -> return the last node of the list|
|[ft_lstnew](https://github.com/Zveaga/Libft/blob/master/ft_lstnew.c) -> create a new node|
|[ft_lstsize](https://github.com/Zveaga/Libft/blob/master/ft_lstsize.c) -> count the number of nodes in a list|
|[ft_](https://github.com/Zveaga/Libft/blob/master/ft_.c) -> |count


### Additional functions

|                               Functions                              |
|                                   -                                  |
|[ft_atoi](https://github.com/Zveaga/Libft/blob/master/ft_atoi.c) -> convert ASCII string to integer|
|[ft_itoa](https://github.com/Zveaga/Libft/blob/master/ft_itoa.c) -> convert integer to ASCII string|
|[ft_putchar_fd](https://github.com/Zveaga/Libft/blob/master/ft_putchar_fd.c) -> output the character ’c’ to the given file descriptor|
|[ft_putendl_fd](https://github.com/Zveaga/Libft/blob/master/ft_putendl_fd.c) -> output the string ’s’ to the given file descriptor, followed by a newline|
|[ft_putnbr_fd](https://github.com/Zveaga/Libft/blob/master/ft_putnbr_fd.c) -> output the integer ’n’ to the given file descriptor|
|[ft_putstr_fd](https://github.com/Zveaga/Libft/blob/master/ft_putstr_fd.c) -> output the string ’s’ to the given file descriptor|
|[ft_split](https://github.com/Zveaga/Libft/blob/master/ft_ft_split.c) -> split a string into an array of strings based on a delimiter character|
|[ft_striteri](https://github.com/Zveaga/Libft/blob/master/ft_striteri.c) -> applies the function ’f’ on each character of a string|
|[ft_strmapi](https://github.com/Zveaga/Libft/blob/master/ft_strmapi.c) -> applies the function ’f’ on each character of a string to create a new string|
|[ft_strjoin](https://github.com/Zveaga/Libft/blob/master/ft_strjoin.c) -> concatenate two strings|
|[ft_substr](https://github.com/Zveaga/Libft/blob/master/ft_substr.c) -> create a substring from a string|
|[ft_strtrim](https://github.com/Zveaga/Libft/blob/master/ft_strtrim.c) -> trim a character set from a string|

## Remarks
Most of these functions are already implemented and available to us from the C standard library, so you might ask yourselves, why spending the time to recode these functions that are readily available to us? That was my question too, but it slowly became obvious why. It played a crucial role in forming how 
