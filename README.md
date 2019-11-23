- Remove the unnecessary
    - .editorconfig
    - .gitattributes
    - .github
    - /docs
    - /test
    - CHANGELOG.md
    - minimal-mistakes-jekyll.gemspec
    - README.md
    - screenshot-layouts.png

- Update `Gemfile`
    - May need to install `zlib1g-dev`

- Run `bundle install` to install dependencies

- Run `bundle exec jekyll serve` to develop