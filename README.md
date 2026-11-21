> **Nota:** este proyecto está superado por [Duplicados-finder-v2](https://github.com/VSGdev-ops/Duplicados-finder-v2).

# Buscador de Archivos Duplicados

## Descripción

Este proyecto es una aplicación de escritorio en Python para buscar y gestionar archivos duplicados en tu sistema. La herramienta permite escanear una carpeta seleccionada, buscar archivos duplicados basados en su contenido (utilizando hashes), y luego mover o eliminar los duplicados según lo desees.

La aplicación usa una interfaz gráfica construida con `Tkinter`, y la búsqueda de duplicados se optimiza con `ThreadPoolExecutor` para el procesamiento paralelo de archivos.

## Características

- Escaneo de carpetas para detectar archivos duplicados.
- Filtrado de archivos duplicados por tamaño (mínimo y máximo).
- Interfaz gráfica de usuario sencilla con `Tkinter`.
- Funcionalidades para mover y eliminar archivos duplicados.
- Soporta búsqueda de duplicados en múltiples carpetas y subcarpetas.

## Requisitos

- Python 3.x
- Bibliotecas Python:
  - `tkinter` (interfaz gráfica)
  - `hashlib` (cálculo de hash)
  - `shutil` (manejo de archivos)
  - `concurrent.futures` (procesamiento paralelo)

## Instalación

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/tu_usuario/buscador-de-archivos-duplicados.git
   cd buscador-de-archivos-duplicados

![image](https://github.com/user-attachments/assets/7ec6a931-9446-4c36-bb9c-4ebc09c19bfd)
![image](https://github.com/user-attachments/assets/c58a20a0-02f5-4ef9-b283-542dd951e653)
