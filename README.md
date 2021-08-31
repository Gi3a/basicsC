# Simple library implementation in C
____
## Use "make" to build the project
____
## The following functions have been implemented:
- :white_check_mark: atoi.c - converts the string argument str to an integer (type int).
- :white_check_mark: bzero.c - erases the data in the n bytes of the memory starting at the location pointed to by s, by writing zeros (bytes containing '\0') to that area.
- :white_check_mark: calloc.c - allocates memory for an array of num objects of size and initializes all bytes in the allocated storage to zero.
- :white_check_mark: isalnum.c - checks whether the argument passed is an alphanumeric character (alphabet or number) or not.
- :white_check_mark: isalpha.c - checks whether a character is an alphabet or not.
- :white_check_mark: isascii.c
- :white_check_mark: isdigit.c - checks whether a character is numeric character (0-9) or not.
- :white_check_mark: isprint.c - checks whether a character is a printable character or not.
- :white_check_mark: itoa.c - converts an integer value to a null-terminated string using the specified base and stores the result in the array given by str parameter.
- :white_check_mark: lstadd_back.c - Adds the element ’new’ at the end of the list.
- :white_check_mark: lstadd_front.c - Adds the element ’new’ at the beginning of the list.
- :white_check_mark: lstclear.c - Deletes and frees the given element and every successor of that element, using the function ’del’ and free().
- :white_check_mark: lstdelone.c - Takes as a parameter an element and frees the memory of the element’s content using the function ’del’ given as a parameter and free the element. The memory of ’next’ must not be freed.
- :white_check_mark: lstiter.c - Iterates the list ’lst’ and applies the function ’f’ to the content of each element.
- :white_check_mark: lstlast.c - Returns the last element of the list.
- :white_check_mark: lstmap.c - Iterates the list ’lst’ and applies the function ’f’ to the content of each element. Creates a new list resulting of the successive applications of the function ’f’. The ’del’ function is used to delete the content of an element if needed.
- :white_check_mark: lstnew.c -  returns a new element. The variable ’content’ is initialized with the value of the parameter ’content’. The variable ’next’ is initialized to NULL.
- :white_check_mark: lstsize.c - Counts the number of elements in a list.
- :white_check_mark: memccpy.c - copies bytes from src to dest, up to and including the first occurrence of the character c, or until cnt bytes have been copied, whichever comes first.
- :white_check_mark: memchr.c - returns a pointer to the matching byte or NULL if the character does not occur in the given memory area.
- :white_check_mark: memcpy.c - copies n characters from the object pointed to by s2 into the object pointed to by s1. It returns a pointer to the destination.
- :white_check_mark: memcmp.c - compares the first n bytes of memory area str1 and memory area str2.
- :white_check_mark: memmove.c - copies n characters from str2 to str1, but for overlapping memory blocks, memmove() is a safer approach than memcpy().
- :white_check_mark: memset.c - copies the character c (an unsigned char) to the first n characters of the string pointed to, by the argument str.
- :white_check_mark: putchar_fd.c - Outputs the character ’c’ to the given file descriptor.
- :white_check_mark: putendl_fd.c - Outputs the string ’s’ to the given file descriptor, followed by a newline.
- :white_check_mark: putnbr_fd.c - Outputs the integer ’n’ to the given file descriptor.
- :white_check_mark: putstr_fd.c - Outputs the string ’s’ to the given file descriptor.
- :white_check_mark: split.c - Allocates and returns an array of strings obtained by splitting ’s’ using the character ’c’ as a delimiter. The array must be ended by a NULL pointer.
- :white_check_mark: strchr.c - searches for the first occurrence of the character c (an unsigned char) in the string pointed to by the argument str.
- :white_check_mark: strdup.c - Returns a pointer to a null-terminated byte string, which is a duplicate of the string pointed to by str1. The returned pointer must be passed to free to avoid a memory leak.
- :white_check_mark: strjoin.c - returns a new string, which is the result of the concatenation of ’s1’ and ’s2’.
- :white_check_mark: strlcat.c - appends the NUL-terminated string src to the end of dst. It will append at most size - strlen(dst) - 1 bytes, NUL-terminating the result.
- :white_check_mark: strlcpy.c -  copies up to size - 1 characters from the NUL-terminated string src to dst, NUL-terminating the result.
- :white_check_mark: strlen.c - calculates the length of a given string.
- :white_check_mark: strmapi.c - Applies the function ’f’ to each character of the string ’s’ to create a new string (with malloc(3))resulting from successive applications of ’f’.
- :white_check_mark: strncmp.c - compares at most the first n bytes of str1 and str2.
- :white_check_mark: strnstr.c - locates the	first occurrence of the	null-terminated string little in the	string big, where not more than	len characters are searched.  Characters that appear after a `\0'	character are not searched.	
- :white_check_mark: strrchr.c - searches for the last occurrence of the character c (an unsigned char) in the string pointed to, by the argument str.
- :white_check_mark: strtrim.c - returns a copy of ’s1’ with the characters specified in ’set’ removed from the beginning and the end of the string.
- :white_check_mark: substr.c -  returns a substring from the string ’s’. The substring begins at index ’start’ and is of maximum size ’len’.
- :white_check_mark: tolower.c - takes an uppercase alphabet and convert it to a lowercase character.
- :white_check_mark: toupper.c - converts a lowercase alphabet to an uppercase alphabet.