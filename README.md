# 🏆 Torneo Libre 2026 - Clash Royale & Brawl Stars

Sitio web oficial para la gestión e inscripción de torneos relámpago de **Clash Royale (1v1)** y **Brawl Stars (2v2)**. La plataforma permite visualizar las llaves de los torneos, consultar las reglas, ver la transmisión en vivo y realizar la inscripción mediante un formulario integrado con Formspree.

## 🚀 Tecnologías Utilizadas

* **Astro** - Framework web para la velocidad.
* **Tailwind CSS** - Diseño responsivo y estilos modernos con estética gaming.
* **Formspree** - Manejo de formularios e inscripciones directamente al correo.
* **TypeScript** - Para un desarrollo más seguro y sin errores de lógica.

## 📋 Características Principales

* **Hero Section Dinámico**: Muestra el costo de inscripción (S/ 1.00) y el premio (S/ 10.00) de forma impactante.
* **Brackets (Llaves)**: Sistema de pestañas deslizables para alternar entre los cuadros de Clash Royale y Brawl Stars (16 participantes por juego).
* **Reglas Claras**: Sección detallada con normas de participación, niveles de cartas (Nivel 11) y premios.
* **Integración con Kick**: Sección dedicada para seguir la transmisión oficial del torneo.
* **Formulario de Registro Inteligente**: 
    * Cambia dinámicamente según el juego elegido (1 o 2 jugadores).
    * Incluye código QR de pago integrado.
    * Soporte para subida de captura de pantalla (comprobante).

## 🛠️ Instalación y Configuración

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
    cd TU_REPOSITORIO
    ```

2.  **Instalar dependencias:**
    ```bash
    npm install
    ```

3.  **Configurar Formspree:**
    * Crea un formulario en [formspree.io](https://formspree.io/).
    * Copia el ID de tu formulario.
    * Pégalo en el archivo `src/components/Inscripcionesform.astro` en el atributo `action`.

4.  **Ejecutar en modo desarrollo:**
    ```bash
    npm run dev
    ```

5.  **Abrir el navegador:**
    Visita `http://localhost:4321` para ver los cambios en tiempo real.

## 📸 Imágenes del Proyecto

Asegúrate de colocar tu logo como `favicon.png` y tu QR de pago como `qr-pago.png` en la carpeta `public/` para que se visualicen correctamente en la web.

---
*Este proyecto es de participación libre y no está afiliado oficialmente con Supercell.*
