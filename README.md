# Taller 4 – Análisis de Componentes Principales (ACP) sobre la base Parkinsons

Repositorio con el proyecto del curso **Análisis Multivariado**, que incluye un notebook desarrollado en **R**, la base de datos utilizada y el informe en LaTeX.

## Autor

**Santiago Rincon - Valentina Reyes**

## Contexto académico

- Universidad Santo Tomás, Facultad de Estadística
- Curso: Análisis Multivariado
- Docente: Edna Moreno
- Actividad: Taller 4 – Proyecto ACP sobre una base de datos abierta

## Contenido del repositorio

El proyecto reúne las etapas del análisis:

- Exploración y análisis descriptivo de los datos
- Preprocesamiento y verificación de supuestos (correlaciones, KMO, Bartlett)
- ACP "a mano" mediante la descomposición en valores singulares
- ACP con las librerías FactoMineR y factoextra
- Selección del número de componentes e interpretación
- Individuos atípicos, indicadores y ACP robusto
- Conclusiones y limitaciones

## Base de datos

- Nombre: Parkinsons
- Fuente: UCI Machine Learning Repository
- Enlace: https://archive.ics.uci.edu/dataset/174/parkinsons
- Descripción: 195 grabaciones de voz, 22 variables acústicas y la variable `status` (sano / Parkinson)

## Estructura del repositorio

```text
taller-acp-parkinsons/
├─ README.md
├─ Taller_ACP_Parkinsons.ipynb
├─ data/
│  └─ parkinsons.csv
└─ informe/
   ├─ informe.tex
   └─ informe.pdf
```

## Cómo reproducir el análisis

1. Abrir el notebook con un kernel de **R** (Jupyter o Colab).
2. Instalar los paquetes indicados en la primera celda.
3. Ejecutar con *Restart & Run All*.

## Atribución

El código del ACP fue adaptado del material del profesor Mario Pacheco:

Pacheco, M. (s.f.). *Análisis Multivariado* [Repositorio de código y material de clase]. https://datastatistic.github.io/multivariate/

