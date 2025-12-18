# Poker 21 Game

Juego de cartas inspirado en el clásico 21 (Blackjack), desarrollado en JavaScript puro, donde el jugador debe sumar cartas hasta acercarse lo más posible a 21 puntos sin pasarse.

El proyecto está pensado como práctica de lógica de programación, manipulación básica del DOM, y estructura de proyectos frontend, manteniendo un código claro y progresivamente optimizado.

## ¿Cómo funciona el juego?

* El jugador recibe cartas de forma aleatoria.

* Cada carta tiene un valor numérico.

* El objetivo es llegar a 21 puntos o quedar lo más cerca posible.

* Si el jugador supera los 21 puntos, pierde automáticamente.

* La computadora juega después del jugador siguiendo reglas básicas.

## Vista general

El juego cuenta con:

* Mesa estilo casino (fondo verde)

* Cartas apiladas dinámicamente

* Botones interactivos:

    * Nuevo Juego

    * Pedir Carta

    * Detener

## Tecnologías utilizadas
* HTML5 – Estructura del juego

* CSS3 – Estilos y diseño visual

* JavaScript (Vanilla) – Lógica del juego y DOM

* Bootstrap 5 – Estilos base y botones

* Underscore.js – Utilidades para manejo de datos

## Estructura del proyecto

Poker-21-Game/
* │
* ├── index.html
* ├── assets/
* │ ├── css/
* │ │ └── style.css
* │ ├── js/
* │ │ ├── juego.js
* │ │ └── underscore-min.js
* │ ├── cartas/ # imagenes de las cartas
* │ └── poker-icon.png
* └── README.md

## Cómo ejecutar el proyecto

1. Clona este repositorio:
```
git clone https://github.com/Mauricio-Codes/poker-21-game.git
```

2. Abre el archivo index.html en tu navegador o usa una extensión como Live Server en VS Code.

## Objetivos del proyecto

* Practicar lógica de programación en JavaScript

* Reforzar el uso de condicionales, ciclos y funciones

* Aplicar manipulación básica del DOM

# Estado del proyecto

* Juego funcional
* Interfaz completa
* Lógica implementada 
* Optimización y refactorización en progreso

* Demo online disponible: https://poker21game.netlify.app/