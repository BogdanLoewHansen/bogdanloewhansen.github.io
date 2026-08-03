source 'https://rubygems.org'

# Jekyll itself is intentionally not declared here. The github-pages gem
# pins it to the version GitHub's build servers run; an unconstrained
# `gem 'jekyll'` asks for the latest and the two cannot both be satisfied,
# which is what produced the "github-pages gem can't satisfy your Gemfile's
# dependencies" warning on every Pages build.
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

gem 'github-pages'
gem 'connection_pool', '2.5.0'

# Windows does not ship the IANA timezone database, so bundle it.
# Platform-gated: not installed on GitHub Pages' Linux build servers.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end
