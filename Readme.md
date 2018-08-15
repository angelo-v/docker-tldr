# tldr

Containerized version of [tldr](https://github.com/tldr-pages/tldr) based on alpine linux.

## Usage

```bash
alias tldr='docker run --rm -it -v tldr_cache:/root/.tldr aveltens/tldr'
tldr --help
```

