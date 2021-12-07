# frozen_string_literal: true

source "https://rubygems.org"
gemspec

unless ENV["CI"]
  gem "byebug", require: false, platforms: :mri
  gem "yard",   require: false
end

gem "addressable"

gem 'pg_query'

gem 'rack'
gem "devise"
gem "breakman"
gem "redis"

gem 'webpacker'
gem 'ruby-progressbar'
gem 'sidekiq-pro'
gem 'strong_migrations'
gem 'faraday'

gem 'hashie'
gem 'hiredis'
gem 'httparty'
gem 'ipcat'
gem 'jwt'
gem 'bootstrap-sass' # Bootstrap 3
gem 'buffer', github: 'bufferapp/buffer-ruby'
gem 'carrierwave'

gem "hanami-devtools", require: false, git: "https://github.com/hanami/devtools.git", branch: "main"

gem "dry-files", git: "https://github.com/dry-rb/dry-files.git", branch: "master"
gem "dry-configurable", git: "https://github.com/dry-rb/dry-configurable.git", branch: "master"

group :test do
  gem "dotenv"
  gem "dry-types"
  gem "slim"
end
