# libft

My own C standard library, written from scratch as the first project of the 42 Kuala Lumpur Core Programme (2024). Later projects reuse it.

## What's in it
- **libc re-implementations:** `strlen`, `memcpy`, `memmove`, `strlcpy`, `strlcat`, `strnstr`, `atoi`, `calloc`, `strdup` and others
- **String utilities:** `substr`, `strjoin`, `strtrim`, `split`, `itoa`, `strmapi`, `striteri`
- **File-descriptor output:** `putchar_fd`, `putstr_fd`, `putendl_fd`, `putnbr_fd`
- **Linked lists:** `lstnew`, `lstadd_front`, `lstadd_back`, `lstsize`, `lstlast`

## Build
```sh
make        # builds libft.a
make clean  # removes object files
```

Written to the 42 Norm: no `for` loops and functions of 25 lines or fewer. Graded by peer review and automated tests.
