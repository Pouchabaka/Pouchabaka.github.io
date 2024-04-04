source "https://rubygems.org"

# To run: bundle exec jekyll serve

gem "minima", "~> 2.5"

# Add Plugins here
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "github-pages", group: :jekyll_plugins
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
