# MCDI501 - Predicción de la Deserción y el Éxito Académico de los Estudiantes

## Grupo 1 | MCDI501 - Estadística Computacional para la Toma de Decisiones

### Integrantes

- Pablo Ignacio Balbontín Constenla @pabbalbontin-maker
- Melany Esmeralda Reyes Leiva @melanyreyesy
- Ingeborg Andrea Muñoz Carnot @dark452
- Mario Alejandro López Pulgar @malp2203

### Descripción de problemática

El dataset contiene información socioeconómica, académica y demográfica de estudiantes de educación superior en Portugal. El objetivo es predecir si un estudiante se graduará, abandonará o permanecerá matriculado, lo que permite implementar intervenciones tempranas de retención.

*Dataset (Predict Students' Dropout and Academic Success)*:

- 4,424 registros
- 37 columnas

*Columna objetivo*:

- `Target`: variable categórica con 3 clases
  - **Graduate** (49.9%): el estudiante completó sus estudios
  - **Dropout** (32.1%): el estudiante abandonó
  - **Enrolled** (17.9%): el estudiante sigue matriculado al cierre del período

### Estructura del repositorio

```bash
mcdi501-grupo1/
├── data/
│   ├── raw/                        # Dataset original (CSV, separado por ';')
│   └── processed/                  # datos generados por los notebook
├── notebooks/
│   ├── F2.ipynb 
│   ├── F3.ipynb   
│   └── F4.ipynb  
├── src/
├── docs/                        
├── requirements.txt          # Librerias dependientes
└── README.md
```

### Cómo reproducir el entorno

```bash
# Clonacion del repositorio
git clone https://github.com/dark452/mcdi501-grupo1.git
cd mcdi501-grupo1

# Crecion del entorno virtual e instalacion de librerias
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# Ejecucion del notebook
jupyter notebook notebooks/F3.ipynb
```

### Fase 3

La Fase 3 del proyecto se encarga de realizar la validación computacional de los resultados obtenidos en la Sumativa 1 (Fase 2 - Análisis Exploratorio e Inferencial) mediante técnicas de simulación y remuestreo (bootstrap, permutación, Monte Carlo y jackknife).

### Fase 4

La Fase 4 corresponde a la presentación final del proyecto integrado (Sumativa 3). Integra los resultados de las tres fases anteriores en una narrativa coherente que muestra la progresión (S1, S2, S3), comunicando de manera clara los hallazgos del modelamiento predictivo, la interpretación de los modelos de regresión logística y las recomendaciones para la toma de decisiones.

