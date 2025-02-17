# ft_printf

![C Language](https://img.shields.io/badge/C-Programming-blue.svg) ![Makefile](https://img.shields.io/badge/Makefile-Build-orange.svg) ![Git](https://img.shields.io/badge/Git-Version%20Control-red.svg) ![Norminette](https://img.shields.io/badge/Norminette-Code%20Style-brightgreen.svg)

## 📌 Descripción

El proyecto **ft_printf** tiene como objetivo crear una implementación personalizada de la función `printf` en C. A través de este proyecto, se profundiza en el formato de salida, la gestión de parámetros variables y la conversión de tipos. Este desafío es fundamental para comprender mejor la manipulación de cadenas y la salida formateada en C, brindando una oportunidad para reforzar conocimientos sobre el uso de funciones variádicas y la optimización del procesamiento de datos en el lenguaje C.

## 🛠 Lenguajes y Tecnologías

- **C**
- **GIT**
- **Makefile**
- **Norminette**
- **File descriptors**
- **Variables estáticas**

## 💡 Conceptos de Programación Aplicados

- Manipulación de Cadenas
- Conversión de Tipos
- Formato de Salida

## 📂 Estructura del Proyecto

```
ft_printf
├── Makefile
├── README.md
├── includes
│   └── ft_printf.h
└── src
    ├── ft_print_char.c
    ├── ft_print_hex.c
    ├── ft_print_hexcap.c
    ├── ft_print_int.c
    ├── ft_print_punt.c
    ├── ft_print_str.c
    ├── ft_print_uint.c
    └── ft_printf.c
```

## 🚀 Instalación y Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/RikiGuerrero/ft_printf.git
   cd ft_printf
2. Compilar la librería:
   ```bash
   make
3. Incluir libftprintf.a en tu proyecto:
   ```bash
   #include "includes/ft_printf.h"

## 🎯 Ejemplo de Uso

### Puedes probar `ft_printf` en un archivo de prueba:
```c
#include "includes/ft_printf.h"

int main() {
    ft_printf("Hola, %s! Tienes %d mensajes.\n", "usuario", 5);
    return 0;
}
```
### Salida:
```bash
Hola, usuario! Tienes 5 mensajes.
```

## ✅ Normas y Estilo de Código

El código sigue las reglas de la **Norminette**, la herramienta de estilo de 42. Para verificar:
```bash
norminette
```

## 📜 Licencia

Este proyecto es parte del currículo de 42 y sigue las reglas de la escuela.
