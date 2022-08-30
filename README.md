# angularjs-webpack-boilerplate
#### Overview
The goal of this project is to provide boilerplate code that would be useful for creating a new web application with AngularJS (1.8) and webpack (5.71.0). Examples are provided to illustrate best practices for structuring a component-based workflow. 

Features include:
- ES6 support with Babel
- Separate webpack builds for development/production (with linting, minification, and source maps)
- Themeable styling with Sass; includes icon font (`foundation-icons`)

#### Instructions

- Start a new project without the repository's commit history:
`git clone --depth=1 https://github.com/j3k2/angularjs-webpack-boilerplate.git <your-project-name>`
- `npm install` to install dependencies
- `npm run start` to start app on development server (localhost:8080)
- `npm run build` to generate production build in public/ directory.