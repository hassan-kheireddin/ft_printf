# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: hkheired <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2024/06/21 14:17:42 by hkheired          #+#    #+#              #
#    Updated: 2024/06/21 14:18:57 by hkheired         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #
CC = cc
AR = ar rcs
CFLAGS = -Wall -Wextra -Werror -I../includes/
NAME = libft.a

SRC =	\
		ft_atoi.c\
        	ft_bzero.c\
        	ft_calloc.c\
        	ft_isalnum.c\
        	ft_isalpha.c\
        	ft_isascii.c\
        	ft_isdigit.c\
        	ft_isprint.c\
        	ft_memchr.c\
        	ft_memcmp.c\
        	ft_memcpy.c\
        	ft_memmove.c\
        	ft_memset.c\
		ft_strncmp.c\
        	ft_strchr.c\
        	ft_strdup.c\
        	ft_strlcat.c\
        	ft_strlcpy.c\
        	ft_strlen.c\
        	ft_strnstr.c\
        	ft_strrchr.c\
        	ft_tolower.c\
        	ft_toupper.c\
		ft_itoa.c\
		ft_split.c\
		ft_strjoin.c\
		ft_strmapi.c\
		ft_substr.c\
		ft_strtrim.c\
		ft_striteri.c\
		ft_putchar_fd.c\
		ft_putstr_fd.c\
		ft_putendl_fd.c\
		ft_putnbr_fd.c\

SRC_B =  \
		ft_lstdelone_bonus.c\
		ft_lstclear_bonus.c\
		ft_lstadd_back_bonus.c\
		ft_lstsize_bonus.c\
		ft_lstiter_bonus.c\
		ft_lstlast_bonus.c\
		ft_lstmap_bonus.c\
		ft_lstnew_bonus.c\
		ft_lstadd_front_bonus.c\

OBJ = $(SRC:.c=.o)

OBJ_B = $(SRC_B:.c=.o)

FLAGS = -Wall -Wextra -Werror

all: $(NAME)

$(NAME) : $(OBJ)
	$(AR) $(NAME) $(OBJ)

bonus: $(OBJ_B)
	$(AR) $(NAME) $(OBJ_B)

%.o : %.c
	$(CC) $(FLAGS) -c $< -o $@

clean:
	rm -rf $(OBJ) $(OBJ_B)

fclean: clean
	rm -rf $(NAME)

re: fclean all
.PHONY: all clean fclean re bonus
