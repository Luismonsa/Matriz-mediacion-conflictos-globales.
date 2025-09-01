````markdown name=README.md
# Matriz de Mediación y Resolución de Conflictos Globales

Este repositorio académico tiene como objetivo construir colaborativamente una matriz que identifique los conflictos más recurrentes a nivel mundial y proponga métodos de mediación y resolución fundamentados en enfoques académicos y multidisciplinarios.

## Objetivos

- Identificar y documentar los conflictos globales más frecuentes.
- Analizar actores, causas y consecuencias de cada conflicto.
- Proponer métodos de mediación y resolución basados en evidencia científica.
- Fomentar la colaboración interdisciplinaria y el acceso abierto al conocimiento.

## ¿Cómo contribuir?

1. Revisa la [metodología](docs/metodologia.md) para entender el enfoque del proyecto.
2. Usa las plantillas en la sección de Issues para reportar conflictos o proponer soluciones.
3. Actualiza la matriz principal en `/data/matriz_mediacion.xlsx` siguiendo la guía de contribución.
4. Mantén el respeto y la colaboración siguiendo el [Código de Conducta](CODE_OF_CONDUCT.md).

## Estructura del repositorio

- `/data/`: Archivos de la matriz de mediación (Excel o CSV).
- `/docs/`: Documentos de apoyo, metodología y referencias.
- `/src/`: Scripts de procesamiento y análisis de la matriz.
- `.github/ISSUE_TEMPLATE/`: Plantillas para reportar conflictos y soluciones.
- Otros archivos administrativos (README, LICENSE, etc.)

## Licencia

Este repositorio está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

¡Gracias por tu interés y colaboración!
````

```gitignore name=.gitignore
# Archivos de Python
__pycache__/
*.pyc

# Archivos temporales de sistemas operativos
.DS_Store
Thumbs.db

# Archivos de configuración de editores
.vscode/
*.sublime-project
*.sublime-workspace

# Archivos y carpetas de entorno virtual
env/
venv/
.venv/

# Archivos temporales de Excel y CSV
*.xlsx~
*.csv~

# Archivos de logs y temporales
*.log
*.tmp

# Otros archivos sensibles
*.env
secrets.*
```
