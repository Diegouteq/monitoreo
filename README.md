# Monitoreo de Sensores IoT

Aplicación web para monitorear datos de sensores en tiempo real usando React, Vite y Firebase.

## 🚀 Características

- Dashboard en tiempo real con datos de sensores
- Visualización de ubicaciones de sensores
- Conexión a Firebase Realtime Database
- Interfaz responsive con componentes reutilizables
- Hot Module Reloading (HMR) en desarrollo

## 📋 Requisitos previos

- Node.js 16 o superior
- npm o yarn

## ⚙️ Instalación

1. Clonar el repositorio
```bash
git clone <url-repositorio>
cd monitoreo
```

2. Instalar dependencias
```bash
npm install
```

3. Configurar variables de entorno (.env)
```
VITE_FIREBASE_API_KEY=...
VITE_FIREBASE_AUTH_DOMAIN=...
VITE_FIREBASE_DATABASE_URL=...
VITE_FIREBASE_PROJECT_ID=...
VITE_FIREBASE_STORAGE_BUCKET=...
VITE_FIREBASE_MESSAGING_SENDER_ID=...
VITE_FIREBASE_APP_ID=...
```

## 🏃 Uso

**Desarrollo:**
```bash
npm run dev
```

**Build para producción:**
```bash
npm run build
```

**Preview de build:**
```bash
npm run preview
```

## 📁 Estructura del Proyecto

- `src/components/` - Componentes React reutilizables
- `src/pages/` - Páginas principales (Dashboard, Ubicaciones)
- `src/hooks/` - Hooks personalizados (useSensorData)
- `src/services/` - Servicios (Firebase)
- `public/` - Archivos estáticos

## 🛠️ Tecnologías

- React 18
- Vite
- Firebase Realtime Database
- CSS3
