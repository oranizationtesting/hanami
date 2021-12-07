# frozen_string_literal: true

source "https://rubygems.org"
gemspec

unless ENV["CI"]
  gem "byebug", require: false, platforms: :mri
  gem "yard",   require: false
end

gem "addressable"
gem "kaminari"

gem 'pg_query'

gem 'rack'
gem "devise"
gem "breakman"
gem "redis"

gem "hanami-devtools", require: false, git: "https://github.com/hanami/devtools.git", branch: "main"

gem "dry-files", git: "https://github.com/dry-rb/dry-files.git", branch: "master"
gem "dry-configurable", git: "https://github.com/dry-rb/dry-configurable.git", branch: "master"

group :test do
  gem "dotenv"
  gem "dry-types"
  gem "slim"
end
