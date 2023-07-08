# RPM Consumer Group - Ejercicio práctico básico de nivelación PowerBI 👋

El ejercicio se debe entregar con plazo máximo el **Martes 11 de Julio 18:00hs**.


Utilizar el siguiente dataset
https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9

**JSON**  https://data.cityofnewyork.us/resource/erm2-nwe9.json


## Titulo del Dashboard
Nombre: **311 Service Requests** |  **[Tu Nombre y Apellido]**

## Objetivo
Visualización de Información de llamadas al número 311 en NYC.
Crear 2 páginas, una para KPIs generales y otra para Mapa.

## Estilos
Ver los 3 ejemplos adjuntos del email, más que nada tomar en cuenta el diseño minimalista y forma de representación de información. 


## Página 1 - KPIs

**Filtros a incluir**
- Creation Date (Desde/Hasta, default mes en curso)
- Closed Date
- Agency Name
- Complaint Type
- Location Type
- City
- Open Data Channel Type
- Status
```javascript
Los mismos no deben ser obligatorios, pero si combinables.
```

**KPIs a visualizar**
- Total de Incidentes en 2023
- Gráfico de Barras con Ranking de Agency Name y recuento
- Gráfico de Anillos con Ranking de Complaint Type y recuento
- Gráfico de Anillos con Status y recuento
- Gráfico de Barras con Ranking de Open Data Channel Type y recuento
- Gráfico de Lineas con multiples series por Complaint Type y fecha, ultimos 30 días
- Gráfico TreeMap con Market Share de Agency y Complaint Type


## Página 2 - Mapa

**Filtros**

Mismos de Pagina 1


```javascript
Los mismos no deben ser obligatorios, pero si combinables.
```


- Mostrar Mapa con burbujas, localizando los datos según coordenadas GPS (Longitud/Latitud)

```javascript
El filtrado debe impactar en la visualización del mapa

```



## Consideraciones
- Subir el archivo PBI y/o cualquier archivo externo utilizado a GitHub personal y compartir el repositorio.
- Incluir el readme.md en el proyecto subido



## Contacto

Cualquier duda escribime a carlos.castro@rustoleum.com.ar


