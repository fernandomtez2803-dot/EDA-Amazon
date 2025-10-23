# EDA Dropshipping (E-commerce)

Proyecto de **Exploratory Data Analysis** orientado a evaluar oportunidades para **dropshipping**.

## Estructura
```
src/
├── data/          # datasets (CSV/XLSX). NO subir pesados a GitHub
├── notebooks/     # notebooks de pruebas y análisis
├── utils/         # funciones auxiliares
└── memoria.ipynb  # notebook "memoria" con narrativa + resultados
```

## Cómo ejecutar
1. Crea y activa un entorno (opcional).
2. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Coloca tu dataset en `src/data/` (ej: `ecommerce.csv`).
4. Abre `src/notebooks/EDA_Ecommerce_Dropshipping.ipynb` y ajusta `DATA_PATH = "../data/ecommerce.csv"`.
5. Escribe conclusiones en `src/memoria.ipynb`.

## Entregable (según rúbrica)
- **Presentación** (10 min)
- **Memoria**: `src/memoria.ipynb`
- **Código**: `src/` completo
- **Repositorio GitHub**: enlace actualizado
