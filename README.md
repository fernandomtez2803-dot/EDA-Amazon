# EDA Amazon producto ganador
![imagen](https://www.supplychain247.com/images/legacy/amazon_india_image.jpg)

# Exploratory Data Analysis (EDA) – Amazon India Best Sellers

## 🥇 ¿Cómo encontrar el nicho de oro?
**Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un snapshot de Best Sellers de Amazon India (amazon.in) para detectar subcategorías con poca competencia y mucha demanda y, dentro de ellas,candidatos a producto ganador**.
Herramientas: **Python + Pandas + Matplotlib/Seaborn**. Menos humo, más datos.

---

## 🗂️ Organización de carpetas

- **presentacion/**: Presentacion hecha en canvas pero exportada en Word.
- **src/**  
  - **data/**: carga del dataset 
  - **memoria/**: EDA- notebook principal con todo el análisis.
- **.gitignore**
- **README.md** (este documento)

---

## 🎯 Descripción del proyecto

**Objetivo**  
1) Medir **competencia** por categoría (nº de productos).  
2) Estimar **demanda** con `rating_count` (proxy de ventas).  
3) Señalar **nichos**: *pocos productos + muchas reviews* (y alta eficiencia `reviews/sku`).  
4) Listar **productos candidatos** y priorizar los que tienen **alta demanda con rating mejorable** (oportunidad clara de mejora).

**Preguntas guía**
- ¿Qué **macro-categorías** concentran más oferta?  
- ¿Qué **subcategorías** (leaf) tienen **menos productos** pero **acumulan más reviews**?  
- ¿Qué **productos** lideran en esas subcategorías y con qué **rating**?  
- ¿Dónde compensa entrar si quiero **máxima demanda con mínima competencia**?

---

## 📦 Dataset

- **Fuente:** Kaggle – *Amazon India Best Sellers*  
 





- **Columnas principales:**
  - `product_id` (ASIN), `product_name`
  - `category`: ruta jerárquica `Macro|Sub|...|Leaf`
  - `discounted_price`, `actual_price`, `discount_percentage`
  - `rating` (float), `rating_count` (nº de reviews)
  - `about_product`, `img_link`, `product_link`

- **Limitaciones:** Es un **Top-N por categoría**, no todo Amazon. `rating_count` es un **proxy** de demanda.

---

## 🧰 Librerías

- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
-  `jupyter` para ejecutar los notebooks




