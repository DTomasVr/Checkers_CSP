# Proyecto: Solución de Damas utilizando Programación Restrictiva (CSP)

### Curso: Tópicos de la Computación - Universidad Peruana de Ciencias Aplicadas

### Descripción

Este proyecto tiene como objetivo desarrollar una solución basada en **Programación Restrictiva (CSP)** para resolver el juego de Damas en tableros de diferentes dimensiones. Utilizamos **OR-Tools** de Google para modelar las restricciones del juego y encontrar las mejores jugadas. En fases futuras, este proyecto incluirá un enfoque basado en **Sistemas Multiagente (MAS)** para comparar ambos métodos en términos de eficiencia y escalabilidad.

### Tabla de Contenidos

1. [Problemática y Motivación](#problemática-y-motivación)
2. [Objetivos](#objetivos)
3. [Diseño de Solución](#diseño-de-solución)

---

### Problemática y Motivación

Los juegos de mesa, como el ajedrez o las damas, presentan desafíos estratégicos complejos que requieren técnicas avanzadas para su resolución. Este proyecto se basa en el uso de **Programación Restrictiva (CSP)** para modelar las reglas y restricciones del juego de Damas, permitiendo un enfoque matemático para resolver problemas de búsqueda y optimización. La motivación es explorar cómo el CSP puede manejar las restricciones inherentes del movimiento de piezas y sentar las bases para utilizar **Sistemas Multiagente (MAS)** en una fase posterior.

### Objetivos

- **Objetivo principal**: Desarrollar una solución basada en CSP para resolver el juego de Damas en tableros de diferentes dimensiones.
  
- **Objetivos secundarios**:
  - Implementar un modelo de CSP que restrinja los movimientos y decisiones de cada pieza, minimizando los conflictos entre restricciones.
  - Evaluar la eficiencia del modelo CSP mediante simulaciones y comparaciones con algoritmos clásicos.
  - Preparar una segunda fase donde se utilice MAS para abordar el juego de Damas y comparar su eficiencia con CSP.

### Diseño de Solución

La solución se basa en modelar las reglas de Damas mediante **OR-Tools** de Google. Se utiliza un modelo CSP que asigna valores a cada celda del tablero, donde las piezas blancas, negras y sus variantes (reinas) tienen representaciones numéricas. El algoritmo evalúa la posición de cada turno para encontrar la mejor jugada posible bajo las restricciones del juego. El objetivo es desarrollar una solución escalable que pueda adaptarse a variaciones del juego.

---

**Equipo del proyecto**:

- Samuel Esteban Cano Chocce
- Eduardo Elías Puglisevich Vergara
- Nicolás Miguel Guerrero Icochea
- Diego Tomas Villafuerte Ramírez
