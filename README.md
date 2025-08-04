# QHSE

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:


For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# QHSE App

![QHSE Logo](assets/logoqhse.png)

Flutter · Android · iOS · Web · Firebase

QHSE App es una aplicación multiplataforma para la gestión de eventos, riesgos y comunicación en entornos laborales, desarrollada con Flutter y Firebase.

## 📱 Descripción

La app permite:
- Registrar y visualizar eventos e incidentes.
- Gestionar riesgos y acciones preventivas.
- Acceder a reportes y tablas interactivas.
- Autenticación de usuarios y gestión de sesiones.
- Interfaz adaptativa para móvil y web.

## 🏗️ Estructura del Proyecto

```
qhse-main/
├── android/               # Código nativo y configuración Android
│   ├── app/               # Módulo principal de la app
│   └── ...
├── ios/                   # Código nativo y configuración iOS
├── lib/                   # Código fuente Flutter
│   ├── screens/           # Pantallas principales
│   ├── widgets/           # Componentes reutilizables
│   └── ...
├── assets/                # Imágenes y recursos
├── fonts/                 # Tipografías
├── test/                  # Pruebas unitarias y de widgets
├── web/                   # Configuración para web
└── README.md              # Documentación del proyecto
```

## ⚙️ Subir el código a GitHub

1. Inicializa el repositorio:
   ```powershell
      git init
      git add .
      git commit -m "Subir QHSE App"
      git remote add origin https://github.com/tuusuario/qhse-main.git
      git push -u origin master
```
   (Reemplaza `tuusuario` y el nombre del repo por los tuyos.)

## 📦 Cómo generar y subir la APK

1. Genera la APK:
   ```powershell
flutter build apk --release
```
   El archivo generado estará en:
   `build/app/outputs/flutter-apk/app-release.apk`

2. Sube la APK a GitHub:
   - Ve a tu repositorio en GitHub.
   - Haz clic en "Releases" > "Draft a new release".
   - Ponle un nombre (ejemplo: `v1.0.0`), una descripción y adjunta el archivo `app-release.apk`.
   - Publica la release.

## ⚠️ Nota

Subir solo la carpeta `android` NO incluye el código fuente de la app Flutter (`lib/`).
No se puede compilar ni ejecutar la app completa solo con la carpeta `android`.

---
QHSE App – Julia Herrera
