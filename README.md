# Network Monitor

Este script Python proporciona una herramienta de monitoreo de conexiones de red en tiempo real en tu sistema. Utiliza la biblioteca `psutil` para acceder a información detallada sobre los procesos y sus conexiones, identificando y mostrando conexiones establecidas a través de Internet, excluyendo conexiones locales.

## Características

- Identificación de conexiones establecidas por procesos.
- Detalles detallados del proceso, incluyendo nombre, PID y estado.
- Consultas de geolocalización para direcciones IP remotas utilizando la base de datos no comercial de IP2GeoTools.

## Uso

1. Clona este repositorio en tu máquina.
2. Ejecuta el script `network_monitor.py`.
3. Observa detalles sobre las conexiones establecidas y la geolocalización de las direcciones IP remotas.

Este script es una herramienta útil para aquellos interesados en monitorear las conexiones de red activas en su sistema y obtener información geográfica asociada a las direcciones IP remotas.

## Requisitos

Asegúrate de tener Python instalado en tu sistema.

```bash
pip install psutil
pip install ip2geotools
