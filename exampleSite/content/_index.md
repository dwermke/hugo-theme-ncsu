+++
date = 2024-11-02
menuHighlight = "about"
+++

# hugo-theme-ncsu

(Unofficial) [Hugo](https://github.com/gohugoio/hugo) (static site generator written in Go) theme using Bootstrap 5 and inspired by the NC State branding and resources.

- Github Repo: https://github.com/wspr-ncsu/hugo-theme-ncsu
- This page: https://wspr-ncsu.github.io/hugo-theme-ncsu/
- This page also included in theme itself in `exampleSite` as website using the theme, run with:
```sh
$ cd exampleSite
$ hugo --themesDir ../.. server
```


## Changelog

Changelog of theme changes not including individual changes to this theme website.

### Upcoming

These changes are live on the `main` branch (i.e., you will get them when adding the theme as submodule) but not yet set in a specific release.

- {{< badge "text-bg-primary" >}}Breaking{{< /badge >}} Update schedule shortcodes to v2, more intelligent and flexible, but breaking change because different shortcodes. ([f9131b2](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/f9131b28a0a3c9389bae86d38198cfa7dd9185b9))
- {{< badge "text-bg-warning" >}}Fix{{< /badge >}} Updated footer text to just display longer class description text from `cdesc` variable (easier handling). ([11f68fc](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/11f68fc6bf387694d435e4f20333c0442f660229))
- {{< badge "text-bg-success" >}}Add{{< /badge >}} Add shortcodes `col` and `row` for Bootstrap col & row classes (Bootstrap-native way to set up columns and rows in Markdown, should be more stable than previous column shortcode). ([72df9d8](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/72df9d8ac21be62c973adbeb037db422e0440298))
- {{< badge "text-bg-success" >}}Add{{< /badge >}} Add shortcode `badge` for Bootstrap badge. ([32fdabb](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/32fdabb9b9c39da98edba0ab1f83a14f21a3a464))
- {{< badge "text-bg-success" >}}Add{{< /badge >}} Add shortcode `button` for Bootstrap button. ([32fdabb](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/32fdabb9b9c39da98edba0ab1f83a14f21a3a464))
- {{< badge "text-bg-success" >}}Add{{< /badge >}} Add shortcode `include` for including content from other markdown files. ([57a1cf1](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/57a1cf11c166a03db725d3a45d7c0732a6ff88d0))
- {{< badge "text-bg-success" >}}Add{{< /badge >}} Add more badge colors (based on base colors, e.g. `bg-blue`, `bg-indigo`, etc). ([6d447c1](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/6d447c166e9d0c31a0f06efd72587039359928fa))

### 2024.08

- {{< badge "text-bg-warning" >}}Fix{{< /badge >}} Fix website breakpoints to work with Bootstrap 5 layout. ([4256cf9](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/4256cf9851d20ed2586b700e0c5efa320833a46b))
- {{< badge "text-bg-success" >}}Add{{< /badge >}} Add manual split parameter for `column` shortcode to control split percentages manually. ([9b0679e](https://github.com/wspr-ncsu/hugo-theme-ncsu/commit/9b0679ef05121a068da550df9b25cc6d7d91012a))

### Earlier

- {{< badge "text-bg-primary" >}}Breaking{{< /badge >}} Move theme to Bootstrap 5.
