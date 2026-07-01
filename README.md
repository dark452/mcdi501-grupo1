# MCDI501 - Predicción de la Deserción y el Éxito Académico de los Estudiantes

## Grupo 1 | MCDI501 - Estadística Computacional para la Toma de Decisiones

### Integrantes

- Pablo Ignacio Balbontin Constenla @pabbalbontin-maker
- Melany Esmeralda Reyes Leiva @melanyreyesy
- Ingeborg Andrea Munoz Carnot @dark452
- Mario Alejandro Lopez Pulgar @malp2203

### Descripción de problemática

El dataset contiene información socioeconómica, académica y demográfica de estudiantes de educación superior en Portugal. El objetivo es predecir si un estudiante se graduará, abandonará o permanecerá matriculado, lo que permite implementar intervenciones tempranas de retención.

*Dataset (Predict Students' Dropout and Academic Success)*:

- 4,424 registros
- 37 columnas

*Columnas objetivo*:

- Target

### Estructura del repositorio

### Cómo reproducir el entorno

```bash
git clone https://github.com/dark452/mcdi501-grupo1.git
cd mcdi501-grupo1
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/F2.ipynb
```