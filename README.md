<p align="center">
  <a href="https://docsify.js.org">
  </a>
</p>


<p align="center">
    DOCUMENTATION
</p>

<p align="center">
  <a href="https://opencollective.com/docsify/order/3254">
    <img src="https://opencollective.com/docsify/tiers/gold-sponsor.svg?avatarHeight=36">
  </a>
</p>

## Change Credentials
> Routes. 
<p> 
  
</p>
>   

## Installation

Install `docsify-cli` via `npm` or `yarn` globally.

```shell
npm i docsify-cli -g
# yarn global add docsify-cli
```

## Usage

### `init` command

Use `init` to generate your docs.

```shell
docsify init <path> [--local false] [--theme vue] [--plugins false]

# docsify i <path> [-l false] [-t vue] [--plugins false]
```

`<path>` defaults to the current directory. Use relative paths like `./docs` (or `docs`).

- `--local` option:
  - Shorthand: `-l`
  - Type: boolean
  - Default: `false`
  - Description: Copy `docsify` files to the docs path, defaults to `false` using `cdn.jsdelivr.net` as the content delivery network (CDN). To explicitly set this option to `false` use `--no-local`.
- `--theme` option:
  - Shorthand: `-t`
  - Type: string
  - Default: `vue`
  - Description: Choose a theme, defaults to `vue`, other choices are `buble`, `dark` and `pure`.
- `--plugins` option:
  - Shorthand: `-p`
  - Type: boolean
  - Default: `false`
  - Description: Provide a list of plugins to insert as `<script>` tags to `index.html`.

### `serve` command

Run a server on `localhost` with livereload.

```shell
docsify serve <path> [--open false] [--port 3000]

# docsify s <path> [-o false] [-p 3000]
```

- `--open` option:
  - Shorthand: `-o`
  - Type: boolean
  - Default: `false`
  - Description: Open the docs in the default browser, defaults to `false`. To explicitly set this option to `false` use `--no-open`.
- `--port` option:
  - Shorthand: `-p`
  - Type: number
  - Default: `3000`
  - Description: Choose a listen port, defaults to `3000`.

### `generate` command

Docsify's generators.

```shell
docsify generate <path> [--sidebar _sidebar.md]

# docsify g <path> [-s _sidebar.md]
```

- `--sidebar` option:
  - Shorthand: `-s`
  - Type: string
  - Default: `_sidebar.md`
  - Description: Generate sidebar file, defaults to `_sidebar.md`.

## Contributing
Please see the [Contributing Guidelines](./CONTRIBUTING.md)

## Contribution

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/docsifyjs/docsify-cli)
