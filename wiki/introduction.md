# Introduction

- [About the project](#about-the-project)
- [Development culture](#development-culture)
- [Techincal stack](#techincal-stack)
- [Getting started](#getting-started)
- [Development flow](#development-flow)

## About the project

We have huge plans and roadmap. Regarding the project vision and goals, read this section please - [Aboout Project](/wiki/about-project.md).

## Techincal stack

There are some major libs we use:

### [Typescript](https://www.typescriptlang.org/)

Type errors are found within compile time - it's beautiful.

### [React](https://reactjs.org/)

We are also using [react hooks](https://reactjs.org/docs/hooks-reference.html). All the components are functional components (except the ones that should be inherited from lib's class components, like nextjs root "App" component).

### [Next](https://nextjs.org/)

It's ok if you have no experience with it. Just read some docs about it. Two main things you need to know:

- There are no "routes" - the routes are generated by Next, depending on ["pages"](https://github.com/prometheonsystems/bedrock-client2/tree/master/src/pages) folder structure (but dynamic routes are also doable - read [this](https://nextjs.org/learn/basics/create-dynamic-pages) and [that](https://nextjs.org/learn/basics/clean-urls-with-route-masking)). We call such a special component a "Page Component".

- Page components have `getInitialProps` which is used to make requests, to get initial data ([See docs](https://nextjs.org/learn/basics/fetching-data-for-pages))

### [Electron](https://electronjs.org/)

That's it, Electron. It's a desktop app. However, it's working in web too.

### [react-request-hook](https://github.com/schettino/react-request-hook)

I've mentioned we are using react hooks. Basic hooks come with React. But this custom one lets you make requests in a beautiful way. It also has a great typescript integration, see the hints:

<p align="center">
  <img src="https://raw.githubusercontent.com/schettino/react-request-hook/master/other/type-hint.png" width="599">
</p>

## Development culture

### Linters

We are using bunch of linters to remain the code clean and unified. That's a reason why Visual Studio Code is recommended - they will work out of the box for you. You can see all the errors while developing with no setup. For other IDEs you should make sure they are working, by yourself. If you won't setup - it will be inconvenient for you to develop, but the dirty code will not get to the repository anyway - because of the checks on github.

### Project TODOs

There a lot of places in the code under the question. Leave TODOs and make sure you've read the [Project TODOs](/wiki/todos.md) doc.

## Getting started

Once you've read the [README.md](/README.md) and this introduction, and your electron app is booted up, use these testing credentials on login page:

```txt
admin@bedrock.ai
bedrock
```

This is accessing a remote server with testing data.

Also, since you're reading this introduction, you are new to the project. Please, look into [<kbd>good-first-issue</kbd>`s](https://github.com/prometheonsystems/bedrock-client2/labels/good-first-issue), and take one of them as your first issue. This is one-time procedure. After this one you shouldn't get <kbd>good-first-issue</kbd>s.

## Development flow

> If you need any help, you can contact me, Jerry Green - [https://t.me/jerrygreen](https://t.me/jerrygreen) in Telegram.

### 1. Solve (close) issues

And if you have questions related to an issue - please, formulate your concerns in the issue, so we can keep track of it.

Once you've done with your first issue, don't touch <kbd>good-first-issue</kbd> anymore - left it for others. Since that, use "[Project issues](https://github.com/prometheonsystems/bedrock-client2/projects/1?fullscreen=true)" - you can assing any issue you want from the "To do" list.

### 2. File (create) new issues, create PRs

If you find some bugs or places in code to improve - please, don't hesitate, [file new issues](https://github.com/prometheonsystems/bedrock-client2/issues/new).

For further reading of the development flow, please, read [CONTRIBUTING.md](/.github/CONTRIBUTING.md).

We want to have OpenSource-like development flow, so all of these is very important.