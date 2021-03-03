# find releases

> An [octoherd](https://github.com/octoherd) script to find GitHub releases

## Usage

```
$ npx @octoherd/script-close-renovate-dashboard-issues \
  --octoherd-token 0123456789012345678901234567890123456789 \
  script-star-or-unstar/script.js \
  "octokit/*"
```

Optionally add a `--since` flag to ignore releases before a defined date, e.g. `--since 2020-02-02`

## License

[ISC](LICENSE.md)
