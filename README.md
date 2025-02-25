# TallerLinux2025

Repositorio para el Obligatorio de Taller de Servidores Linux 2025.

## Descripción

Este proyecto forma parte del curso Taller de Servidores Linux 2025 y tiene como objetivo familiarizarse con el uso de la herramienta ansible y GitHub. Aquí se incluyen inventario, comandos ad-hoc y playbooks para configurar un servidor web apache y acceso SSH con clave publica/privada.

## Contenidos del Repositorio

- `collections/`: Contiene las colecciones adicionales necesarias para ejecutar el playbook.
- `inventories/`: Contiene el archivo de inventario de nodos.
- `results/`: Capturas de ejecucion.
- `templates/`: Plantillas utilizadas.
- `TallerLX.md`: Documentacion detallada del trabajo.
- `ad-hoc.txt`: Contiene comandos ad-hoc requeridos en la letra.
- `ansible_basics.txt`: Respuestas a preguntas planteadas.
- `hardening.yml`: Playbook.
- `web_setup.yml`: Playbook.

## Instalación

Para utilizar este proyecto, sigue los siguientes pasos:

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/Gutiz19/TallerLinux2025.git
   ```

2. **Navegar al directorio del proyecto:**

   ```bash
   cd TallerLinux2025
   ```

3. **Instalar dependencias:**

   ```bash
   asible-galaxy install -r collections/requirements.yml
   ```
## Uso

Se deben copiar las claves publicas de los host al servidor desde el cual se ejecuta antes de ejecutar los playbooks.

## Licencia

Este proyecto está bajo la licencia CC0-1.0. Para más detalles, consulta el archivo [LICENSE](LICENSE).
