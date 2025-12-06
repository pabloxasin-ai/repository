# repository
Educación
# Sistema Inteligente de Monitoreo del Proceso de Laminado (Node-RED)

## Descripción
Este proyecto implementa un sistema integral de monitoreo industrial con detección de fallas y análisis predictivo, construido en Node-RED.  
Simula sensores, analiza tendencias, genera alertas automáticas y presenta toda la información en un dashboard industrial.

---

## Tecnologías utilizadas
- **Node.js**  
- **Node-RED**  
- **Node-RED Dashboard**  
- **MQTT (diseñado para expansión futura)**  
- JavaScript (nodos Function)

---

## Funcionalidades
- Simulación de sensores en tiempo real  
- Detección automática y manual de fallas  
- Histórico de fallas (últimos 10 eventos)  
- Dashboard profesional estilo industrial  
- Alarma sonora y por voz  
- Análisis predictivo basado en tendencias  
- Estado global del sistema  

---

## Modelo Predictivo
Calcula riesgo usando:
- Pendiente (tendencia)  
- Umbrales dinámicos  
- Repetición de fallas recientes  

Clasificación:
- Riesgo Bajo  
- Riesgo Medio  
- Riesgo Alto  

---

## Estructura del Proyecto
- `proyecto.json` → Flow completo de Node-RED  
- `Manual Tecnico.pdf`  
- `Manual de Usuario.pdf`  
- `Presentación.pdf`  
- `Mapa Mental.pdf`

---

## Instalación y ejecución 
1. Instalar Node.js  
2. Instalar Node-RED  
3. Ejecutar:
Ingresar al CMD y escribir node-red (esperar que no haya errores)
En el navegador ingresar a http://127.0.0.1:1880/ (ingresamos al interfaz de programación de node-red por bloques), importar proyecto.json en el editor
Para la visualización del DashBoard ingresamos a la siguiente dirección http://127.0.0.1:1880/ui

----

## Autores
Ingeniero en Sistemas Pablo Sinchiguano
Ingeniero Electrónico Henry Toapanta
