# Análisis de LTV, CAC y ROMI 

### Descripción del Proyecto

En este proyecto, se realizaron prácticas en el departamento de analítica de Showz, una empresa dedicada a la venta de entradas de eventos. La tarea principal fue optimizar los gastos de marketing. Para ello, se utilizaron datos de la empresa Showz desde enero de 2017 hasta diciembre de 2018, incluyendo un archivo con pedidos y otro con estadísticas de gastos de marketing.


### Objetivos:

El proyecto se centró en investigar los siguientes aspectos:

   * Cómo los clientes utilizan el servicio.
   * Cuándo los clientes comienzan a realizar compras.
   * Cuánto dinero aporta cada cliente a la compañía.
   * Cuándo los ingresos generados cubren el costo de adquisición de los clientes.

### Metodología:

Para llevar a cabo este proyecto utilicé Python como herramienta principal para el procesamiento, análisis y visualización de datos. Las etapas incluyeron:

   * Análisis exploratorio de datos: limpieza de valores nulos, identificación de duplicados y transformación de datos para facilidatar su análisis.
   * Cálculo de la retención de los usuarios, para conocer cuantos usuarios permanecen con nosotros a través del tiempo.
   * Cálculo de LTV (Valor del ciclo de vida del cliente), para conocer cuanto dinero podemos obtener con cada cliente a lo largo de su relación.
   * Cálculo del CAC (Costo de Adquisicón del Cliente) para conocer cuanto nos cuentas en promodio adquirir un nuevo cliente.
   * Cálculo del ROMI (Retorno de inversión de mercadotecnia) esto nos permite medir el retorno económico de las campañas de mkt.

### Conclusiones:

Teniendo en cuenta que el promedio de las ganancias iniciales de las cohortes han sido de aproximadamente `$` 5 dólares, solo en estas dos cohortes se han incrementado más del 100% las otras cohortes se han quedado por debajo.

La compañía de mkt que más cliente nos trajo es la de la compañía 3, con un promedio de 5 clientes cada vez que realizamos un pago, seguido por la 4 y 5 que nos trajo en promedio 2 clientes, el detalle esta en que 5 de nuestras campañas no nos traen clientes.

La compañía que más nos cobra es la 3, nos cobra `$`3.90 por cliente, seguida de las campañas 4 y 5 con un CAC de `$` 1.67 y `$` 1.41 por cliente, respectivamente

Tendremos que ver la eficiencia de las campañas de marketing para poder saber el porque tan baja la retención, así como las utilidaes. El análisis reveló que las campañas publicitarias no han recuperado la inversión realizada, con algunas campañas de menor costo mostrando un mejor Retorno sobre la Inversión en Marketing (ROMI) debido a su bajo gasto. Específicamente, la campaña publicitaria número 3, a pesar de ser la más costosa y la que genera más clientes, solo está produciendo un rendimiento del 33.64%, lo que indica una recuperación de la inversión muy por debajo de lo esperado. Se sugiere la necesidad de obtener en promedio 15 clientes por cada pago publicitario en esta campaña para alcanzar al menos el punto de equilibrio. Los resultados indican la necesidad de una revisión profunda del equipo de marketing y los canales utilizados.

### Lenguajes y herramientas principales:

   * Python (pandas, matplotlib, numpy, seaborn, matplotlib)
   * Jupyter Notebook para la documentación del flujo de trabajo
