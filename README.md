<p align="center">
  <a href="#" rel="noopener" target="_blank"><img width="150" src="https://raw.githubusercontent.com/LissetteIbnz/vscode-vue-typescript-sfc-snippets/master/images/VueTS_icon_large.png" alt="Vue.js + Typescript SFC Snippets logo"></a></p>
</p>

<h1 align="center">Vue.js + TypeScript SFC Snippets for VS Code</h1>

This extension for VS Code adds snippets to use Vue with TypeScript as standard API and based on class-style, as well HTML.

![SnippetDemo](https://raw.githubusercontent.com/LissetteIbnz/vscode-vue-typescript-sfc-snippets/master/images/vcibase.gif)

## Usage

Type part of a snippet, press enter, and the snippet unfolds.

## Snippets

### Base for Vue Standard API

| Snippet | Purpose                    |
| ------- | -------------------------- |
| `vbase` | SFC standard API with TS |
| `vcbase` | SFC standard API with VueConstructor & TS |
| `vcibase` | SFC standard API with VueConstructor extending interface & TS |

### Base for Class-style API

| Snippet | Purpose                    |
| ------- | -------------------------- |
| `vcsbase` | SFC class-style API with TS |
| `vcsibase` | SFC class-style API extending Props with TS |

### Template

| Snippet | Purpose                    |
| ------- | -------------------------- |
| `vfor` | v-for directive |
| `vmodel` | v-model directive |
| `vmodel-num` | v-model directive with number modifier |
| `von` | v-on custom handler |
| `von-arg` | v-on custom handler with arguments |
| `von-click` | v-on click handler with arguments |
| `von-submit` | v-on submit handler with prevent |

### Script for Vue Standard API

| Snippet | Purpose                    |
| ------- | -------------------------- |
| `vc-imp` | Import Vue and VueConstructor |
| `vc-header` | Definition export default component as VueConstructor |
| `vci-header` | Definition export default component as VueConstructor + interface |
| `vdata` | Component type data as a function |
| `vprops` | Vue props |
| `vprops-req` | Vue props required |
| `vinterface` | Interface for extend Vue |
| `vmethod` | Vue method |
| `vcomputed` | Vue computed |
| `vwatcher` | Vue watcher |
| `vrefs` | Declaration Refs by VueConstructor |
| `vfilter` | Vue filter |
| `vrender` | Vue render |

### Scripts for Class-style API

| Snippet | Purpose                    |
| ------- | -------------------------- |
| `vcc-imp` | Import Component with vue-class-property |
| `vpd-imp` | Import Vue and Component with vue-property-decorator |
| `vcs-data` | Class-style API initial data |
| `vcs-refs` | Class-style API annotate refs type |
| `vcs-computed` | Class-style API computed |

### Scripts TypeScript file

| Snippet | Purpose                    |
| ------- | -------------------------- |
| `v-augmenting` | Augmenting Types to declare an instance property |
| `v-augmenting-global` | Declare additional global properties |
| `v-augmenting-comp` | Declare additional components options |

## Installation

1. Install Visual Studio Code
2. Launch VS Code
3. From the command palette Ctrl-Shift-P (Windows, Linux) or Cmd-Shift-P (OSX)
4. Select Install Extension
5. Choose the extension
6. Reload Visual Studio Code

## Release Notes

### 1.0.0

Initial release.

**Enjoy!**

---

## Thanks

Inspired by [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets) of Sarah Drasner

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/LissetteIbnz/vscode-vue-typescript-sfc-snippets)
