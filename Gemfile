source 'https://rubygems.org'
# source 'http://rubygems.de' # untested

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'html-pipeline'
gem 'jekyll-assets'
gem 'jekyll-html-pipeline'
gem 'jekyll-sitemap'
gem 'autoprefixer-rails'

group :jekyll_plugins do
  gem "jekyll-assets-autoprefixer"
end
