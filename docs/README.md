# nd

## Introduction

Neodymium stack is targeted towards single page applications with [state management](http://vuex.vuejs.org/en/intro.html) and support for [Electron](http://electron.atom.io/).

You can read the [tutorial for first-time users](TutoNeodymium.md) to get started.

In order to fully enjoy working with the nd stack, you **need** to have read these docs ~~entirely~~ 🤓, preferably in that order:

- [ES2015 syntax](https://babeljs.io/docs/learn-es2015/)
- [vue](http://vuejs.org/guide/)
- [vue-router](router.vuejs.org/en/index.html)
- [vuex](http://vuex.vuejs.org/en/index.html)
- [electron](http://electron.atom.io/)
- [standard style](https://github.com/feross/standard)
- [successfull git branching model](http://nvie.com/posts/a-successful-git-branching-model/)

You will also need to have:

- [ESLint](http://eslint.org/) installed.

If you just want to whip out a quick prototype, use the [webpack-simple](https://github.com/vuejs-templates/webpack-simple) template instead.

## Quickstart

To use this template, scaffold a project with [vue-cli](https://github.com/vuejs/vue-cli). **It is recommended to use npm 3+ for a more efficient dependency tree.**

``` bash
$ npm install -g vue-cli
$ vue init soixantecircuits/nd my-project
$ cd my-project
$ npm install
$ npm run dev

# if you picked Electron support,
# in another terminal window
$ npm run electron
```

<p style="opacity: 0;">P.S: the `:wq` on the template README: it's on purpose* 🙃</p>
