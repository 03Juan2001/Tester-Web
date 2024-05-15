# Proyecto de Automatización con Selenium

## Automatización de Inicio de Sesión y Registro en Facebook

---

### Autores:
- **AVILA AYALA JUAN CARLOS - 20210546**


### Fecha:
**13 de Mayo de 2024**

---

## Descripción del Proyecto

Este proyecto tiene como objetivo automatizar el proceso de inicio de sesión y registro en el sitio web de Facebook utilizando Selenium. La automatización incluye la capacidad de seleccionar el navegador (Chrome o Edge) y realizar acciones como completar formularios de inicio de sesión y registro.

## Estructura del Proyecto

### Archivos Principales:
- `login.py`: Contiene el código principal para la automatización del inicio de sesión y registro.
- `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto.

## Instrucciones de Uso

1. **Instalación de Dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

2. **Ejecución del Script:**
    ```bash
    python login.py
    ```

3. **Parámetros de Entrada:**
    - **Navegador**: Chrome o Edge.
    - **Acción**: Iniciar sesión o crear una nueva cuenta.

---

## Consideraciones Técnicas

El proyecto hace uso de los siguientes principios y patrones de diseño:
- **Patrón Factory**: Selección dinámica del navegador.
- **Patrón Command**: Encapsulación de la lógica de inicio de sesión.
- **Patrón Template Method**: Estructura del método `login`.
- **Principio de Responsabilidad Única (SRP)**: Métodos con responsabilidades definidas.
- **Encapsulamiento**: Lógica del proceso de inicio de sesión y registro.
- **DRY (Don't Repeat Yourself)**: Uso eficiente de métodos y variables.
- **Patrón Facade**: Simplificación del proceso de automatización.

---

## Contacto

Para cualquier consulta o colaboración, pueden contactar a los autores a través de:

- **Correo Electrónico**: juan.avila201@tectijuana.edu.mx

---

© 2024 - Todos los derechos reservados.
