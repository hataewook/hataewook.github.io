source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'jekyll'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool', '2.5.0'

# ffi 1.17+ requires Ruby >= 3.0. Keep Ruby 2.7 local setups installable.
if Gem::Version.new(RUBY_VERSION) < Gem::Version.new('3.0')
  gem 'ffi', '< 1.17'
end
