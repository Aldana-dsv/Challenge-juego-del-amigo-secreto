# 🎁 Proyecto Amigo Secreto

Este proyecto es una pequeña aplicación que permite organizar un **Amigo Secreto** (también conocido como "Amigo Invisible"). Su objetivo principal es automatizar el proceso de ingresar los nombres de los participantes y asignar aleatoriamente a quién le debe regalar cada persona, garantizando que nadie se asigne a sí mismo.

---

## ⚙️ Funcionalidades
   Permite agregar todos los nombres de los participantes
   Realiza un sorteo aleatorio con los nombres ingresados 

---

## Estructura del Proyecto

```bash
amigo-secreto/
├── main.py              # Script principal que ejecuta el programa
├── sorteador.py         # Lógica del sorteo aleatorio
├── participantes.txt    # (opcional) Lista de nombres cargados desde archivo
└── README.md            # Documentación del proyecto
```

---

## Cómo usar

1. Ejecuta el script principal
2. Ingresa los nombres uno por uno o carga una lista desde archivo.
3. Ejecuta el sorteo.
4. Visualiza o guarda el resultado.

---

## Ejemplo de uso

```
Ingrese un nombre (o escriba 'fin' para terminar): Ana
Ingrese un nombre (o escriba 'fin' para terminar): Pablo
Ingrese un nombre (o escriba 'fin' para terminar): Laura
Ingrese un nombre (o escriba 'fin' para terminar): fin

Realizando el sorteo...

Sorteo completado:
- Ana → Pablo
- Pablo → Laura
- Laura → Ana
```



