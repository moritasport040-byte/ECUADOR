# Ecuador Quiz Game - Juego Educativo

Un juego móvil educativo sobre historia y geografía del Ecuador diseñado para Android.

## 🎮 Características

✅ **Modo Provincia**: Selecciona una provincia del mapa  
✅ **24 Provincias**: Organizadas en Costa, Sierra, Amazonia y Galápagos  
✅ **5 Preguntas por Nivel**: Cada provincia tiene 5 preguntas  
✅ **Timer de 15 Segundos**: Límite por pregunta  
✅ **Sistema de Puntuación**: 20 puntos por respuesta correcta  
✅ **Interfaz Interactiva**: Mapa visual de provincias  

## 📋 Provincias

### COSTA (Naranja)
- Esmeraldas
- Manabí
- Santa Elena
- Guayas
- El Oro
- Los Ríos

### SIERRA (Morado)
- Carchi
- Imbabura
- Pichincha
- Cotopaxi
- Tungurahua
- Chimborazo
- Cañar
- Azuay
- Loja

### AMAZONIA (Verde)
- Sucumbíos
- Orellana
- Napo
- Pastaza
- Morona Santiago
- Zamora Chinchipe

### GALÁPAGOS (Azul)
- Galápagos

## 🚀 Instalación

### Requisitos
- Flutter SDK 3.0+
- Android SDK
- Dispositivo Android o emulador

### Pasos

1. Clonar repositorio
```bash
git clone https://github.com/moritasport040-byte/ECUADOR.git
cd ECUADOR
```

2. Instalar dependencias
```bash
flutter pub get
```

3. Ejecutar
```bash
flutter run
```

4. Generar APK
```bash
flutter build apk --release
```

## 📱 Cómo Jugar

1. Abre la aplicación
2. Selecciona "Modo Provincia"
3. Elige una región (Costa, Sierra, Amazonia, Galápagos)
4. Selecciona una provincia
5. Responde 5 preguntas en 15 segundos cada una
6. ¡Obtén tu puntuación!

## 📊 Sistema de Puntuación

- ✅ Respuesta correcta: +20 puntos
- ❌ Respuesta incorrecta: 0 puntos

## 📁 Estructura del Proyecto

```
lib/
├── main.dart
├── models/
│   ├── province.dart
│   ├── question.dart
│   └── player_progress.dart
├── screens/
│   ├── splash_screen.dart
│   ├── main_menu_screen.dart
│   ├── game_mode_selector.dart
│   └── map_selection_screen.dart
└── data/
    └── questions_database.dart
```

## 🔧 Tecnologías

- Flutter
- Dart
- Material Design 3

---

**¡Aprende sobre Ecuador de una forma divertida!** 🇪🇨
