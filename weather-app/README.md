# Plan so far:
- desktop app
- stack: React (frontend) + Typescript, Tauri (framework for building tiny desktop applications) which uses Rust for the backend. *Tauri essentially packages your web-based UI into a native desktop application.
- open-meteo Weather API
- run app: `npm run tauri dev` inside weather-app/

# Tauri set up
- Project name: weather-app
- Identifier: com.aliciakee.weatherapp
- Frontend language: TypeScript / JavaScript
- Package manager: npm
- UI template: React
- UI flavor: TypeScript
- src-tauri/: This is the Tauri/native desktop portion.  The Rust code is what allows your React application to become a desktop application.
- Cargo.toml: Rust equivalent of a dependency/build configuration file

# Tauri + React + Typescript

This template should help get you started developing with Tauri, React and Typescript in Vite.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
