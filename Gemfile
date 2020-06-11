# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

DECIDIM_VERSION = "0.20.1" 

gem "decidim", DECIDIM_VERSION
gem "decidim-consultations", DECIDIM_VERSION
gem "decidim-initiatives", DECIDIM_VERSION

gem "bootsnap", "~> 1.3"

gem "puma", "~> 3.12"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.9"
gem "sidekiq", "~> 5.2"
gem "figaro"
gem "wicked_pdf", "~> 1.1"
gem 'wkhtmltopdf-binary'
gem "ransack", "~> 2.1.1"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "decidim-dev", DECIDIM_VERSION
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  gem "passenger"
  gem 'delayed_job_active_record'
  gem "daemons"
end
