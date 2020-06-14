## Empirical Website

This is the source for [empirical-soft.com](https://www.empirical-soft.com). It uses [Jekyll](https://jekyllrb.com) to generate the site from the included [Markdown](https://jekyllrb.com/docs/configuration/markdown/) files. Hosting is provided by [GitHub Pages](https://pages.github.com).

To build this locally, just run Jekyll in the shell.

```
$ bundle exec jekyll serve
```

## Try Empirical Online

[Open this repo with repl.it](https://repl.it/github/empirical-soft/empirical-soft.github.io). Then click the green **run** button at the top.

You will get a prompt like

```
Empirical version 0.1.0
Copyright (C) 2019 Empirical Software Solutions,
 LLC

>>>
```

Pre-included example files are:

 - `prices.csv`
 - `trades.csv`
 - `quotes.csv`
 - `events.csv`

You will be able to load these.

```
>>> load$("prices.csv")
```

See the [Demo](https://www.empirical-soft.com/demo.html) and [Tutorial](https://www.empirical-soft.com/tutorial.html) for how to use Empirical.
