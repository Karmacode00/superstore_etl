
# Proyecto: ETL

## Contexto
Problema: Los datos vienen de dos fuentes diferentes las cuales son un archivo csv y una página web. 

Objetivo: Por una parte, lo primero es obtener los datos que interesan de la página web haciendo scraping de esta, luego llevar los datos a un data lake para luego hacer las consultas que permitan generar una o más nuevas tablas de la información relevante.

## Herramientas
- AWS (S3, Glue, Athena, IAM)
- GoogleColab

## Lenguaje
- SQL
- Python

## Librerías
- Pandas
- BeautifulSoup
- Requests

## Técnicas Aplicadas
1. **Web scraping:** Obtener los datos de una tabla que existe en una página web.
2. **Servicios Cloud:** AWS S3 para guardar los datos, AWS Glue para crear crawlers que detecten el esquema de los datos y Athena para realizar consultas SQL.

## Siguientes pasos
Luego de estos pasos iniciales es posible transformar los datos y almacenarlos a través de pipelines con AWS Glue, con un job como el demostrado de ejemplo al final de la sección de Screenshots. También es posible llevar los datos a un servicio de visualización como AWS QuickSight.

## Screenshots

![image](https://drive.google.com/thumbnail?id=1j2BFouwQWpJ9KBa6FF0pQqKXXH6P64Yx&sz=s4000)


![image](https://drive.google.com/thumbnail?id=1lnF8SwnNI2IB6na-aIEF-RMLePiNFekw&sz=s4000)


![image](https://drive.google.com/thumbnail?id=1sOUmX19JSylbS83byKYRE7BLTTC5CC0C&sz=s4000)


![image](https://drive.google.com/thumbnail?id=1MLXrBiVmLOznctc042N7yFyaoqK3MiQI&sz=s4000)


![image](https://drive.google.com/thumbnail?id=1SdhoUsz33Cvmddsqj5egtz2lhYj3xiMn&sz=s4000)


![image](https://drive.google.com/thumbnail?id=1fO3V3soLIJfn5tFJ9YJvem3TKNhSz4eY&sz=s4000)


