# Examen Práctico Progreso 2 – Atraco en Leonida

Programación II · Java 17 · IntelliJ IDEA

## Integrantes

- _Nombre completo 1_
- _Nombre completo 2_
- _Nombre completo 3_

**NRC:** _______

## Contenido

| Archivo | Descripción |
|---|---|
| `src/Integrante.java` | Clase abstracta: nombre, nivel y pago; método abstracto `rol()` |
| `src/Conductor.java` | Subclase de `Integrante` con vehículo de escape |
| `src/Golpe.java` | Agrega integrantes con un cupo y se compara con otro golpe |
| `src/Main.java` | Partes A (arreglos), B (matriz), C (ArrayList) y D (clases) |
| `docs/AtracoLeonida_UML.png` | Diagrama de clases UML (PowerDesigner) |

## Cómo ejecutar

### En IntelliJ IDEA

1. Abrir la carpeta del proyecto (`File → Open`).
2. Configurar un JDK 17 en `File → Project Structure → Project SDK`.
3. Abrir `src/Main.java` y ejecutar con el botón **Run**.
4. Cuando el programa pida el número de etapa, escribir un valor entre 0 y 4 (por ejemplo `3`).

### Desde la terminal

```bash
javac -d out src/*.java
java -cp out Main
```
