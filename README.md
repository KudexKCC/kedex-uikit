# 💻 Kudex UIkit

[![Version](https://img.shields.io/npm/v/@kudexkcc/kudex-uikit)](https://www.npmjs.com/package/@kudexkcc/kudex-uikit) [![Size](https://img.shields.io/bundlephobia/min/@kudexkcc/kudex-uikit)](https://www.npmjs.com/package/@kudexkcc/kudex-uikit)

Kudex UIkit is a set of React components and hooks used to build pages on Kudex's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @kudexkcc/kudex-uikit`

## Setup

### Theme

Before using Kudex UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@kudexkcc/kudex-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@kudexkcc/kudex-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
