## libft prefácios

O objectivo desse projecto é refazer um conjunto de funções da libc. Suas funções terão o
mesmos protótipos e implementam os mesmos comportamentos dos originais. Eles devem cumprir
com a forma como são definidos em seu homem. A única diferença serão seus nomes. Eles
começará com o prefixo ‘ft_’. Por exemplo, strlen torna-se ft_strlen.

## Funções que devemos replicar

• isalpha
• isdigit
• isalnum
• isascii
• isprint
• strlen
• memset
• bzero
• memcpy
• memmove
• strlcpy
• strlcat
• toupper
• tolower
• strchr
• strrchr
• strncmp
• memchr
• memcmp
• strnstr
• atoi

Para implementar as duas funções a seguir, você usará malloc():

• calloc
• strdup

## Funções adicionais

É importante lembrar de que essa funções adicionais não fazer parte de  bíclioteca libc, mas no enúciado do projecto está todas as instruções para a criação das funções

•  ft_substr
•  ft_strjoin
•  ft_strtrim
•  ft_split
•  ft_itoa
•  ft_strmapi
•  ft_striteri
•  ft_putchar_fd
•  ft_putstr_fd
•  ft_putendl_fd
•  ft_putnbr_fd

## Parte do Bonus
Essa parte é apenas de Bonus, não é obrigatória mas é muito importante para entender alguns conceitos de listas, que posteriormente podem vir nos exames
ATENÇÃO: o BONUS apenas será aceite de  a parte obrigatória toda estiver certa;

No teu arquivo decabeçalho(libft.h) deve ir essa estrutura :
typedef struct s_list
{
      void *content;
      struct s_list *next;
}            t_list;

Com base nessa estrutura deve criar as  seguintes funções
•  ft_lstnew
•  ft_lstadd_front
•  ft_lstsize
•  ft_lstlast
•  ft_lstadd_back
•  ft_lstdelone
•  ft_lstclear
•  ft_lstiter
•  ft_lstmap
