# AcadeMia Frontend

This is the frontend application for AcadeMia, a comprehensive web application for managing educational academies. Built with Vue.js 3 and Vite, it provides a user-friendly interface for administrators to manage users, instructors, groups, student enrollments, scheduling, and payment processing.

## Features

- **User Interface**: Modern, responsive UI using Vuetify and Bootstrap components.
- **Authentication**: Secure login and route protection with JWT tokens.
- **Module Management**: Navigate through different modules like users, instructors, groups, agenda, and payments.
- **Calendar Integration**: Interactive calendar for scheduling classes and events using FullCalendar.
- **Payment Integration**: Interface for processing payments via MercadoPago, including success/failure handling and manual payments.
- **CRUD Operations**: Create, read, update, and delete functionality for users, instructors, and groups.

## Technologies Used

- **Vue.js 3**: Progressive JavaScript framework for building user interfaces.
- **Vite**: Fast build tool and development server.
- **Vuetify**: Material Design component framework for Vue.
- **Bootstrap**: CSS framework for responsive design.
- **FullCalendar**: JavaScript calendar library for scheduling.
- **Axios**: HTTP client for API requests.
- **Vue Router**: Official router for Vue.js for single-page application navigation.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

### Format Code

```sh
npm run format
```
