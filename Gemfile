source "https://rubygems.org"

ruby RUBY_VERSION

gem "jekyll", "~> 4.2.0"

group :jekyll_plugins do
  gem 'jekyll-archives'
  gem 'jekyll-feed'
  gem "jekyll-github-metadata"
  gem 'jekyll-paginate'
  gem 'jekyll-redirect-from'
  gem 'jekyll-relative-links'
  gem 'jekyll-remote-theme'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
  gem 'jekyll-minifier'
end

platforms :mingw, :x64_mingw, :mswin, :jruby  do
  gem "tzinfo"
  gem "tzinfo-data"
end

if RUBY_PLATFORM.downcase.include?('mswin') || RUBY_PLATFORM.downcase.include?('mingw') 
  gem "tzinfo"
  gem "tzinfo-data" 
end 

gem "webrick"

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
