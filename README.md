# Hands-on Tauri Vue.js

Demo application to showcase a Tauri based desktop application with Vue.js frontend.
Everything shown here is pretty much auto generated.

## Project setup
``` bash
# see https://tauri.studio/en/docs/getting-started/intro
$ npm i -g @vue/cli
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
$ cargo install tauri-bundler

# see https://github.com/tauri-apps/vue-cli-plugin-tauri
$ vue create hands-on-tauri-vue
$ cd hands-on-tauri-vue
$ vue add tauri
```

### Development and Building

```bash
# Compiles and hot-reloads for development
$ npm run tauri:serve

# Build final executable
$ npm run tauri:build
```

## Maintainer

M.-Leander Reimer (@lreimer), <mario-leander.reimer@qaware.de>

## License

This software is provided under the MIT open source license, read the `LICENSE` file for details.
