source "https://rubygems.org"

if RUBY_PLATFORM != 'java'
  gem "github-pages", group: :jekyll_plugins
else
  gem "jekyll", "~> 3.7.3"

  gem "minima", "~> 2.0"

  # If you have any plugins, put them here!
  group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.6"
  end

  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
end

