# 📊 Análisis de Rendimiento de Tiendas - Alura Store

## Descripción del Proyecto

Este proyecto consiste en un análisis exploratorio de datos de ventas de cuatro tiendas pertenecientes a la cadena **Alura Store**. El objetivo principal es evaluar el rendimiento de cada tienda para recomendar al Sr. Juan cuál de ellas debería vender con el fin de invertir en un nuevo emprendimiento.

Para realizar esta evaluación se analizaron diferentes métricas clave como:

* Facturación total por tienda
* Cantidad de productos vendidos
* Categorías de productos más populares
* Calificación promedio de los clientes
* Productos más y menos vendidos
* Costo promedio de envío
* Distribución geográfica de las ventas

A partir de estos análisis se generaron visualizaciones y mapas que permiten comprender mejor el comportamiento comercial de cada tienda.

---

# 🎯 Objetivo del Análisis

El objetivo de este proyecto es identificar **la tienda con menor rendimiento general** dentro de la cadena, considerando diferentes indicadores de desempeño, con el fin de recomendar cuál debería venderse para liberar capital e invertir en un nuevo negocio.

---

# 🛠 Tecnologías Utilizadas

El análisis fue desarrollado en **Python utilizando Google Colab**, empleando las siguientes bibliotecas:

* **Pandas** → Manipulación y análisis de datos
* **Matplotlib** → Visualización de datos
* **Seaborn** → Gráficos estadísticos
* **Folium** → Visualización geográfica y mapas interactivos

---

# 📂 Fuente de los Datos

Los datos utilizados provienen del repositorio público del challenge de **Alura Latam Data Science**, que incluye registros de ventas de cuatro tiendas.

Cada dataset contiene información como:

* Producto
* Categoría del producto
* Precio
* Calificación del cliente
* Costo de envío
* Latitud y longitud de la compra

---

# 📈 Análisis Realizados

## 1️⃣ Análisis de Facturación

Se calculó la facturación total de cada tienda sumando el precio de todos los productos vendidos.

Resultados principales:

| Tienda   | Facturación    |
| -------- | -------------- |
| Tienda 1 | $1,150,880,400 |
| Tienda 2 | $1,116,343,500 |
| Tienda 3 | $1,098,019,600 |
| Tienda 4 | $1,038,375,700 |

La **Tienda 1 presenta la mayor facturación**, mientras que **Tienda 4 muestra el valor más bajo**.

También se analizó la **cantidad total de productos vendidos**, observándose volúmenes muy similares entre todas las tiendas.

---

## 2️⃣ Ventas por Categoría

Se analizaron las categorías más vendidas en cada tienda.

Las categorías con mayor volumen de ventas son:

* **Muebles**
* **Electrónicos**
* **Juguetes**

Estas categorías dominan el mercado en todas las tiendas, mostrando un patrón de demanda consistente.

---

## 3️⃣ Calificación Promedio de Clientes

Se calculó la calificación promedio otorgada por los clientes a cada tienda.

| Tienda   | Calificación promedio |
| -------- | --------------------- |
| Tienda 1 | 3.98                  |
| Tienda 2 | 4.04                  |
| Tienda 3 | 4.05                  |
| Tienda 4 | 4.00                  |

La **Tienda 3 presenta la mayor satisfacción del cliente**.

---

## 4️⃣ Productos Más y Menos Vendidos

Al analizar todas las tiendas en conjunto:

* **Producto más vendido:** Mesa de noche (210 ventas)
* **Producto menos vendido:** Celular ABXY (157 ventas)

También se generaron gráficos con los **10 productos más vendidos y menos vendidos**.

---

## 5️⃣ Costo Promedio de Envío

Se calculó el costo promedio de envío para cada tienda.

| Tienda   | Envío promedio |
| -------- | -------------- |
| Tienda 1 | 26,018         |
| Tienda 2 | 25,216         |
| Tienda 3 | 24,805         |
| Tienda 4 | 23,459         |

La **Tienda 4 tiene el costo de envío más bajo**, lo que representa una ventaja operativa.

---

# 🌎 Análisis Geográfico de Ventas

Utilizando las coordenadas geográficas (latitud y longitud) se generaron **mapas de calor interactivos** para visualizar la distribución de las ventas.

Los mapas muestran que:

* Las ventas se concentran principalmente en **Bogotá y Medellín**
* También existe actividad comercial en ciudades como:

  * Cali
  * Cartagena
  * Santa Marta
  * Barranquilla
  * Cúcuta
  * Pereira

Se observan patrones geográficos similares entre las tiendas, aunque algunas presentan presencia más fuerte en determinadas regiones.

---

# 📊 Visualizaciones

El proyecto incluye múltiples visualizaciones, entre ellas:

* Gráficos de barras de facturación por tienda
* Gráficos de ventas por categoría
* Gráficos de productos más y menos vendidos
* Comparación de calificaciones de clientes
* Comparación de costos de envío
* Mapas de calor geográficos de ventas

Estas visualizaciones permiten comprender rápidamente el rendimiento de cada tienda.

---

#  Conclusión

Después de analizar todos los indicadores clave, se identificaron diferencias claras en el desempeño de las tiendas.

Observaciones principales:

* **Tienda 1** tiene la mayor facturación.
* **Tienda 3** presenta la mayor satisfacción del cliente.
* **Tienda 2** mantiene un desempeño estable.
* **Tienda 4** presenta la **facturación más baja**.

---

#  Recomendación Final

Se recomienda al **Sr. Juan vender la Tienda 4**.

### Justificación

La Tienda 4 muestra:

* La **facturación total más baja** entre las cuatro tiendas
* Un volumen de ventas similar al de las otras tiendas
* Posible venta de productos de menor valor

Aunque tiene el costo de envío promedio más bajo, su contribución a los ingresos totales de la cadena es la menor.

Por lo tanto, vender esta tienda permitiría liberar capital sin afectar significativamente el rendimiento global de la cadena.
