## **INTRODUCCIÓN**

Hola!👋 Me llamo Navy, les presento uno de los proyectos realizados para Dicsys. 
Es una App de Analitica Social que permitirá combinar datos de diferentes canales y mejorar la calidad de los datos de marketing


## **Objetivo**

La plataforma permitirá integrar automáticamente datos de la API de Reporting - Data de Google Analytics. Además, podriamos enviar sus conjuntos de datos limpios y 
armonizados a cualquier herramienta de BI, software de visualización, base de datos o almacén de datos.
Utilizaremos un módulo ETL avanzado, los usuarios podran recopilar, armonizar y enviar datos de Google Analytics visualizar los datos en paneles dentro de nuestra 
plataforma.

La plataforma de análisis de datos avanzada de Social Analizer podra  extraer, transformar y cargar datos provenientes de Google Analytics a través de su API. Podremos ejecutar este tipo de consultas para las dimensiones y métricas que son relevantes para una empresa o individuo desde la API de informes centrales. A través de la plataforma se podrá personalizar las consultas y automatizar la generación de informes.

Además la plataforma permitirá combinar datos de diferentes canales y mejorar la calidad de los datos de marketing. Obtener la información más reciente sobre el rendimiento de las propiedades web y descubrir qué es lo que más les importa a los clientes.

## **Directorios y archivos del repositorio**

- [**Data**:](./Data/) Directorio donde se disponibilizan las fuentes de datos sin procesar. Son todos archivos csv
  
- [**Prophet**:] (./[Prophet/](/data_analytics_python/blob/main/Prophet%20-%20New%20Users%20-%20Time.ipynb)

- [**Análisis EDA y Modelo de datos**:](.[/Analytics%20EDA%20-%20New%20Users.ipynb) Análisis exploratorio de datos y modelado necesario para llevar
   a cabo el reporte

## **ETAPAS DEL PROYECTO**

---

### **1) Estudio de la fuente de datos y EDA (Exploratory Data Analysis)**

En primer lugar se realiza un estudio de las fuentes de datos disponibilizadas en archivos `.csv` de Google analytics 4
Se agregaron otras fuentes de datos como redes sociales (Instagram, twitter...)
Se hace una exploración de datos, revisión de duplicados, tipos de datos, valores faltantes y errores en los datos tomando las acciones necesarias.

*Google Analytics 4 - API Data V1 Reporting*

Los informes devueltos por los métodos de informes de la API Data v1 son tablas de datos de eventos para una propiedad de Google Analytics 4. Una tabla de informe se compone de dimensiones y métricas especificadas en la solicitud de API del informe, con datos de informe devueltos en filas individuales.

La API de datos de Google Analytics v1 nos permite generar informes de embudo. La exploración del embudo le permite visualizar los pasos que toman sus usuarios para completar una tarea y ver rápidamente qué tan bien están teniendo éxito o fallando en cada paso.Funciones compartidas con Core Reports: Las solicitudes de informes de embudo tienen la misma semántica que las solicitudes de informes principales para muchas funciones compartidas. Por ejemplo, la paginación, los filtros de dimensión y las propiedades de usuario se comportan de la misma manera en los informes de embudo que en los informes principales.

*INSIGHTS PRINCIPALES DE GA4*

La gran cantidad de usuarios que llegaron a su sitio desde las redes sociales, tanto por primera vez como como visitantes recurrentes. ¿Sus redes sociales están haciendo un buen trabajo para atraer a nuevos usuarios que estén lo suficientemente interesados ​​en convertir, o al menos en visitar su sitio? Si es así, está funcionando como una plataforma de descubrimiento.

El número de sesiones de engagemen y el tiempo promedio de participación por sesión. Utilice estas métricas para tener una idea de cuántos usuarios de redes sociales visitan su sitio y lo visitan en lugar de rebotar. ¿Cuánto tiempo se quedan? ¿El tiempo suficiente para ver un video o hacer clic en algunas páginas? Cuanto más comprometido, mayor será la calidad de los clientes potenciales en las redes sociales.

Sesiones de engagement  por usuario. Esto le dice cuántas veces un usuario regresará a su sitio en promedio durante el período de tiempo seleccionado, y esto es importante. Los clientes comprometidos deberían regresar varias veces durante un período de varios meses y (lo que es más importante) a menudo visitarán su sitio varias veces durante el proceso de compra.

Eventos por sesión y recuento de eventos. ¿Vienen los usuarios a su sitio y no realizan ninguna acción? Eso puede significar que te estás dirigiendo a la audiencia equivocada en las redes sociales o que necesitas tener un mejor embudo configurado. Esto podría incluir tener una página de destino específicamente para sus anuncios de redes sociales o tráfico de referencia. También podría significar que necesita mejorar su embudo en el sitio con una mejor navegación u ofertas más relevantes.
Si bien es común que los usuarios solo tomen uno o dos eventos por sesión (como ver una página y tal vez ver un video), se debe intentar apuntar a eventos de alto valor como completar formularios de clientes potenciales o agregar elementos a un carrito.

Número total de conversiones. Las conversiones pueden ser cosas diferentes, como suscribirse a una lista de correo electrónico o realizar una compra. ¿Cuántas personas que provienen de las redes sociales están realmente realizando una acción como esta, que es una acción de alta intención? Dado que los usuarios orgánicos de las redes sociales deberían ser audiencias bastante cálidas, querrá ver este número a la par con otras fuentes de tráfico, como el tráfico de referencia de enlace directo.
Los ingresos totales. Si tiene configurado el seguimiento de ingresos, puede ver cuántos ingresos ha generado su tráfico proveniente de las redes sociales. Esto puede ser invaluable, aunque querrá asegurarse de que se alinee con los datos de su sistema de comercio electrónico; a veces puede haber una disparidad.

### **2) ETL (Extract, Transform and Load)**

En el archivo de [**Análisis EDA y Modelo de datos**:](./AnalisisEDA-ModeloDatos.md) Se utilizaron scripts de Python como parte de la transformación para la obtención de las columnas de fecha. Se realiza el modelado para obtener datos que se relacionen entre sí.


## **STACK TECNOLÓGICO**

---

- Google Analytics 4
- Python
- Pandas

<div>
<img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Power-BI.svg" width=45px height=45px/>        
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width=50px height=50px/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width=50px height=50px/>



