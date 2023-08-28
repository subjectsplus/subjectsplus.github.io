# subjectsplus.github.io
Website files for SubjectsPlus landing page hosted on Github Pages

https://subjectsplus.github.io/

### Dependencies & requirements
* Ruby 3.1.3 (https://www.ruby-lang.org/en/downloads/) | ruby -v
* Ruby Gems 3.3.26 (https://rubygems.org/pages/download) | gem -v
* Bundler 2.3.15 | bundle update bundle -v
* NPM 6.14.17 (https://docs.npmjs.com/cli/update) | npm -v
* Node 14.19.3 (https://nodejs.org/) | node -v
* Jekyll 4.3.2 | jekyll --version

### Instructions
* After cloning repo, run:
- `gem install bundler` using the version specified on the Gemfile
- then run `bundle install` to install the missing gems

* Local build: `bundle exec jekyll build --config=_config_dev.yml`
* Local serve: `bundle exec jekyll serve --config=_config_dev.yml --incremental`

* Localhost preview URL:  http://localhost:4000/subjectsplus.github.io/index.html

* **Production Build:**
  `bundle exec jekyll build --config=_config.yml`

### For Github Pages

If you want to use GitHub Pages, remove/comment out "gem "jekyll" listed in the Gemfile. Then uncomment this line: 

gem "github-pages", group: :jekyll_plugins

To upgrade, run `bundle update github-pages`