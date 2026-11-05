# Observatorio de ofertas y descuentos de Farmacia Cuxibamba en Loja

Ofertas, promociones y descuentos de Farmacia Cuxibamba comparados con la competencia en la ciudad de Loja. Proyecto integrador de Programación Aplicada a la Inteligencia de Mercados (UIDE Loja).

## Pregunta de negocio

¿Debemos lanzar nuevas promociones, igualar los descuentos de la competencia, mantener los precios normales, o conviene esperar a tener más datos del mercado en Loja durante este mes?

## Quién decide y qué decisión apoya

* **Quién decide:** Gerente de Marketing y Comercial de Farmacia Cuxibamba
* **Decisión:** Definir la estrategia mensual de promociones y descuentos para atraer más clientes sin sacrificar el margen de la farmacia.

## Indicadores

* Porcentaje promedio de descuento en productos clave frente a la competencia
* Frecuencia semanal de campañas y ofertas lanzadas por otras farmacias

## Fuentes previstas

* Redes sociales y piezas publicitarias digitales de la competencia en Loja
* Catálogos virtuales y páginas web de farmacias locales

## Estructura del proyecto

* `data/raw/`: datos originales (no se modifican)
* `data/processed/`: datos limpios
* `notebooks/`: cuadernos de análisis
* `src/`: funciones reutilizables
* `reports/`: resultados para quien decide
* `pyproject.toml`: dependencias del proyecto

## Cómo ejecutar

Abrir el cuaderno en Google Colab y usar *Entorno de ejecución > Reiniciar sesión y ejecutar todo*.

## Declaración de uso de IA

Se utilizó Gemini para una mejor redacción, verificando que los textos fueran claros y sencillos.


## Supuestos y limitaciones

Supuesto 1: Los descuentos publicados en redes sociales, catálogos virtuales y páginas web son los que realmente se aplican en las farmacias de Loja.
Supuesto 2: Los clientes de Loja toman en cuenta los descuentos al elegir en qué farmacia comprar sus productos clave.
Limitación: El observatorio solo ve las ofertas publicadas en medios digitales; no incluye las promociones exclusivas de los locales físicos ni las ventas y márgenes de la competencia, por lo que no permite medir cuántos clientes atrae cada oferta.
  
¿Por qué importa para el decisor? 
Declarar estos supuestos y esta limitación ayuda al Gerente de Marketing y Comercial de Farmacia Cuxibamba a definir la estrategia mensual de promociones y descuentos con mayor cautela. Así sabrá que los datos muestran lo que la competencia publica, pero no confirman el efecto de esas ofertas en sus ventas, y evitará igualar un descuento que reduzca el margen sin atraer más clientes.
