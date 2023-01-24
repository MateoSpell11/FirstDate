<p align="center">
  <a href="https://docsify.js.org">
  </a>
</p>


<p align="center">
    DOCUMENTATION
</p>

<p align="center">
  <a href="https://opencollective.com/docsify/order/3254">
  </a>
</p>

## POST /Change Credentials
<p>
Admin method true
Auth true 
</p>
### response
```shell
    {
      "status": "success",
      "data": {
      }
    }
```

## GET /Clear-Cache
>Admin method true
>Auth true 
### Body
```shell
    {
    "userEmail": "logan1@corporatealliance.net.sbx1"
    }
```
### Response
```shell
    {
      "status": "success",
      "data": {
      }
    }
```

## GET /Clear-Cache

>Admin method true
>Auth true 
### response
```shell
    {
      "status": "success",
      "data": {
      }
    }
```

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
