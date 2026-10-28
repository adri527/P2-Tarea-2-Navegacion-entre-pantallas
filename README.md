# PGL-P2-MyPortfolio

Portfolio personal en Flutter para la asignatura de Programación Multimedia y Dispositivos Móviles (2º DAM).
Segunda práctica: **navegación mediante Drawer con `go_router`**.

## Funcionalidades

- Navegación con `go_router` (rutas definidas en `lib/router/app_router.dart`).
- `Drawer` común a todas las pantallas, con la opción actual resaltada.
- **Pantalla de bienvenida** (`/`).
- **Pantalla de portfolio** (`/portfolio`): presentación y hobbies.
- Colores del nuevo diseño centralizados en `lib/constants/app_colors.dart`.

## Estructura

```
lib/
├── main.dart
├── constants/
│   ├── app_colors.dart
│   ├── app_routes.dart
│   └── portfolio_data.dart
├── router/
│   └── app_router.dart
├── screens/
│   ├── welcome_screen.dart
│   └── portfolio_screen.dart
└── widgets/
    ├── app_drawer.dart
    ├── hobby_chip.dart
    └── initials_avatar.dart
```

## Ejecución

```
flutter pub get
flutter run -d chrome
```

## Capturas de pantalla

| Bienvenida | Drawer | Portfolio |
|---|---|---|
| ![Bienvenida](docs/screenshots/bienvenida.png) | ![Drawer](docs/screenshots/drawer.png) | ![Portfolio](docs/screenshots/portfolio.png) |

## Autor

Adrián Jacob Ramos Reverón
