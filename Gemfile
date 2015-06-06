source 'https://rubygems.org'

## Was not working at one stage, see: https://github.com/bundler/bundler/issues/3717#issuecomment-109157302
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll' 
gem 'jekyll-assets'
gem 'github-pages', versions['github-pages']

#gem 'html-pipeline'
#gem 'jekyll-html-pipeline'
#gem 'autoprefixer-rails'
gem 'jekyll-sitemap'

#group :jekyll_plugins do
#  gem "jekyll-assets-autoprefixer"
#end
