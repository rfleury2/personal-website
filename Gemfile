# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

group :development do
  gem 'rake', '~> 10.4.2'
  gem 'sass', '~> 3.4.10'
  gem 'jekyll'
end
