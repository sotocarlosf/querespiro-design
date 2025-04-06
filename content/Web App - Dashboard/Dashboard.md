El objetivo principal es el siguiente: Informar y alertar a la población sobre las condiciones contaminantes y climatológicas en el Área Metropolitana en la que se encuentra.

Aquí se detallan los objetivos y el alance de la plataforma. Esta plataforma ofrecerá lo siguiente:

### Visibilidad
El sistema no contará con manejo de cuentas de usuario. Contendrá información para uso público y para toda la población.
### Despliegue georreferenciado de sensores de calidad del aire

**Despliegue georreferenciado de sensores de calidad del aire** (oficiales y de bajo costo (calibrados)). 
	Esto se hará por medio de un despliegue de mapa con lecturas de sensores confiables. Al hacer clic en la estación, se despliega la información siguiente:
	- Nombre
	- Red De Monitoreo
	- Fotos del entorno
	- Dirección Postal
	- Coordenadas
	- Altitud
	- Zona Horaria
	- Ultimo envío de datos
	- Personal a cargo
	- Mapa con ubicación de la estación
	- Patrocinador del sensor. Puede ser una marca, AC, empresa, etc.

Opcional: Sensores de terceros por medio de web scraping de otras fuentes.

Mostrar un área de representatividad de las lecturas de cada uno de los sensores. La idea es que cada persona dentro de esta área podría confiar en que lo que mide el sensor es representativo de su área. Cada área de representatividad mostraría lo siguiente basado en el parámetro que se escoja:
- Despliegue de información usando índice de Aire y Salud
	- También se da información relevante para grupos vulnerables.
	- Despliegue de información actualizado usando NOM-172-SEMARNAT-2026. Diferente a la anterior ya que entra en vigor en el 2026

### Interpretación de los datos mostrados

El sistema debe dar al usuario una interpretación de las lecturas de los sensores.
### Exportación de datos
Generar exportaciones de datos satisfactoriamente. Preferentemente que cumplan con las especificaciones de la NOM-172 y den un código de colores a los datos generados.

Generar exportaciones de reportes semanales, y mensuales.

### Visualización de gráficos históricos
Se muestran las lecturas de los sensores antes y después de su calibración. Por defecto, se muestra la lectura calibrada (Aplica únicamente a sensores colocados junto al SIMA)
Los histogramas incluyen una línea punteada que delimita los límites establecidos por la Normativa Mexicana y por la OMS
- Se muestran métricas de las lecturas a lo largo del día:
	- Máximo
	- Mínimo
	- Promedio
	- Porcentaje de mediciones a lo largo del día por arriba de la norma
	- Porcentaje de Datos válidos y de Datos nulos

### Herramienta de suscripción a chatbot que notificará alertas

El usuario puede encontrar información de cómo comunicarse con el chatbot.

Suscripción sencilla a un bot que mandará alertas periódicas basado en tu área de representatividad. La gente debe querer estar dentro del área de representatividad. El bot tendrá las siguientes funcionalidades:
- **Alertas de contingencia**
- **Alertas basadas en pronósticos de contingencia (depende de las dos anteriores)**
- Recomendaciones basadas en el índice de calidad del aire
Opcional: Predicciones de contaminación ambiental en el área de representatividad seleccionada
### Herramienta de contacto con el equipo de STGuimel
Opción de reportar algún problema.


--------------------------------------------------------------------------
## Perfil de Stakeholders
Clientes:
	Sector privado
		Empresas con emisiones contaminantes
		Agencias inmobiliarias residenciales
		Trabajadores de las empresas
		
	Instituciones Educativas
		Escuelas
		Universidades
		Personal de la escuela
		Estudiantes
		
	Instituciones Gubernamentales
		Trabajadores de gobierno
		Equipo de trabajo del SIMA
		
	Población general
	
## Usuarios funcionales generales:
Usuarios para proyectos financiados por sector privado o empresas:
	Trabajadores de una empresa con actividad industrial
	Vecinos de la empresa en donde se instalaron los sistemas de monitoreo
		Quieren evaluar el impacto de las operaciones de la empresa contaminante

Usuarios de Instituciones Educativas
	Estudiantes de una escuela
	Padres de familia
	
Usuarios de agencias inmobiliarias
	Residentes
		Quieren revisar el estado de la calidad del aire en sus áreas comunes
		
Usuarios  de proyectos financiados por instituciones gubernamentales.
	Población general
		Quieren conocer la calidad del aire en su zona donde no hay cobertura de los monitores de gobierno.


Tipos de usuario:
- Al que le interesa echar un vistazo rápido a la contaminación en la ZMM. 
- El técnico que quiere obtener datos históricos e información detallada.
- Al que le interesa estar informado de manera periódica sobre la contaminación en su área representativa.

## Definición de prioridades.

Partimos de satisface al que le interesa echar un vistazo rápido a la contaminación en la ZMM. 

1. Despliegue georreferenciado de sensores de calidad del aire
		El mapa muestra lo siguiente:
			Sensores de STGuimel mostrados en el mapa
			Sensores de Estaciones de Monitoreo del SIMA
		Mostrar polígonos de área de representatividad.
			- Lecturas en tiempo real	
			- Nombre del módulo
			- Ultimo envío de datos
			- Patrocinador del sensor. Puede ser una marca, AC, empresa, etc.
		Despliegue de información usando índice de Aire y Salud
			- También se da información relevante para grupos vulnerables.
			- Despliegue de información actualizado usando NOM-172-SEMARNAT-2026. Diferente a la anterior ya que entra en vigor en el 2026

Nombre del sitio: QueRespiro

