
# ESLint, Prettier, and Husky in your React project

Setting up ESLint, Prettier, and Husky in your React project can greatly improve your development workflow and code quality.

ESLint: ESLint is a popular JavaScript linter that helps you catch and fix code errors, enforce coding conventions, and ensure consistent code style across your project. It analyzes your code for potential issues or violations of predefined rules and provides warnings or errors to help you identify and correct them. ESLint offers a wide range of configurable rules, and you can customize them based on your project's requirements or use popular preset configurations like Airbnb, Google, or Standard.

Prettier: Prettier is an opinionated code formatter that helps you maintain consistent code style and formatting in your project. It automatically analyzes your code and applies a set of rules to format it consistently, taking care of aspects like indentation, line length, semicolons, quotes, and more. Prettier simplifies the process of enforcing a unified code style across your team, reducing unnecessary debates over formatting choices.

Husky: Husky is a tool that allows you to easily incorporate Git hooks into your project. Git hooks are scripts that run automatically at certain points in the Git workflow, such as before committing or pushing code. With Husky, you can set up pre-commit and pre-push hooks to run tasks like running ESLint or Prettier on your code before it's committed or pushed. This ensures that your code meets the defined standards and avoids pushing potentially problematic code to your repository.


## Installation

Install my-project with npm

```bash
  npm install eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-react eslint-plugin-react-hooks --save-dev

  npm install prettier --save-dev
  
  npm i husky lint-staged --save-dev
  npm set-script prepare "husky install" && npm run prepare
  npx husky add .husky/pre-commit "npx lint-staged" 

  cd my-project
```
    
## Authors

- [@gideonekekeke](https://www.github.com/gideonekekeke)

