source "https://rubygems.org"
gem "jekyll", "~> 4.0.0"
gem "minima", "~> 2.5"
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-gist'
  gem 'jekyll-paginate'
  gem "jekyll-asciidoc"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem 'asciidoctor', '~> 1.5.4'
gem 'coderay', '1.1.1'

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?