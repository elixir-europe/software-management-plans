# software-management-plans
For the Tools Platform.

[![Website](https://img.shields.io/website?url=https%3A%2F%2Felixir-europe.github.io/software-management-plans&style=flat-square)](https://elixir-europe.github.io/software-management-plans/)

This is the source repository for the **ELIXIR Software Management Plan**, built with [Jekyll](https://jekyllrb.com/) using the [ELIXIR Toolkit Theme](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme).

---

## Development

You need Ruby (>= 3.3 recommended) and Bundler installed:
```bash
gem install bundler
bundle install
```

Run a local server with:
```bash
bundle exec jekyll serve
```
The site will be available at http://localhost:4000.

## Known Limitations

Some Sass code (from upstream theme) emits deprecation warnings due to changes in Sass v2/v3. 
This does not affect build correctness but may require theme update in the future.

