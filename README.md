# Daily News — Flutter Architecture Prototype

A Flutter news-application prototype focused on clean project structure, state management, routing, API integration, and local persistence.

> **Status:** work in progress. The repository currently contains the application architecture and supporting layers, while several UI pages are still placeholders. It should be treated as a development prototype rather than a finished production app.

## Engineering focus

- Flutter + Dart
- BLoC-based state management
- GoRouter navigation
- Dio + Retrofit API layer
- Hive / SharedPreferences local persistence
- Repository and use-case separation
- Dependency-injection setup
- Theme management
- Android and iOS project targets

## Current project structure

```text
lib/
├── blocs/
├── core/
├── models/
├── pages/
├── repositories/
├── services/
├── usecases/
├── utils/
├── widgets/
└── main.dart
```

## Main packages

`flutter_bloc` · `go_router` · `dio` · `retrofit` · `hive` · `shared_preferences` · `cached_network_image` · `connectivity_plus`

## Why this repository is public

This project documents an earlier stage of my Flutter architecture work. My current production-focused projects are linked from my [GitHub profile](https://github.com/Rahulrwt99).
