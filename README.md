# Dashboard_IoT
Desarrollar un dashboard web interactivo para el monitoreo ambiental que integre datos de sensores IoT y APIs públicas, proporcionando visualización geoespacial y análisis de calidad del aire en tiempo real.
<img width="833" height="658" alt="image" src="https://github.com/user-attachments/assets/bc14d16c-ebba-42d9-a3d6-a1b0105ed31f" />



# 🌐 Diseño de una Interfaz Web Accesible para Gestión de Dispositivos IoT

## 📖 Descripción

Este proyecto consiste en el desarrollo de una **interfaz web accesible, responsiva e intuitiva** para la gestión y monitoreo de dispositivos del Internet de las Cosas (IoT). La aplicación proporciona una visualización centralizada del estado de los dispositivos mediante un panel de control (Dashboard), facilitando el monitoreo de variables ambientales y la administración de sensores distribuidos geográficamente.

La interfaz fue diseñada siguiendo principios de **accesibilidad web (WCAG)** y experiencia de usuario (UX), permitiendo que cualquier usuario pueda interactuar de forma sencilla con la plataforma.

---

## 🎯 Objetivos

- Diseñar una interfaz web moderna para la gestión de dispositivos IoT.
- Implementar un dashboard con información en tiempo real.
- Visualizar dispositivos mediante mapas interactivos.
- Facilitar la consulta del estado de sensores ambientales.
- Garantizar una experiencia accesible y adaptable a diferentes dispositivos.

---

# ✨ Características

- 📊 Dashboard con indicadores principales (KPIs).
- 🌍 Integración con OpenStreetMap mediante Leaflet.
- 📍 Visualización geográfica de estaciones IoT.
- 📋 Tabla de dispositivos con búsqueda dinámica.
- 📈 Panel de información detallada por estación.
- 🌡️ Monitoreo de temperatura, humedad, calidad del aire y partículas contaminantes.
- 🚨 Sistema de alertas para estaciones con niveles críticos.
- 📱 Diseño completamente Responsive.
- ♿ Accesibilidad mediante navegación por teclado, Skip Links y elementos semánticos.

---

# 🛠 Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura del sitio |
| CSS3 | Diseño y estilos |
| JavaScript | Lógica e interacción |
| Leaflet.js | Mapas interactivos |
| OpenStreetMap | Cartografía |
| Google Fonts | Tipografía |
| SVG | Iconografía |

---

# 📂 Estructura del proyecto

```text
📦 Proyecto-IoT
│
├── index.html          # Página principal
├── styles.css          # Hoja de estilos
├── README.md           # Documentación
│
└── assets/
    ├── imágenes/
    ├── iconos/
    └── capturas/
```

---

# 🖥 Funcionalidades principales

## Dashboard

Muestra indicadores generales del sistema:

- Número total de dispositivos
- Calidad promedio del aire
- Alertas activas

---

## Mapa Interactivo

Permite visualizar todas las estaciones IoT utilizando **OpenStreetMap**.

Características:

- Selección de estaciones
- Marcadores personalizados
- Identificación por colores
- Visualización de alertas

---

## Tabla de dispositivos

Presenta información organizada sobre cada dispositivo IoT.

Incluye:

- ID del dispositivo
- Ubicación
- Tipo de sensor
- Última transmisión
- Estado del dispositivo

Además incorpora un filtro de búsqueda dinámico.

---

## Panel de detalle

Al seleccionar una estación se muestran:

- Información general
- Estado del dispositivo
- Sensores instalados
- Temperatura
- Humedad
- Calidad del aire
- PM2.5
- PM10
- Gráficas históricas
- Alertas ambientales

---

# ♿ Accesibilidad

La interfaz incorpora diversas buenas prácticas de accesibilidad:

- Navegación mediante teclado.
- Skip Links.
- Etiquetas ARIA.
- Alto contraste.
- Indicadores visibles de enfoque.
- Diseño adaptable (Responsive Design).
- Uso de HTML semántico.

---

# 📱 Diseño Responsive

La aplicación se adapta automáticamente a:

- 💻 Computadoras
- 💼 Laptops
- 📱 Tablets
- 📲 Teléfonos móviles

---

# 🚀 Instalación

1. Clonar el repositorio

```bash
git clone https://github.com/usuario/proyecto-iot.git
```

2. Ingresar al directorio

```bash
cd proyecto-iot
```

3. Abrir el archivo principal

```text
index.html
```

No se requiere instalar dependencias adicionales.

---

# 📸 Capturas

IMAGENES DEL DASHBOARD FUNCIONANDO:



DATOS TEMPERATURA QUITO-ECUADOR 
<img width="842" height="551" alt="image" src="https://github.com/user-attachments/assets/b25388e2-35f8-4564-b14b-9b8b032190aa" />
DATOS TEMPERATURA BOGOTÁ-COLOMBIA
<img width="842" height="503" alt="image" src="https://github.com/user-attachments/assets/5fd4f79b-c8fb-40e5-bf48-a1d95435b1d0" />
DATOS TEMPERATURA LIMA-PERÚ
<img width="886" height="486" alt="image" src="https://github.com/user-attachments/assets/0325fc4c-9c59-408c-99fe-6d55612e56d8" />



---

# 🔮 Mejoras futuras

- Integración con bases de datos.
- Conexión con dispositivos IoT reales.
- Autenticación de usuarios.
- Panel administrativo.
- Reportes descargables.
- Notificaciones en tiempo real.
- Modo oscuro.
- Integración con MQTT.
- API REST.

---

# 👨‍💻 Autores

Desarrolado por Jorge Plaza Pisanan
8 vo TELEMÁTICA .

---

# 📄 Licencia

Este proyecto se distribuye bajo la licencia de la Universidad Tecnica Estatal de Quevedo.

```
License

Copyright (c)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

---

# ⭐ Vista general del proyecto

La plataforma permite monitorear una red de dispositivos IoT desde una única interfaz web, integrando mapas interactivos, indicadores clave, tablas dinámicas y paneles de información detallada para facilitar la supervisión de sensores ambientales de forma eficiente, accesible y responsiva.
