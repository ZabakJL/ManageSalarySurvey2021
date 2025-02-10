# **Manager Salary Survey 2021**  
📊 **Análisis de datos salariales de gerentes**  

## **Descripción**  
Este repositorio contiene el código y los datos utilizados en el análisis de la encuesta **Manager Salary Survey 2021**. El objetivo es limpiar, transformar y analizar la información para obtener insights sobre salarios, compensaciones y tendencias por industria, país, género y nivel educativo.  

## **Estructura del repositorio**  

```
📂 Data
│── 📂 Processed              # Datos procesados y normalizados
│   │── ManagerSalarySurvey2021_pr...  # Archivo procesado final (nombre truncado)
│   │── TasasDeCambio.csv     # Archivo con tasas de conversión de monedas
│   │── codigosMoneda.csv     # Mapeo de códigos de moneda
│   │── dataProcessed.csv     # Datos después de la transformación
│   │── mapearIndustrias.csv  # Archivo para normalizar industrias
│   │── mapearPaisCiudad.csv  # Archivo para normalizar países y ciudades
│
│── 📂 Raw                    # Datos sin procesar
│   │── ManagerSalarySurvey 2021.csv  # Archivo original de la encuesta
│
📂 Docs                        # Documentación del proyecto
│   │── Descripción del proyecto y entrega...  # Documentos explicativos
│
📂 Scripts                     # Scripts de procesamiento y análisis de datos
│   │── transform_data.ipynb   # Notebook para transformación de datos
│   │── .ipynb_checkpoints     # Carpeta de checkpoints de Jupyter
│
│── README.md                  # Archivo de documentación principal
```

## **Uso del repositorio**  

### **1. Requisitos previos**  
Para ejecutar los scripts y notebooks de este proyecto, asegúrate de tener instaladas las siguientes dependencias en Python:  

```bash
pip install pandas numpy jupyter
```

### **2. Uso del notebook de transformación de datos**  
Ejecuta el siguiente comando en la terminal para abrir el notebook y procesar los datos:  

```bash
jupyter notebook Scripts/transform_data.ipynb
```

Este notebook se encarga de:  
✅ Cargar los datos brutos desde la carpeta `Raw`.  
✅ Normalizar nombres de columnas y corregir inconsistencias.  
✅ Convertir valores monetarios utilizando `TasasDeCambio.csv`.  
✅ Mapear industrias y ubicaciones con `mapearIndustrias.csv` y `mapearPaisCiudad.csv`.  
✅ Exportar los datos transformados a `dataProcessed.csv` en la carpeta `Processed`.  

## **Contribuciones**  
Si deseas contribuir con mejoras en la limpieza y análisis de datos, por favor sigue estos pasos:  
1. Realiza un **fork** del repositorio.  
2. Crea una nueva rama para tus cambios:  
   ```bash
   git checkout -b feature-mejora
   ```  
3. Realiza tus modificaciones y haz un commit:  
   ```bash
   git commit -m "Mejoras en la transformación de datos"
   ```  
4. Envía un **pull request** para revisión.  

## **Contacto**  
Para dudas o sugerencias, puedes contactarme a través de **[tu correo o LinkedIn]**.  


