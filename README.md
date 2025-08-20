# 📊 Análisis de Churn en Clientes - Telecom X

Este proyecto corresponde al desafío final del curso de Data Science, en el cual se realiza un **análisis de evasión de clientes (Churn)** para la empresa ficticia *Telecom X*.  

El objetivo principal es identificar patrones en los datos que expliquen por qué los clientes abandonan el servicio, y a partir de ello proponer recomendaciones que ayuden a reducir el churn.

---

## 🚀 Flujo del proyecto
El trabajo sigue la metodología **ETL + EDA**:

1. **Extracción**  
   - Los datos fueron obtenidos a través de una API en formato JSON.  
   - Se cargaron en un DataFrame de Pandas para su manipulación.

2. **Transformación**  
   - Limpieza de espacios en blanco y valores nulos.  
   - Conversión de tipos de datos.  
   - Normalización de categorías (`yes/no` → `1/0`).  
   - Eliminación de duplicados.  
   - Creación de variables derivadas, como `total_services`.

3. **Carga y Análisis Exploratorio (EDA)**  
   - Visualización de la distribución del churn.  
   - Exploración de la relación entre churn y el número de servicios contratados.  

---

## 📈 Principales hallazgos
- La mayoría de los clientes **no abandonan** la empresa, pero existe un grupo importante de churn que debe atenderse.  
- Los clientes con **un solo servicio** muestran mayor tendencia a abandonar.  
- Los clientes con **dos o más servicios** presentan menor churn, lo que indica que los planes combinados generan mayor fidelidad.  

---

## ✅ Conclusiones y recomendaciones
- El churn está fuertemente asociado a clientes con baja contratación de servicios.  
- Estrategias sugeridas:  
  1. Fomentar la **contratación de paquetes múltiples** (internet + teléfono).  
  2. Implementar **campañas de retención específicas** para clientes con un solo servicio.  
  3. Evaluar y mejorar la calidad de los planes más básicos.  

---

## 🛠️ Tecnologías utilizadas
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
