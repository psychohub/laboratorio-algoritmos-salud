# Laboratorio de Algoritmos en Salud

Práctica interactiva de Python para la **Tutoría 4** de 03564 Lógica y Algoritmos para Sistemas de Información en Salud (UNED, Costa Rica). Python corre en el navegador de cada estudiante con [Pyodide](https://pyodide.org): no hay que instalar nada.

## Las siete misiones

| Misión | Nivel | Qué se practica |
|---|---|---|
| 1 · El menú que no se detiene | Base | Menú con `while`, opción inválida y salida con `break` |
| 2 · El contador que nace antes | Base | Contador con ciclo y valor límite (ejercicio de la casa del Taller 4) |
| 3 · La búsqueda que se rinde temprano | Intermedia | Búsqueda secuencial que devuelve la posición o -1 |
| 4 · El dato que no se deja pasar | Intermedia | Validación con `while`, `.isdigit()` y rango |
| 5 · Dos jornadas, tres respuestas | Intermedia | Conjuntos dentro de una función |
| 6 · El sistema que recuerda | Avanzada | Persistencia con `json.dump` / `json.load` y `os.path.exists` |
| 7 · Detective | Reto | Sistema de inventario con cinco defectos sembrados |

Cada misión tiene pruebas automáticas que dicen qué falla y qué revisar.

## Seguimiento de la persona tutora

Si el enlace lleva `?e=<URL de Google Apps Script>` (o `CONFIG.ENDPOINT` tiene esa URL), cada verificación se registra en una hoja de Google de la persona tutora (nombre, misión, pruebas que pasa, prueba que falla y código). La vista `#tutor` muestra el tablero en vivo. El código del script lo tiene la persona tutora (no se publica aquí).

## Publicar

Es un solo archivo, `index.html`. GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
