# Generación de paquetes con archivos TOML y publicación en Test PyPI 🚀

**Mario de León**  
**Jorge Caballeros**

Este lab tiene como objetivo aprender a empaquetar y distribuir un proyecto de Python utilizando el estándar de archivos TOML y publicarlo en Test PyPI. Este proceso permite distribuir fácilmente código reutilizable, ideal para proyectos de Machine Learning y otras áreas.

## Archivos

- `myModule.py`: Contiene una función simple como ejemplo.
- `pyproject.toml`: Archivo de configuración del paquete, especifica nombre, versión, y dependencias.
- `README.md`: Descripción del paquete, que se muestra en PyPI.
- `dist/`: Directorio donde se generan los archivos empaquetados (`.whl`, `.tar.gz`) después de la construcción.

## Reflexión sobre empaquetado de proyectos de Machine Learning

Paquetizar un proyecto de Machine Learning es clave para facilitar la distribución y reutilización del código. Si bien para modelos grandes o entornos complejos se suelen usar soluciones como Docker o Pickle/Joblib, empaquetar el código con herramientas como `setuptools` y publicarlo en repositorios como PyPI es una opción muy buena para compartir librerías, scripts o utilidades. Esto permite a otros instalar y usar el proyecto de forma fácil, asegurando control sobre las versiones y dependencias del código.
