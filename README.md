# cra-template-please

My personal template for [Create React App](https://github.com/facebook/create-react-app).

Read about the features of this template [here](./guide.md).

Useful for creating:

✔ React web apps
✔ Non-React web apps
✔ Web-based experiments
✔ Test grounds for new libraries

## Usage

> This assumes I have already [configured my computer](#configuring-your-computer).

To scaffold an app, use:

```
cra {name_of_app}
```

To create an app in the current directory, use:

```
cra .
```

### New App Checklist

When building an application, there are a couple of things I need to do after installing the template.

- [ ] Search for the string `~~TEMPLATE~~` and change those values.
- [ ] Add a favicon. I typically use [this app](https://realfavicongenerator.net).

## Configuring My Computer

Create an alias for `cra`:

```
alias cra="npx create-react-app --template cra-template-please"
```

## Developing

I can test changes to this template without publishing using this command:

```
npx create-react-app my-app --template file:./cra-template-please
```

## Learn More

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.

### Notes

- Everything is a `dependency` in `template.json` because Create React App templates do not support
  `devDependencies` as of July 2020.
