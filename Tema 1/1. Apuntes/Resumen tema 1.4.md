# Sistemas CRM y BI
> Un CRM es un sistema que se enfoca en mejorar la gestión de las relaciones con los clientes. Optimizando áreas como ventas, marketing y atención al cliente. 

## Resumen de los sistemas de gestión empresarial
- ERP:
	- Integran todos los datos y procesos de una organización
	- Suelen incorporar CRM
	- Suelen incorporar BI
- CRM:
	- Apoya la gestión de las relaciones con los clientes
	- Venta y marketing
- BI:
	- Herramienta que te permite tomar decisiones a partir de los datos.

## Función CRM
- Conocimiento de los clientes
- Detecta necesidades:
	- Satisfacción
	- Fidelidad
	- Beneficios
- Recogida de datos:
	- Ventas telefónicas
	- Registros realizados sobre la web

## Módulos CRM
- Clientes:
	- Alta de los clientes en la herramienta (ERP-CRM)
- Clientes potenciales
- Contactos:
	- Saber quienes son las personas asociadas para poder comunicarse con ese cliente
- Productos:
	- Alta de productos (ERP-CRM)
- Soporte:
	- Recoge los detalles de los contactos entre empresa-cliente
		- Email, teléfono, web…
		- Acciones pendientes
		- Fecha, responsable, contenido
	- Módulo de informes y gráficos
		- Informes para toma de decisiones
		- Solución BI del CRM

## CRM independientes
- Adoptan módulos propios de los ERP
	- Ofertas
	- Gestión de pedidos de ventas
	- Gestión de órdenes de entrega
	- Facturación
- Duplicidad de datos con el ERP
	-  Si se tiene un CRM independiente al ERP puede:
		- Haber duplicidad de datos
		- Uno se debe declarar como principal
		- Se debe hacer un volcado de datos
- Se pueden alimentar de la BD del ERP


## Funcionalidades BI
- Busca en los datos de la organización
- Genera escenarios, informes y pronósticos
- Toma de decisiones
- Áreas donde se aplica
	- Ventas:
		- Análisis de ventas
		- Detección de clientes importantes
		- Análisis de productos
	- Marketing:
		- Análisis de clientes 
		- Seguimiento de nuevos productos
	- Finanzas:
		- Análisis de gastos
	- Fabricación:
		- Productividad
		- Calidad
		- Rotación de stock
- Niveles jerárquicos 
	- Estratégico: la directiva decide
	- Táctico: la gerencia organiza y planifica cada área
	- Conocimiento: profesionales con habilidades TIC
	- Operativo: operaciones de los circuitos de:
		- Compraventa
		- Fabricación
		- Contabilidad y finanzas
	- Cada nivel, tiene una necesidad de acceso
- Datos:
	- la herramienta BI, puede obtener los datos de distintas fuentes
- OLTP:
	- Procesos de transacciones en línea
- Repositorio:
	- Lugar donde BI centraliza y almacena los datos 
	- Tipos:
		- Data warehouse
			- Almacén de datos
			- Base para herramientas analíticas
			- Orientada a un ámbito
			- Integrada: contiene datos de todos los orígenes
			- No volátil: ni se modifica ni se elimina
			- Auditable
			- ETL: proceso de filtrado, reestructuración de los datos y eliminación de inconsistencias antes de ser almacenado.
		- Cubos multidimensionales (OLAP)
	- Data mart:
		- Subconjunto de datos del Data Warehouse
		- Se enfoca en un área en concreto
	- Herramientas analíticas
		- Miden la potencia del BI
		- query&reporting:
			- Consultas e informes
			- Diseñan y ejecutan consultas
			- Usa los data warehouse / data marts
		- data mining:
			- Minería de datos
			- Prepara, sondea y explora los datos para obtener información oculta
		- KPI:
			- Indicadores Clave del desempeño
			- Se dice que no se puede mejorar lo que no se puede medir
			- Métricas que se usan para cuantificar el rendimiento de la organización
		- Análisis OLAP:
			- OLAP es el proceso analítico en línea
			- Big data
		- Dashboard:
			- Proporciona información específica del estado de una empresa
			- Muestra la realidad de las áreas de negocio
			- Usa los KPI
			- Alerta cuando un indicador baja del nivel normal

---
# Resumen de Sistemas CRM y BI

**CRM (Customer Relationship Management)**:
- Sistema para gestionar relaciones con los clientes, mejorando ventas, marketing y atención al cliente.
- **Funciones**:
  - Conocer mejor a los clientes.
  - Detectar necesidades para mejorar satisfacción, fidelidad y beneficios.
  - Recoger datos de interacciones (ventas telefónicas, registros web).
- **Módulos**:
  - Clientes, clientes potenciales, contactos, productos, soporte (comunicaciones empresa-cliente, informes y gráficos).
- **CRM independiente**:
  - Integra funciones del ERP.
  - Puede generar duplicidad de datos con ERP, que requiere sincronización o volcado de datos.

**BI (Business Intelligence)**:
- Herramienta que analiza datos para apoyar la toma de decisiones.
- **Áreas de aplicación**: Ventas, marketing, finanzas, fabricación.
- **Niveles jerárquicos**:
  - Estratégico (directiva), táctico (gerencia), operativo (compraventa, fabricación, contabilidad).
- **Datos y OLTP**:
  - BI centraliza datos en repositorios como data warehouses y cubos OLAP, que permiten generar informes y análisis.
- **Herramientas analíticas**:
  - **Query & Reporting**: Diseño de consultas y reportes.
  - **Data Mining**: Exploración de datos para encontrar patrones ocultos.
  - **KPI (Indicadores clave)**: Métricas que cuantifican el rendimiento.
  - **Dashboard**: Visualización de indicadores clave para evaluar el estado de la empresa.

**Repositorio BI**:
- **Data Warehouse**: Almacén de datos que contiene información integrada y auditada.
- **Data Mart**: Subconjunto enfocado en áreas específicas.
- **ETL (Extract, Transform, Load)**: Proceso de transformación de datos antes de almacenarlos.