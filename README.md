# Análisis Inicial y Selección de Problema

## Descripción  
Este proyecto tiene como objetivo realizar un análisis exploratorio inicial (EDA) de cuatro conjuntos de datos, diagnosticar sus características principales, identificar problemas específicos relevantes y seleccionar uno de ellos para un análisis posterior más profundo. Este enfoque permite explorar diferentes dominios de datos, destacando oportunidades y desafíos específicos en cada conjunto de datos.

## Conjuntos de Datos Analizados  
1. **Uso de Aplicaciones Móviles**  
   - Simula patrones de uso de usuarios, ofreciendo oportunidades en segmentación y análisis de experiencia del usuario.  

2. **Clientes de Centros Comerciales**  
   - Se enfoca en segmentación de clientes basada en variables demográficas y de gasto.  

3. **Ventas Minoristas**  
   - Analiza transacciones anuales y patrones de compra, ideal para segmentación y análisis de ventas.  

4. **Calidad de Vino**  
   - Explora la relación entre características fisicoquímicas y calidad del vino, con potencial para predicción de calidad.  

## Resumen del EDA Inicial  
1. **Uso de Aplicaciones Móviles**  
   - Balanceado y con datos independientes, pero la baja correlación entre variables podría complicar modelos predictivos.  
   - **Potenciales aplicaciones**: clasificación de retroalimentación y segmentación de usuarios.  

2. **Clientes de Centros Comerciales**  
   - Adecuado para segmentación, con patrones claros de gasto relacionados con la edad.  
   - **Desafío**: manejo de outliers en ingresos y falta de correlación significativa entre otras variables.  

3. **Ventas Minoristas**  
   - Variables de ventas bien distribuidas y correlaciones fuertes en monto total, precio y cantidad.  
   - **Desafío**: falta de correlación significativa entre género/categoría y variables numéricas requiere análisis más avanzado.  

4. **Calidad de Vino** *(seleccionado)*  
   - **Correlaciones clave**: alcohol con calidad (positiva) y acidez volátil con calidad (negativa).  
   - Presencia de valores atípicos en azúcar residual y dióxido de azufre, ofreciendo un desafío único para modelado.  
   - La variable objetivo `quality` está bien definida y balanceada, lo que permite abordar problemas de clasificación.  

## Problema Seleccionado  
### Predicción de la Calidad del Vino  
El dataset de calidad de vinos fue seleccionado debido a sus características bien estructuradas, correlaciones significativas entre variables y un desafío claro en la predicción de la calidad a partir de las propiedades fisicoquímicas. Este análisis tiene relevancia en la industria vinícola, donde modelos predictivos podrían optimizar procesos de producción o evaluar productos en tiempo real. Además, la presencia de outliers y la naturaleza continua de las variables ofrecen una oportunidad para aplicar técnicas avanzadas de preprocesamiento y modelado.

## Instrucciones para Ejecutar  
1. Clonar el repositorio desde GitHub.  
2. Copiar todos los datasets de la carpeta "datasets" y pegarlos junto a los archivor .ipynb de la carpeta EDA
2. Explorar los notebooks en la carpeta `/EDA` para comprender los análisis iniciales realizados en los cuatro datasets.  

## Autores  
- Cristian Rivas - Análisis y desarrollo del proyecto.  

## Licencia  
Este proyecto está bajo una licencia de uso libre para fines educativos y no comerciales.
