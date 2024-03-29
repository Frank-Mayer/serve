# serve

[![Test](https://github.com/Frank-Mayer/serve/actions/workflows/test.yml/badge.svg)](https://github.com/Frank-Mayer/serve/actions/workflows/test.yml)

Run `serve` to start a webserver hosting the content of a directory.

## Install

### Go install

```bash
go install github.com/Frank-Mayer/serve/cmd/serve@latest
```

### Homebrew

```sh
brew tap Frank-Mayer/tap
brew install Frank-Mayer/tap/serve
```

## Usage

```bash
serve [directory] [flags...]
```

## Flags

- `--md`

  Compile Markdown files to HTML

- `--port` `-p` int

  Port to listen on (default is a random port)

- `--verbose` `-v`

  Verbose output
