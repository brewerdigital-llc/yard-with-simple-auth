# frozen_string_literal: true
source 'https://rubygems.org'

gemspec

group :development do
  gem 'rspec'
  gem 'rake'
  gem 'rdoc'
  gem 'json'
  gem 'simplecov'
  gem 'samus', '~> 3.0.8', :require => false
  gem 'coveralls', :require => false
end

group :asciidoc do
  gem 'asciidoctor'
end

group :markdown do
  gem 'redcarpet', :platforms => [:ruby]
end

group :textile do
  gem 'RedCloth', :platforms => [:ruby]
end

group :server do
  gem 'rack'
end

group :i18n do
  gem 'gettext'
end
