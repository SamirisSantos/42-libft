# Libft
![C Language](https://img.shields.io/badge/language-C-blue.svg)
![Status](https://img.shields.io/badge/status-finished-brightgreen)
![42 100/100](https://img.shields.io/badge/42-100%2F100-gree?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
-
 ## 🧠Funções da Biblioteca Padrão (Standard Library)
A libft consiste em reimplementar muitas funções da biblioteca C (<string.h>, <ctype.h>, <stdlib.h>).

💡 Isso permite entender a lógica e os algoritmos por trás das funções da biblioteca padrão do C.

## 📚 Conteúdo

Esta biblioteca implementa funções divididas nas seguintes categorias:

- **Manipulação de memória:** `memset`, `memcpy`, `memmove`, `memchr`, `memcmp`, `bzero`
- **Alocação dinâmica:** `calloc`, `strdup`
- **Manipulação de strings:** `strlen`, `strlcpy`, `strlcat`, `strchr`, `strncmp`, `substr`, `strjoin`, `split`, `strmapi`, `striteri`
- **Verificação de caracteres:** `isalpha`, `isdigit`, `isalnum`, `isascii`, `isprint`
- **Conversão de caracteres:** `toupper`, `tolower`
- **Conversão de strings:** `atoi`, `itoa`
- **Escrita em ficheiros:** `putchar_fd`, `putstr_fd`, `putendl_fd`, `putnbr_fd`

## 🧱 Estrutura da Libft
- Ficheiro libft.h com as declarações das funções.
- Makefile para compilar a biblioteca (libft.a).
- Os ficheiros *.c implementam as funções.

## 🛠️ Compilação

Para compilar a biblioteca, basta usar o `Makefile`:

```bash
make            # Compila libft.a
make clean      # Remove os ficheiros objetos (.o)
make fclean     # Remove os ficheiros objetos e libft.a
make re         # Limpa e recompila tudo
```
## 📁 Estrutura do Projeto
```bash
libft/
├── ft_*.c            # Implementações das funções
├── libft.h           # Header com todas as declarações
├── Makefile          # Para compilar a biblioteca
└── libft.a           # Arquivo gerado com as funções compiladas criado via Makefile
```
## 📝 Uso de FD (File Descriptor)
Algumas funções como putstr_fd escrevem em ficheiros usando o número do descritor:

- fd = 0: stdin
- fd = 1: stdout
- fd = 2: stderr

Outros números: ficheiros abertos com open()

## 🧪 Testes
Testers externos:
- [libft-unit-test](https://github.com/alelievr/libft-unit-test)
- [moulitest](https://github.com/yyang42/moulitest)
- [libft-war-machine](https://github.com/0x050f/libft-war-machine)
- [francinette](https://github.com/xicodomingues/francinette)
---
👩‍💻 Autora
Samiris Santos — [LinkedIn](https://www.linkedin.com/in/samiris-santos/)
