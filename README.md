# Statistical Analytics Homicide

**Análisis Exploratorio y Estadístico de Tendencias de Homicidios en Estados Unidos**

## 📋 Descripción del Proyecto

Este proyecto investiga los factores sociales, demográficos y geográficos que influyen en las tendencias de homicidios en Estados Unidos. A través de análisis exploratorio de datos (EDA), estadística descriptiva e inferencial, y visualizaciones avanzadas, buscamos identificar patrones, vulnerabilidades específicas y relaciones entre variables para comprender mejor este fenómeno de salud pública.

**Pregunta de Investigación Principal:** ¿Qué factores sociales, demográficos y geográficos influyen en las tendencias de homicidios en Estados Unidos?

## 👥 Autores

- **Estiven Ospina González**
- **Juan José García Álvarez**

*Proyecto realizado para el curso de Fundamentos de Ciencia de Datos - Semestre 2026/1*

## 📊 Contenido del Repositorio

### **Sesiones Prácticas** (`sesiones_practicas/`)

El proyecto está estructurado en seis cuadernos Jupyter que documentan el proceso completo de análisis

### **Datos** (`data/`)

- **database.csv** - Base de datos compilada de registros de homicidios en Estados Unidos
  - Fuente: [Kaggle Homicide Dataset](https://www.kaggle.com/code/harshilahalpara/homicide)
  - Incluye variables geográficas, demográficas, temporales y contextuales

## 🛠️ Tecnologías y Herramientas Utilizadas

### **Lenguajes y Plataformas**
- **Python 3.x** - Lenguaje de programación principal
- **Jupyter Notebook** - Ambiente interactivo de análisis

### **Librerías de Análisis y Visualización**
- **pandas** - Manipulación y análisis de datos
- **NumPy** - Computación numérica
- **matplotlib** - Visualización base
- **seaborn** - Visualizaciones estadísticas avanzadas
- **scikit-learn** - Análisis estadístico y machine learning
- **scipy** - Métodos estadísticos

## 📁 Estructura del Repositorio

```
statistical_analytics_homicide/
├── README.md                           # Este archivo
├── LICENSE                             # Licencia del proyecto
├── data/
│   └── database.csv                    # Base de datos principal
└── sesiones_practicas/
    ├── sp_1_*.ipynb                    # Exploración y limpieza
    ├── sp_2_*.ipynb                    
    ├── sp_3_*.ipynb                    
    ├── sp_4_*.ipynb                    
    ├── sp_5_*.ipynb                    
    └── trabajo_final_*.ipynb           # Síntesis integral
```

## 🚀 Cómo Descargar y Ejecutar el Proyecto

### **Requisitos Previos**
- **Python 3.7+** instalado en tu equipo
- **pip** (gestor de paquetes de Python)
- **git** (para clonar el repositorio)

### **Opción 1: Ejecución Local**

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/eospgonz10/statistical_analytics_homicide.git
   cd statistical_analytics_homicide
   ```

2. **Crear un entorno virtual (recomendado):**
   ```bash
   # En Windows
   python -m venv venv
   venv\Scripts\activate
   
   # En macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt
   ```
   
   Si no existe `requirements.txt`, instala manualmente:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
   ```

4. **Iniciar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. **Navegar a `sesiones_practicas/` y abrir los cuadernos:**
   - Comenzar con `sp_1_*.ipynb`
   - Seguir en orden hasta `trabajo_final_*.ipynb`

### **Opción 2: Ejecución en Google Colab (Recomendado)**

1. **Abre Google Colab:** [colab.research.google.com](https://colab.research.google.com)

2. **Carga el repositorio:**
   ```python
   !git clone https://github.com/eospgonz10/statistical_analytics_homicide.git
   %cd statistical_analytics_homicide
   ```

3. **Monta Google Drive (opcional, para guardar resultados):**
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

4. **Instala dependencias (si es necesario):**
   ```python
   !pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

5. **Carga y ejecuta los cuadernos:**
   - Abre los archivos `.ipynb` directamente desde Colab
   - O copia/pega el código en una celda de Colab

### **Opción 3: Archivos Pre-Configurados en Colab**

Los cuadernos incluyen un botón "Open in Colab" al inicio. Simplemente:
1. Haz clic en el botón para abrir directamente en Google Colab
2. Ejecuta las celdas en orden

## 📖 Guía de Uso

1. **Comienza por la Sesión 1:** Familiarízate con los datos, su estructura y calidad
2. **Sigue secuencialmente:** Cada sesión práctica construye sobre los análisis anteriores
3. **Experimenta:** Modifica visualizaciones, prueba filtros adicionales
4. **Consulta el Trabajo Final:** Para ver la síntesis integral y conclusiones

## 📊 Hallazgos Clave

El análisis revela:
- Patrones geográficos significativos en la distribución de homicidios
- Disparidades demográficas en grupos de riesgo específicos
- Tendencias temporales y estacionales identificables
- Factores correlacionados con tasas de homicidios elevadas

(Para hallazgos detallados, consulta `trabajo_final_*.ipynb`)

## 📝 Notas Importantes

- Los datos provienen de fuentes públicas de Kaggle
- Los análisis son educativos y de investigación
- Los resultados deben interpretarse en contexto social y geográfico
- Se recomienda validar hallazgos con fuentes adicionales

## 📄 Licencia

Este proyecto está bajo la licencia especificada en el archivo [LICENSE](LICENSE)

## 🔗 Referencias

- Fuente de Datos: [Kaggle - Homicide Dataset](https://www.kaggle.com/code/harshilahalpara/homicide)
- Librerías utilizadas:
  - [Pandas Documentation](https://pandas.pydata.org/)
  - [Seaborn](https://seaborn.pydata.org/)
  - [Matplotlib](https://matplotlib.org/)
  - [Scikit-learn](https://scikit-learn.org/)

---

**Última actualización:** Mayo 2026
**Semestre:** 2026/1 - Fundamentos de Ciencia de Datos
