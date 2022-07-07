# ETL

## Módelo

![](https://github.com/MISW-4402-Analisis-y-Modelado-de-datos/Estudiante_42/blob/main/ETL/modelo.png)

## Diseño 

En este proceso de ETL, se extraen los datos de las movimientos de una base de datos transaccional y se almacenan en otra base de datos que corresponde a la bodega de datos, siguiendo una aproximación ROLAP. A continuación, se presenta el modelo multidimensional que es el modelo conceptual que representa el proceso de registro de movimientos. Este modelo se utilizó para crear las tablas en la bodega de datos que representan el proceso de negocio y que serán cargadas como resultado del proceso ETL.

### Proveedor
![](https://github.com/MISW-4402-Analisis-y-Modelado-de-datos/Estudiante_42/blob/main/ETL/dimen_proveedor.png)

### TipoTransaccion
![](https://github.com/MISW-4402-Analisis-y-Modelado-de-datos/Estudiante_42/blob/main/ETL/dimen_tipo_transa.png)

### Hecho_movimiento
![](https://github.com/MISW-4402-Analisis-y-Modelado-de-datos/Estudiante_42/blob/main/ETL/tabla_hecho_movimientos.png)

## Implementación 

[Link jupyter notebook](https://github.com/MISW-4402-Analisis-y-Modelado-de-datos/Estudiante_42/blob/main/ETL/Dise%C3%B1ar-construir-proceso-ETL.ipynb)

