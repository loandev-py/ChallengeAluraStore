# Análisis de Ventas - AluraStore Latam

## Descripción del Proyecto
Este proyecto analiza los datos de ventas de AluraStore en Latinoamérica (principalmente Colombia) para identificar patrones de comportamiento, rendimiento por tienda y distribución geográfica de las ventas.

## Estructura del Proyecto

│
├── data/ # Datos originales (4 archivos CSV)
├── notebooks/
│ └── AluraStoreLatam.ipynb # Notebook principal con el análisis
├── images/ # Gráficos generados
├── README.md # Este archivo
└── requirements.txt # Dependencias


## Análisis Realizados

### 1. Facturación por Tienda
- Cálculo de ingresos totales por tienda
- Identificación de la tienda con mayor facturación (Tienda 1: $1,150M)

### 2. Ventas por Categoría
- Análisis de productos vendidos por categoría
- Categoría más popular: Muebles (en todas las tiendas)
- Distribución detallada por categorías secundarias

### 3. Calificación Promedio
- Cálculo de satisfacción del cliente por tienda
- Mejor calificada: Tienda 3 (4.05/5)

### 4. Productos Más y Menos Vendidos
- Identificación de productos estrella y de bajo desempeño
- Microondas (más vendido en Tienda 1)
- Juego de mesa (menos vendido en Tienda 2)

### 5. Análisis Geográfico
- Mapeo de ventas por coordenadas (lat/lon)
- Heatmaps de densidad de ventas
- Relación entre ubicación y:
  - Precios de productos
  - Métodos de pago
  - Satisfacción del cliente

## Hallazgos Clave

1. **Patrones Geográficos**:
   - Ventas concentradas en áreas urbanas principales
   - Correlación entre ubicación y valor promedio de compra

2. **Desempeño por Tienda**:
   - Tienda 1 lidera en ingresos pero no en satisfacción
   - Tienda 3 tiene mejor balance entre volumen y calidad

3. **Preferencias Regionales**:
   - Variación significativa en categorías preferidas por zona
   - Diferencias en métodos de pago predominantes

## Tecnologías Utilizadas

- Python 3
- Bibliotecas:
  - Pandas (análisis de datos)
  - Matplotlib/Seaborn (visualización)
  - Scikit-learn (análisis básico)

## Cómo Ejecutar

1. Clonar repositorio
2. Instalar dependencias:

pip install -r requirements.txt

3. Ejecutar Jupiter Notebook:

jupyter notebook notebooks/AluraStoreLatam.ipynb

Recomendaciones Comerciales

    Optimización de Inventario:

        Ajustar stock según preferencias locales

        Reducir productos de bajo movimiento en zonas específicas

    Estrategias de Marketing:

        Campañas geolocalizadas

        Promociones por métodos de pago predominantes

    Mejora de Experiencia:

        Investigar causas de bajas calificaciones en zonas específicas

        Programas de fidelización regionalizados

Próximos Pasos

    Integrar datos demográficos

    Análisis temporal de ventas

    Modelado predictivo por región

Licencia

MIT License


Este README proporciona una visión completa del proyecto, incluyendo:
1. Estructura organizacional
2. Resumen de análisis realizados
3. Hallazgos clave
4. Instrucciones de ejecución
5. Recomendaciones basadas en datos
6. Roadmap futuro

El formato Markdown permite visualización clara en GitHub/GitLab y facilita la comprensión del alcance del proyecto.