# Visión de Resolana

> "Lo sentimos, pero no sabemos cómo actuar"

## El problema

Actualmente el municipio de Los Patios del departamento de Norte de Santander se enfrenta a un fenómeno que se ha ido prolongado y que por la contaminación tan presente, las consecuencias ya están tomando control sobre la forma en cómo vivimos. 

En la primera semana de mayo de 2026, el IDEAM registró 35,6°C en el aeropuerto de Cúcuta ([IDEAM, mayo de 2026](https://www.ideam.gov.co/file-download/download/public/19994)), 2,7°C por encima del promedio historico. Sin embargo, este registro proviene de una sola estación, nadie sabe cuanto calor hace en cada barrio de los Patios. 

Con lo anterior, y centrando solo el municipio de Los Patios en Colombia, las personas no reciben información anticipada, local y accionable sobre el calor extremo, por lo que no pueden protegerse a tiempo. 

## Para quién es

La idea es beneficiar a las personas afectadas por el enfrentamiento de esta situación de manera general. De igual forma, beneficiar a comercios que desean mantener sus actividades sin este impedimento de saber cómo trabajar con el calentamiento. 
     
Analizando la forma en cómo se desea interactuar con el sistema actualmente, se contempla unicamente un rol de persona en el MVP. Sin embargo, para versiones futuras ya se buscara una forma de clasificar a las personas segun su edad y condiciones especificas, para personalizar la información.

## Propuesta de valor

Para **personas del comun** que **desconocen cómo actuar o que consejos tomar para los picos de calor**,
Resolana es **una plataforma** que **mejora la forma en como se actua ante el calentamiento**.
A diferencia de **solo conocer la temperatura actual del momento**,
Resolana **avisa con anticipación, por barrio y diciendote qué hacer.**

## Cómo sabremos que funciona

* 3 horas de aviso de anticipación en el 95% de los episodios. 
* Entregar el 95% de las alertas en un periodo inferior a 2 minutos. 
* La antiguedad del dato recopilado no sera superior a 60 minutos.

## Alcance del MVP

* Recopilar datos del clima de una API publica unicamente del municipio de Los Patios
* Calculo de un nivel de riesgo por calor por cada zona 
* Alertas anticipadas y en el momento con un sistema de recomendaciones
* Registro de usuarios con consentimiento de privacidad
* Mapa por zonas con colorimetria segun el nivel de riesgo por barrios que sale del pronostico más la capa fija de cada zona

## Fuera de alcance

* Gestión de agua, consumo y racionamiento porque el objetivo central es actuar ante el calor tomando medidas preventivas de manera general
* Sensores propios (en árboles) y lectura de baterias de celulares porque por tema de recursos limitados y acceso, no es posible implementarlo

## Ideas futuras

* Mapa de continuo en tiempo real sobre los riesgos presentados
* Predicción con modelos de machine learning
* Rutas de sombra
* Personalización por vulnerabilidad con sus riesgos 
* WhatsApp como canal de alertas. 