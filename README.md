# Pong Game

Este es un juego de Pong clásico implementado en Java 21. El proyecto es una simple recreación del famoso juego de arcade, donde dos jugadores compiten para golpear una pelota con paletas (paddles) y marcar puntos.

## Características

- Juego de Pong clásico para dos jugadores.
- Controles sencillos para cada jugador.
- Sistema de puntuación.
- Movimiento y colisión de la pelota.
- Interfaz gráfica simple y eficiente usando `javax.swing` y `java.awt`.

## Interfaz

![Captura de pantalla 2024-08-09 025228](https://github.com/user-attachments/assets/4a077f2f-1d9b-4164-92f0-95ac67f47c50)


## Requisitos del Sistema

- Java 21 o superior.
- Entorno de desarrollo compatible con proyectos Java (por ejemplo, IntelliJ IDEA, Eclipse, etc.).

## Cómo Ejecutar el Juego

1. **Clona el repositorio** : https://github.com/SoyRafaelDev/ping_pong_game.git
2. Compila y ejecuta el proyecto:

Si estás usando un IDE, importa el proyecto como un proyecto Java y ejecuta la clase PongGame.

------------------------------------------------------------------------
Controles del Juego
Jugador 1:

W: Mover la paleta hacia arriba.
S: Mover la paleta hacia abajo.

Jugador 2:

↑: Mover la paleta hacia arriba.
↓: Mover la paleta hacia abajo.

Estructura del Código

PongGame.java: La clase principal que inicia el juego.
GameFrame.java: Configura la ventana del juego.
GamePanel.java: Maneja el panel del juego, incluyendo la lógica de dibujo, movimiento y colisiones.
Paddle.java: Representa las paletas controladas por los jugadores.
Ball.java: Representa la pelota en el juego.
Score.java: Gestiona y dibuja el marcador del juego.

Mejoras Futuras
Algunas ideas para mejorar el juego:

Implementar modos de juego adicionales (por ejemplo, un solo jugador contra la IA).
Agregar efectos de sonido.
Mejorar la interfaz gráfica.
Añadir niveles de dificultad.

Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar el código, por favor haz un fork de este repositorio y envía un pull request.
