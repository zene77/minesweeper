
#  Minesweeper AI — CS50 Artificial Intelligence

Implementación del clásico juego **Minesweeper (Buscaminas)** con un agente inteligente capaz de analizar el tablero, actualizar conocimiento y tomar decisiones basadas en lógica.  
Proyecto desarrollado como parte del curso **CS50’s Introduction to Artificial Intelligence with Python** (Harvard).

---

##  Objetivo del Proyecto

Construir un agente capaz de:

- Analizar el estado del tablero.
- Identificar casillas seguras y posibles minas.
- Actualizar conocimiento tras cada movimiento.
- Tomar decisiones basadas en reglas lógicas.
- Jugar automáticamente cuando el usuario lo desee.

---

##  ¿Cómo funciona la IA?

El agente utiliza:

- **Conocimiento acumulado** sobre casillas reveladas.
- **Conteo de minas cercanas** para generar reglas.
- **Inferencia lógica** para deducir:
  - Casillas seguras.
  - Casillas que contienen minas.
- **Movimientos aleatorios controlados** cuando no existe deducción posible.

El flujo general es:

1. El usuario o la IA selecciona una casilla.
2. El juego revela el número de minas cercanas.
3. La IA actualiza su conocimiento.
4. Se generan nuevas inferencias.
5. Se decide el siguiente movimiento.

---

##  Estructura del Proyecto

```
minesweeper/
│── assets/             # Recursos gráficos (imágenes, iconos, etc.)
│── minesweeper.py      # Lógica del tablero y reglas del juego
│── runner.py           # Interfaz gráfica y bucle principal del juego
│── requirements.txt    # Dependencias del proyecto
│── README.md           # Documentación del proyecto
```

---

##  Cómo ejecutar el proyecto

### 1. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 2. Ejecutar el juego

```bash
python runner.py
```

El juego abrirá una ventana gráfica donde podrás:

- Jugar manualmente.
- Observar cómo la IA analiza el tablero.
- Ver el proceso de inferencia en tiempo real.

---

##  Características principales

- Interfaz gráfica con **Pygame**.
- Lógica de inferencia basada en reglas.
- Deducción automática de casillas seguras.
- Marcado automático de minas.
- Movimientos inteligentes y aleatorios cuando es necesario.
- Código modular y fácil de extender.

---

##  Tecnologías utilizadas

- Python 3  
- Pygame  
- Estructuras de datos  
- Lógica e inferencia  

---

##  Autor
 
Proyecto académico — CS50 AI (Harvard)

---

## 📄 Licencia

Proyecto con fines educativos.
