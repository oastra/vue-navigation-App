# Vue Navigation App

A simple Vue.js project demonstrating the use of Vue Router and component-based architecture.

## Project Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (v12+ recommended)
- [npm](https://www.npmjs.com/) (v6+ recommended)

### Installation

1. **Clone the repository**

   ```sh
   git clone <repository_url>
   cd vue-navigation-app
   ```

2. **Install dependencies**

   ```sh
   npm install
   ```

### Running the Development Server

    ```sh
    npm run serve
    ```

Starts the application at `http://localhost:8080`.

### Building for Production

    ```sh
    npm run build
    ```

Outputs built files to the `dist` directory.

## Project Structure

    main.js: Entry point, sets up Vue instance and router.

    App.vue: Root component with navigation and router-view.

    router.js: Router configuration with routes and guards.

    components/: Vue components.

    - TheNavigation.vue
    - TeamsItem.vue
    - UserItem.vue

    pages/: Main application pages.

    - TeamsList.vue
    - UsersList.vue
    - TeamMembers.vue
    - NotFound.vue
    - TeamsFooter.vue
    - UsersFooter.vue

## Routing

Defined in router.js:

    /teams: List of teams.
    /teams/:teamId: Members of a specific team.
    /users: List of users.
    /:notFound(.*): 404 Not Found.

## Navigation Guards

Global and per-route guards for authentication and logging.

## Dependencies

    vue
    vue-router

## DevDependencies

    @vue/cli-plugin-babel
    @vue/cli-plugin-eslint
    @vue/cli-service
    @vue/compiler-sfc
    babel-eslint
    eslint
    eslint-plugin-vue

## License

Licensed under the MIT License.
# vue-navigation-App
