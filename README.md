# Nuxt VS Code Snippets

![GitHub](https://img.shields.io/github/license/zhaolinlau/nuxt-vscode-snippets)
![Nuxt Version](https://img.shields.io/badge/Nuxt-3-00DC82?logo=nuxt)
![Vue Version](https://img.shields.io/badge/Vue-3-42B883?logo=vuedotjs)

## Description

Boost your Nuxt development with useful snippets that speed up your workflow. This extension includes snippets for Nuxt 3, Vue 3, and Pinia, making it easier and faster to write common code.

> I took my inspiration from the [vue-vscode-snippets](https://github.com/sdras/vue-vscode-snippets) extension by @sdras, the [vue3-vscode-snippets](https://github.com/ExEr7um/vue3-vscode-snippets) extension by @ExEr7um, and the [Vue-3-Code-Snippets](https://github.com/okriiza/Vue-3-Code-Snippets) extension by @okriiza.

## Features

- Nuxt 3 snippets
- Vue 3 snippets
- Pinia snippets
- Composition API snippets
- Support for JavaScript and TypeScript

## Requirements

- Visual Studio Code 1.75 or higher

## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Nuxt VS Code Snippets` by **zhaolinlau**.
3. Click **Install** to install it.

## Usage

Type part of a snippet, press `enter`, and the snippet unfolds.

## Snippets

### Support File `.vue`

- Nuxt

| Prefix        | Purpose                     |
| ------------- | --------------------------- |
| `nlink`       | Nuxt router link            |
| `nlink-param` | Nuxt router link with param |

- Vue

| Prefix           | Purpose                                                               |
| ---------------- | --------------------------------------------------------------------- |
| `vstart`         | start for Vue 3 File with `<script setup>` No style                   |
| `vstart-scss`    | start for Vue 3 File with `<script setup>` Style `SCSS`               |
| `vstart-sass`    | start for Vue 3 File with `<script setup>` Style `SASS`               |
| `vstart-less`    | start for Vue 3 File with `<script setup>` Style `LESS`               |
| `vstart-pcss`    | start for Vue 3 File with `<script setup>` Style `PostCSS`            |
| `vstart-css`     | start for Vue 3 File with `<script setup>` Style `CSS`                |
| `vstart-ts`      | start for Vue 3 File with `<script setup lang='ts'>`, No Style        |
| `vstart-ts-scss` | start for Vue 3 File with `<script setup lang='ts'>`, Style `SCSS`    |
| `vstart-ts-sass` | start for Vue 3 File with `<script setup lang='ts'>`, Style `SASS`    |
| `vstart-ts-less` | start for Vue 3 File with `<script setup lang='ts'>`, Style `LESS`    |
| `vstart-ts-pcss` | start for Vue 3 File with `<script setup lang='ts'>`, Style `PostCSS` |
| `vstart-ts-css`  | start for Vue 3 File with `<script setup lang='ts'>`, Style `CSS`     |

| Prefix        | Purpose                       |
| ------------- | ----------------------------- |
| `vscript`     | `<script setup>`              |
| `vscript-ts`  | `<script setup lang='ts'>`    |
| `vtemplate`   | `<template></template>`       |
| `vfor`        | `v-for` statement             |
| `vslot-named` | `<template #name></template>` |

### Support File `.js, .ts`

- Vue Router

| Prefix               | Purpose                                         |
| -------------------- | ----------------------------------------------- |
| `vrouter`            | Vue Router start                                |
| `vscrollbehavior`    | Vue Router `scrollBehavior`                     |
| `vbeforeeach`        | Vue Router global guards `beforeEach`           |
| `vbeforeresolve`     | Vue Router global guards `beforeResolve`        |
| `vaftereach`         | Vue Router global guards `afterEach`            |
| `vbeforeenter`       | Vue Router per-route guard `beforeEnter`        |
| `vbeforerouteenter`  | Vue Router component guards `beforeRouteEnter`  |
| `vbeforerouteupdate` | Vue Router component guards `beforeRouteUpdate` |
| `vbeforerouteleave`  | Vue Router component guards `beforeRouteLeave`  |

- Pinia

| Prefix     | Purpose                                                       |
| ---------- | ------------------------------------------------------------- |
| `pstart`   | Start code needed for a Pinia store file                      |
| `pstart-c` | Start code needed for a Pinia store file with Composition API |

### Support File `.vue, .js, .ts`

- Nuxt

| Prefix                  | Purpose                                            |
| ----------------------- | -------------------------------------------------- |
| `nfetch`                | `useFetch` composable                              |
| `nfetch-lazy`           | `useLazyFetch` composable                          |
| `ndfetch    `           | `$Fetch`                                           |
| `ndfetch-post`          | `$Fetch` with method POST and Body                 |
| `ndfetch-put`           | `$Fetch` with method PUT and Body                  |
| `ndfetch-delete`        | `$Fetch` with method DELETE and Body               |
| `nasyncdata`            | `useAsyncData` composable                          |
| `nasyncdata-lazy`       | `useLazyAsyncData` composable                      |
| `nhead`                 | `useHead` composable                               |
| `nhead-description`     | `useHead` composable with description              |
| `nhead-template`        | `useHead` composable with title template           |
| `npagemeta`             | `definePageMeta` composable                        |
| `npagemeta-description` | `definePageMeta` composable with description       |
| `npagemeta-layout`      | `definePageMeta` composable with layout            |
| `npagemeta-middleware`  | `definePageMeta` composable with middleware        |
| `npagemeta-ml`          | `definePageMeta` composable with middleware layout |
| `nplugin`               | Start code for Nuxt plugin                         |
| `nmiddleware`           | Start code for Nuxt middleware                     |
| `nserver`               | Start code for Nuxt server                         |

- Vue

| Prefix             | Purpose                     |
| ------------------ | --------------------------- |
| `vref`             | Vue `ref`                   |
| `vreactive`        | Vue `reactive`              |
| `vcomputed`        | Vue `computed`              |
| `vwatch`           | Watcher                     |
| `vwatcheffect`     | Watch Effect                |
| `vonmounted`       | onMounted hook              |
| `vonbeforemount`   | onBeforeMount hook          |
| `vonbeforeupdate`  | onBeforeUpdate hook         |
| `vonupdated`       | onUpdated hook              |
| `vonerrorcaptured` | onErrorCaptured hook        |
| `vonunmounted`     | onUnmounted hook            |
| `vonbeforeunmount` | onBeforeUnmount hook        |
| `vdefineprops`     | Define props                |
| `vdefineemits`     | Define emits                |
| `vsingleemit`      | Single emit for defineEmits |
| `vdefineslots`     | Define slots                |
| `vsingleslot`      | Single slot for defineSlots |
| `vdefineoptions`   | Define Options              |
| `vdefinemodel`     | Define Model                |

## License

[MIT](https://github.com/zhaolinlau/nuxt-vscode-snippets/blob/master/LICENSE) © [Zhaolin Lau](https://github.com/zhaolinlau)

**Enjoy!**