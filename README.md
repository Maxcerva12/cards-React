# Proyecto de Tarjetas Interactivas

Este repositorio contiene el código para un proyecto de tarjetas interactivas desarrollado con React. El diseño de las tarjetas está estilizado utilizando CSS y ofrece una experiencia de usuario atractiva e interactiva.

## Archivos

Este repositorio incluye los siguientes archivos:

1. **card.css**: Archivo de estilos CSS para las tarjetas.
2. **card.jsx**: Componente React que define la estructura y funcionalidad de una tarjeta individual.
3. **cards.jsx**: Componente React que maneja una colección de tarjetas y su renderizado.

## Estructura del Proyecto

- `card.css`: Define los estilos de las tarjetas, incluyendo propiedades de diseño como `box-shadow`, `border-radius`, y transiciones.
- `card.jsx`: Este archivo contiene el código del componente `Card`. Cada tarjeta presenta una imagen y un texto, y está estilizada según las clases definidas en `card.css`.

- `cards.jsx`: Este archivo gestiona la colección de tarjetas. Renderiza múltiples componentes `Card` y aplica estilos y propiedades adicionales según sea necesario.

## Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1. Clona este repositorio:

   ```
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   ```

2. Navega al directorio del proyecto:

   ```
   cd nombre-del-repositorio
   ```

3. Instala las dependencias necesarias:

   ```
   npm install
   ```

4. Inicia la aplicación:
   ```
   npm start
   ```

## Uso

Una vez que la aplicación esté en ejecución, deberías poder ver las tarjetas interactivas en tu navegador en `http://localhost:3000`. Las tarjetas están diseñadas para responder a eventos de usuario como `hover` y mostrar diferentes gradientes de fondo dependiendo de su posición.

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una rama con tu nueva característica:
   ```
   git checkout -b mi-nueva-caracteristica
   ```
3. Realiza tus cambios y realiza commits de tus cambios:
   ```
   git commit -m 'Añadir nueva característica'
   ```
4. Empuja tus cambios al repositorio remoto:
   ```
   git push origin mi-nueva-caracteristica
   ```
5. Crea un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
