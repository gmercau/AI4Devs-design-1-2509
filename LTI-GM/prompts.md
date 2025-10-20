# Documento de Requisitos y Diseño para un Sistema ATS (Applicant Tracking System)

## 1. Investigación y análisis de requisitos

### Prompt 1  
> Sos un experto en producto, con experiencia en ATS (Applicant-Tracking System).
> Estás en la etapa de investigación y análisis de requisitos.  
> Define las funcionalidades básicas en general.  
> Descríbelas en un listado, ordenado de mayor a menor prioridad.

### Prompt 2  
> ¿Qué beneficios obtiene el cliente de un ATS para considerar su uso?

### Prompt 3  
> ¿Qué alternativas tiene a usar un ATS y cuándo pueden ser relevantes?

### Prompt 4  
> ¿Cómo es el *customer journey* normal de un cliente que usa un ATS?  
> Descríbeme paso a paso todas las interacciones.

### Prompt 5  
> De acuerdo a las funcionalidades básicas que enumeras, analiza en cuáles es posible incorporar IA para obtener un beneficio extra.

---

## 2. Definición de casos de uso

### Prompt 1  
> Sos un analista de software experto.
> Estoy construyendo un sistema ATS como el representado en la información que adjunto.  
> Enumera y describe brevemente los casos de uso más importantes a implementar para lograr una funcionalidad básica.

### Prompt 2  
> Representa estos casos de uso en el tipo de diagrama más adecuado usando el formato PlantUML.  
> Diferencia entre usuarios visitantes y usuarios logueados.  
> Acorde a la sintaxis y buenas prácticas UML, define y describe lo que sea necesario.

### Prompt 3  
> De lo analizado anteriormente, dame los 3 casos de uso principales, con diagramas UML asociados a cada uno.

---

## 3. Modelado de datos

### Prompt 1  
> Sos un arquitecto de software experto.
> Estoy construyendo un sistema ATS como el representado en la información que adjunto.  
> ¿Cuáles son las 3 entidades de modelo de datos esenciales en el sistema?  
> Dame algunos campos esenciales de cada una y cómo se relacionan.

### Prompt 2  
> Considera lo analizado anteriormente y los archivos adjuntos.  
> Sos un brillante arquitecto de software. Sos capaz de diseñar, explicar y diagramar los diferentes aspectos de un sistema de software. 
>  
> Estoy construyendo un sistema ATS. He definido las entidades `Candidate`, `Vacancy` y `Application`, con sus campos y relaciones.  
>  
> ¿Qué otras entidades del modelo de datos son importantes en el sistema ATS?  
> Dame los campos más importantes de cada una y cómo se relacionan entre entidades.

---

## 4. Diseño del sistema y arquitectura de alto nivel

### Prompt 1  
> Sos un experto en arquitectura de software.  
> Considerando la documentación adjuntada para un sistema ATS, define la estructura general del sistema, incluyendo:  
> - La arquitectura de software  
> - La distribución de componentes  
> - La integración de sistemas externos  
> - Los patrones de comunicación

---

## 5. Diagramas C4

### Prompt 1  
> De acuerdo al análisis anterior, genera un Diagrama C4 que llegue en profundidad a uno de los componentes del sistema.  
> Considera un componente simple para obtener un diagrama sencillo.  
> Generar el diagrama en PlantUML.