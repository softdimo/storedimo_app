# 📱 storedimo_app

Aplicación móvil del proyecto de storedimo

## 🚀 Instalación

### 1️⃣ Clonar el repositorio
```sh
git clone git@github.com:softdimo/storedimo_app.git
git clone https://github.com/softdimo/storedimo_app.git
cd storedimo_app
```

### 2️⃣ Instalar Flutter (si no lo tienes)
Asegúrate de tener Flutter instalado. Puedes verificarlo con:
```sh
flutter --version
```
Si no lo tienes, sigue la guía de instalación oficial: [Flutter Docs](https://docs.flutter.dev/get-started/install)

### 3️⃣ Instalar las dependencias
```sh
flutter pub get
```

### 4️⃣ Ejecutar la aplicación
#### En un emulador o dispositivo físico:
```sh
flutter run
```

#### Si usas un dispositivo iOS, corre antes:
```sh
cd ios
pod install
cd ..
```

### 5️⃣ Compilación para producción (Opcional)
Para generar el APK:
```sh
flutter build apk
```
Para compilar en iOS:
```sh
flutter build ios
```

## 🛠 Dependencias utilizadas
- `http`: Para hacer peticiones HTTP.
- `provider`: Para la gestión de estado.
- `shared_preferences`: Para almacenamiento local.

