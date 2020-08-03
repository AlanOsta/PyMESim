Autor: Alan Ostaszynski
Mail: alanosta@gmail.com
Fecha: 2/8/2020

Concepto:
La idea del proyecto es una web app de gestion y planificacion de la produccion para pequeñas y medianas empresas manufactureras (posiblemente ampliable a empresas proveedoras de servicios).
Gran parte de los conceptos y estrategias del proyecto se basan en el blog https://production-scheduling.com/ que explica como hacer sistemas de gestion y planificacion con planillas de Excel.
Se toma como caso de analisis la empersa Mobica SRL que es de mi propiedad y en donde aplique satisfactoriamente los conceptos aprendidos del citado blog.

Estructura:
Hasta el momento el analisis es conceptual, plasmado en una planilla de excel donde se evalua la interaccion entre los distintos modulos que formaran parte de la app.

bocetoGeneral.xlsx se compone de las siguientes hojas:

ProdParte: la idea de esta planilla/tabla es enumerar las distintas partes (finales o semielboradas) que componen a un producto de venta. La idea predominante es que existe un nivel de jerarquias donde se relacionan co-dependencias entre partes hijas y partes padres afectadas (porcesadas) por los distintos centros de produccion.

CentrosDeProduccion: es una tabla que define unidades transformadoras de materias primas, semielaborados o servicios. Ej: cortado, mecanizado, transporte, compra, gestion de venta, etc.

Materiales: es una tabla donde se listan las materias primas afectadas a la produccion del bien, sus propiedades, sus proveedores, tiempos de entrega, etc.

MO: (vacia) "mano de obra" es un componente indispensable para el analisis finito de las capacidades productivas de una empresa, todavia no tengo claro todos los conceptos que debemos incluir en esa tabla.

Proveedores: (vacia) basicamente lista informacion sobre los distintos proveedores y por sobre todo sus lead times (tiempos de entrega) variable indispensable para la correcta planificacion de la produccion.


Este proyecto esta formalmente comenzando el dia de hoy, 2/8/2020.







