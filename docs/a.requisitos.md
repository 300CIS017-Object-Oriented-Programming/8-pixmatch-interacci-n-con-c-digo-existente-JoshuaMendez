## Requisitos Funcionales y Criterios de Aceptación
### 1. Configuración de Nivel de Dificultad
**Requisito:** El sistema debe permitir a los jugadores seleccionar el nivel de dificultad antes de comenzar el juego.

**Criterios de Aceptación:**
- Opciones de dificultad fácil, medio y difícil disponibles para selección.
- La configuración de dificultad debe influir en la mecánica del juego, como la frecuencia de regeneración de imágenes y la puntuación.
- Tiempos de regeneración específicos:
  - Fácil: cada 8 segundos.
  - Medio: cada 6 segundos.
  - Difícil: cada 5 segundos.

### 2. Gestión de tablero de juego

**Requisito:** El sistema debe generar, mostrar y gestionar un tablero de juego con casillas vacías que contengan emojis aleatorios. Al menos un emoji debe coincidir con el emoji de referencia mostrado en la barra lateral. El usuario debe poder seleccionar una casilla del tablero.

**Criterios de aceptación:**

- El tablero de juego debe generarse con la cantidad correcta de casillas vacías según el nivel de dificultad seleccionado.
- Cada casilla del tablero debe mostrar un emoji aleatorio diferente.
- Al menos una casilla del tablero debe mostrar el mismo emoji que el emoji de referencia en la barra lateral.
- El usuario debe poder seleccionar una casilla del tablero haciendo clic en ella.

### 3. Selección de emojis

**Requisito:** El sistema debe mostrar un emoji de referencia en la barra lateral y asociar un emoji con cada casilla del tablero. Al seleccionar una casilla, el sistema debe revelar el emoji asociado y comparar si coincide con el emoji de referencia.

**Criterios de aceptación:**

- El emoji de referencia debe mostrarse claramente en la barra lateral.
- Cada casilla del tablero debe tener un emoji asociado aleatoriamente.
- Al seleccionar una casilla, el emoji asociado debe revelarse visualmente.
- El sistema debe comparar el emoji revelado con el emoji de referencia y determinar si la respuesta del usuario es correcta o incorrecta.

### 4. Validación de respuestas

**Requisito:** El sistema debe comparar el emoji de la casilla seleccionada con el emoji de referencia, indicar si la respuesta del usuario es correcta o incorrecta, y actualizar el puntaje del jugador en consecuencia.

**Criterios de aceptación:**

- El sistema debe comparar correctamente el emoji de la casilla seleccionada con el emoji de referencia.
- El sistema debe indicar claramente si la respuesta del usuario es correcta o incorrecta, utilizando feedback visual (por ejemplo, cambio de color de la casilla).
- El sistema debe actualizar el puntaje del jugador en uno por cada respuesta correcta.
- El sistema no debe actualizar el puntaje del jugador por respuestas incorrectas.

### 5. Gestión de puntaje

**Requisito:** El sistema debe inicializar el puntaje del jugador en cero, incrementarlo en uno por cada respuesta correcta y mostrar el puntaje actual en la pantalla.

**Criterios de aceptación:**

- El puntaje del jugador debe inicializarse en cero al iniciar el juego.
- El puntaje del jugador debe incrementarse por cada respuesta correcta.
- El puntaje actual del jugador debe mostrarse claramente en la pantalla durante el juego.
- El puntaje del jugador no debe modificarse de forma incorrecta (por ejemplo, por respuestas incorrectas o errores del sistema).
Requisito 5: Control de juego

### 6. Control del Juego

**Requisito:** El sistema debe permitir al usuario iniciar y detener el juego, restablecer el tablero de juego y el puntaje del jugador, y mostrar un mensaje de victoria o derrota al final del juego.

**Criterios de aceptación:**

- El usuario debe poder iniciar el juego haciendo clic en un botón o utilizando un atajo de teclado.
- El usuario debe poder detener el juego en cualquier momento haciendo clic en un botón o utilizando un atajo de teclado.
- El usuario debe poder restablecer el tablero de juego y el puntaje del jugador haciendo clic en un botón o utilizando un atajo de teclado.
- Al finalizar el juego, el sistema debe mostrar un mensaje de victoria si el usuario ha completado todas las respuestas correctamente o un mensaje de derrota si no lo ha hecho.

### 7. Interfaz de usuario

**Requisito:** El sistema debe proporcionar una interfaz de usuario atractiva, fácil de usar e intuitiva, utilizando elementos visuales como emojis e imágenes para representar el juego y proporcionando instrucciones claras sobre cómo jugar.

**Criterios de aceptación:**

- La interfaz de usuario debe ser visualmente atractiva y utilizar colores y diseños que sean agradables a la vista.
- La interfaz de usuario debe ser fácil de usar y navegar, con elementos intuitivos y una disposición lógica.
- La interfaz de usuario debe utilizar