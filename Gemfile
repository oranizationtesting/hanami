# frozen_string_literal: true

source "https://rubygems.org"
gemspec

unless ENV["CI"]
  gem "byebug", require: false, platforms: :mri
  gem "yard",   require: false
end

gem "addressable"

gem 'pg_query'
gem 'rails', '6.1.4.1'
gem 'globalid', '~> 0.4.2' if Gem.ruby_version < Gem::Version.new('2.6.0')
gem 'rouge', '~> 3.26.0'
gem 'request_store', '~> 1.5.0'
gem 'mini_mime', '~> 1.1.0'
gem "actionpack-xml_parser"
gem 'roadie-rails', '~> 2.2.0'
gem 'marcel'
gem "mail", "~> 2.7.1"
gem 'csv', '~> 3.2.0'
gem 'nokogiri', '~> 1.12.2'
gem 'i18n', '~> 1.8.2'
gem "rbpdf", "~> 1.20.0"
gem 'addressable'
gem 'rubyzip', '~> 2.3.0'
gem 'net-smtp', '~> 0.3.0'
gem 'net-imap', '~> 0.2.2'
gem 'net-pop', '~> 0.1.1'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :x64_mingw, :mswin]

# TOTP-based 2-factor authentication
gem 'rotp'
gem 'rqrcode'

# Optional gem for LDAP authentication
group :ldap do
  gem 'net-ldap', '~> 0.17.0'
end

# Optional gem for OpenID authentication
group :openid do
  gem "ruby-openid", "~> 2.9.2", :require => "openid"
  gem "rack-openid"
end

# Optional gem for exporting the gantt to a PNG file
group :minimagick do
  gem 'mini_magick', '~> 4.11.0'
end

# Optional Markdown support, not for JRuby
group :markdown do
  gem 'redcarpet', '~> 3.5.1'
end

# Optional CommonMark support, not for JRuby
group :common_mark do
  gem "html-pipeline", "~> 2.13.2"
  gem "commonmarker", (Gem.ruby_version < Gem::Version.new('2.6.0') ? '0.21.0' : '0.23.1')
  gem "sanitize", "~> 6.0"
end

gem 'rack'
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
