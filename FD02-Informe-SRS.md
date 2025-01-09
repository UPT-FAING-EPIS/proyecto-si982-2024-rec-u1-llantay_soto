<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *{Nombre de Proyecto}***

Curso: *{Nombre de Asignatura}*

Docente: *{Nombre de Docente}*

Integrantes:

***{Apellidos y nombres del estudiante (código universitario)}***

**Tacna – Perú**

***{Año}***

**  
**
</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|












**Sistema *{Nombre del Sistema}***

**Documento de Visión**

**Versión *{1.0}***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**INDICE GENERAL**
#
[1.	Introducción ] (#_Toc52661346)

[1.1 Generalidades de la Empresa  ](#_Toc52661346)

1.1	Nombre de la Empresa 

1.2 Visión  

1.3 Misión  

1.4 Organigrama 

[1.2.	Visionamiento de la Empresa  ](#_Toc52661347)

2.1	Descripción del Problema  

2.2 Objetivos de Negocios  

2.3 Objetivos de Diseño  

2.4 Alcance del proyecto  

2.5 Viabilidad del Sistema  

2.6 Información obtenida del Levantamiento de Información  

[2. ANÁLISIS DE PROCESOS](#_Toc52661348)

a. Diagrama del Proceso Actual – Diagrama de actividades  

b. Diagrama del Proceso Propuesto – Diagrama de actividades Inicial  

[3.	ESPECIFICACIÓN DE REQUERIMIENTOS DE SOFTWARE](#_Toc52661349)

a. Cuadro de Requerimientos funcionales Inicial  

b. Cuadro de Requerimientos No funcionales  

c. Cuadro de Requerimientos funcionales Final  

d. Reglas de Negocio 

[4.	FASE DE DESARROLL](#_Toc52661350)

1. Perfiles de Usuario  

2. Modelo Conceptual

a. Diagrama de Paquetes  

b. Diagrama de Casos de Uso  

c. Escenarios de Caso de Uso (narrativa)  

3. Modelo Lógico  
   a. Análisis de Objetos  

   b. Diagrama de Actividades con objetos  

   c. Diagrama de Secuencia  

   d. Diagrama de Clases  

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de SRS</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Introducción**

1.1 Generalidades de la Empresa

1.1	Nombre de la Empresa 

1.2 Visión  

1.3 Misión  

1.4 Organigrama 

1.2.	Visionamiento de la Empresa

2.1	Descripción del Problema  

En el mercado laboral actual, existe una desconexión entre empleadores y potenciales empleados, especialmente en regiones donde las herramientas digitales son limitadas o ineficaces. Los empleadores enfrentan dificultades para encontrar candidatos cualificados de manera eficiente, mientras que los solicitantes de empleo carecen de una plataforma centralizada para explorar oportunidades. Esto genera un proceso lento, costoso y poco accesible.

2.2 Objetivos de Negocios  

1. Proveer una plataforma eficiente que conecte empleadores con candidatos calificados.
2. Reducir los costos asociados a la búsqueda de empleo y reclutamiento.
3. Aumentar la visibilidad de las oportunidades laborales para los usuarios registrados.

2.3 Objetivos de Diseño  

1. Crear una interfaz intuitiva y accesible para empleadores y candidatos.
2. Garantizar la seguridad de la información personal y profesional de los usuarios.
3. Permitir la escalabilidad del sistema para incorporar futuras funcionalidades y soportar un aumento en usuarios.

2.4 Alcance del proyecto 

El sistema de bolsa de trabajo incluye el desarrollo de una plataforma web y/o móvil que permite la publicación de ofertas
laborales y la gestión de candidaturas. Los usuarios podrán crear perfiles, tanto empleadores como candidatos, con la
capacidad de subir currículums y descripciones de empresa. Se implementará un sistema de búsqueda y filtrado eficiente que
facilite la conexión entre las ofertas de empleo y los postulantes. Además, el sistema generará reportes sobre métricas
clave, como el número de postulaciones y visualizaciones. También se integrarán métodos de comunicación directa, como chats
o correos, entre empleadores y postulantes. Finalmente, contará con módulos administrativos para el monitoreo y gestión del
sistema por parte de los administradores.

2.5 Viabilidad del Sistema  

El proyecto es técnicamente viable mediante el uso de tecnologías modernas, como frameworks de desarrollo web o móvil
(Flutter, React, etc.) y bases de datos escalables como PostgreSQL o MongoDB. Desde un punto de vista económico, los costos
iniciales de desarrollo y mantenimiento pueden ser cubiertos mediante el modelo de negocio, que incluye ingresos por
anuncios y suscripciones, garantizando la sostenibilidad a largo plazo. Operativamente, los usuarios finales, tanto
empleadores como candidatos, están familiarizados con el uso de plataformas digitales, lo que facilita la adopción del
sistema. Legalmente, el sistema cumplirá con las regulaciones de protección de datos personales, como el RGPD, para
garantizar la privacidad y la confianza de los usuarios.

2.6 Información obtenida del Levantamiento de Información  

A través del levantamiento de información se identificó que los empleadores necesitan una solución que les permita
encontrar perfiles calificados de forma rápida y confiable. Por otro lado, los candidatos demandan una plataforma que
ofrezca una búsqueda laboral personalizada y eficiente. También se detectaron problemas comunes, como la falta de
organización de currículums y la limitada comunicación entre empleadores y postulantes. Aunque existen plataformas
similares, muchas presentan costos elevados o no están adaptadas a necesidades locales específicas. Por último, los
usuarios esperan una experiencia amigable, segura y con notificaciones claras sobre los procesos de postulación y selección.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**ANÁLISIS DE PROCESOS**

a. Diagrama del Proceso Actual – Diagrama de actividades  

b. Diagrama del Proceso Propuesto – Diagrama de actividades Inicial  

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**ESPECIFICACIÓN DE REQUERIMIENTOS DE SOFTWARE**

a. Cuadro de Requerimientos funcionales Inicial  

b. Cuadro de Requerimientos No funcionales  

c. Cuadro de Requerimientos funcionales Final  

d. Reglas de Negocio 

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**FASE DE DESARROLLo**

1. Perfiles de Usuario  

2. Modelo Conceptual

a. Diagrama de Paquetes  

b. Diagrama de Casos de Uso  

c. Escenarios de Caso de Uso (narrativa)  

3. Modelo Lógico  
a. Análisis de Objetos  

b. Diagrama de Actividades con objetos  

c. Diagrama de Secuencia  

d. Diagrama de Clases  

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661355" class="anchor"></span>**CONCLUSIONES**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661356" class="anchor"></span>**RECOMENDACIONES**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661357" class="anchor"></span>**BIBLIOGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661358" class="anchor"></span>**WEBGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>
