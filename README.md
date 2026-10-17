# Cliner AI

Cliner AI is a cross-platform AI coding assistant for Android and Windows. This repository is being initialized as a monorepo with shared TypeScript libraries, Android app scaffolding, desktop app scaffolding, and CI workflows.

## Current status

This repository was empty when access was verified. The initial scaffold is being created in the default branch before creating the working branch for Milestone 1.

## Repository structure

- `apps/android` – Android app scaffold (Kotlin + Jetpack Compose)
- `apps/desktop` – Windows desktop scaffold (Tauri 2 + React + TypeScript + Rust)
- `libs/shared` – shared TypeScript packages for models, providers, and tools
- `.github/workflows` – CI configuration for Android and Windows
- `docs` – architecture and implementation notes

## Development goals

- Real AI provider integration
- Local model management
- Safe project editing and execution
- Git and GitHub workflows
- Android debug APK and Windows installer CI

## Notes

This repository is intentionally scaffolded as a foundation for incremental implementation. It does not claim production feature completeness yet.
