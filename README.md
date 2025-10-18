# Evaluacion2
# 🛰️ Proyecto de Geolocalización con GraphHopper

Este proyecto consiste en un script desarrollado en **Python** que utiliza la API de GraphHopper Directions para **calcular rutas entre dos puntos geográficos**.  
El objetivo es que el usuario pueda ingresar coordenadas de origen y destino para obtener la distancia total, el tiempo estimado de viaje y las instrucciones paso a paso en español.

El programa:  
- 📍 Calcula la **distancia total** en kilómetros.  
- ⏱️ Muestra el **tiempo estimado de viaje** en minutos.  
- 🧭 Entrega las **instrucciones paso a paso** de la ruta en español.  
- 🌐 Traduce todos los mensajes de interacción al español.  
- 🧮 Formatea valores numéricos con un máximo de **dos decimales**.  
- 🚪 Permite salir escribiendo `s` o `salir` en cualquier momento.  

Para ejecutar el script, el usuario debe tener una **API Key de GraphHopper** válida y conexión a internet.

---

## 🧰 Requisitos

- Python 3.8 o superior  
- Conexión a internet  
- API Key válida de GraphHopper  
- Editor recomendado: Visual Studio Code

---

## 📦 Instalación y Ejecución

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/proyecto-geolocalizacion.git
   cd proyecto-geolocalizacion

## Ejemplo de salida

Ingrese coordenadas de origen (lat,long) o 's' para salir: -33.4489,-70.6693
Ingrese coordenadas de destino (lat,long) o 's' para salir: -33.0341,-71.6296

🚘 Distancia total: 116.52 km
⏱️ Tiempo estimado: 84.35 min

🧭 Instrucciones:
1. Siga hacia el norte por Av. Libertador Bernardo O'Higgins.
2. Tome la salida hacia Ruta 68.
3. Continúe hasta Valparaíso.
4. Ha llegado a su destino.
