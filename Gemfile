<<<<<<< HEAD
# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "kramdown", ">= 2.3.1"

# return true if ENV['NETLIFY']
gem "jekyll", ">= 3.8.5"
gem "nokogiri", ">= 1.11.0"
gem "rubyzip", ">= 1.3.0"

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-autoprefixer"
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-include-cache"
  gem "github-pages"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!x64_mingw|mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
=======
# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "kramdown", ">= 2.3.1"

# return true if ENV['NETLIFY']
gem "jekyll", ">= 3.8.5"
gem "nokogiri", ">= 1.11.0"
gem "rubyzip", ">= 1.3.0"

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-autoprefixer"
  #gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-include-cache"
  gem "github-pages"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
>>>>>>> d256711bc986a8812894f1e4797a8eeb52ee9a6f
