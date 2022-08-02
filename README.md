# jekyll-theme-solarized-dark

Theme implements Solarized Dark color theme.

## Installation

### No auto-updates (recomended)

Copy file and folders to your Jekyll website
```
_config.yml
assets/
_layouts/
```

### With auto-updates

Include `jekyll-remote-theme` in your `Gemfile` and `_config.yml` and replace _layouts with given here. In `_config.yml` remove `theme` field if present and insert

```yml
remote_theme: ivabus/jekyll-theme-solarized-dark
```

## Usage

You can customize `_config.yml`, any assets and layouts for your own needs.

Write your posts at `_posts/` directory. Every post should be named like `YYYY-MM-DD-name_of_post.md` and have specific header.

```yml
---
layout: post
title: "POSTNAME"
---
```

This demo`s source or [ivabus.dev source](https://github.com/ivabus/ivabus-website) could be used as examples of usage.

## Contributing

Bug reports and pull requests are welcome on [GitHub](https://github.com/ivabus/jekyll-theme-solarized-dark).

## Development

To set up testing environment run `bundle install`.

To build site and start server run `bundle exec jekyll s`. Server will be present at [http://localhost:4000](http://localhost:4000)

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

