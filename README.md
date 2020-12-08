# Overreacted clone
⚡️ Let's clone one of the most inspiring blogs about front-end development ⚡️

Dan Abramov is co-creator of Redux and an active member of React core team. I can't think a better tribute to his open source contribution career that a clone of his personal blog, but with Vue.js 😜

[Check it out!](https://overreacted.io/) 🤓


## The goal

We benefit everyday from the ODS design system, a powerful but limited ecosystem where we feel comfy. There are other tools out there we don't use, and we can't adopt them as fast as we like. We are a large team of developers and we should make smart and safe moves.

That's why I propose this small exercise, trying to keep ourselves a little bit more up to date.


## The job

* Use Vue.js through it's most used and loved SSR framework, [Nuxt](https://nuxtjs.org/docs/2.x/get-started/installation) 😻
* For the API, we'll use [@nuxt/content module](https://content.nuxtjs.org/). You can choose which file format to use, but the exercise will provide Markdown files.
* Use [Typescript](https://typescript.nuxtjs.org/) to type methods, computed properties, and try at leat to implement one interface, probably the post model will fit okay 👀
* Use Tailwind, and try to write the less CSS you can. Why? I don't know, it should be fun to dive in Tailwind docs, it's a really well done API for a CSS library. We can use [this handy module for Nuxt](https://tailwindcss.nuxtjs.org/).
* Of course, install Eslint and Prettier, and make these two [coexist together properly](https://github.com/prettier/eslint-config-prettier) 💀
* [StyleLint](https://stylelint.io/) and [CommitLint](https://github.com/conventional-changelog/commitlint) are good optional choices to keep the house clean adn tidy
* Try to replicate the light/dark mode, it's fun.
* If you feel strong enough, please add some unit testing

> Disclaimer => Most of this configs, if not all, are selectable from the Nuxt create app CLI, do not panic. But probably you`ll need to tweak the settings along you code the app. Fun!

## Where to start?
If you need to follow some first steps to get started, here we go:

* Create a Nuxt app: yarn create nuxt-app <project-name>
* Make choices based on app specs
* Our deployment target will be Static
* Create a `content` directory for our posts
* Fetch your first data using `asyncData` from the homepage

> Skip all those functionalities you do not want to replicate, ie: code highlighting, subscribing form, etc...
