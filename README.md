# jsonresume-theme-even-more

Additions to the [even](https://github.com/rbardini/jsonresume-theme-even) theme by Rafael Bardini.

- fix for first day of the month displaying as the previous month
- include region (state) in location display
- display skill levels

## Installation

```console
npm install jsonresume-theme-even-more
```

See [example](https://github.com/rbardini/resume.rbardini.com).

### Standalone usage

_Even_more_ comes with a barebones CLI that reads resumes from `stdin` and outputs HTML to `stdout`. This allows usage without any resume builder tools:

```console
cat resume.json | npx jsonresume-theme-even-more > resume.html
```
