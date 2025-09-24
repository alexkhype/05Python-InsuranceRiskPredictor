# Predicción de Prestaciones de Seguros

## Tabla de Contenidos
- [Descripción](#Descripción)
- [Datos](#Datos)
- [Análisis](#Análisis)
- [Tecnologías y herramientas](#Tecnologías-y-herramientas)
- [Resultados](#Resultados)
- [Contribuciones](#Contribuciones)
- [Licencia](#Licencia)
- [Contacto](#Contacto)

## Descripción
Este proyecto mejora la asignación de seguros en Sure Tomorrow usando modelos de machine learning para predecir la probabilidad de que un cliente reciba un seguro y proteger sus datos personales mediante enmascaramiento, optimizando así los servicios de la compañía.

## Datos
Se utilizó un conjunto de datos principal:  
- **insurance_us.csv**: DataFrame con 5000 registros y 5 columnas: género, edad, ingresos, miembros familiares y beneficios de seguro, sin valores nulos.

## Análisis
El enfoque incluyó:  
- Se identificaron patrones en clientes equilibrados en género, con ingresos medios-bajos y baja cobertura de seguro.
- Se aplicó algoritmo kNN con distancias euclidiana y Manhattan, destacando la importancia del escalado para mejorar resultados.
- Se construyó un clasificador KNN con y sin escalado, demostrando mejoras significativas en el F1 score tras el escalado.
- Implementación de regresión lineal propia que confirmó robustez en métricas pese al escalado.
- Desarrollo de un algoritmo para ofuscar datos mediante transformaciones lineales sin afectar la calidad predictiva.

## Tecnologías y herramientas
- Python 3.9 para desarrollo general
- Pandas y NumPy para manipulación y análisis de datos
- Matplotlib y Seaborn para visualización gráfica
- Scikit-learn para construcción y evaluación de modelos predictivos
- Jupyter Notebook para desarrollo interactivo y presentación de análisis

## Resultados
- El escalado para el kNN mejoró la detección de clases con un F1 score de 0.97.
- La regresión lineal mantuvo precisión y ajustes similares tras escalado, validando estabilidad del modelo.
- La ofuscación de datos protegió información sensible sin afectar la calidad del modelo, manteniendo métricas como R² y RMSE constantes.
- La matriz invertible usada para ofuscación mantuvo las predicciones intactas, confirmando el éxito de la protección sin pérdida de rendimiento.

## Contribuciones
Bienvenidas sugerencias, correcciones y nuevas visualizaciones. Por favor, abre un issue o pull request para colaborar.

## Licencia
Este proyecto está bajo la licencia MIT.

## Contacto
Nombre: Alejandro M. García  
Email: [alexkhype@gmail.com](mailto:alexkhype@gmail.com)  
LinkedIn: [linkedin.com/in/amggl](https://linkedin.com/in/amggl)
