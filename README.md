# Hexo Theme Cupertino (Yun's Branch)

The Hexo Blog Theme Cupertino (Yun's Branch)

![A screenshot](https://zhuoyun233.com/covers/20220510.png)

Visit [https://zhuoyun233.com/](https://zhuoyun233.com/) to preview it.

This theme is modified for my own use and is based on [hexo-theme-cupertino](https://github.com/MrWillCom/hexo-theme-cupertino).

## Differences

Now Bilibili and WebDAV have a dedicated logo on the navigation bar.

Pages have some new attributes`page.no_about`and`page.no_title` that can be changed to customize your page layout.

A new page called Meditations is created. Posts that has the first `categories` attribute as `Meditation` will be put into the Meditations page and won't be shown in the home page. 

If license and license_link are left empty in the theme config file, no license will be shown in About.

'post-list-item' is now a separated part if you'd like to know.

## Installation

If you don't have a [Hexo](https://hexo.io/) blog, just [create one](https://hexo.io/docs/).

To install it, just clone this as a Git submodule to your `themes/cupertino/` directory and edit your `_config.yml`. After that, you should remember to edit `themes/cupertino/_config.yml`.

`_config.yml`:

```yaml
...
theme: cupertino
...
```

## Configuration

See [docs/configuration.md](./docs/configuration.md)
