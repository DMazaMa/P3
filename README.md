# 📝 **Práctica 3 - Juego de las Banderas**

## 🎯 **Descripción del Proyecto**
En esta práctica vamos a **crear una web que utiliza una API REST ya creada**. El objetivo es aplicar los **conocimientos adquiridos en el aula** sobre:
- **Llamadas asíncronas a un API REST con JavaScript**
- **Manipulación del DOM** para presentar los datos obtenidos

Para poner en práctica estos conceptos, hemos desarrollado **un juego interactivo de banderas** donde el usuario debe adivinar a qué país pertenece la bandera mostrada.

---

## 🌍 **Características del Juego**
- **Uso de la API REST:** Se utiliza la API pública de [REST Countries](https://restcountries.com/) para obtener información actualizada sobre países y sus banderas.
- **Llamadas asíncronas:** Las banderas y opciones se cargan dinámicamente mediante peticiones `fetch` con manejo de promesas y `async/await`.
- **Interactividad:**
  - El usuario selecciona la respuesta correcta entre cuatro opciones.
  - Se muestra una barra de progreso con límite de tiempo.
  - El juego incluye un sistema de puntuación y multiplicador que aumenta con respuestas consecutivas correctas.
- **Puntuación:**
  - Se guarda la mejor puntuación en el `localStorage` del navegador.
  - Se puede consultar el récord desde la sección "Scores".
- **Navegación simple:**
  - **Inicio:** Permite iniciar el juego, ver scores o salir.
  - **Juego:** Desafía al usuario con banderas aleatorias.
  - **Scores:** Muestra la mejor puntuación obtenida.

---

## 🗂️ **Estructura del Proyecto**
```plaintext
Practica3/
├── images/
│   └── Adobe Express - file.png  # Imagen de título utilizada en todas las páginas
├── inicio.html                   # Página principal con opciones de navegación
├── p3.html                       # Página del juego de banderas
├── score.html                    # Página que muestra la mejor puntuación guardada
└── README.md                     # Documento explicativo del proyecto
```

---

## 🖥️ **Instrucciones de Uso**
1. **Descarga o clona** el repositorio en tu equipo.
2. Abre el archivo `inicio.html` en tu navegador.
3. En el menú principal, selecciona una opción:
   - **INICIAR JUEGO:** Comienza la partida de adivinanzas de banderas.
   - **SCORES:** Consulta la mejor puntuación registrada.
   - **SALIR:** Muestra un mensaje de despedida.
4. Durante el juego:
   - Haz clic en la opción que creas correcta.
   - Observa tu puntuación, multiplicador y récord actualizados en tiempo real.
5. Puedes volver al menú principal desde el botón **VOLVER AL MENÚ** en la página del juego.

---

## ⚙️ **Tecnologías Utilizadas**
- **HTML5:** Estructura de las páginas.
- **CSS3:** Estilizado con fondos dinámicos, botones interactivos y diseño responsive.
- **JavaScript:**
  - Llamadas a la API REST mediante `fetch`.
  - Manipulación del DOM para actualizar imágenes, opciones y puntuaciones.
  - Manejo de `localStorage` para guardar el mejor puntaje.
- **API:** [REST Countries](https://restcountries.com/) para obtener datos de banderas y nombres de países.

---

## 🚀 **Mejoras y Funcionalidades Futuras**
- Añadir un **modo contrarreloj** más desafiante.
- Implementar **niveles de dificultad** (fácil, medio, difícil).
- Mostrar **información adicional** del país tras responder (capital, población, continente).
- Incluir **efectos sonoros** y animaciones.
- Añadir **una tabla de clasificación global** con puntuaciones de diferentes usuarios.

---

## 📢 **Conclusión**
Esta práctica ha permitido reforzar los conocimientos sobre **consumo de APIs REST** y la **manipulación del DOM** en JavaScript. Además, se ha aprendido a manejar la **persistencia de datos en el navegador** mediante `localStorage` y a **crear una experiencia de usuario interactiva** y amigable.

¡Diviértete jugando y aprendiendo sobre las banderas del mundo! 🌎🚩🎮
