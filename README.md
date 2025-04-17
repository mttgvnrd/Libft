# 📚 Libft - Your Custom C Library  

**42 Firenze Project | C Programming**  
*Rimplementazione di funzioni standard C + strutture dati aggiuntive, completa di parte obbligatoria e bonus.*  

---

## 📋 Specifiche  
✅ **Parte Obbligatoria**:  
   - 42 funzioni **libc** riimplementate (prefisso `ft_`)  
     - Manipolazione stringhe (`strlen`, `memcpy`, `atoi`, ...)  
     - Memoria dinamica (`calloc`, `strdup`)  
   - 15 funzioni **aggiuntive**  
     - `split`, `itoa`, `strmapi`, ...  
   - Makefile con regole `all`, `clean`, `fclean`, `re`  

✅ **Parte Bonus**:  
   - Implementazione di **liste concatenate** (`t_list`)  
   - 9 funzioni per gestione liste:  
     - `lstnew`, `lstadd_front`, `lstsize`, `lstlast`, ...  
     - `lstmap`, `lstclear`, `lstdelone`  

✅ **Conformità**:  
   - Norminette-compliant  
   - Zero memory leaks  
   - Compilazione con `-Wall -Wextra -Werror`  

---

## 🛠 Utilizzo  
```bash
git clone https://github.com/mttgvnrd/Libft.git
cd Libft
make        # Compila libft.a (obbligatorio)
make bonus  # Aggiunge le funzioni bonus

![Libft](https://img.shields.io/badge/Libft-Complete-brightgreen)
![Bonus](https://img.shields.io/badge/Bonus-Complete-green)
![Norm](https://img.shields.io/badge/Norminette-OK-blue)
