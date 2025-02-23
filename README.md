# UI Kit Andrey Samaev Components

This template should help get you started developing with Vue 3 in Vite using ready made StoryBook components. Read the Documentation How to Use.
Check our GitHUb [https://github.com/Samaev/vue-storybook-npm]

## Customize configuration (beta version 0.0.2)

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm i @andreysamaev/ui-kit
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
# Quick Guide
Import components to use them in your template

```sh
import { Header } from "@andreysamaev/ui-kit";
import { Button } from "@andreysamaev/ui-kit";
```
And Use in the Template with props
```shell
<template>
  <Header :user="user" />
  <Button label="Button" primary size="large" />

</template>
```