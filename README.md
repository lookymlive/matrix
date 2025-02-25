# Efecto Matrix Webcam

Una aplicación web interactiva que combina la entrada de la webcam con el icónico efecto visual de "The Matrix", creando una experiencia única donde tu silueta aparece a través de la lluvia de caracteres estilo Matrix.

## Características

- Captura de video en tiempo real desde la webcam
- Efecto de lluvia de caracteres estilo Matrix personalizable
- Controles interactivos para ajustar:
  - Umbral de contraste
  - Velocidad de la lluvia de caracteres
  - Densidad de los caracteres
- Función de captura de imagen
- Diseño responsivo con tema Matrix
- Interfaz minimalista y fácil de usar

## Cómo usar

1. Abre el archivo `matrix.html` en un navegador web moderno
2. Haz clic en "Iniciar Webcam" y permite el acceso a la cámara
3. Ajusta los controles deslizantes para personalizar el efecto:
   - **Umbral de contraste**: Ajusta la sensibilidad de la detección de silueta
   - **Velocidad de lluvia**: Controla qué tan rápido caen los caracteres
   - **Densidad de caracteres**: Modifica la cantidad de caracteres en pantalla
4. Usa el botón "Capturar Imagen" para guardar el resultado

## Requisitos técnicos

- Navegador web moderno con soporte para:
  - WebRTC (getUserMedia)
  - Canvas API
  - JavaScript ES6+
- Cámara web funcional
- Se recomienda usar Chrome, Firefox o Edge actualizados

## Notas de privacidad

- La aplicación funciona completamente en el navegador
- No se almacena ningún dato de video
- Las capturas de imagen se guardan localmente en tu dispositivo
