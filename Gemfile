# bundle exec jekyll serve --livereload
# frozen_string_literal: true

source "https://rubygems.org"

# gem "rails"
# gem "jekyll", "~> 4.2"
gem "jekyll-remote-theme"
gem "github-pages", group: :jekyll_plugins
gem "webrick", "~> 1.7"

group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.12"
    # gem 'jekyll-sitemap'
    # gem 'jekyll-seo-tag', '~>2.7.1'
  end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", "~> 1.2"
    gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
  

