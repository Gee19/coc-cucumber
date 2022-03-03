# coc-cucumber

> fork from a [cucumber/vscode](https://github.com/cucumber/vscode)

Cucumber extension for [coc.nvim](https://github.com/neoclide/coc.nvim)

<img width="780" alt="coc-cucumber-demo" src="https://user-images.githubusercontent.com/188642/156540810-1b3a47d4-6cfd-4dbc-852b-5849d0bcfcc0.png" />

## Install

**vim-plug**:

```vim
Plug 'Gee19/coc-cucumber', {'do': 'yarn install --frozen-lockfile'}
```

**manually**

`git clone git@github.com:Gee19/coc-cucumber.git`

`cd ~/path/to/coc-cucumber`

`yarn && yarn build`

Add the following to your vimrc:

`set runtimepath^=~/path/to/coc-cucumber`

## Filetype related

The "filetype" must be `cucumber` for this extension to work.

Install "cucumber" related plugin (e.g. [tpope/vim-cucumber](https://github.com/tpope/vim-cucumber) or [sheerun/vim-polyglot](https://github.com/sheerun/vim-polyglot)).

## Quickstart

Add the following to your `coc-settings.json`:
```
  "cucumber.enable": true,
  "cucumber.glue": [
    "cypress/integration/**/*.cucumber.ts"
  ],
  "cucumber.features": [
    "cypress/integration/**/*.feature"
  ],
```

## Configuration options

Check the "contributes.configuration" section of `package.json`.

## Thanks

- <https://github.com/yaegassy>
- <https://github.com/cucumber/vscode>
- <https://github.com/cucumber/language-server>

## License

MIT

---

> This extension is built with [create-coc-extension](https://github.com/fannheyward/create-coc-extension)
