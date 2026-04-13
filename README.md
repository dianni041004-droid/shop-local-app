# ShopLocal App

Aplicación móvil multiplataforma desarrollada con Ionic, Angular y Capacitor que permite a los usuarios encontrar negocios locales cercanos utilizando geolocalización, mapas interactivos y consumo de APIs.

---

# Descripción del Proyecto

ShopLocal App es una aplicación diseñada para facilitar la búsqueda de negocios cercanos en tiempo real. Permite visualizar comercios en un mapa, filtrarlos por categorías, guardar favoritos y agregar reseñas.

La aplicación integra funcionalidades modernas como:

- Geolocalización en tiempo real
- Mapas interactivos
- Almacenamiento local
- Multimedia (cámara, audio, QR)
- Consumo de servicios web (OpenStreetMap)

---

# Tecnologías Utilizadas

- Ionic Framework
- Angular
- Capacitor
- Leaflet
- OpenStreetMap (Overpass API)
- Ionic Storage
- TypeScript

---

# Estructura del Proyecto


shop-local-app/
├── src/
│ ├── app/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── tabs/
│ │ └── app.routes.ts
│ ├── assets/
│ ├── theme/
│ └── global.scss
├── android/
├── www/
├── capacitor.config.ts
├── ionic.config.json
└── package.json


---

# Instalación y Ejecución

## 1. Clonar el repositorio


git clone https://github.com/dianni041004-droid/shop-local-app.git

cd shop-local-app


---

## 2. Instalar dependencias


npm install


---

## 3. Ejecutar en navegador


ionic serve


---

## 4. Ejecutar en Android


ionic build
npx cap sync android
npx cap open android


---

# APK

El archivo APK se encuentra en la carpeta:


android/app/build/outputs/apk/debug/


---

# Funcionalidades Principales

- Búsqueda de negocios en tiempo real  
- Mapa interactivo con geolocalización  
- Sistema de favoritos  
- Reseñas con calificación  
- Reseñas de voz  
- Uso de cámara y galería  
- Login y registro de usuario  
- Perfil personalizable  

---

# Permisos de la Aplicación

- Ubicación
- Cámara
- Micrófono
- Almacenamiento

---

# API Utilizada

OpenStreetMap (Overpass API)  
Permite obtener datos reales de negocios cercanos mediante coordenadas geográficas.

---

# Autor

Dianni Paredes  
Desarrollador principal del proyecto

---

# Enlaces

Repositorio:  
https://github.com/dianni041004-droid/shop-local-app  

APK:  
https://drive.google.com/file/d/1Dy2T9Jnh3V5mahDIqmthJuU0WgQnYaTf/view?usp=drive_link

Video demostrativo:  
https://drive.google.com/file/d/1PkGKsWsGm_OBJ4UIz6UqbsP8Yt3tsO8b/view?usp=sharing

---

# Licencia

Este proyecto fue desarrollado con fines académicos para la asignatura Programación de Dispositivos Móviles (UAPA).

---

# Estado del Proyecto

Aplicación funcional  
APK generado  
Integración de APIs  
Geolocalización activa  
Documentación completa  

---

# Conclusión

ShopLocal App representa una solución completa para la búsqueda de negocios locales, integrando tecnologías modernas y cumpliendo con todos los requerimientos del proyecto final.

---
