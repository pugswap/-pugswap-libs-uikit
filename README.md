# 🥞 Pug UIkit

**This repository is not used anymore. See the [https://github.com/pugswap/pug-toolkit](Pug toolkit) instead**

[![Version](https://img.shields.io/npm/v/@pugswap-libs/uikit)](https://www.npmjs.com/package/@pugswap-libs/uikit) [![Size](https://img.shields.io/bundlephobia/min/@pugswap-libs/uikit)](https://www.npmjs.com/package/@pugswap-libs/uikit)

Pug UIkit is a set of React components and hooks used to build pages on Pug's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @pugswap-libs/uikit`

## Setup

### Theme

Before using Pug UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@pugswap-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@pugswap-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pugswap.github.io/pug-uikit/)
