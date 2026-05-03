# Three — Writeup Summary

## Hands-on lab focused on AWS misconfigurations, enumeration and data exposure.

## Methodology
1. Enumeration (DNS, subdomains, cloud endpoints)
2. Service Analysis (web + AWS S3)
3. Exploitation (misconfigured S3 bucket)
4. Data Extraction

## Documentation
1. Key Findings
2. Se identificó un dominio que apuntaba a infraestructura en AWS
3. Enumeración reveló un bucket S3 público
4. El bucket permitía listar y descargar archivos sin autenticación
5. Se encontraron archivos sensibles (credenciales / config)
6. Uso de credenciales para acceso adicional y obtención de la flag

##Tools Used
1. Nmap
2. Gobuster / FFUF
3. AWS CLI
4. Browser

##Skills Practiced
1. Cloud Enumeration (AWS)
2. S3 Bucket Misconfiguration
3. OSINT básico sobre dominios
4. Análisis de exposición de datos
