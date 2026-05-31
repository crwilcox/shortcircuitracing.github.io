source "https://rubygems.org"

gem "minima", "~> 2.5"
gem "github-pages", "~> 232", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17.0"
end

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", platforms: [:windows]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

gem "webrick", "~> 1.8"

# Ruby 3.4 removes these from the default bundled set. Listing them keeps
# local builds working on newer Rubies while remaining harmless on GitHub Pages.
gem "bigdecimal"
gem "base64"
gem "csv"
gem "logger"
gem "liquid", "~> 4.0", ">= 4.0.4"
