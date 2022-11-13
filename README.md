# Comandos para usar Ionic

---

## Para instalar

---

```sh
npm install -g @ionic/cli
```

## Comandos Ionic

---

### Iniciar proyecto

```sh
ionic start nombreProyecto blank
```

### Crear una pantalla

```sh
ionic g page pages/nombrePantalla
```

### Crear un servicio

```sh
ionic g service services/nombreServicio
```

## Para instalar SQLite

---

```sh
npm install cordova-sqlite-storage
npm install @ionic-native/core
npm install @ionic-native/sqlite
ionic cap sync
```

## Para instalar cámara y scanner

---

```sh
npm install @ionic-native/core
npm install @capacitor/camera
npm install @capacitor-community/barcode-scanner
npm install @capacitor/android
npx cap add android
```

## Para correr aplicación

---

### En navegador

```sh
ionic serve
```

### En móvil o emulador

```sh
ionic cap run android --livereload --external
```

### Abrir proyecto en Android Studio

```sh
ionic cap open android
```
