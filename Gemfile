# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 3.9"
gem "ffi", "~> 1.16.3"
gem "jekyll-gist"
gem "jekyll-feed"
gem "jekyll-redirect-from"
gem "jekyll-include-cache"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
  
gemspec
