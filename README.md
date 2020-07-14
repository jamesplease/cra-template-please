# cra-template-please

My template for [Create React App](https://github.com/facebook/create-react-app).

## Usage

Add the option `--template cra-template-please` when creating a new CRA app.

```
npx create-react-app --template cra-template-please my-app
```

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.

### Checklist

There are a couple of things to do after installing the template.

- [ ] Search for the string `~~TEMPLATE~~` and change those values.
- [ ] Add a favicon. I typically use [this app](https://realfavicongenerator.net).

## Developing

You can test changes to this template without publishing using this command:

```
npx create-react-app my-app --template file:./cra-template-please
```

## Notes

- Everything is a `dependency` in `template.json` because Create React App templates do not support
  `devDependencies` as of July 2020.
