# Initial setup

Clone this repository. Run `yarn` to install all dependencies, then

```
yarn start
```

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

See its [`README`](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) for details.

# Environment setup

## Prettier

[Prettier](https://github.com/prettier/prettier) is installed as a pre-commit hook.
All staged code is formatted on commit according to the configuration defined in the `.prettierrc` file.

Install a prettier extension in your IDE to also format directly from there.

## ESLint

Install an eslint plugin in your IDE to visualize lint errors before they appear in console.

## Flow

[flow](https://flow.org/) is configured in the project. Add:

```
// @flow
```

at the beginning of all JS files to enable type checking.

Install a flow extension in your IDE and make sure to add types when requested.
Refrain from using `any` and do not commit code with flow errors.
