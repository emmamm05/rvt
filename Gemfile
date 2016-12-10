source 'https://rubygems.org'

gemspec

gem 'rails-controller-testing'
gem 'actionmailer'
gem 'activerecord'

group :development do
  gem 'puma'

  gem 'byebug'

  # Only require this one explicitly.
  gem 'pry-rails', require: false

  platforms :jruby do
    gem 'activerecord-jdbcsqlite3-adapter'
  end

  platforms :ruby do
    gem 'thin'
    gem 'sqlite3'
  end
end

group :test do
  gem 'rake'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end
